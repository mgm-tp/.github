<a  href="https://a12.ai"> <img  src="https://www.mgm-tp.com/global-content/cd/logos/a12/app-icons/light/A12-Light.svg" height="200"  alt="A12 logo"/> </a>

# mgm A12 AI Low Code Plattform

**English version: [here](./README.md).**
<br/>

**A12** ist eine Plattform zur Entwicklung von Unternehmenssoftware in komplexen IT-Landschaften. Aufgebaut auf modellgetriebener Softwareentwicklung (MDSE), überträgt sie das Low-Code-Prinzip auf große, geschäftskritische Anwendungen — von Portalen und Antragsmanagementsystemen der öffentlichen Verwaltung über digitale Registerlösungen bis hin zu komplexen Geschäftsprozessen in verschiedenen Branchen. KI-Funktionen sind auf zwei Ebenen integriert — innerhalb von Anwendungen und auf Entwicklungsebene durch Agentic Coding —
stets in einem deterministischen, kontrollierten Rahmen, der Teams die vollständige Kontrolle sichert.


## Kernfunktionen

- **Modellgetriebene Entwicklung** — Geschäftslogik wird modelliert, nicht kodiert; das reduziert den Entwicklungsaufwand und erhöht die langfristige Wartbarkeit
- **Enterprise-KI** — KI-Integration auf Anwendungs- und Entwicklungsebene, gesteuert durch einen deterministischen Rahmen (Enterprise Edition)
- **Vollständiges Komponentenökosystem** — Von der Datenschicht über UI-Engines und Authentifizierung bis hin zu Workflows — alles in einer Plattform 
- **Erweiterbar** — Eigener Code, externe Datenquellen, APIs oder UI-Anpassungen lassen sich nahezu ohne Einschränkungen integrieren
- **Skalierbar** — Bewährt in geschäftskritischen Umgebungen mit mehr als 200.000 gleichzeitig aktiven Nutzenden
- **Offene Standards** — Kein Vendor Lock-in; basiert auf offenen Standards mit EUPL v1.2-Lizenzierung, offenen Low-Code-Modellen und offenem Anwendungscode
- **Barrierefreiheit & Compliance** — WCAG-konforme UI-Komponenten mit integrierter Sicherheit und Governance
- **Duales Lizenzmodell** — Verfügbar unter EUPL 1.2 und kommerzieller Lizenz mit definiertem Support (SLA)

## A12 Editionen

Diese Software wird von der [mgm technology partners GmbH](https://www.mgm-tp.com/) entwickelt und dual lizenziert.

Es muss genau eine Lizenzoption ausgewählt und eingehalten werden (siehe auch Datei [LICENSE](LICENSE)).

Das **[A12 Modeling Environment](https://geta12.com/#/docs/latest/latest/overall/installing_a12)** ist unabhängig von der Lizenz kostenlos nutzbar.

Das [A12 Community Forum](https://discourse.geta12.com/) kann für Fehlerberichte oder Funktionsvorschläge genutzt werden. Reaktionszeiten werden jedoch nur im Rahmen eines Enterprise Support Agreements zugesichert.

Einen vollständigen Überblick bietet [Editionen & Lizenzierung](https://geta12.com/#/editions-licensing).


### Community Edition - Open Source

[![License:EUPL-1.2](https://img.shields.io/badge/License-EUPL_1.2-orange)](https://eupl.eu/1.2/de/)

Die **A12 Community Edition** umfasst den A12 Platform Core (alle unten aufgeführten Repositories),  lizenziert unter der  [European Public License - EUPL v1.2](https://eupl.eu/). Der Lizenztext ist abrufbar unter https://eupl.eu/1.2/de/ (deutsche Fassung maßgebend).

### Enterprise Edition - Kommerzielle Lizenz

[![License:Commercial](https://img.shields.io/badge/License-Kommerziell-orange)](https://geta12.com/#/editions-licensing)

Die **Enterprise Edition** erweitert die Community Edition um zusätzliche Komponenten und Funktionen — darunter KI-Services, weitere UI-Komponenten und Enterprise-Integrationen — und beinhaltet Enterprise Support mit Service Level Agreement (SLA).

Für kommerzielle Lizenzierung einschließlich Enterprise Support mit SLA kontaktieren Sie bitte [a12-license@mgm-tp.com](mailto:a12-license@mgm-tp.com)

## Erste Schritte

[![Documentation](https://img.shields.io/badge/Docs-Geta12.com-green)](https://geta12.com/#/docs)  [![Community](https://img.shields.io/badge/Community-Forum-green)](https://discourse.geta12.com/) [![A12 Blog](https://img.shields.io/badge/Blog-mgm_Insights-green)](https://insights.mgm-tp.com/de/)
[![A12 Platform Code](https://img.shields.io/badge/A12-Platform_Code-blue)](https://github.com/mgm-tp) [![A12 Tutorial Apps](https://img.shields.io/badge/A12-Tutorial_Apps-blue)](https://github.com/mgm-tp/a12-tutorial-application) [![A12 Project Template](https://img.shields.io/badge/A12-Project_Template-blue)](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation)

### Voraussetzungen

Folgendes Toolset wird zum Erstellen von A12-Anwendungen benötigt:
- JDK<sup>2</sup> ≥21 bis ≤25
- Gradle<sup>1</sup> ≥9.0.x
- Node 24.x.x
- npm<sup>1</sup> ≥11.x.x
- Docker<sup>1</sup> >=20.x
- Docker Compose >=2.20.3

<sup>1</sup>) Diese Tools müssen für den Zugriff auf Artifactory konfiguriert werden, siehe [technische Dokumentation](https://geta12.com/#/docs/latest/latest/overall/a12_development) für Details.
<sup>2</sup>) SDKMAN empfohlen für Linux und macOS; unter Windows nur über WSL.

**Je nach Anwendungsfall einen der folgenden Pfade wählen:**

### Anwendungen mit A12 entwickeln

Die Plattform selbst muss nicht gebaut werden. mgm stellt alle erforderlichen Artefakte vorgefertigt bereit.

- [A12 Modeling Environment](https://geta12.com/#/docs/latest/latest/overall/installing_a12) — A12-Modelle, Vorschauen und Anwendungen erstellen. Kostenlos nutzbar.
- [A12 Tutorial Apps](https://github.com/mgm-tp/a12-tutorial-application) — Einstieg in die Entwicklung mit A12
- [A12 Project Template](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation) — Ausgangspunkt für neue A12-Anwendungen
- [Technische Dokumentation](https://geta12.com/#/docs/latest/latest/overall/a12_development) — Vollständige Plattformdokumentation auf [GetA12.com](https://geta12.com/)

Viele Komponenten-Repositories enthalten einen `devapp` oder `showcase` Ordner mit Beispielcode und Best Practices des A12 Entwicklungs-Teams.

Zum Einstieg die Dokumentation des
[A12 Project Template](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation)
lesen und das Template-Repository klonen:

```bash
git clone https://github.com/mgm-tp/a12-full-stack-project-template
```

### Die A12 Plattform bauen

Der Quellcode der A12 Platform Community Edition ist verfügbar unter:
<https://github.com/mgm-tp>

Jede Komponente hat ein eigenes Repository. Die Build-Anweisungen finden sich im jeweiligen Ordner.

## A12 Komponenten (Repositories)

| Ebene | Komponente | Repository | Beschreibung |
|---|---|---|---|
| Projekt | Project Template | [a12-full-stack-project-template](https://github.com/mgm-tp/a12-full-stack-project-template) | Ausgangspunkt für A12-Projekte. Zeigt eine mögliche Projektstruktur, stets auf dem aktuellen A12-Stand. [Dokumentation](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation) |
| Core | Base | [a12-base](https://github.com/mgm-tp/a12-base) | Stellt einheitliche Modellschnittstellen und eine Validierungsinfrastruktur bereit. Die Model API Library definiert eine standardisierte Modellstruktur (TypeScript/Java). Die Model Consistency Library ermöglicht systematische Validierung mit konfigurierbaren Regeln und Schweregraden. |
| Core | Kernel | [a12-kernel](https://github.com/mgm-tp/a12-kernel) | Kernfunktionalität zur Verarbeitung von Datenmodellen und Instanzen (Document Models und Documents). Enthält eine DSL für Validierungen und Berechnungen, Code-Generatoren für Java, TypeScript und Groovy sowie client- und serverseitige Laufzeitkomponenten mit Java- und TypeScript-API. |
| Core | Localization | [a12-localization](https://github.com/mgm-tp/a12-localization) | Hilfsbibliothek für Lokalisierung und Konvertierung in A12-Anwendungen, mit Integration für A12-Modelldatenstrukturen. |
| Core | Data Services | [a12-dataservices](https://github.com/mgm-tp/a12-dataservices) | Dokumentenorientierte Datenschicht von A12. Bietet hochperformanten, erweiterbaren und skalierbaren Datenzugriff über CLI, TypeScript-API, Java-API oder HTTP. Die Query API unterstützt präzises Filtern. |
| Core | Client | [a12-client](https://github.com/mgm-tp/a12-client) | Modellgetriebene, clientseitige Laufzeitkomponente. Implementiert das Plasma Design System und unterstützt Desktop, Tablet und Smartphone. Übernimmt Orchestrierung, Datenabruf und Zustandsverwaltung. |
| Core | Relationship Engine | [a12-relationship-engine](https://github.com/mgm-tp/a12-relationship-engine) | Ermöglicht die Definition von Beziehungen zwischen A12 Document Models und bildet die Grundlage der Datenanwendungsarchitektur. Wird von Form, Overview und Tree Models verwendet. |
| Core | Workflows | [a12-workflows](https://github.com/mgm-tp/a12-workflows) | Integriert BPMN und DMN in A12 für grafische Modellierung und serverseitige Ausführung von Geschäftsprozessen, einschließlich Human Tasks, Service Tasks und bedingter Gateways. |
| Core | Print Engine | [a12-print](https://github.com/mgm-tp/a12-print) | Erzeugt PDF/A-3 und PDF/UA aus Print Models; WYSIWYG Print Model Editor für barrierefreie Bescheide und Dokumente. |
| Core | UAA | [a12-uaa](https://github.com/mgm-tp/a12-uaa) | Bündelt Lösungen rund um Authentifizierung (Keycloak, OAuth 2.0/OpenID, SAML, LDAP) und Autorisierung (Spring Security, RBAC, ABAC, eigene Logik). Bietet flexible, attributbasierte Zugriffskontrolle bis auf Feldebene von Datendokumenten. |
| Library | Utils | [a12-utils](https://github.com/mgm-tp/a12-utils) | Querschnittsbibliotheken: typsichere Collections, ein Logger mit austauschbaren Ausgabestrategien und ein Server Connector für HTTP-REST-Kommunikation. |
| Library | Server Connector | [a12-utils-server-connector](https://github.com/mgm-tp/a12-utils-server-connector) | Generische Komponente für Request-Response-Serverkommunikation. |
| UI | Content Engine | [a12-content-engine](https://github.com/mgm-tp/a12-content-engine) | Wandelt Content Models in interaktive Benutzeroberflächen mit einheitlicher Struktur, Gestaltung und Verhalten um. |
| UI | Widgets | [a12-widgets](https://github.com/mgm-tp/a12-widgets) | Vorgefertigte, WCAG-konforme UI-Komponenten für die Erstellung interaktiver Oberflächen mit einheitlichem Look & Feel in A12-Anwendungen. |
| UI | Form Engine | [a12-form-engine](https://github.com/mgm-tp/a12-form-engine) | Interpretiert Form Models und rendert sie als interaktive Formulare — einschließlich Screens, Sections, wiederholbarer Strukturen, modellierter Aktionen und Navigation. |
| UI | Overview Engine | [a12-overview-engine](https://github.com/mgm-tp/a12-overview-engine) | React-Komponente für die Darstellung vollständiger Übersichten aus Overview und Document Models, mit Paginierung, Infinite Scroll, Suche, Sortierung und Mehrfachauswahl. |
| UI | Tree Engine | [a12-tree-engine](https://github.com/mgm-tp/a12-tree-engine) | Modellgetriebene UI-Komponenten zur Konfiguration und Darstellung vollständiger Baumansichten. Unterstützt umfangreiche Anpassung, Drag & Drop und skalierbares Datenladen. |
| UI | Diagram Editor | [a12-diagram-editor](https://github.com/mgm-tp/a12-diagram-editor) | Vollständiges Framework für interaktive Diagramme auf Basis von React und Redux. Unterstützt Erstellen, Verbinden und Löschen von Knoten und Kanten; anpassbar über eigene Knoten, Kanten und Ports. |
| UI | Expressions | [a12-expression](https://github.com/mgm-tp/a12-expression) | Konfigurierbare, schreibgeschützte Anzeige von Dokumentfeldinhalten über eine dedizierte Ausdruckssprache. Unterstützt Feldreferenzen, bedingte Ausdrücke und Markdown-Formatierung. |
| Library | Migration Tool | [a12-migration-tool](https://github.com/mgm-tp/a12-migration-tool) | Einheitliches Migrationswerkzeug, das komponentenspezifische Migrationstools in einem konsistenten Framework vereint — mit einheitlicher CLI/Browser-Nutzung, APIs und Fehlerbehandlung. |
| Library | ANTLR Code Editor | [a12-antlr4-code-editor](https://github.com/mgm-tp/a12-antlr4-code-editor) | Editor-Widget für ANTLR4-basierte domänenspezifische Sprachen mit Syntaxvalidierung, Syntaxhervorhebung und Auto-Vervollständigung. |
| Library | ANTLR4 | [a12-kernel-antlr4](https://github.com/mgm-tp/a12-kernel-antlr4) | Fork der ANTLR4-Bibliothek mit Anpassungen für die Kernel-Komponente. |

## Mitwirkung (Contributions)

Die A12-Repositories sind derzeit für externe Beiträge schreibgeschützt. Als großskalige Enterprise-Plattform mit Millionen von Codezeilen braucht der Aufbau geeigneter Richtlinien, Review-Prozesse, Qualitätsstandards Zeit. Wir arbeiten daran, mittelfristig Beiträge zu ermöglichen und werden Updates im [A12 Blog](https://geta12.com/#/blog) ankündigen.

**Fehler gefunden oder Verbesserungsvorschlag?**
- **Plattform-Issues & Feature Requests** — einreichen über [GetA12.com](https://geta12.com/)
- **Fragen & Diskussionen** — im [A12 Community Forum](https://discourse.geta12.com/)
- **Geschäftliche Anfragen** — per [hello.a12@mgm-tp.com](mailto:hello.a12@mgm-tp.com)
- **Sicherheitslücken** — siehe [SECURITY.md](./SECURITY.md)
- **Support** — siehe [SUPPORT.md](./SUPPORT.md)

In der Zwischenzeit: Quellcode und die Code-Beispiele in den Komponenten-Repositories erkunden. Das
[A12 Modeling Environment](https://geta12.com/#/docs/latest/latest/overall/installing_a12) installieren und das [A12 Project Template](https://geta12.com/#/docs/latest/latest/project_template/project-template-documentation) für den Aufbau einer Entwicklungsumgebung nutzen.

## Kontakt

- [A12 Community Forum](https://discourse.geta12.com/) (technisch)
- [hello.a12@mgm-tp.com](mailto:hello.a12@mgm-tp.com) (geschäftlich)
- [a12-license@mgm-tp.com](mailto:a12-license@mgm-tp.com) (kommerzielle Lizenz)

---

**Das mgm A12 Team**

[mgm technology partners GmbH](https://www.mgm-tp.com/) | [a12.ai](https://a12.ai) | [mgm Insights Blog](https://insights.mgm-tp.com/de/) | [Impressum](https://www.mgm-tp.com/imprint.html)
