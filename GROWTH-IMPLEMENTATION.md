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

## Phase 1B implemented

- Repositioned the homepage to actively market PNGee as a website, web application, SaaS MVP, managed support, Cloudflare/domain/email, IT/network and cybersecurity provider for PNG businesses.
- Added first-viewport messaging: "Secure websites, cloud applications and IT solutions built for PNG businesses."
- Added a dedicated Websites, Apps & SaaS MVPs section covering:
  - business website development;
  - website redesign and modernisation;
  - custom web applications;
  - custom SaaS and MVP development;
  - domain, Cloudflare, DNS and business email setup;
  - managed website support.
- Preserved the accuracy boundary: PNGee can deliver custom SaaS/MVP projects, but the site does not imply mature off-the-shelf SaaS subscription products already exist.
- Updated the managed-support section to include website care alongside network and security support.
- Added trust/credibility messaging around security-aware delivery, Cloudflare/domain/email experience and incremental MVP delivery.
- Replaced the basic contact block with a structured lead-generation enquiry flow for service need, budget, timeframe, contact preference and project details.
- The lead form generates a local email or WhatsApp enquiry to `mark@pngeeitsolutions.com` / `+675 7100 5220`; no backend or customer data storage is introduced yet.
- Updated page metadata, Open Graph copy, ProfessionalService structured data and FAQ structured data for the broader commercial offer.

## Phase 2 — external setup required

These require account/domain details before production integration:

1. **Custom domain**
   - Production domain active: https://pngeeitsolutions.com.
   - Canonical, Open Graph, structured-data, robots.txt and sitemap references updated to the production domain.
   - Redirect the workers.dev hostname to the production hostname where practical.

2. **Domain email**
   - Primary public business identity is `mark@pngeeitsolutions.com`.
   - Keep role addresses such as `info@`, `sales@`, `support@` and `billing@` routed through the chosen mail flow.
   - Complete outbound sending authentication with SPF, DKIM and DMARC before scaling website forms or CRM notifications.

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
   - Preserve the current static lead form as a fallback path to email/WhatsApp until CRM capture is production-ready.

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
   - Current WhatsApp Business number: `+675 7100 5220`.
   - Continue using pre-filled enquiry links for website, support and health-check pathways.

## Phase 3 — content expansion

Build dedicated landing pages once the custom domain is selected:

- /website-development
- /website-redesign
- /custom-web-applications
- /saas-mvp-development
- /domain-cloudflare-business-email
- /managed-website-support
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
