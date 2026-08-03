# Adobe Creative Cloud (adobe-creative-cloud)

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

Adobe Creative Cloud is a suite of software and cloud services for graphic design, video editing, web development, photography, and 3D content creation. Its developer platform provides APIs for generative AI via Firefly Services, cloud storage and asset management, PDF document processing, electronic signatures, stock asset licensing, font delivery, and embeddable creative tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI/ML, Cloud, Creative, Design, Documents, Photography, SaaS, Video

## Timestamps

- **Created:** 2025-02-26
- **Modified:** 2026-04-17

## APIs

17 APIs covering Firefly generative AI, PDF Services, Document Generation, Acrobat Sign, Stock, Creative Cloud Libraries, Cloud Storage, Fonts, Photoshop, Lightroom, Express Embed SDK, I/O Events, I/O Runtime, App Builder, UXP, CEP, and Developer Distribution.

See [apis.yml](apis.yml) for the complete API inventory.

## Features

| Name | Description |
|------|-------------|
| Generative AI Image Creation | Generate images from text prompts, fill masked regions, and expand images using Adobe Firefly AI models. |
| PDF Document Processing | Create, convert, extract, compress, OCR, and protect PDF documents programmatically. |
| Electronic Signatures | Create and manage electronic signature workflows with Acrobat Sign. |
| Stock Asset Licensing | Search, preview, and license photos, vectors, videos, and templates from Adobe Stock. |
| Creative Cloud Libraries | Sync colors, styles, graphics, and design assets across Adobe applications. |
| Cloud Storage | Manage files, folders, and projects in Creative Cloud cloud storage. |
| Font Delivery | Access and deliver Adobe Fonts for web and application typography. |
| Embeddable Creative Tools | Embed Adobe Express editor and quick actions in web applications. |
| Plugin Development | Build extensions for Photoshop, InDesign, Illustrator using UXP or CEP. |
| Event-Driven Webhooks | Subscribe to real-time notifications via I/O Events. |
| Cloud Image Processing | Automate Photoshop and Lightroom operations in the cloud. |
| Document Generation | Generate PDFs and Word documents by merging JSON data into templates. |

## Use Cases

| Name | Description |
|------|-------------|
| Creative Asset Automation | Automate image generation, editing, and processing workflows. |
| Document Workflow Automation | Generate, convert, sign, and archive documents. |
| E-commerce Product Images | Use Firefly and Photoshop for product photography automation. |
| Brand Asset Management | Sync brand colors, fonts, and assets across teams. |
| Content Personalization | Generate personalized visual content at scale for marketing. |
| Digital Publishing | Automate PDF creation, compression, and accessibility tagging. |
| Contract Management | Create, send, sign, and track electronic agreements. |
| Stock Asset Integration | Embed Adobe Stock search and licensing into platforms. |

## Solutions

| Name | Description |
|------|-------------|
| Creative Cloud All Apps | Complete suite of 20+ creative applications with API access. |
| Adobe Firefly Services | Generative AI APIs combining Firefly, Photoshop, and Lightroom. |
| Adobe Acrobat Services | PDF Services, Document Generation, and Acrobat Sign APIs. |
| Adobe App Builder | Full-stack application framework for custom enterprise extensions. |

## Artifacts

### OpenAPI

- [Adobe Firefly API](openapi/adobe-firefly-api-openapi-original.yml)
- [Adobe CC Libraries API](openapi/adobe-cc-libraries-api-openapi-original.yml)
- [Adobe PDF Services API](openapi/adobe-pdf-services-api-openapi-original.yml)
- [Adobe Stock API](openapi/adobe-stock-api-openapi-original.yml)

### AsyncAPI

- [Adobe I/O Events](asyncapi/adobe-io-events-asyncapi-original.yml)

### JSON Schema

18 standalone JSON Schema files in [json-schema/](json-schema/).

### JSON Structure

18 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [Adobe Creative Cloud Context](json-ld/adobe-creative-cloud-context.jsonld) — 18 types, 43 properties

### Examples

18 example JSON files in [examples/](examples/).

## Vocabulary

- [Adobe Creative Cloud Vocabulary](vocabulary/adobe-creative-cloud-vocabulary.yaml) — 7 resources, 9 APIs, 5 domains, 5 personas

## Rules

- [Adobe Creative Cloud Spectral Rules](rules/adobe-creative-cloud-spectral-rules.yml) — 20 rules enforcing Adobe API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
