
<a href="https://a12.ai"> <img src="https://www.mgm-tp.com/global-content/cd/logos/a12/app-icons/light/A12-Light.svg" height="200" alt="A12 logo"/> </a>

# mgm A12 AI Low Code Platform

**Deutsche Version: [hier](../README_DE.md).**
<br/>

**A12** is a platform for developing enterprise software in complex IT landscapes. Built on Model-Driven Software Engineering (MDSE), it applies the low-code principle to large-scale, mission-critical applications — from public sector portals and application management systems to digital register solutions and complex business processes across industries. AI capabilities are integrated at two levels — within applications and at the development level through Agentic Coding — always within a deterministic, governed framework that keeps teams in full control.


## Key Features

- **Model-Driven Development** — Business logic is modeled, not coded; reducing development effort and increasing long-term maintainability
- **Enterprise AI** — AI integration at both the application and development level, governed by a deterministic framework (Enterprise Edition)
- **Full Component Ecosystem** — From data layer to UI engines, authentication, and workflows — everything in one platform
- **Extendable** — Custom code, external data sources, APIs or UI styling can be integrated with almost no limitations
- **Built for Scale** — Battle-tested in mission-critical environments with 200K+ concurrent users
- **Open Standards** — No vendor lock-in; built on open standards with EUPL v1.2 licensing, open low code models and application code
- **Accessibility & Compliance** — WCAG-compliant UI components with integrated security and governance
- **Dual License** — Available under EUPL 1.2 and commercial license with defined support (SLA)

## A12 Editions

This software is developed by [mgm technology partners GmbH](https://www.mgm-tp.com/) and dual-licensed.

Exactly one licensing option must be selected and complied with (see also file [LICENSE](LICENSE)).

The [A12 Modeling Environment](https://geta12.com/#/docs/latest/latest/overall/installing_a12) is free to use independently of the license.

The [A12 Community Forum](https://discourse.geta12.com/) can be used for bug reports or feature requests. However, response times are only guaranteed under an Enterprise Support Agreement.

See [Editions & Licensing](https://geta12.com/#/editions-licensing) for a full comparison.

### Community Edition - Open Source

[![License:EUPL-1.2](https://img.shields.io/badge/License-EUPL_1.2-orange)](https://eupl.eu/1.2/de/)

The **A12 Community Edition** includes the A12 Platform Core (all repositories listed below), licensed under the
[European Union Public Licence - EUPL v1.2](https://eupl.eu/) - license text is available at https://eupl.eu/1.2/de/
(German version prevailing).

### Enterprise Edition - Commercial License

[![License:Commercial](https://img.shields.io/badge/License-Commercial-orange)](https://geta12.com/#/editions-licensing)

The **Enterprise Edition** extends the Community Edition with additional components and capabilities — among them AI Services, further UI components, and enterprise integrations — and includes Enterprise Support with a Service Level Agreement (SLA).

For commercial licensing including Enterprise Support with SLA, please contact [a12-license@mgm-tp.com](mailto:a12-license@mgm-tp.com)

## Getting Started

[![Documentation](https://img.shields.io/badge/Docs-Geta12.com-green)](https://geta12.com/#/docs)  [![Community](https://img.shields.io/badge/Community-Forum-green)](https://discourse.geta12.com/) [![A12 Blog](https://img.shields.io/badge/Blog-mgm_Insights-green)](https://insights.mgm-tp.com/de/)
[![A12 Platform Code](https://img.shields.io/badge/A12-Platform_Code-blue)](https://github.com/mgm-tp) [![A12 Tutorial Apps](https://img.shields.io/badge/A12-Tutorial_Apps-blue)](https://github.com/mgm-tp/a12-tutorial-application) [![A12 Project Template](https://img.shields.io/badge/A12-Project_Template-blue)](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation)

### Prerequisites

The following toolset is required to build A12 applications:
- JDK<sup>2</sup> ≥21 to ≤25
- Gradle<sup>1</sup> ≥9.0.x
- Node 24.x.x
- npm<sup>1</sup> ≥11.x.x
- Docker<sup>1</sup> >=20.x
- Docker Compose >=2.20.3

<sup>1</sup>) These tools must be configured for Artifactory access, see [technical documentation](https://geta12.com/#/docs/latest/latest/overall/a12_development) for details.
<sup>2</sup>) SDKMAN recommended on Linux and macOS; on Windows only via WSL.

**Depending on your use case, choose one of the following paths:**

### Building Applications with A12

There is no need to build the platform itself. mgm provides all required artifacts pre-built.

- [A12 Modeling Environment](https://geta12.com/#/docs/latest/latest/overall/installing_a12) — Create A12 models, previews, and applications. Free to use.
- [A12 Tutorial Apps](https://github.com/mgm-tp/a12-tutorial-application) — Introduction to development with A12
- [A12 Project Template](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation) — Starting point for new A12 applications
- [Technical Documentation](https://geta12.com/#/docs/latest/latest/overall/a12_development) — Full platform documentation on [GetA12.com](https://geta12.com/)

Many component repositories include a `devapp` or `showcase` folder with tutorial code and best practices from the A12 development team.

To get started, check the
[A12 Project Template](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation)
documentation and clone the template repository:

```bash
git clone https://github.com/mgm-tp/a12-full-stack-project-template
```

### Building the A12 Platform

The source code of the A12 Platform Community Edition is available at:
<https://github.com/mgm-tp>

Each component has its own repository. Build instructions can be found in the respective folder.

## A12 Components (Repositories)

| Layer | Component | Repository | Description |
|---|---|---|---|
| Project | Project Template | [a12-full-stack-project-template](https://github.com/mgm-tp/a12-full-stack-project-template) | Starting point for A12 projects. Shows one way to structure a project, always kept up to date with the latest A12 version. [Documentation](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation) |
| Core | Base | [a12-base](https://github.com/mgm-tp/a12-base) | Provides unified model interfaces and a validation infrastructure. The Model API Library defines a standardized model structure (TypeScript/Java). The Model Consistency Library enables systematic validation with configurable rules and severity levels. |
| Core | Kernel | [a12-kernel](https://github.com/mgm-tp/a12-kernel) | Core functionality for processing data models and instances (Document Models and Documents). Includes a DSL for validations and computations, code generators for Java, TypeScript, and Groovy, both client- and server-side runtime components, and a Java and TypeScript API. |
| Core | Localization | [a12-localization](https://github.com/mgm-tp/a12-localization) | Utility library for localization and conversion functionality in A12-based applications, with integration for A12 model data structures. |
| Core | Data Services | [a12-dataservices](https://github.com/mgm-tp/a12-dataservices) | Document-oriented data layer of A12. Provides high-performance, extensible, and scalable data access via CLI, TypeScript API, Java API, or HTTP. The Query API supports precise filtering. |
| Core | Client | [a12-client](https://github.com/mgm-tp/a12-client) | Model-driven, client-side runtime component. Implements the Plasma Design System and supports desktop, tablet, and smartphone. Handles orchestration, data retrieval, and state management. |
| Core | Relationship Engine | [a12-relationship-engine](https://github.com/mgm-tp/a12-relationship-engine) | Enables the definition of relationships between A12 Document Models, forming the foundation of an application's data architecture. Used by Form, Overview, and Tree models. |
| Core | Workflows | [a12-workflows](https://github.com/mgm-tp/a12-workflows) | Integrates BPMN and DMN into A12 for graphical modeling and server-side execution of business processes, including human tasks, service tasks, and conditional gateways. |
| Core | Print Engine | [a12-print](https://github.com/mgm-tp/a12-print) | Generates PDF/A-3 and PDF/UA output from Print Models; WYSIWYG Print Model Editor for accessible documents and notices. |
| Core | UAA | [a12-uaa](https://github.com/mgm-tp/a12-uaa) | Bundles solutions around authentication (Keycloak, OAuth 2.0/OpenID, SAML, LDAP) and authorization (Spring Security, RBAC, ABAC, custom logic). Provides flexible, attribute-based access control down to the field level of data documents. |
| Library | Utils | [a12-utils](https://github.com/mgm-tp/a12-utils) | Cross-cutting libraries: type-safe collections, a logger with pluggable output strategies, and a server connector for HTTP REST communication. |
| Library | Server Connector | [a12-utils-server-connector](https://github.com/mgm-tp/a12-utils-server-connector) | Generic component for request/response server communication. |
| UI | Content Engine | [a12-content-engine](https://github.com/mgm-tp/a12-content-engine) | Turns Content Models into interactive user interfaces with consistent structure, styling, and behavior. |
| UI | Widgets | [a12-widgets](https://github.com/mgm-tp/a12-widgets) | Pre-built, WCAG-compliant UI components for assembling interactive interfaces with a consistent look and feel across A12 applications. |
| UI | Form Engine | [a12-form-engine](https://github.com/mgm-tp/a12-form-engine) | Interprets Form Models and renders them as interactive forms — including screens, sections, repeatable structures, modeled actions, and navigation. |
| UI | Overview Engine | [a12-overview-engine](https://github.com/mgm-tp/a12-overview-engine) | React component for rendering full-featured overviews from Overview and Document Models, with pagination, infinite scroll, search, sorting, and multi-selection. |
| UI | Tree Engine | [a12-tree-engine](https://github.com/mgm-tp/a12-tree-engine) | Model-driven UI components for configuring and rendering full-featured tree views. Supports deep customization, drag & drop, and scalable data loading. |
| UI | Diagram Editor | [a12-diagram-editor](https://github.com/mgm-tp/a12-diagram-editor) | Complete framework for interactive diagrams based on React and Redux. Supports creating, connecting, and deleting nodes and edges; customizable via custom nodes, edges, and ports. |
| UI | Expressions | [a12-expression](https://github.com/mgm-tp/a12-expression) | Configurable, read-only display of document field values using a dedicated expression language. Supports field references, conditional expressions, and Markdown formatting. |
| Library | Migration Tool | [a12-migration-tool](https://github.com/mgm-tp/a12-migration-tool) | Unified migration tool that standardizes engine-specific migration tools into a consistent framework — aligning CLI/browser usage, APIs, and error handling. |
| Library | ANTLR Code Editor | [a12-antlr4-code-editor](https://github.com/mgm-tp/a12-antlr4-code-editor) | Editor widget for ANTLR4-based domain-specific languages, with syntax validation, syntax highlighting, and auto-suggestions. |
| Library | ANTLR4 | [a12-kernel-antlr4](https://github.com/mgm-tp/a12-kernel-antlr4) | Fork of the ANTLR4 library with customizations for the Kernel component. |

## Contributing

A12 repositories are currently read-only for external contributions. As a large-scale enterprise platform with millions of lines of code, setting up appropriate guidelines, review processes, and quality standards takes time. We are working on enabling contributions in the medium term and will announce updates on the [A12 Blog](https://geta12.com/#/blog).

**Found a bug or have a suggestion?**
- **Platform issues & feature requests** — submit via [GetA12.com](https://geta12.com/)
- **Questions & discussions** — use the [A12 Community Forum](https://discourse.geta12.com/)
- **Business inquiries** — contact [hello.a12@mgm-tp.com](mailto:hello.a12@mgm-tp.com)
- **Security vulnerabilities** — see [SECURITY.md](../SECURITY.md)
- **Support** — see [SUPPORT.md](../SUPPORT.md)

In the meantime, feel free to explore the codebase and the code examples in the component repositories. Install the
[A12 Modeling Environment](https://geta12.com/#/docs/latest/latest/overall/installing_a12) and check the [A12 Project Template](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation) for details on how to set up a development environment.

## Contact

- [A12 Community Forum](https://discourse.geta12.com/) (technical)
- [hello.a12@mgm-tp.com](mailto:hello.a12@mgm-tp.com) (business)
- [a12-license@mgm-tp.com](mailto:a12-license@mgm-tp.com) (commercial licensing)

---

**The mgm A12 Team**

[mgm technology partners GmbH](https://www.mgm-tp.com/) | [a12.ai](https://a12.ai) | [mgm Insights Blog](https://insights.mgm-tp.com/de/) | [Imprint](https://www.mgm-tp.com/imprint.html)
