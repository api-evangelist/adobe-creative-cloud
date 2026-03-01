# Adobe Creative Cloud (adobe-creative-cloud)
Adobe Creative Cloud is a suite of software and cloud services for graphic design, video editing, web development, photography, and 3D content creation. Its developer platform provides APIs for generative AI, PDF document processing, stock asset licensing, font delivery, electronic signatures, and embeddable creative tools, along with extension frameworks and serverless platform services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Creative, Design, Photography, Video, Documents, Cloud, AI/ML, SaaS

## Timestamps

- **Created:** 2025-02-26
- **Modified:** 2026-02-28

## APIs

### Adobe Firefly API
The Adobe Firefly API provides programmatic access to generative AI capabilities for image creation and manipulation. Key endpoints include text-to-image generation, generative fill for inpainting masked regions, image expansion for extending content beyond original boundaries, and style transfer for matching visual aesthetics. Part of Adobe Firefly Services, the API uses OAuth Server-to-Server authentication via the Adobe Developer Console and is designed for commercial-safe content generation with built-in Content Credentials.

**Human URL:** [https://developer.adobe.com/firefly-services/docs/firefly-api/](https://developer.adobe.com/firefly-services/docs/firefly-api/)


#### Tags:

 - Generative AI, Text-to-Image, Generative Fill, Image Generation, AI/ML

#### Properties

- [Documentation](https://developer.adobe.com/firefly-services/docs/firefly-api/)
- [GettingStarted](https://developer.adobe.com/firefly-services/docs/firefly-api/guides/)
- [APIReference](https://developer.adobe.com/firefly-services/docs/firefly-api/guides/api/)
- [OpenAPI](openapi/adobe-firefly-api-openapi-original.yml)

### Adobe Express Embed SDK
A JavaScript SDK for embedding Adobe Express creative editing tools directly into web applications. The SDK provides a full editor component for design creation, quick actions for common image and video operations such as resize, crop, remove background, and convert formats, and template access for professional design starting points. Developers integrate using API keys from the Adobe Developer Console. The SDK enables non-designers to create professional content without leaving the host application.

**Human URL:** [https://developer.adobe.com/express/embed-sdk/docs/guides/](https://developer.adobe.com/express/embed-sdk/docs/guides/)


#### Tags:

 - Embed SDK, JavaScript, Quick Actions, Editor, Web Components

#### Properties

- [Documentation](https://developer.adobe.com/express/embed-sdk/docs/guides/)
- [GettingStarted](https://developer.adobe.com/express/embed-sdk/docs/guides/quickstart/)
- [APIReference](https://developer.adobe.com/express/embed-sdk/docs/v4/)
- [GitHubRepository](https://github.com/AdobeDocs/cc-everywhere)

### Creative Cloud Libraries API
A REST API for accessing and managing Creative Cloud Libraries, enabling synchronization of colors, character styles, paragraph styles, graphics, and other creative assets across Adobe applications and custom integrations. The API supports creating, reading, updating, and deleting library elements, and includes an Asset Browser SDK for building web-based library browsing experiences. Libraries provide a central repository for brand assets that stay synchronized across Photoshop, Illustrator, InDesign, and other Creative Cloud applications.

**Human URL:** [https://developer.adobe.com/creative-cloud-libraries/](https://developer.adobe.com/creative-cloud-libraries/)


#### Tags:

 - Libraries, Assets, Collaboration, Sync, Colors, Styles

#### Properties

- [Documentation](https://developer.adobe.com/creative-cloud-libraries/docs/)
- [APIReference](https://developer.adobe.com/creative-cloud-libraries/docs/api/)
- [GitHubRepository](https://github.com/AdobeDocs/creative-cloud-libraries)
- [OpenAPI](openapi/adobe-cc-libraries-api-openapi-original.yml)

### Adobe Cloud Storage and Collaboration API
A REST API for managing files, folders, and projects in Adobe Creative Cloud cloud storage. The API supports creating and organizing projects with hierarchical folder structures, uploading and downloading files, assigning user roles for collaboration, and integrating cloud storage operations into automated creative workflows. It provides programmatic access to the same cloud storage that Creative Cloud desktop and mobile applications use for file synchronization.

**Human URL:** [https://developer.adobe.com/cloud-storage/](https://developer.adobe.com/cloud-storage/)


#### Tags:

 - Cloud Storage, Files, Projects, Collaboration, REST API

#### Properties

- [Documentation](https://developer.adobe.com/cloud-storage/)
- [APIReference](https://developer.adobe.com/cloud-storage/guides/api/)

### Adobe Stock API
A REST API for searching, licensing, and integrating Adobe Stock assets including photos, vectors, illustrations, videos, templates, and 3D content into applications and workflows. The Search API enables querying the Stock catalog with filters for asset type, orientation, color, and keywords. The Licensing API handles asset licensing and high-resolution download. Additional endpoints provide license history retrieval and member profile information. Free for developers with an Adobe ID for search operations; licensing requires Stock entitlements.

**Human URL:** [https://developer.adobe.com/stock/](https://developer.adobe.com/stock/)


#### Tags:

 - Stock Photos, Assets, Licensing, Media, Search, Vectors

#### Properties

- [Documentation](https://developer.adobe.com/stock/docs/)
- [APIReference](https://developer.adobe.com/stock/docs/api/)
- [APIReference](https://developer.adobe.com/stock/docs/api/11-search-reference/)
- [APIReference](https://developer.adobe.com/stock/docs/api/12-licensing-reference/)
- [GitHubRepository](https://github.com/adobe/stock-api-sdk)
- [OpenAPI](openapi/adobe-stock-api-openapi-original.yml)

### Adobe Fonts API
The Adobe Fonts API (formerly Typekit API) provides programmatic access to Adobe's font library for web and application integration. The API supports querying font family information and variations, creating and managing font kits for web deployment, generating font preview data, and retrieving font metadata. Kits are collections of fonts configured for specific domains and published to Adobe's CDN for web font delivery. Authentication uses user tokens generated via the Typekit API Token page.

**Human URL:** [https://developer.adobe.com/fonts/](https://developer.adobe.com/fonts/)


#### Tags:

 - Fonts, Typography, Web Fonts, Typekit, Kits

#### Properties

- [Documentation](https://fonts.adobe.com/docs/api)
- [GitHubRepository](https://github.com/typekit/fonts-api-docs)

### Adobe PDF Services API
A cloud-based REST API for creating, converting, and manipulating PDF documents programmatically. Part of Adobe Acrobat Services, the API supports PDF creation from HTML, images, and Office formats, conversion to and from multiple formats, OCR for scanned documents, document compression, password protection, content extraction with AI-powered text, table, and image recognition, and accessibility auto-tagging. SDKs are available for Java, Node.js, Python, and .NET. Includes a free tier of 500 document transactions per month.

**Human URL:** [https://developer.adobe.com/document-services/apis/pdf-services/](https://developer.adobe.com/document-services/apis/pdf-services/)


#### Tags:

 - PDF, Document Processing, OCR, Conversion, Extraction, Acrobat Services

#### Properties

- [Documentation](https://developer.adobe.com/document-services/docs/overview/pdf-services-api/)
- [APIReference](https://developer.adobe.com/document-services/docs/apis/)
- [GettingStarted](https://developer.adobe.com/document-services/docs/overview/pdf-services-api/quickstarts/)
- [OpenAPI](openapi/adobe-pdf-services-api-openapi-original.yml)

### Adobe Document Generation API
A REST API for generating PDF and Word documents by merging JSON data into Microsoft Word templates. Part of Adobe Acrobat Services, the API supports conditional content insertion, dynamic table generation, ordered and unordered list creation, image placement, and JSONata expression evaluation within templates. The Adobe Document Tagger Word add-in assists with template authoring by inserting tags for data binding. Commonly used for generating contracts, proposals, invoices, and reports from structured data.

**Human URL:** [https://developer.adobe.com/document-services/docs/overview/document-generation-api/](https://developer.adobe.com/document-services/docs/overview/document-generation-api/)


#### Tags:

 - Document Generation, Templates, PDF, Word, Data Merge

#### Properties

- [Documentation](https://developer.adobe.com/document-services/docs/overview/document-generation-api/)
- [GettingStarted](https://developer.adobe.com/document-services/docs/overview/document-generation-api/gettingstarted/)

### Acrobat Sign API
A REST API for creating and managing electronic signature workflows programmatically. The API supports document upload, agreement creation with configurable signing flows, real-time status tracking via webhooks, signed document retrieval, and embedded e-signature experiences within custom applications. Acrobat Sign is compliant with SOC 2 Type 2, ISO 27001, FedRAMP Tailored, and PCI DSS. The standard workflow involves uploading transient documents (available for 7 days), creating agreements with signer definitions, and tracking completion status.

**Human URL:** [https://developer.adobe.com/document-services/apis/sign-api/](https://developer.adobe.com/document-services/apis/sign-api/)


#### Tags:

 - Electronic Signatures, Agreements, Workflows, Compliance, Documents

#### Properties

- [Documentation](https://developer.adobe.com/document-services/apis/sign-api/)
- [APIReference](https://opensource.adobe.com/acrobat-sign/developer_guide/index.html)
- [GettingStarted](https://experienceleague.adobe.com/en/docs/acrobat-services-learn/tutorials/acrobatsign/signapi)

### Adobe I/O Events
Adobe I/O Events provides an event-driven webhook infrastructure for subscribing to changes across Adobe services. Developers register webhook endpoints to receive real-time HTTP POST notifications when events occur, such as Creative Cloud Libraries asset updates, Photoshop API job completions, or Experience Cloud data changes. Webhook payloads include an x-adobe-signature header for authenticity verification. Event registrations are configured through the Adobe Developer Console and support filtering and routing rules.

**Human URL:** [https://developer.adobe.com/events/](https://developer.adobe.com/events/)


#### Tags:

 - Webhooks, Events, Real-Time, Notifications, Event-Driven

#### Properties

- [Documentation](https://developer.adobe.com/events/docs/guides/)
- [GitHubRepository](https://github.com/AdobeDocs/adobeio-events)
- [AsyncAPI](asyncapi/adobe-io-events-asyncapi-original.yml)

### Adobe I/O Runtime
A serverless computing platform built on Apache OpenWhisk that enables developers to deploy and execute custom code on Adobe's cloud infrastructure. I/O Runtime supports event-driven and HTTP-triggered function execution in JavaScript, Python, and other languages. Functions can be invoked via REST API or CLI and integrate natively with Adobe I/O Events for reactive workflows. The platform is a core component of Adobe App Builder and eliminates the need to manage server infrastructure for custom Adobe integrations.

**Human URL:** [https://developer.adobe.com/app-builder/docs/get_started/runtime_getting_started/](https://developer.adobe.com/app-builder/docs/get_started/runtime_getting_started/)


#### Tags:

 - Serverless, Functions, FaaS, Cloud Computing, OpenWhisk

#### Properties

- [Documentation](https://developer.adobe.com/app-builder/docs/get_started/runtime_getting_started/)
- [Documentation](https://adobedocs.github.io/adobeio-runtime/)

### Adobe App Builder
A complete application development framework for building custom enterprise applications on Adobe infrastructure. App Builder combines Adobe I/O Runtime for serverless backend functions, Adobe I/O Events for event-driven architecture, and React Spectrum for consistent UI components. Developers can build headful single-page applications or headless microservices that extend Adobe Experience Cloud solutions. The framework includes a CLI, code generators, and deployment tooling for building, testing, and publishing applications to the Adobe ecosystem.

**Human URL:** [https://developer.adobe.com/app-builder/](https://developer.adobe.com/app-builder/)


#### Tags:

 - Application Framework, Enterprise, React Spectrum, Custom Apps, SPA

#### Properties

- [Documentation](https://developer.adobe.com/app-builder/docs/overview/)
- [GettingStarted](https://developer.adobe.com/app-builder/docs/intro_and_overview/)

### Adobe UXP (Unified Extensibility Platform)
The Unified Extensibility Platform (UXP) is Adobe's modern cross-app plugin development framework replacing the legacy CEP platform. UXP uses a JavaScript engine with support for ES6+ and provides a common set of platform APIs for file system access, network I/O, and UI rendering using HTML, CSS, and curated Spectrum design components. Plugins built with UXP run natively within Creative Cloud desktop applications including Photoshop, InDesign, Illustrator, Premiere Pro, and XD. UXP supports both full plugin panels and lightweight scripts for workflow automation.

**Human URL:** [https://developer.adobe.com/photoshop/uxp/2022/](https://developer.adobe.com/photoshop/uxp/2022/)


#### Tags:

 - Plugin Framework, JavaScript, HTML/CSS, Cross-App, Extensions, Modern

#### Properties

- [Documentation](https://developer.adobe.com/photoshop/uxp/2022/)
- [GitHubRepository](https://github.com/adobe/cc-ext-uxp-types)

### Adobe CEP (Common Extensibility Platform)
The Common Extensibility Platform (CEP) is Adobe's legacy framework for building integrated HTML5 panels across multiple Creative Cloud desktop applications. CEP panels use HTML5, CSS, and JavaScript for the UI layer and communicate with application DOMs through ExtendScript. The framework supports InDesign, Photoshop, Illustrator, Premiere Pro, Audition, After Effects, and other CC applications. While CEP is still supported and functional, Adobe recommends migrating to UXP for new plugin development as UXP provides improved performance, modern JavaScript support, and a more secure execution environment.

**Human URL:** [https://adobe-cep.github.io/CEP-Resources/](https://adobe-cep.github.io/CEP-Resources/)


#### Tags:

 - Plugin Framework, Legacy, HTML5, ExtendScript, Panels

#### Properties

- [Documentation](https://adobe-cep.github.io/CEP-Resources/)
- [GitHubRepository](https://github.com/Adobe-CEP/CEP-Resources)
- [GitHubRepository](https://github.com/Adobe-CEP/Getting-Started-guides)
- [JSONSchema](json-schema/adobe-cep-extension-manifest-schema.json)

### Adobe Photoshop API
A cloud-based REST API that provides programmatic access to Photoshop's image editing capabilities without requiring a local installation. Part of Adobe Firefly Services, the API supports PSD document operations, layer editing, Smart Object replacement, text layer editing, background removal, mask creation, product crop, depth blur, and Photoshop Actions execution. All operations are asynchronous, returning a polling URL to check job status.

**Human URL:** [https://developer.adobe.com/photoshop/](https://developer.adobe.com/photoshop/)


#### Tags:

 - Image Processing, Photoshop, Automation, Cloud, Firefly Services

#### Properties

- [Documentation](https://developer.adobe.com/firefly-services/docs/photoshop/)
- [APIReference](https://developer.adobe.com/firefly-services/docs/photoshop/api/)

### Adobe Lightroom API
A REST API for managing photos, albums, and applying presets in Adobe Lightroom, enabling automated photo organization and editing workflows. The API provides programmatic access to Lightroom's cloud-based photo library including uploading and downloading photos, creating and managing albums, applying editing presets, and retrieving photo metadata. Part of Adobe Firefly Services for cloud-based image processing automation.

**Human URL:** [https://developer.adobe.com/lightroom/](https://developer.adobe.com/lightroom/)


#### Tags:

 - Photography, Photo Management, Image Editing, Cloud, Presets

#### Properties

- [Documentation](https://developer.adobe.com/lightroom/lightroom-api-docs/)
- [APIReference](https://developer.adobe.com/lightroom/lightroom-api-docs/api/)

### Adobe Developer Distribution
The Adobe Developer Distribution portal for publishing and managing plugins and extensions in the Creative Cloud Marketplace and Adobe Exchange. Supports UXP plugins, CEP extensions (ZXP format), and other extension types across Creative Cloud applications. The portal provides listing management, version control, metadata editing, scheduled and immediate publication, and the ability to recall or retract published listings. Developers submit plugins through a review process before they become available to Creative Cloud users.

**Human URL:** [https://developer.adobe.com/developer-distribution/creative-cloud/](https://developer.adobe.com/developer-distribution/creative-cloud/)


#### Tags:

 - Plugin Distribution, Marketplace, Exchange, Publishing

#### Properties

- [Documentation](https://developer.adobe.com/developer-distribution/creative-cloud/)
- [GettingStarted](https://developer.adobe.com/developer-distribution/creative-cloud/docs/guides/getting-started)
- [Documentation](https://developer.adobe.com/developer-distribution/creative-cloud/docs/guides/submission/overview)

## Common Properties

- [Portal](https://developer.adobe.com/)
- [Portal](https://developer.adobe.com/creative-cloud/)
- [Documentation](https://developer.adobe.com/apis)
- [Portal](https://developer.adobe.com/developer-console/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/ServerToServerAuthentication/)
- [Website](https://www.adobe.com/creativecloud.html)
- [Blog](https://blog.developer.adobe.com/)
- [Blog](https://medium.com/adobetech)
- [Forum](https://forums.creativeclouddeveloper.com)
- [Forum](https://community.adobe.com/)
- [GitHubOrganization](https://github.com/adobe)
- [GitHubOrganization](https://github.com/AdobeDocs)
- [GitHubOrganization](https://github.com/Adobe-CEP)
- [Support](https://developer.adobe.com/support/)
- [Pricing](https://developer.adobe.com/document-services/pricing/main/)
- [Status](https://status.adobe.com/)
- [Documentation](https://developer.adobe.com/adobe-status/)
- [Security](https://helpx.adobe.com/security.html)
- [X](https://x.com/AdobeDevs)
- [YouTube](https://www.youtube.com/@AdobeCreativeCloud)
- [TermsOfService](https://www.adobe.com/legal/terms.html)
- [PrivacyPolicy](https://www.adobe.com/privacy/policy.html)
- [License](https://www.adobe.com/legal/licenses-terms.html)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
