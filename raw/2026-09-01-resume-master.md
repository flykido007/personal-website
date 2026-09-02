# Rishabh Singh Thakur

Website: https://rishabh-singh-thakur.vercel.app | Toronto, ON | +1 514-803-2804 | rishabh.4082@gmail.com | GitHub: https://github.com/thakurrishabh | LinkedIn: https://linkedin.com/in/rishabh-singh-thakur-ba3bb4168 | Blog: https://dev.to/thakurrishabh

## Summary

Helping businesses leverage AI and cloud infrastructure to automate workflows, reduce operational costs, and accelerate time-to-market. AI Cloud Engineer & SRE with around 5 years of hands-on experience building scalable GCP infrastructure with HL7 FHIR compliance for 1000+ SDM stores across Canada. Built 3 full-stack AI SaaS apps, including one production-grade app with Google auth, Stripe payments, and OWASP security. Lately applying AI agent workflows to store-platform delivery, document intelligence, and incident recovery.

## Experience

### Senior Site Reliability Engineer
**Loblaw Companies Limited** — Toronto, Canada | 03/2025 – Present

**Built and Architected HL7 FHIR Compliant GCP based Services**
- Collaborated with teams to onboard new province integration to SDM stores, ensuring HL7 FHIR compliance with provincial systems, and successfully led control GAP TRA assessments.
- Collaborated with teams to drive business decisions in Eprescription, EHealth, and Interactive Voice Response (IVR) to ensure HL7 FHIR compliance with external systems and seamless integration between GCP and on-prem edge devices.

**SDM On-Prem VMware to Vanilla Kubernetes Migration With GCP Integration**
- Participated in pilots to migrate on-prem VMware instances of 15 stores to vanilla Kubernetes as part of an initiative to cover 700 stores across Ontario. Rebuilt entire store from the ground up including Dell hardware, Kubernetes node config, and OS install.
- Developed Ansible playbooks that run on GKE to migrate VMware workloads to vanilla Kubernetes containers and VMs using KubeVirt for each store.
- Configured FluxCD GitOps to enable seamless deployment of microservices using Kustomization from a central management GKE cluster.

**GenAI document intelligence for pharmacy operations**
- Designed GCP + Gemini document-intelligence workflows to classify and organize high-volume inbound fax and digital documents for pharmacy operations.
- Turned model output into an operator workflow with duplicate detection so staff can search, compare, and clear same-day work faster.

**AI-orchestrated Kubernetes store rollout**
- Used AI agent workflows (skills/rules) to design and generate GitLab pipelines and Ansible automation for the on-prem VMware to vanilla Kubernetes + GCP store migration.
- Wired FluxCD GitOps from a central management cluster so store rebuilds follow one repeatable path.

**AI-engineered delivery for platform migrations**
- Built an AI delivery system (agent skills, rules, MCP toolchains) that orchestrates tickets, repo changes, docs, and GitLab jobs across store-platform SRE repositories.
- Applied it to store-scale database migration (DB2 to Postgres) and messaging migration (IBM MQ to ActiveMQ) with convert/cutover/rollback pipelines; human review at production cutover gates.

**AI-assisted incident intelligence and store recovery**
- Built AI-assisted incident intelligence over historical store-platform incidents: pattern analysis, RCA playbooks, prioritized remediation.
- Authored Kubernetes store-down recovery runbooks and GitLab recovery jobs so on-call can confirm reachability from a pipeline.
- Used AI-assisted debugging during a large multi-store release to trace monitoring failures across GitLab, Pub/Sub, and Grafana and restore stuck pipeline jobs.

### Site Reliability Engineer 2
**Loblaw Companies Limited** — Toronto, Canada | 11/2022 – 03/2025

**Web UI to manage and trigger SDM Deployments provisioned using Terraform**
- Developed a web UI using HTML, Bootstrap, JavaScript, and Python Flask to manage deployment configurations and trigger deployments in GitLab using API.
- Employed a Cloud SQL MySQL backend DB for data storage and integrated Azure AD of the org to only allow authenticated access.
- Deployed the app on a GKE cluster and enabled access via internally managed DNS and Istio.

**Google Kubernetes Engine runners for 1000+ Store Deployment Framework and event-driven monitoring provisioned using Terraform**
- Provisioned a GKE cluster hosting GitLab runners to support deployments to 1000+ stores using Helm, involving 20k+ GitLab jobs per deployment a few times a week.
- Implemented job auto-retry and adjusted concurrency to achieve a failure rate of less than 1%.
- Migrated auto-scaling Prometheus-based GitLab pipeline exporters to Cloud SQL, achieving 2x performance and efficiency. Converted PromQL queries in Grafana dashboards to SQL.
- Implemented GitLab webhooks to push pipeline and job events to GCP Pub/Sub via Cloud Functions, which are inserted into MySQL via autoscaling Python exporter pods.

**Custom Ansible Framework Development**
- Developed a custom Ansible framework inspired by Rundeck to enable users to configure SDM stores remotely.
- Played a key role in modernizing the existing legacy shell-based deployment framework by re-architecting the solution to leverage GCP and Ansible.
- Migrated 10+ complex processes as part of the modernization involving sequential file processing, IBM MQ configurations, microservice deployment, etc.
- Participated in 5+ pilots and 10+ rollouts that involved up to 1200 SDM stores across multiple provinces in a single night.

Skills: Python, GCP, Google Kubernetes Engine (GKE), Docker, Ansible, Terraform, GitLab, CI/CD, MySQL, Prometheus.io, Grafana, Helm, Flask, JavaScript, Bootstrap, HTML, Istio, DNS, VPC, API, IBM MQ, Cloud Functions, GCP Pub/Sub, Linux, Scripting, Containerization

### Site Reliability Engineer 1
**Loblaw Companies Limited** — Toronto, Canada | 05/2021 – 10/2022

**GCP Infra and CI/CD to deploy 20+ apps on Google Kubernetes Engine provisioned using Terraform**
- Created a common CI/CD catalog for 20+ apps in GitLab to support deployments of Docker artifacts from GAR to GKE using Helm, and built pipelines for infrastructure management in GCP using Terraform.
- Implemented security through Workload Identity for keyless auth to GCP services for the deployed apps, Istio to enable external connections, and Secret Manager for storing sensitive keys and parameters.
- Documented the end-to-end setup in Confluence to enable developers to implement the above without SRE intervention.

**Dynamic GitLab Pipelines Infra and Monitoring to support 1000+ store deployment**
- Created dynamic nested pipelines in GitLab using Python and Jsonnet for concurrent deployments to 1000+ SDM stores.
- Created MIG (managed instance group) based GitLab runners to support 5000+ parallel GitLab job execution, and a Cloud Function to create dynamic runner tags for each pipeline.
- Developed auto-scaling Prometheus exporter pods using Python on GKE to monitor the above GitLab pipelines through Grafana dashboards.
- Implemented a controller pod for auto-scaling based on load and performed memory invalidation and segmentation to prevent errors relating to stale and duplicate data.

## Personal Projects
Toronto, Canada | 09/2024 – 10/2025

**RenderMuseAI — Text-to-Explainer Animation Platform**
Built and launched RenderMuseAI, an AI-powered platform that converts text prompts into educational Manim animations.
- Used GitHub Copilot and Claude to generate concept-aware Manim code with supervised sub-agents.
- Features: Lovable.dev frontend, Supabase backend, Daytona containerized hosting, Stripe payments, Google auth.
- Demo: https://youtu.be/DSLrlUCjsSA

**AI Video Reel Generator**
Built a tool to create 1-minute reels from text prompts.
- Integrated Gemini for script generation, Imagen for images, GPT-4o-mini TTS for narration, FFmpeg for video + subtitles.
- Frontend: Lovable.dev; Backend: GCP Firebase + Cloud Run.

**AI Meal Planning & Recipe App**
Built a conversational app for meal planning and grocery management.
- Flutter frontend mobile app + GCP Firebase backend; GPT-4o for grocery bill image scanning and recipe generation.
- Gemini multimodal voice-to-voice for recipe CRUD via natural conversation.

Skills: Python, React, Flutter, GCP (Firebase, Cloud Run, OAuth login), Supabase, Stripe, FFmpeg, GitHub Copilot, Claude Code, OpenAI and Gemini API (text, image, TTS, voice), Microsoft Playwright MCP, Lovable.dev, Vercel, Daytona.

## Certificates
- 06/2024 — Machine Learning Modeling Pipelines in Production, Coursera — https://coursera.org/share/877a1fc7ab16f3d029b9778b98aa41bd
- Machine Learning Data Lifecycle in Production, Coursera — https://coursera.org/share/447273530eeaa5e24b5166f8a383e6da
- 12/2020 – 12/2023 — AWS Certified Solutions Architect – Associate — https://www.credly.com/badges/1d35a3c5-9266-4a6c-8848-902f0f05c4a1

## Education
- **Concordia University**, Electrical and Computer Engineering, M.Eng — Montreal, Canada | 01/2019 – 12/2020 | GPA 3.75/4
- **Jawaharlal Nehru Technological University (JNTU)**, Electronics and Communication Engineering, B.Tech — Hyderabad, India | 09/2014 – 05/2018

**Soft skills:** Communication, Team Player, Quick Learner, Innovative. **Languages:** English, Hindi, Telugu. **Hobbies:** Reading, Playing and recording Guitar, Ice Skating.
