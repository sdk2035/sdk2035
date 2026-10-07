# Kevin Sanchez

### Senior Software Engineer & Systems Architect

**Enterprise modernization · AI integration · Scientific computing · Polyglot runtimes**

Lima, Peru · Open to remote opportunities across LATAM and the U.S., technical partnerships and collaborative R&D.

[LinkedIn](https://www.linkedin.com/in/kjsanc) · [Email](mailto:kjsanc@gmail.com) · [Personal repositories](https://github.com/sdk2035?tab=repositories) · [Robotics & Intelligent Systems](https://github.com/robotics-intelligent-systems)

## About

I am a systems analyst and senior software engineer with **10+ years of experience**
across **50+ enterprise projects** in FinTech, banking, microfinance, e-commerce,
ERP and electronic invoicing.

My work connects enterprise software engineering with AI-assisted architectures
and scientific computing. I focus on modular systems, explicit integration
contracts and practical modernization paths across Java, .NET and cloud platforms.

My current project portfolio explores **GraalVM, Truffle, IKVM/.NET, Modelica
and language engineering**, alongside low-code authoring, data engineering,
legacy modernization, simulation and 3D tools. Complementary JFX projects hosted
under `sdk2035` provide architecture workstreams for integration with the domain
portfolio at Robotics & Intelligent Systems.

## Explore

- [Engineering Focus](#engineering-focus)
- [Personal Project Portfolio](#personal-project-portfolio)
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

### Enterprise Modernization and Business Platforms

| Project | Focus |
| --- | --- |
| [OpenBAP](https://github.com/sdk2035/OpenBAP) | AI-assisted enterprise modernization platform combining Apache OFBiz, GraalVM/Truffle and OpenXava for semantic reconstruction, legacy ABAP interoperability and incremental ERP migration |
| [GraalCOBOL](https://github.com/sdk2035/GraalCOBOL) | Proposed COBOL modernization architecture combining Rascal MPL analysis, a versioned intermediate representation and Truffle/GraalVM execution, with mainframe training and Cobrix–Trino data integration |

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

| Project | Focus |
| --- | --- |
| [GraalModelica](https://github.com/sdk2035/GraalModelica) | Modelica-based physical modeling with a GraalVM-oriented runtime approach |
| [JModelica-Flow](https://github.com/sdk2035/JModelica-Flow) | Low-code simulation and control canvas for GraalModelica |

These projects address the modeling language and visual workflow layers. The JFX
projects below explore complementary authoring, simulation and visualization roles.

### Complementary JFX Engineering Projects

These six repositories are currently hosted under **sdk2035**. Use these links for
the complementary projects transferred into or maintained in this account; domain
applications remain separately cataloged by Robotics & Intelligent Systems.

| Project | Focus and complementary role |
| --- | --- |
| [jfxlcdp](https://github.com/sdk2035/jfxlcdp) | Reference architecture for metadata-driven low-code authoring, declarative JavaFX interfaces and AI-assisted systems engineering |
| [jfxlegacy2modern](https://github.com/sdk2035/jfxlegacy2modern) | AI-assisted legacy modernization architecture: source analysis, architecture recovery, candidate transformations and behavior-preserving validation |
| [jfxetl4de](https://github.com/sdk2035/jfxetl4de) | Data-engineering integration laboratory for ETL/ELT, streaming, lakehouse workflows, data contracts and engineering-data pipelines |
| [jfxicp](https://github.com/sdk2035/jfxicp) | Reference architecture for cloud and polyglot interoperability, distributed engineering computing and co-simulation |
| [jfxengine](https://github.com/sdk2035/jfxengine) | Research and architecture connecting MBSE/SysML, 3D visualization, simulation and digital twins with AI-assisted engineering workflows |
| [jfxmodelica](https://github.com/sdk2035/jfxmodelica) | JFXModelica Cloud AI: modeling, multiphysics simulation and digital-twin platform work around GraalModelica |

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

| Project | Focus |
| --- | --- |
| [llm-d](https://github.com/sdk2035/llm-d) | Fork of [llm-d/llm-d](https://github.com/llm-d/llm-d): distributed LLM inference serving on Kubernetes, including cache-aware routing and prefill/decode disaggregation over model servers such as vLLM |

A candidate for the JFXAI4ARCH inference workstream when measured demand justifies
distributed serving. Adoption requires compatible accelerators, networking and
Kubernetes operations; it remains a proposed integration with the JFX portfolio.

### Scientific Computing Languages

| Project | Focus |
| --- | --- |
| [GraalJulia](https://github.com/sdk2035/GraalJulia) | Julia language implementation work targeting GraalVM |
| [GraalScilab](https://github.com/sdk2035/GraalScilab) | Scilab language implementation work targeting GraalVM |

### JVM and .NET Interoperability

| Project | Focus |
| --- | --- |
| [GraalIKVM](https://github.com/sdk2035/GraalIKVM) | Interoperability initiative connecting IKVM.NET concepts with GraalVM and Truffle |
| [TruffleMono](https://github.com/sdk2035/TruffleMono) | AST interpreter infrastructure and IKVM/Mono integration research |
| [rascal-mono](https://github.com/sdk2035/rascal-mono) | Rascal-based language tooling with ECMA CLI, C# and .NET integration scope |
| [asharplang](https://github.com/sdk2035/asharplang) | A# (A Sharp), an Ada-to-.NET port project |
| [jsharplang](https://github.com/sdk2035/jsharplang) | JSharp.NET (J#), a Java-oriented language transition project for the .NET ecosystem |

### Metaprogramming and Language Workbenches

| Project | Focus |
| --- | --- |
| [GraalRascal](https://github.com/sdk2035/GraalRascal) | Rascal metaprogramming language work targeting GraalVM |
| [rascal-latino](https://github.com/sdk2035/rascal-latino) | Rascal metaprogramming with a Latino core implementation |
| [GraalLatino](https://github.com/sdk2035/GraalLatino) | Latino language implementation work targeting GraalVM |

### Polyglot Language Projects

| Project | Focus |
| --- | --- |
| [GraalClang](https://github.com/sdk2035/GraalClang) | Clang-related compiler and GraalVM integration work |
| [GraalVala](https://github.com/sdk2035/GraalVala) | Vala language implementation work targeting GraalVM |
| [GraalAugusta](https://github.com/sdk2035/GraalAugusta) | Augusta language implementation work targeting GraalVM |
| [GraalOCaml](https://github.com/sdk2035/GraalOCaml) | OCaml language implementation work targeting GraalVM |
| [GraalEiffel](https://github.com/sdk2035/GraalEiffel) | Eiffel language implementation work targeting GraalVM |

### 3D Modeling, CAD and Educational Visualization

| Project | Focus |
| --- | --- |
| [JFXBlender](https://github.com/sdk2035/JFXBlender) | 3D modeling environment |
| [JWebCAD](https://github.com/sdk2035/JWebCAD) | Browser-based 3D CAD design and editing project using GraalVM |
| [JDot](https://github.com/sdk2035/JDot) | Educational 3D animation web engine with a unified interface and GraalVM integration |

## Selected Organization Projects

My broader architecture and research work is organized under
[Robotics & Intelligent Systems](https://github.com/robotics-intelligent-systems).

| Project | Area |
| --- | --- |
| [jfxai4arch](https://github.com/robotics-intelligent-systems/jfxai4arch) | Technical knowledge and agent architecture, with an initial local RAG pilot |
| [jfxai4nlp](https://github.com/robotics-intelligent-systems/jfxai4nlp) | Language extraction, code intelligence and AI evaluation architecture |
| [jfxai4dia](https://github.com/robotics-intelligent-systems/jfxai4dia) | Physics-driven industrial design, CAD and engineering validation |
| [jfxlms4air](https://github.com/robotics-intelligent-systems/jfxlms4air) | Localization, mapping and perception for autonomous inspection |
| [jfxfmis](https://github.com/robotics-intelligent-systems/jfxfmis) | Farm management, agricultural digital twins and telemetry |
| [jfxai4bss](https://github.com/robotics-intelligent-systems/jfxai4bss) | Buildings, infrastructure and smart-community digital-twin architecture |
| [jfxai4obs](https://github.com/robotics-intelligent-systems/jfxai4obs) | Financial engineering, payment/credit workflows and banking interoperability |
| [jfxai4ohs](https://github.com/robotics-intelligent-systems/jfxai4ohs) | B2B e-commerce and integration across catalog, order, payment and ERP workflows |

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


