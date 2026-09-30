# PNGee IT Solutions — Growth Implementation

## Phase 1 implemented

- Repositioned the homepage around reliability, security and resilience.
- Expanded services to cover business networking, Wi-Fi, firewall/security, audits, backup/continuity, VPN and infrastructure consulting.
- Productised the PGK 750 Network & Security Health Check.
- Added a managed-support section to establish a recurring-revenue path.
- Added a four-step sales/service process.
- Added FAQ content and FAQ structured data.
- Added ProfessionalService structured data.
- Added SEO metadata, Open Graph metadata and canonical URL.
- Added responsive/mobile navigation and accessibility improvements.
- Removed the non-functional Formspree placeholder.
- Added functional email CTAs for consultation, health-check and urgent network enquiries.
- Added an inline privacy notice.
- Added robots.txt and sitemap.xml.

## Phase 2 — external setup required

These require account/domain details before production integration:

1. **Custom domain**
   - Production domain active: https://pngeeitsolutions.com.
   - Canonical, Open Graph, structured-data, robots.txt and sitemap references updated to the production domain.
   - Redirect the workers.dev hostname to the production hostname where practical.

2. **Domain email**
   - Replace mark@pngeeitsolutions.com with a branded address such as hello@<domain>.
   - Keep a separate support@<domain> for managed-service customers.

3. **Online scheduling**
   - Create a Cal.com booking page for:
     - Free 15-minute network consultation
     - Onsite Network & Security Health Check
     - Existing-customer support
   - Replace mailto booking CTAs with the production booking URL/embed.

4. **CRM**
   - Create HubSpot pipeline:
     - New Lead
     - Qualified
     - Consultation Booked
     - Assessment Scheduled
     - Proposal Sent
     - Won
     - Managed Service
   - Route website enquiries to CRM once a secure form backend is added.

5. **Secure form backend**
   - Prefer a Cloudflare Worker endpoint.
   - Add Cloudflare Turnstile.
   - Validate and rate-limit server-side.
   - Send notifications and CRM payloads from the Worker rather than exposing tokens client-side.

6. **Analytics**
   - Add Plausible or another lightweight analytics platform.
   - Track:
     - consultation CTA
     - health-check CTA
     - urgent-support CTA
     - email click
     - booking completed
     - future form started/submitted

7. **Google Business Profile**
   - Configure PNGee IT Solutions as a Port Moresby service-area business.
   - Link the production domain.
   - Begin requesting reviews from completed customer engagements.

8. **WhatsApp Business**
   - Add a business number and pre-filled enquiry link after the number is confirmed.

## Phase 3 — content expansion

Build dedicated landing pages once the custom domain is selected:

- /business-network-wifi
- /cybersecurity-firewall
- /network-security-health-check
- /backup-business-continuity
- /vpn-remote-access
- /managed-it
- /about
- /case-studies
- /knowledge

Do not publish customer names, employer information, certifications, project metrics or testimonials until they are explicitly verified and approved.
