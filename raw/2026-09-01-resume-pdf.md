# Existing Drive PDF — messy capture (2026-09-01)

Source: Google Drive `Resume/Rishabh_Singh_Thakur_latest-3.pdf` (fileId `1TdovzPzC219FO7g6lO8-Xvozqk9mHmmL`). Spine for the public resume. Text below is a messy extraction of the current PDF, including original wording, contact-line wrapping, and the `public_url` cert-link artifact.

---

Rishabh Singh Thakur

Website: https://rishabh-singh-thakur.vercel.app | Address: Toronto, ON. | Phone number: +15148032804 Email address: rishabh.4082@gmail.com | Github: https://github.com/thakurrishabh LinkedIn: https://linkedin.com/in/rishabh-singh-thakur-ba3bb4168 | Blog: https://dev.to/thakurrishabh

Summary

Helping businesses leverage AI and cloud infrastructure to automate workflows, reduce operational costs, and accelerate time-to-market. AI Cloud Engineer & SRE with around 5 years of hands-on experience building scalable GCP infrastructure with HL7 FHIR compliance for 1000+ SDM stores across Canada. Built 3 full stack AI Saas apps with one production grade app with google auth, stripe payments and OWASP security integration.

Work experience

Senior Site Reliability Engineer
Loblaw Companies Limited
TORONTO, CANADA 03/2025 – Present

Built and Architected HL7 FHIR Compliant GCP based Services
- Collaborated with the teams to onboard new province integration to SDM stores ensuring HL7 FHIR compliance with provincial systems and successfully led control GAP TRA assessments.
- Collaborated with teams to drive business decisions in Eprescription, EHealth, Interactive voice response (IVR) to ensure HL7 FHIR compliance with external systems while seamless integration between GCP and on prem edge devices.

SDM On-Prem VMWARE to Vanilla Kubernetes Migration With GCP Integration
- Participated in pilots to migrate on prem vmware instances of 15 stores to vanilla kubernetes as part of an initiative to cover 700 stores across ontario. Rebuilt entire store from ground up including Dell hardware, kubernetes node config, OS install.
- Developed ansible playbooks that run on GKE to migrate vmware workloads to vanilla Kubernetes containers & VMs using kubevirt for each store.
- Configured FLUXCD gitops to enable seamless deployment of microservices using Kustomization from a central management gke cluster

Site Reliability Engineer 2
Loblaw Companies Limited
TORONTO, CANADA 11/2022 – 03/2025

Web UI to manage and trigger SDM Deployments provisioned using Terraform
- Developed a web UI using HTML, bootstrap, javascript and python flask to manage deployment configurations and trigger deployments in gitlab using API.
- Employed a CloudSQL mysql backend DB for data storage and integrated Azure AD of the org to only allow authenticated access.
- Deployed the app on GKE cluster and enabled access via internally managed DNS and istio.

Google Kubernetes Engine runners for 1000+ Store Deployment Framework and event driven monitoring provisioned using Terraform
- Provisioned GKE Cluster hosting gitlab runners to support deployments to 1000+ stores using helm involving 20k plus gitlab jobs per deployment happening few times a week.
- Implemented job auto retry and adjusted concurrency to achieve a failure rate of less than 1%.
- Migrated auto-scaling Prometheus based gitlab pipeline exporters to CloudSQL, achieving 2x performance and efficiency. Converted PROMQL queries in Grafana dashboards to SQL.
- Implemented gitlab webhooks to push pipeline and job events to GCP PubSub via cloud functions which are inserted into mysql via autoscaling python exporter pods.

Custom Ansible Framework Development
- Developed a custom ansible framework inspired by rundeck to enable users to configure SDM stores remotely.
- Played a key role in modernizing existing legacy shell based deployment framework by re-architecting the solution to leverage GCP and ansible.
- Migrated 10+ complex processes as part of the modernization involving sequential file processing, IBM MQ configurations, microservice deployment etc.
- Participated in 5+ pilots and 10+ rollouts that involved up to 1200 SDM stores across multiple provinces in a single night.

Skills: Python, GCP, Google Kubernetes Engine (GKE), Docker, Ansible, Terraform, Gitlab, CICD, MySQL, Prometheus.io, Grafana, Helm (Software), Flask, JavaScript, Bootstrap (Framework), HTML, Istio, DNS, VPC, API, IBM MQ, cloud function, GCP PubSub, Linux, Scripting, Containerization

Site Reliability Engineer 1
Loblaw Companies Limited TORONTO, CANADA 05/2021 – 10/2022

GCP Infra and CI/CD to deploy 20+ apps on Google Kubernetes Engine provisioned using Terraform
- Created a common CI/CD catalog for 20+ apps in Gitlab to support deployments of docker artifacts from GAR to GKE using helm and built pipelines for infrastructure management in GCP using terraform.
- Implemented security through workload identity for keyless auth to GCP services for the deployed apps, Istio to enable external connections and secret manager for storing sensitive keys and parameters.
- Documented the end-to-end setup in confluence to enable devs in implementing above without SRE intervention

Dynamic Gitlab Pipelines Infra and Monitoring to support 1000+ store deployment
- Created dynamic nested pipelines in Gitlab using python and jsonnet for concurrent deployments to 1000+ SDM stores.
- Created MIG (managed instance group) based Gitlab runners to support 5000+ parallel Gitlab job execution. and a cloud function to create dynamic runner tags for each pipeline.
- Developed auto scaling prometheus exporter pods using python on GKE to monitor the above Gitlab pipelines through Grafana dashboards.
- Implemented a controller pod for auto scaling based on load and performed memory invalidation and segmentation to prevent errors relating to stale and duplicate data.

Personal Projects
TORONTO, CANADA 09/2024 – 10/2025

RenderMuseAI – Text-to-Explainer Animation Platform
Built and launched RenderMuseAI, an AI-powered platform that converts text prompts into educational Manim animations.
- Used GitHub Copilot & Claude to generate concept-aware Manim code with supervised sub-agents
- Features: Lovable.dev frontend, Supabase backend, Daytona containerized hosting, Stripe payments, Google auth
- Demo: Fourier Transform explainer text to explainer animation platform - RenderMuseAI Demo
  https://youtu.be/DSLrlUCjsSA

AI Video Reel Generator
Built a tool to create 1-minute reels from text prompts.
- Integrated Gemini for script generation, Imagen for images, GPT-4o-mini TTS for narration, FFmpeg for video + subtitles.
- Frontend: Lovable.dev; Backend: GCP Firebase + Cloud Run.

AI Meal Planning & Recipe App
Built a conversational app for meal planning and grocery management.
- Flutter frontend mobile app + GCP Firebase backend; GPT-4o for grocery bill image scanning & recipe generation.
- Gemini multimodal voice-to-voice for recipe CRUD via natural conversation

Skills: Python, React, Flutter, GCP (Firebase, Cloud Run, OAUTH login), Supabase, Stripe, FFmpeg, GitHub Copilot, Claude Code, OpenAI and Gemini API (text, image, tts, voice), Microsoft Playwright MCP, lovable.dev, vercel, daytona.

Certificates
06/2024 Machine Learning Modeling Pipelines in Production Coursera https://coursera.org/share/877a1fc7ab16f3d029b9778b98aa41bd

Machine Learning Data Lifecycle in Production Coursera https://coursera.org/share/447273530eeaa5e24b5166f8a383e6da

12/2020 - 12/2023 AWS (Amazon Web Services) Certified Solutions Architect Associate https:/www.youracclaim.com/badges/1d35a3c5-92664a6c-8848-902f0f05c4a1/public_url

(extracted hyperlink target, with the public_url artifact:)
https://www.youracclaim.com/badges/1d35a3c5-9266-4a6c-8848-902f0f05c4a1/public_url

Education
Concordia University
Electrical and Computer Engineering | M.Eng
MONTREAL, CANADA 01/2019 – 12/2020
Graduated with 3.75/4 GPA

Jawaharlal Nehru Technological University
Electronics and Comm Engineering | B.Tech
HYDERABAD, INDIA 09/2014 – 05/2018

SOFT SKILLS: Communication, Team Player, Quick Learner, Innovative.
LANGUAGES: English, Hindi, Telugu.
HOBBIES: Reading, Playing and recording Guitar and Ice Skating

---

Extracted URL dump from PDF annotations:
- https://rishabh-singh-thakur.vercel.app
- mailto:rishabh.4082@gmail.com
- https://github.com/thakurrishabh
- https://dev.to/thakurrishabh
- https://youtu.be/DSLrlUCjsSA
- https://coursera.org/share/877a1fc7ab16f3d029b9778b98aa41bd
- https://coursera.org/share/447273530eeaa5e24b5166f8a383e6da
- https://www.youracclaim.com/badges/1d35a3c5-9266-4a6c-8848-902f0f05c4a1/public_url
