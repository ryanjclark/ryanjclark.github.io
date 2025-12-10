---
layout: default
title: "Curriculum Vitae"
---

## Profile 
Amsterdam-based Senior DevOps Engineer with expertise in microservice design, automating deployments, monitoring services, and creating AI applications.

## Experience

### Fetch (Unicorn mobile app) — 2021-Present
**> AI and Foundational Models**
- Created **MCP server knowledge base** that helps developers configure deployments for the bespoke Terraform tool that powers 1000+ production deploys; 50+ MCP tool calls per day (few-shot prompting, retrieval-augmented generation).
- Currently helping design and implement a **MCP Gateway** to address tool discoverability, metrics, and auth (Golang).
- Designed **penetration testing framework** that detects newly created public IP addresses and uses a foundational model to enrich them by retrieving OpenAPI routes, gateway proxy routes, and deployment metadata (AI as a judge, AWS Lambda).

**> DevOps**
- Core maintainer of a bespoke **Terraform deploy tool** responsible for 1000 deploys per week across hundreds of services (Golang); participate in DevOps support of 200 engineers [CICD, troubleshooting].
- Improved velocity of machine learning engineers by using **Helm charts** and Karpenter to spin up/down GPU nodes as needed to serve models. Docker mirror was added to reduce image pull time; cut model deployment time by 70%.
- **Administrator of Kubernetes clusters**. Designed multi-cluster strategy, governance, and topology. Automated deployment of core Operators and alarms in each cluster [ArgoCD, LB, DNS, Kube State, Secrets, OPA].
- **Administrator of Kafka clusters** that supports 100k writes/s. Lead architect of a microservice strategy of Kafka Connect to host 250 connectors, each in isolated deployments (AWS ECS, Java).

**> Backend Engineering**
- Wrote **Kafka producers** and consumers to handle asynchronous communication for critical high throughput; Superbowl Ad that resulted in 1.2M signups in 2 minutes (Golang, AWS ECS).
- Architected a fault-tolerant service to perform **canary/blue-green rollouts** for services hosted on any platform [AWS ECS, K8s, etc] using ALB, Target Groups, listener rules (Golang).
- Wrote **Feature Store API** to serve S3 URIs to machine learning model training jobs; given parameters of dataset, version, and timestamps (Golang).
- Wrote **ETL microservice** that tails Graph Database CDC and normalizes JSON; 15k records/s (Golang, K8s Deployment).

### Aptive Resources (Government consulting) — 2020-2021
**> Data Engineering**
- Worked with clients to build highly scalable **social media scraping apps** that accounted for sessions and rate limiting (Kotlin, K8s Deployment).
- Created **daily batch job to clean text** from social media posts and comments. A scoring model picked up the clean data to vectorize and predict (sklearn, spaCy, K8s CronJob).

## Education
M.S. Data Science, Data Engineering

## Certifications
[![AWS Certified Solutions Architect](/assets/images/aws-certified-solutions-architect-associate.png)](https://www.credly.com/badges/69f12e4e-6df0-4eff-8ec0-97c7d022d8d6/public_url)

## Writings
[Medium article: "Kafka Connect as a Microservice"](https://techblog.fetch.com/kafka-connect-as-a-microservice-72b0148bbcee)
