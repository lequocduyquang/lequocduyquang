# Quang Le

**Software Engineer · Backend & ML Systems** — hipages Group (ASX-listed), via CBTW
Ho Chi Minh City · working with Sydney

I build the systems that price and match jobs on Australia's largest online trade marketplace:
the Matching Engine, AI value-based pricing on Amazon Bedrock, and ML model serving on Databricks.

[Portfolio](https://quanglequocduy.github.io/portfolio/) ·
[LinkedIn](https://www.linkedin.com/in/quang-le-448606197/) ·
[Writing](https://quangle.hashnode.dev) ·
[Hugging Face](https://huggingface.co/quanglequocduy) ·
[Email](mailto:duyquangbtx@gmail.com)

## Currently

- **Primary owner of the Matching Engine** (NestJS, PostgreSQL, Kafka CDC, Temporal) — 4× end-to-end latency
  reduction through LRU caching, N+1 elimination, and decoupling from the legacy PHP monolith.
- **Lead engineer on AI Value-Based Pricing** — Claude on Amazon Bedrock values each job and derives lead price;
  Phase 1 A/B read: +15.4% CV/job, +19.9% price/claim, ~$2.3M/yr projected.
- **MLOps owner for model serving on Databricks** — Databricks Asset Bundles CI/CD with staging gate, MLflow registry,
  per-category shadow → A/B → cutover for Dynamic Pricing V2; retrained and served the job-sizing models.
- **Led the team's EKS migration** (legacy KOPS → `hip-eks-prod`) — F5 ingress, IRSA, Kafka mTLS, Bedrock IAM,
  dark deploys across marketplace, leads, and ML serving.
- 720+ merged PRs across 20+ repositories · 27 technical design docs · 3 P2 incidents led to resolution.

## Selected work

| Project | Notes |
|---|---|
| [xray-diagnosis-ai](https://github.com/lequocduyquang/xray-diagnosis-ai) | Pediatric chest X-ray pneumonia diagnosis for Children's Hospital 2 (HCMC) — ResNet50 / DenseNet121, volunteer project |
| [xray-diagnosis-cam](https://github.com/lequocduyquang/xray-diagnosis-cam) | Eigen-CAM explainability: class-agnostic heatmaps so clinicians can see what the model attends to |
| [xray-ui](https://github.com/lequocduyquang/xray-ui) | Clinician-facing UI for the diagnosis system (Remix, TypeScript) |
| [micro-kafka](https://github.com/lequocduyquang/micro-kafka) | Event-driven microservices with Kafka and Node.js |
| [microgo](https://github.com/lequocduyquang/microgo) | Go microservices with Chi, PostgreSQL, MongoDB, RabbitMQ |
| [coffeeN](https://github.com/lequocduyquang/coffeeN) | Design patterns by example in Go |

## Stack

| | |
|---|---|
| **Languages** | TypeScript, Go, Python, SQL |
| **Backend** | Node.js, NestJS, Kafka, Temporal, PostgreSQL, Redis |
| **AI / ML** | Amazon Bedrock, OpenAI, Databricks ML, MLflow, Agentic RAG, GrowthBook experimentation |
| **Infrastructure** | AWS, Kubernetes / EKS, ArgoCD, Docker, Terraform |
| **Observability** | OpenTelemetry, Honeycomb, Grafana |

## Certifications & recognition

- Databricks Certified Machine Learning Engineer Associate (2026)
- Databricks Certified Generative AI Engineer Associate (2025)
- Edison Award · Inspirational Team Member Award — hipages Group
- B.Sc. Software Engineering — VNUHCM University of Science

## Writing

- [The beauty of Orchestration Saga in Microservices](https://quangle.hashnode.dev/the-beauty-of-orchestration-saga-in-microservices)
- [The beauty of Kafka in Microservices system](https://quangle.hashnode.dev/the-beauty-of-kafka-in-microservices-system)
- More at [quangle.hashnode.dev](https://quangle.hashnode.dev)
