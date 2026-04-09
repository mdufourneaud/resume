# Matthieu DUFOURNEAUD / Principal Platform Engineer

📍 Lyon, France | ☎️ *Ask me* | 📧 *Ask me* | [GitHub](https://github.com/mdufourneaud) | [LinkedIn](https://www.linkedin.com/in/matthieu-dufourneaud-a2195030)

## Summary

I'm a Principal Platform Engineer with 20+ years of experience — from backend engineering across the stack (embedded, desktop, mobile and web) to architecting multi-cloud platforms across AWS, Azure, GCP, OVH and on-premises. Same principle throughout: define the real problem, then choose the solution that fits the context — not always a technical one.

Today I lead Cloud Engineering efforts, owning FinOps, SRE and Platform Engineering to optimize cloud costs, improve production stability and developer velocity.

Throughout my career, I've invested in technical writing as a core engineering discipline — from RFCs, ADRs and runbooks to specs that bridge business intent and technical execution. As engineering shifts toward agent-first workflows, I find these skills increasingly central: precision, structure and context are what make both humans and AI agents effective.

## Skills

**Cloud & Infrastructure** — Providers: AWS, Azure, GCP, OVH, on-premises · Containers: Kubernetes, Helm, Kustomize, cert-manager, KEDA, Karpenter, Docker · Networking: Azure API Gateway, NGINX, Kong

**Platform Engineering** — IaC: Cluster API, OpenTofu/Terraform · GitOps: FluxCD · CI/CD: Azure DevOps · Security: Trivy

**Concepts** — SRE · FinOps · Cloud Architecture · DDD · CQRS · Event-Driven Architecture · REST · SOLID · Clean Code · ORM · Refactoring · PoEAA · Test-First

**Leadership & Culture** — Technical leadership · People leadership · Teaching & mentorship · Product ownership & management · Technical writing (RFCs · ADRs · architecture diagrams · guidelines · pre/post-mortems · runbooks · user stories · DoD) · Facilitation: brainstorming, mind mapping, post-mortems · DevOps culture · Agile culture · Pre-sales engineering · Public speaking

**Observability** — OpenTelemetry · Prometheus · Grafana

**Messaging** — Azure Event Hubs · Azure Service Bus · GCP Pub/Sub · RabbitMQ

**Serverless** — Azure Functions · Azure Container Apps · GCP Cloud Run

**Languages** — .NET: C#, F# · Go · Shell: Bash, PowerShell · JavaScript/TypeScript · SQL · Python · C/C++

**Data** — Relational: PostgreSQL · SQL Server · NoSQL: Elasticsearch · CosmosDB · Object: Azure Storage

**Collaboration & Tooling** — Jira · Confluence · Notion · Miro

**IoT** — Protocols: Sigfox, LoRaWAN · Platforms: Azure IoT Hub

**Exploring** — Agentic coding · Clean Architecture · Rust · GraphQL

## Experience

### DataGalaxy | Lyon, France

**Principal Cloud & Run Engineer** (2023/07 – Present) | **Software Architect** (2020/01 – 2023/07)<br>
Full Remote · English

I define and execute DataGalaxy's cloud engineering strategy across a multi-provider environment (AWS, Azure, GCP, OVH and on-premises). I lead FinOps, SRE and Platform Engineering efforts — owning the tools, practices and architectural decisions that keep production reliable, costs under control and developers moving fast.

- **Infrastructure modernization** — Migrated from <10 manually operated Windows VMs to 100+ Kubernetes clusters, fully managed through IaC (Cluster API → OpenTofu) across their entire lifecycle: provisioning, configuration, upgrades and teardown.
- **CI/CD transformation** — Replaced Windows-bound build artifacts with Docker images and Helm charts, automatically built through CI pipelines (Azure DevOps) and delivered via GitOps (FluxCD) — eliminating manual release toil across the engineering team.
- **Tenant provisioning** — Automated full tenant provisioning via GitOps and IaC, reducing lead time from several hours to minutes — supporting both customer onboarding and feature development workflows at a pace of tens of tenants created and deleted per month.
- **Observability** — Replaced per-VM log analysis with centralized logs, metrics and traces in Grafana, enabling proactive alerting across the entire platform.
- **FinOps** — Significantly reduced infrastructure costs through Kubernetes node disk and topology optimizations — without compromising reliability or performance.
- **Incident management** — Replaced ad-hoc, self-organized incident response (Slack alerts, no ownership) with a structured practice: defined roles, dedicated communication channels, alerting runbooks and documented remediation procedures, powered by incident.io.
- **Production access security** — Replaced open, permanent cluster access with a custom kubectl plugin (Go) enforcing least-privilege, time-limited and fully audited access to production and development clusters — rolled out across the entire engineering team.
- **Cloud-native enablement** — Ran a weekly Cloud Office Hours open to all engineers, complemented by hands-on sessions on container basics, Kubernetes, autoscaling and serverless — building cloud-native culture and autonomy across the engineering organization.

### Veolia Connected Solutions | Lyon, France

**Software Architect** (2015/11 – 2020/01)

Joined Birdz as a cloud expert to lead the design and implementation of water meter data pipelines and expand the cloud engineering practice.

- **Azure pipeline (v0)** — Designed and implemented a water meter processing pipeline (identification, decoding, calculation, storage) using Azure Functions, Azure Event Hubs and CosmosDB.
- **GCP pipeline (v1)** — Migrated to GCP GKE (Kubernetes) and Pub/Sub with dedicated microservices per processing stage — driven by cost predictability concerns over serverless.
- **LoRaWAN identifier management** — Acted as Product Owner for a serverless GCP Cloud Run service managing LoRaWAN identifiers for IoT water meters, initiated from internal user needs.
- **Engineering management** — Recruited and managed a junior software engineer.

### Exakis Nelite | Lyon, France

**Technical Lead** (2012/06 – 2015/09) | **Senior Software Engineer** (2011/01 – 2012/06)

Led technical pre-sales, winning multiple projects then owning them end-to-end through design, implementation and production — applying DDD and CQRS across the delivered applications. Delivered expertise missions for clients. Mentored and coached up to 4 interns and junior engineers.

- **Adecco France (mission)** — WPF/MVVM expertise on a client-server desktop application backed by Oracle, including a memory leak investigation: uncollected View/ViewModel references identified via memory profiling and resolved with WeakReferences.
- **Animal drug pricing** — WPF/MVVM desktop application with NHibernate and LINQ, leveraging parallel computing (own design) to handle intensive price calculation workloads.
- **Telemetering web app** — ASP.NET Single-Page Application with TypeScript, Knockout.js (MVVM) and NHibernate, for a water metering operator.
- **Field technician desktop app** — WPF/MVVM application with real-time geolocation via Reactive Extensions and Bluetooth serial communication with handheld IoT devices.
- **Field technician mobile app** — Xamarin.Forms/MVVM Android application communicating with handheld IoT devices via Bluetooth serial.

### Early Career (2004–2010)

.NET software engineering across ISV (Visiativ) and IT services firms (SQLI, Clever Age and Intitek Hinnoya) — building desktop, web and handheld applications for industrial and insurance clients, including a reusable Mono-based TUI framework for handheld barcode scanner terminals, and CAD/PLM integrations via COM APIs (SolidWorks, SmarTeam).

## Side Projects

### Helmeleon

A Helm chart that renders templates provided as values into deployable manifests — without writing chart templates from scratch.

[GitHub – mdufourneaud/helmeleon](https://github.com/mdufourneaud/helmeleon)

### KopyK8s *(pronounced "copycats")*

A Kubernetes operator (Go) that creates and keeps copies of resources synchronized across namespaces or clusters — useful for propagating Secrets, ConfigMaps or any resources in multi-tenant contexts.

[GitHub – mdufourneaud/kopyk8s](https://github.com/mdufourneaud/kopyk8s)

## Education

**Master's degree in Imaging, Vision & Robotics** — Grenoble INP (Institut National Polytechnique de Grenoble)

## Interests & Values

Naturally curious — equally drawn to the burial of Pompeii and the mysteries of particle physics. I travel to discover other cultures, languages and ways of living — by night train where I can, one expression of a commitment to fighting climate change.<br>
I believe in written communication: it forces clarity, creates shared context and outlasts the conversation. I thrive in teams that learn from failure without blame — blameless post-mortems over finger-pointing, systems thinking over scapegoating.
