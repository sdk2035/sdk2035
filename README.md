# Kevin Sanchez

### Senior Software Engineer & Systems Architect

**Enterprise modernization · AI integration · Scientific computing · Polyglot runtimes**

Lima, Peru · Open to remote opportunities across LATAM and the U.S., technical partnerships and collaborative R&D.

[LinkedIn](https://www.linkedin.com/in/kjsanc) · [Email](mailto:kjsanc@gmail.com) · [Personal repositories](https://github.com/sdk2035?tab=repositories) · [Robotics & Intelligent Systems](https://github.com/robotics-intelligent-systems)

## About

I am a systems analyst and senior software engineer with **10+ years of experience**
across **50+ enterprise projects** in FinTech, banking, microfinance, e-commerce,
ERP and electronic invoicing.

I design modular systems and practical modernization paths across **Java, .NET
and cloud platforms**, combining explicit integration contracts with AI-assisted
engineering and behavior-preserving validation.

My open research portfolio connects **enterprise modernization, language runtimes
and scientific computing**: GraalVM/Truffle, JVM/.NET interoperability, Modelica,
data pipelines and 3D engineering tools. The JFX projects contribute complementary
architecture workstreams alongside the domain portfolio at
[Robotics & Intelligent Systems](https://github.com/robotics-intelligent-systems).

The project tables below show the current evidence, an indicative delivery stage
and a proposed next task that AI can help draft, implement or test.

## Explore

- [Engineering Focus](#engineering-focus)
- [Personal Project Portfolio](#personal-project-portfolio)
  - [Project Progress Guide](#reading-the-progress-bars)
  - [Enterprise Modernization and Business Platforms](#enterprise-modernization-and-business-platforms)
    - [GraalCOBOL: COBOL Modernization](#graalcobol--cobol-modernization-and-mainframe-integration)
  - [Modeling, Simulation and Digital Twins](#modeling-simulation-and-digital-twins)
  - [Complementary JFX Engineering Projects](#complementary-jfx-engineering-projects)
  - [AI Infrastructure and Distributed Inference](#ai-infrastructure-and-distributed-inference)
  - [Scientific Computing Languages](#scientific-computing-languages)
  - [JVM and .NET Interoperability](#jvm-and-net-interoperability)
  - [Metaprogramming and Language Workbenches](#metaprogramming-and-language-workbenches)
  - [Polyglot Language Projects](#polyglot-language-projects)
  - [3D Modeling, CAD and Educational Visualization](#3d-modeling-cad-and-educational-visualization)
- [Selected Organization Projects](#selected-organization-projects)
- [JFX Portfolio Integration Proposal](docs/propuesta-integracion-portafolio-jfx.md)
- [Technology Stack](#technology-stack)
- [Collaboration](#collaboration)

## Engineering Focus

| Area | Focus |
| --- | --- |
| Enterprise modernization | Modular architectures, legacy integration, transactional systems and cloud migration |
| AI and knowledge systems | RAG, Model Context Protocol (MCP), agent integration and private/hybrid inference |
| Scientific computing | Physical modeling, digital twins, Scientific Machine Learning (SciML) and HPC |
| Language engineering | GraalVM/Truffle, metaprogramming and JVM/.NET interoperability |
| Engineering tools | Low-code simulation workflows, browser-based CAD and 3D visualization |

## Personal Project Portfolio

The following **29 repositories under sdk2035** are grouped by their primary focus.
This curated portfolio includes the complementary JFX projects now hosted here;
it is not an inventory of every repository or upstream fork in the account.
Descriptions summarize project scope; implementation status, supported features,
licensing and performance evidence belong to each repository's documentation.

### Reading the progress bars

**Snapshot: 2026-10-10.** These are editorial estimates of maturity toward a first
validated MVP, based on repository READMEs and visible contents; they are **not**
measured completion percentages, effort estimates or delivery commitments.

| Indicative stage | Bar | Evidence required |
| --- | --- | --- |
| Concept · ~10% | `█░░░░░░░░░` | Scope described; executable implementation not established |
| Architecture · ~20% | `██░░░░░░░░` | Design documents, contracts or architecture assets |
| Pilot · ~50% | `█████░░░░░` | Executable bounded pilot documented; broader validation pending |
| Validated MVP · ~80% | `████████░░` | Reproducible end-to-end acceptance evidence |
| Released scope · 100% | `██████████` | Declared MVP scope accepted and released |

**N/A** means a local integration milestone is not defined or inherited source
has not been assessed. Upstream maturity does not measure this portfolio's work.
Tasks are **AI-assisted proposals**, inferred from documented scope and gaps,
rather than an approved issue backlog. Maintainers review generated artifacts
and acceptance evidence. This snapshot is updated manually as milestones change.

### Enterprise Modernization and Business Platforms

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [OpenBAP](https://github.com/sdk2035/OpenBAP) | AI-assisted enterprise modernization platform combining Apache OFBiz, GraalVM/Truffle and OpenXava for semantic reconstruction, legacy ABAP interoperability and incremental ERP migration | Architecture | `██░░░░░░░░` ~20% | Define one ERP business-rule fixture and draft semantic equivalence checks. |
| [GraalCOBOL](https://github.com/sdk2035/GraalCOBOL) | Proposed COBOL modernization architecture combining Rascal MPL analysis, a versioned intermediate representation and Truffle/GraalVM execution, with mainframe training and Cobrix–Trino data integration | Architecture | `██░░░░░░░░` ~20% | Specify the first COBOL subset and draft decimal/copybook differential fixtures. |

OpenBAP focuses on semantic-first modernization: extracting legacy ERP metadata and business rules, mapping them to an open enterprise model, validating reconstructed behavior and supporting staged migration without reproducing proprietary application-server internals.

#### GraalCOBOL — COBOL Modernization and Mainframe Integration

[GraalCOBOL](https://github.com/sdk2035/GraalCOBOL) proposes an architecture to
**analyze, migrate and execute an explicitly defined subset of COBOL** using
**Rascal MPL, Truffle and GraalVM**, with gradual integration into existing systems.
Its focus is preserving business behavior while making legacy logic, data
contracts and migration boundaries explicit—particularly relevant to banking,
payroll and other transaction-oriented enterprise applications.

The design connects five workstreams:

- **Language analysis and migration:** a COBOL frontend built with Rascal MPL,
  source and copybook traceability, dependency analysis and reviewable
  transformations. A versioned intermediate representation separates migration
  tooling from the proposed Truffle runtime.
- **Execution and enterprise integration:** explicit decimal, storage and
  calling semantics; host Java and service adapters; differential tests against
  a reference runtime; staged coexistence and rollback.
- **Mainframe laboratory:** Hercules/Hyperion emulation and an emulator-upgrade
  plan, with guest operating systems and CICS/DB2 environments provisioned
  separately. IBM i/AS400 follows a distinct training path.
- **Data engineering:** Cobrix-based record decoding, a proposed
  Spark → Iceberg → Trino pipeline, a Java/JDBC client adapter and an optional
  future read-only Trino connector.
- **Applied training:** Payroll as the batch case, with Mastering JCL,
  Cash Account COBOL and WebJCL as complementary references for JCL,
  CICS/DB2/Embedded SQL and browser-based job workflows. Assessment covers
  demonstrated skills separately from declared years of professional experience.

Within the portfolio, this provides a COBOL-specific architecture workstream
alongside JFXLEGACY2MODERN's modernization scope, JFXETL4DE's data pipelines and
JFXICP's interoperability patterns. These are proposed connections requiring
their own contracts and validation.

**Status: architecture and documentation; no executable GraalCOBOL runtime or
deployed adapters yet.** Compatibility, migration equivalence and performance
remain implementation and validation goals.

[Integration architecture](https://github.com/sdk2035/GraalCOBOL/blob/main/docs/architecture/integration.md)
· [Rascal MPL design](https://github.com/sdk2035/GraalCOBOL/blob/main/docs/architecture/rascal-cobol.md)
· [Cobrix–Trino](https://github.com/sdk2035/GraalCOBOL/blob/main/docs/architecture/cobrix-trino.md)
· [Training laboratory](https://github.com/sdk2035/GraalCOBOL/blob/main/docs/training/mainframe-lab.md)
· [Reference projects and review findings](https://github.com/sdk2035/GraalCOBOL/blob/main/docs/references/projects.md)

### Modeling, Simulation and Digital Twins

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [GraalModelica](https://github.com/sdk2035/GraalModelica) | Modelica-based physical modeling with a GraalVM-oriented runtime approach | Concept | `█░░░░░░░░░` ~10% | Define a minimal Modelica model and solver acceptance criteria. |
| [JModelica-Flow](https://github.com/sdk2035/JModelica-Flow) | Low-code simulation and control canvas for GraalModelica | Architecture | `██░░░░░░░░` ~20% | Draft the canvas-to-model schema and one simulation workflow. |

These projects address the modeling language and visual workflow layers. The JFX
projects below explore complementary authoring, simulation and visualization roles.

### Complementary JFX Engineering Projects

These six repositories are currently hosted under **sdk2035**. Use these links for
the complementary projects transferred into or maintained in this account; domain
applications remain separately cataloged by Robotics & Intelligent Systems.

| Project | Focus and complementary role | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxlcdp](https://github.com/sdk2035/jfxlcdp) | Reference architecture for metadata-driven low-code authoring, declarative JavaFX interfaces and AI-assisted systems engineering | Architecture | `██░░░░░░░░` ~20% | Specify one metadata-to-JavaFX screen and its acceptance tests. |
| [jfxlegacy2modern](https://github.com/sdk2035/jfxlegacy2modern) | AI-assisted legacy modernization architecture: source analysis, behavior-preserving validation, proposed open-source ERP support, cross-product migration and staged version upgrades, with a Frappe-dependent low-code module | Architecture | `██░░░░░░░░` ~20% | Select one legacy fixture and draft behavior-preserving migration checks. |
| [jfxetl4de](https://github.com/sdk2035/jfxetl4de) | Data-engineering integration laboratory for ETL/ELT, streaming, lakehouse workflows, data contracts and engineering-data pipelines | Architecture | `██░░░░░░░░` ~20% | Draft one ingestion contract with provenance, replay and schema-drift cases. |
| [jfxicp](https://github.com/sdk2035/jfxicp) | Reference architecture for cloud and polyglot interoperability, distributed engineering computing and co-simulation | Architecture | `██░░░░░░░░` ~20% | Specify a Java/Python worker contract and timeout/error fixtures. |
| [jfxengine](https://github.com/sdk2035/jfxengine) | Research and architecture connecting MBSE/SysML, 3D visualization, simulation and digital twins with AI-assisted engineering workflows | Architecture | `██░░░░░░░░` ~20% | Turn one SysML-to-visualization use case into a testable vertical slice. |
| [jfxmodelica](https://github.com/sdk2035/jfxmodelica) | JFXModelica Cloud AI: modeling, multiphysics simulation and digital-twin platform work around GraalModelica | Architecture | `██░░░░░░░░` ~20% | Draft one FMU/worker simulation contract and reproducible example. |

JFXLEGACY2MODERN's [ERP modernization specification](https://github.com/sdk2035/jfxlegacy2modern/blob/main/docs/erp-modernization.md) distinguishes operational support, upgrades within one ERP and migration between products. Reference plans cover **Odoo Community 11.0 → 15.0**, **ERPNext 11 → 15** and **Odoo Community 11.0 → ERPNext 15**, with compatibility checks, data reconciliation, cutover and rollback. Its proposed [`erp-low-code` module](https://github.com/sdk2035/jfxlegacy2modern/tree/main/modules/erp-low-code) declares Frappe as a required runtime dependency for that profile. These are documented designs and declarative plans; ERP connectors, upgrade execution and the low-code app still require implementation and testing.

The proposed responsibilities are complementary: JFXLCDP authors specifications
and interfaces; JFXLEGACY2MODERN analyzes and transforms existing software;
JFXETL4DE organizes data pipelines; JFXICP defines interoperability patterns;
JFXENGINE presents engineering models and results; JFXMODELICA explores physical
modeling and simulation workflows. OpenBAP provides a separate enterprise/ERP
modernization workstream.

These roles describe an integration direction, not a single installed platform.
Each repository defines its implementation status. For example, JFXLCDP currently
contains documentation and design diagrams rather than a runnable low-code system.
Cross-project adapters need explicit contracts, maintainers and reproducible tests.

### AI Infrastructure and Distributed Inference

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [llm-d](https://github.com/sdk2035/llm-d) | Fork of [llm-d/llm-d](https://github.com/llm-d/llm-d): distributed LLM inference serving on Kubernetes, including cache-aware routing and prefill/decode disaggregation over model servers such as vLLM | Upstream fork; local integration proposed | N/A · local scope pending | Draft a bounded local integration plan and benchmark criteria against upstream. |

A candidate for the JFXAI4ARCH inference workstream when measured demand justifies
distributed serving. Adoption requires compatible accelerators, networking and
Kubernetes operations; it remains a proposed integration with the JFX portfolio.

### Scientific Computing Languages

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [GraalJulia](https://github.com/sdk2035/GraalJulia) | Julia language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Define an expression parser MVP and Julia reference fixtures. |
| [GraalScilab](https://github.com/sdk2035/GraalScilab) | Scilab language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Define a matrix-expression MVP and numerical reference fixtures. |

### JVM and .NET Interoperability

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [GraalIKVM](https://github.com/sdk2035/GraalIKVM) | Interoperability initiative connecting IKVM.NET concepts with GraalVM and Truffle | Concept | `█░░░░░░░░░` ~10% | Draft a bounded JVM/.NET interop spike with marshaling and exception tests. |
| [TruffleMono](https://github.com/sdk2035/TruffleMono) | AST interpreter infrastructure and IKVM/Mono integration research | Concept | `█░░░░░░░░░` ~10% | Define a minimal CIL instruction subset and interpreter fixtures. |
| [rascal-mono](https://github.com/sdk2035/rascal-mono) | Rascal-based language tooling with ECMA CLI, C# and .NET integration scope | Concept | `█░░░░░░░░░` ~10% | Draft a C# extraction fixture and expected M3 facts. |
| [asharplang](https://github.com/sdk2035/asharplang) | A# (A Sharp), an Ada-to-.NET port project | Imported sources; build unverified | N/A · assessment pending | Inventory the imported mgnat sources and draft a reproducible build plan. |
| [jsharplang](https://github.com/sdk2035/jsharplang) | JSharp.NET (J#), a Java-oriented language transition project for the .NET ecosystem | Concept | `█░░░░░░░░░` ~10% | Define a Java/J#-to-CIL subset and compiler acceptance fixtures. |

### Metaprogramming and Language Workbenches

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [GraalRascal](https://github.com/sdk2035/GraalRascal) | Rascal metaprogramming language work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Define a Rascal expression subset and reference interpreter fixtures. |
| [rascal-latino](https://github.com/sdk2035/rascal-latino) | Rascal metaprogramming with a Latino core implementation | Concept | `█░░░░░░░░░` ~10% | Draft one Latino AST transformation and traceability fixture. |
| [GraalLatino](https://github.com/sdk2035/GraalLatino) | Latino language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Define the first Latino grammar subset and execution fixtures. |

### Polyglot Language Projects

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [GraalClang](https://github.com/sdk2035/GraalClang) | Clang-related compiler and GraalVM integration work | Concept | `█░░░░░░░░░` ~10% | Scope one Clang/GraalVM integration path and a compile/run fixture. |
| [GraalVala](https://github.com/sdk2035/GraalVala) | Vala language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Define a Vala subset and reference compiler fixtures. |
| [GraalAugusta](https://github.com/sdk2035/GraalAugusta) | Augusta language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Document the Augusta grammar and first parser acceptance cases. |
| [GraalOCaml](https://github.com/sdk2035/GraalOCaml) | OCaml language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Define an OCaml expression subset and evaluation fixtures. |
| [GraalEiffel](https://github.com/sdk2035/GraalEiffel) | Eiffel language implementation work targeting GraalVM | Concept | `█░░░░░░░░░` ~10% | Scope a first Eiffel class and design-by-contract fixture. |

### 3D Modeling, CAD and Educational Visualization

| Project | Focus | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [JFXBlender](https://github.com/sdk2035/JFXBlender) | 3D modeling environment | Concept | `█░░░░░░░░░` ~10% | Specify one 3D scene import/view workflow and acceptance criteria. |
| [JWebCAD](https://github.com/sdk2035/JWebCAD) | Browser-based 3D CAD design and editing project using GraalVM | Concept | `█░░░░░░░░░` ~10% | Draft a browser CAD MVP with one editable primitive and export fixture. |
| [JDot](https://github.com/sdk2035/JDot) | Educational 3D animation web engine with a unified interface and GraalVM integration | Concept | `█░░░░░░░░░` ~10% | Specify one educational animation scene and playback acceptance cases. |

## Selected Organization Projects

My broader architecture and research work is organized under
[Robotics & Intelligent Systems](https://github.com/robotics-intelligent-systems).

| Project | Area | Status | Estimated progress | Next AI-assisted task (proposed) |
| --- | --- | --- | --- | --- |
| [jfxai4arch](https://github.com/robotics-intelligent-systems/jfxai4arch) | Technical knowledge and agent architecture, with an initial local RAG pilot | Executable RAG pilot | `█████░░░░░` ~50% | Draft a source-grounded evaluation set and validate optional local-model generation. |
| [jfxai4nlp](https://github.com/robotics-intelligent-systems/jfxai4nlp) | Language extraction, code intelligence and AI evaluation architecture | Architecture | `██░░░░░░░░` ~20% | Draft an extraction schema, labeled sample set and evaluation criteria. |
| [jfxai4dia](https://github.com/robotics-intelligent-systems/jfxai4dia) | Physics-driven industrial design, CAD and engineering validation | Architecture | `██░░░░░░░░` ~20% | Specify one CAD-to-simulation case with units and validation evidence. |
| [jfxlms4air](https://github.com/robotics-intelligent-systems/jfxlms4air) | Localization, mapping and perception for autonomous inspection | Architecture | `██░░░░░░░░` ~20% | Draft one recorded inspection dataset and localization evaluation protocol. |
| [jfxfmis](https://github.com/robotics-intelligent-systems/jfxfmis) | Farm management, agricultural digital twins and telemetry | Architecture | `██░░░░░░░░` ~20% | Draft one observation-to-twin contract and replayable farm scenario. |
| [jfxai4bss](https://github.com/robotics-intelligent-systems/jfxai4bss) | Buildings, infrastructure and smart-community digital-twin architecture | Architecture | `██░░░░░░░░` ~20% | Specify one asset/telemetry mapping and calibration acceptance criteria. |
| [jfxai4obs](https://github.com/robotics-intelligent-systems/jfxai4obs) | Financial engineering, payment/credit workflows and banking interoperability | Architecture | `██░░░░░░░░` ~20% | Draft a sandbox payment contract with idempotency and reconciliation cases. |
| [jfxai4ohs](https://github.com/robotics-intelligent-systems/jfxai4ohs) | B2B e-commerce and integration across catalog, order, payment and ERP workflows | Architecture | `██░░░░░░░░` ~20% | Draft one catalog adapter contract and mocked authorization/error checks. |

See the [organization profile](https://github.com/robotics-intelligent-systems)
for its broader domain catalog. Agriculture belongs to JFXFMIS; JFXAI4BSS focuses
on the built environment.

The proposed connection uses **shared technical AI services and domain-owned
adapters**: JFXAI4ARCH supplies the knowledge/inference workstream, JFXAI4NLP the
language/evaluation workstream, and domain projects retain their models, data and
acceptance decisions. The sdk2035 projects contribute complementary authoring,
modernization, data, interoperability and visualization workstreams.

A practical starting point is the [JFXAI4ARCH technical RAG pilot](https://github.com/robotics-intelligent-systems/jfxai4arch/blob/main/docs/rag/PILOT.md):
local Markdown/TXT retrieval with source references, optional Ollama generation,
a Langfuse metadata adapter and Bruno API checks. Its single-user baseline is
implemented; real-model quality, a live Langfuse deployment and wider integration
still require validation. Other cross-project roles above remain proposed unless
supported by implementation evidence in their repositories.

## Technology Stack

Technologies are selected per project and workload; this list is not a shared
installation requirement. For JFX integration, compatible libraries may run in
process while scientific workloads or external systems use separate workers and
APIs. GraalVM compatibility is evaluated per component, not assumed for the whole
portfolio. Record versions, provenance, licenses and validation results before
adopting a component.

| Domain | Technologies and practices |
| --- | --- |
| Backend | Java, C#/.NET, Scala, Python, TypeScript, Node.js, PHP, Spring Boot, ASP.NET Core, NestJS |
| Cloud and delivery | Azure, AWS, Docker, Kubernetes, Linux, CI/CD, RabbitMQ, Nginx |
| Enterprise integration | REST, SOAP, OData, OpenAPI, ETL, microservices and event-driven architecture |
| AI and knowledge | Azure OpenAI, LangChain, RAG, MCP, agents, vector databases, Ollama and local inference |
| Scientific computing and runtimes | Julia, Kokkos C++, GraalVM, Truffle, IKVM.NET, JModelica/Modelica, SciPy, OCaml, GNAT Ada |
| Data | PostgreSQL, SQL Server, Oracle, MySQL, DynamoDB |
| Business domains | Payments, credit workflows, microfinance, electronic invoicing and ERP interoperability |

## Collaboration

I welcome conversations about:

- **Remote engineering roles:** software architecture, senior/staff engineering and AI systems leadership.
- **Enterprise projects:** modernization, cloud integration, FinTech workflows and private AI deployments.
- **Research partnerships:** language runtimes, JVM/.NET interoperability, simulation, SciML and digital twins.
- **Startups and ventures:** technical co-founding, MVP engineering and product validation.

For a project-specific proposal, start with an issue in the relevant repository.
For professional opportunities and partnerships, connect through
[LinkedIn](https://www.linkedin.com/in/kjsanc) or
[email](mailto:kjsanc@gmail.com).

*Build openly. Integrate intelligently. Validate with engineering.*
