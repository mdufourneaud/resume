# Matthieu DUFOURNEAUD / Principal Platform Engineer

📍 Lyon, France | ☎️ *Ask me* | 📧 *Ask me* | [GitHub](https://github.com/mdufourneaud) | [LinkedIn](https://www.linkedin.com/in/matthieu-dufourneaud-a2195030)

## Résumé

Je suis Principal Platform Engineer avec plus de 20 ans d'expérience — du développement full-stack (embarqué, desktop, mobile et web) à l'architecture de plateformes multi-cloud sur AWS, Azure, GCP, OVH et on-premises. Un principe constant : définir le vrai problème, puis choisir la solution adaptée au contexte — pas toujours technique.

Aujourd'hui, je pilote les efforts de Cloud Engineering, en prenant en charge le FinOps, le SRE et le Platform Engineering pour optimiser les coûts cloud, améliorer la stabilité en production et la vélocité des développeurs.

Tout au long de ma carrière, j'ai considéré l'écriture technique comme une discipline d'ingénierie à part entière — des ADRs et runbooks aux spécifications qui font le lien entre l'intention métier et l'exécution technique. A mesure que l'ingénierie évolue vers des workflows orientés agents, ces compétences me semblent de plus en plus centrales : la précision, la structure et le contexte sont ce qui rend efficaces aussi bien les humains que les agents IA.

## Compétences

**Cloud & Infrastructure** — Fournisseurs : AWS, Azure, GCP, OVH, on-premises · Conteneurs : Kubernetes, Helm, Kustomize, cert-manager, KEDA, Karpenter, Docker · Réseau : Azure API Gateway, NGINX, Kong

**Platform Engineering** — IaC : Cluster API, OpenTofu/Terraform · GitOps : FluxCD · CI/CD : Azure DevOps · Sécurité : Trivy

**Concepts** — SRE · FinOps · Architecture cloud · DDD · CQRS · Event-Driven Architecture · REST · SOLID · Clean Code · ORM · Refactoring · PoEAA · Test-First

**Leadership & Culture** — Leadership technique · Management d'équipe · Enseignement & mentorat · Ownership & management produit · Rédaction technique · Facilitation : brainstorming, mind mapping, post-mortems · Culture DevOps · Culture Agile · Avant-vente technique · Prise de parole en public

**Observabilité** — OpenTelemetry · Prometheus · Grafana

**Messaging** — Azure Event Hubs · Azure Service Bus · GCP Pub/Sub · RabbitMQ

**Serverless** — Azure Functions · Azure Container Apps · GCP Cloud Run

**Langages** — .NET : C#, F# · Go · Shell : Bash, PowerShell · JavaScript/TypeScript · SQL · Python

**Données** — Relationnel : PostgreSQL · SQL Server · NoSQL : Elasticsearch · CosmosDB · Objet : Azure Storage

**Collaboration & Outils** — Jira · Confluence · Notion · Miro

**IoT** — Protocoles : Sigfox, LoRaWAN · Plateformes : Azure IoT Hub

**Exploration** — Agentic coding · Clean Architecture · Rust · GraphQL

## Expérience

### DataGalaxy | Lyon, France

**Principal Cloud & Run Engineer** (2023/07 – Présent) | **Software Architect** (2020/01 – 2023/07)<br>
Télétravail 100% · Anglais

### Veolia Connected Solutions | Lyon, France

**Software Architect** (2015/11 – 2020/01)

Rejoint Birdz en tant qu'expert cloud pour piloter la conception et l'implémentation de pipelines de traitement de données de compteurs d'eau et développer la pratique cloud engineering.

- **Pipeline Azure (v0)** — Conception et implémentation d'un pipeline de traitement de compteurs d'eau (identification, décodage, calcul, stockage) avec Azure Functions, Azure Event Hubs et CosmosDB.
- **Pipeline GCP (v1)** — Migration vers GCP GKE (Kubernetes) et Pub/Sub avec des microservices dédiés par étape de traitement — motivée par des problèmes de prévisibilité des coûts du serverless.
- **Gestion des identifiants LoRaWAN** — Product Owner d'un service serverless GCP Cloud Run gérant les identifiants LoRaWAN pour des compteurs d'eau IoT, initié à partir de besoins utilisateurs internes.
- **Management** — Recrutement et management d'un ingénieur logiciel junior.

### Exakis Nelite | Lyon, France

**Technical Lead** (2012/06 – 2015/09) | **Senior Software Engineer** (2011/01 – 2012/06)

Avant-vente technique, avec ownership complet des projets remportés : conception, implémentation et suivi jusqu'en production — en appliquant DDD et CQRS sur l'ensemble des applications livrées. Missions d'expertise chez des clients. Mentorat et accompagnement de jusqu'à 4 stagiaires et ingénieurs juniors.

- **Adecco France (mission)** — Expertise WPF/MVVM sur une application desktop client-serveur sous Oracle, incluant une investigation de fuite mémoire : références View/ViewModel non collectées identifiées par profilage mémoire et résolues avec des WeakReferences.
- **Tarification de médicaments vétérinaires** — Application desktop WPF/MVVM avec NHibernate et LINQ, exploitant le calcul parallèle massif (conception propre) pour gérer des charges de calcul intensives.
- **Application web de télé-relevé** — Single-Page Application ASP.NET avec TypeScript, Knockout.js (MVVM) et NHibernate, pour un opérateur de compteurs d'eau.
- **Application desktop technicien terrain** — Application WPF/MVVM avec géolocalisation temps réel via Reactive Extensions et communication série Bluetooth avec des appareils IoT portables.
- **Application mobile technicien terrain** — Application Xamarin.Forms/MVVM Android communicant avec des appareils IoT portables via série Bluetooth.

### Intitek Hinnoya | Lyon, France

**Software Consultant** (2009/05 – 2010/12)

En mission chez APRIL Assurances : contribution à la conception et l'implémentation d'un framework ASP.NET Model-View-Presenter réutilisable hébergé dans DotNetNuke, appliqué sur plusieurs applications web.

### Clever Age | Lyon, France

**Software Consultant** (2008/12 – 2009/04)

Missions d'expertise courtes en tant que consultant : formations .NET et mises à jour de CMS en production (DotNetNuke).

### SQLI | Lyon, France

**Software Engineer** (2007/09 – 2008/11)

Développement d'applications desktop .NET avec NHibernate (ORM) sur SQL Server et Oracle, et conception d'un framework TUI réutilisable en Mono pour terminaux de scan codes-barres portables — offrant navigation structurée, saisie de texte et écrans multi-choix.

### Visiativ | Charbonnières-les-Bains, France

**Software Engineer** (2004/02 – 2007/08)

Développement d'applications desktop et web .NET étendant SmarTeam (PLM) et SolidWorks (CAD) via leurs APIs COM pour répondre aux besoins de clients industriels.

## Projets personnels

### Helmeleon

Un chart Helm qui génère des manifests déployables à partir de templates fournis en valeurs — sans avoir à écrire de templates from scratch.

[GitHub – mdufourneaud/helmeleon](https://github.com/mdufourneaud/helmeleon)

### KopyK8s *(prononcé "copycats")*

Un opérateur Kubernetes (Go) qui crée et maintient des copies de ressources synchronisées entre namespaces ou clusters — utile pour propager des Secrets, ConfigMaps ou n'importe quelle ressource dans des contextes multi-tenant.

[GitHub – mdufourneaud/kopyk8s](https://github.com/mdufourneaud/kopyk8s)

## Formation

**DEA (grade de master) Imagerie, Vision, Robotique** — Grenoble INP (Institut National Polytechnique de Grenoble)

## Centres d'intérêt & Valeurs

Curieux de nature — aussi bien attiré par l'ensevelissement de Pompéi que par les mystères de la physique des particules. Je voyage pour découvrir d'autres cultures, langues et façons de vivre — en train de nuit quand je le peux, expression d'un engagement dans la lutte contre le changement climatique.<br>
Je crois en la communication écrite : elle force la clarté, crée un contexte partagé et survit à la conversation. Je m'épanouis dans des équipes qui apprennent de leurs échecs sans chercher de coupable — post-mortems blameless plutôt que mise en cause, pensée systémique plutôt que bouc émissaire.
