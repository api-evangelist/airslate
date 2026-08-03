# airSlate (airslate)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

airSlate is a document workflow automation holding company whose product family covers no-code workflow automation (altaFlow, formerly airSlate WorkFlow), electronic signature (signNow), PDF editing and form filling (pdfFiller and DocHub), legal forms (US Legal Forms), landing pages (Instapage), and an AI-powered marketing intelligence platform. Developer APIs are exposed primarily through the signNow and pdfFiller product lines; WorkFlow / altaFlow surfaces automation bots and integrations rather than a broad public REST API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/airslate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/airslate/refs/heads/main/apis.yml)

## Tags

- Document Automation
- eSignature
- Workflow
- PDF
- No-Code
- AI

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### airSlate WorkFlow (altaFlow)

No-code document workflow automation platform (recently rebranded as altaFlow). Supports building workflows that combine forms, contracts, bots, and integrations across CRM and ERP systems. Developer access is primarily via prebuilt bots and integration connectors.

- **Human URL:** [https://www.airslate.com/workflow](https://www.airslate.com/workflow)
- **Base URL:** `https://www.airslate.com/workflow`

#### Tags

- Workflow Automation
- No-Code
- Bots

#### Properties

- [Website](https://www.airslate.com/workflow)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### signNow API

REST API for signNow, airSlate's electronic signature product. Covers documents, signatures, templates, users, groups, fields, and webhooks. Supports OAuth 2.0 with production base api.signnow.com and evaluation base api-eval.signnow.com.

- **Human URL:** [https://docs.signnow.com/](https://docs.signnow.com/)
- **Base URL:** `https://api.signnow.com`

#### Tags

- eSignature
- REST
- OAuth2

#### Properties

- [Documentation](https://docs.signnow.com/)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### pdfFiller API

REST API for pdfFiller, covering document upload and conversion, form filling, templates, and e-signature flows. Used to embed PDF editing and form workflows into third-party applications.

- **Human URL:** [https://www.pdffiller.com/en/api](https://www.pdffiller.com/en/api)
- **Base URL:** `https://api.pdffiller.com/v2`

#### Tags

- PDF
- Forms
- Document Editing

#### Properties

- [Documentation](https://www.pdffiller.com/en/api)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DocHub

Cloud PDF editor that integrates with Google Workspace. Provides editing, signing, and sharing of PDFs from inside Google apps. Programmatic access is primarily via Google Workspace integration surfaces.

- **Human URL:** [https://dochub.com/](https://dochub.com/)
- **Base URL:** `https://dochub.com/`

#### Tags

- PDF
- Google Workspace

#### Properties

- [Website](https://dochub.com/)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### US Legal Forms

Online catalog of 85,000+ state-specific legal forms. Consumer and SMB product; no public developer API.

- **Human URL:** [https://www.uslegalforms.com/](https://www.uslegalforms.com/)
- **Base URL:** `https://www.uslegalforms.com/`

#### Tags

- Legal Forms

#### Properties

- [Website](https://www.uslegalforms.com/)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Instapage

Landing page builder and personalization platform. Offers REST endpoints for account integration via the Instapage developer surface.

- **Human URL:** [https://instapage.com/](https://instapage.com/)
- **Base URL:** `https://instapage.com/`

#### Tags

- Landing Pages
- Marketing

#### Properties

- [Website](https://instapage.com/)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### airSlate Marketing Intelligence Platform

AI-powered automation platform for end-to-end marketing operations. Positioned as a vertical AI product rather than a developer API.

- **Human URL:** [https://www.airslate.com/](https://www.airslate.com/)
- **Base URL:** `https://www.airslate.com/`

#### Tags

- AI
- Marketing

#### Properties

- [Website](https://www.airslate.com/)
- [Postman Collection](collections/airslate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airslate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.airslate.com/)
- [Documentation](https://docs.signnow.com/)
- [LinkedIn](https://www.linkedin.com/company/airslate)
- [Git Hub](https://github.com/signnow)
- [Twitter](https://twitter.com/airSlate_)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
