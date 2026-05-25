# Sharath Aradhyamath | DevOps / Site Reliability Engineer (SRE)

sharatham94@gmail.com | +8180-6409-5387 | Tokyo, Japan | [linkedin.com/in/sharath-aradhyamath](https://www.linkedin.com/in/sharath-aradhyamath/)

---

## Summary

DevOps and SRE Engineer with 7+ years of experience across robotics, e-commerce, and mobility platforms. Previously the sole SRE for a warehouse robotics system supporting 100+ robots, reporting directly to the CEO. Now building platform reliability at Rakuten Ichiba. Deep experience in Kubernetes, AWS, Terraform, Prometheus/Grafana, and CI/CD automation across cloud and edge environments.

---

## Technical Skills

* **Cloud Platforms**: AWS (EKS, EC2, RDS, S3, IAM, CloudWatch), Azure
* **Containers & Orchestration**: Kubernetes, Docker, Helm, Kustomize, Linkerd, KEDA
* **Infrastructure as Code**: Terraform, Ansible, SaltStack
* **CI/CD**: GitHub Actions, Jenkins, Spinnaker, Fastlane (App Automation)
* **Scripting & Programming**: Python, Bash
* **Observability**: Prometheus, Grafana, Loki, Tempo, ELK Stack (Elasticsearch, Logstash, Kibana), Datadog, PagerDuty
* **Databases**: Cassandra, PostgreSQL (backup/recovery with Barman), Redis, DynamoDB
* **Networking**: UniFi, Wireless network design, VPN/Tailscale, DNS/DHCP/TCP/IP debugging
* **Practices**: SLO/SLI/error budgets, incident management, runbooks, postmortems, on-call, load testing

---

## Professional Experience

### Rakuten Group | Platform Engineer | Tokyo, Japan | *Aug 2025 – Present*
*Rakuten Ichiba is Japan's largest online marketplace, connecting millions of buyers with 50,000+ merchant stores across every retail category.*

- Defined SLOs/SLIs for 3 critical services and established on-call rotation with structured incident management. Authored runbooks and incident response documentation so engineers new to the team could get up to speed on-call quickly. Conducted postmortems for all P0/P1 incidents.
- Built 20+ Grafana dashboards covering service performance, infrastructure health, and application metrics; authored Prometheus alerting rules and routed alerts through PagerDuty to support on-call incident response and proactive issue detection.
- Planned and executed 10+ Apache JMeter load tests simulating Super Sale traffic conditions, identified and resolved performance bottlenecks before production traffic peaks — keeping the platform stable during Rakuten's highest-revenue sales events.
- Bootstrapped Rakuten Express (same-day delivery service) backend infrastructure from scratch — provisioning Kubernetes workloads, configuring Prometheus monitoring, and establishing production observability ahead of go-live.

### Safe Security | DevOps Engineer | Bengaluru, India | *Aug 2024 – Jul 2025*
*Safe Security helps enterprises measure and manage cyber risk in real time using a SAFE Score — similar to a credit score for cybersecurity.*

- Created reusable GitHub Actions workflows that reduced new-service CI/CD setup from 1 day to 1 hour, so developers could self-serve their own build, test, and deployment pipelines without waiting on the DevOps team.
- Migrated AWS infrastructure from CDK to Terraform across VPC, IAM, ECS, RDS, S3, and CloudWatch. Built reusable modules for shared services so teams could provision new infrastructure without writing it from scratch, cutting setup time from hours to minutes.
- Standardized deployment and repository patterns for a monolith-to-microservices migration, so 17 services could build, test, and release on their own schedule.

### Rapyuta Robotics | Site Reliability Engineer | Tokyo, Japan | *May 2022 – Jul 2024*
*Cloud robotics startup building autonomous mobile robots (AMRs) and a cloud platform for warehouse logistics.*

- Served as the sole SRE for the Rapyuta ASRS team, supporting 25+ engineers and production robotics operations while reporting directly to the CEO.
- Built observability for 100+ robots using Prometheus, Grafana, Loki, Tempo, and OpenTelemetry Collector. Gave the team real-time visibility into robot health, application failures, and infrastructure performance across the entire fleet.
- Automated robot onboarding using Ansible and Semaphore UI, reducing setup time per robot from 2 hours to 5 minutes, so non-engineers could run maintenance workflows without involving the engineering team.
- Implemented PostgreSQL backup and recovery using Barman for disaster recovery, reducing database restore time to 5 minutes so the team could recover quickly without second-guessing the process.
- Owned edge-server infrastructure for robotics deployments, evaluating hardware, provisioning servers, bootstrapping environments, and preparing on-site systems for production use.
- Designed production wireless networks for robot deployments across 7 sites, using UniFi gateways, switches, and access points; optimized AP placement to improve robot connectivity and reduce coverage gaps.
- Built timeout-triggered packet-capture automation that uploaded PCAP files to Slack, which identified LiDAR traffic saturation as the root cause of robot communication failures.
- Simplified deployment workflows using internal Kubernetes manifests & Kustomize, standardizing declarative service configuration and enabling zero-downtime deployments with automated rollback capabilities.

### Vogo Automotive | DevOps Engineer | Bengaluru, India | *Nov 2020 – Mar 2022*
*Electric scooter sharing platform operating 100K+ vehicles across Indian cities.*

- Led a 4-person DevOps team owning AWS infrastructure, Kubernetes operations, CI/CD, monitoring, and production support.
- Migrated 95% of workloads to Kubernetes on Amazon EKS, including MongoDB, Elasticsearch, Kafka, Airflow, and application services.
- Reduced AWS costs by 30% through EC2/EKS right-sizing, unused resource cleanup, and AWS Savings Plans and Reserved Instances for predictable production workloads.
- Built CI/CD and Kubernetes deployment workflows for 12 services using GitHub Actions, Jenkins, Spinnaker, Helm, and Helmfile. Standardized staging, production, and rollback releases across all environments, cutting manual release steps significantly.
- Automated Android APK builds and Play Store release workflows using Fastlane, integrating mobile releases into CI/CD and reducing manual QA/developer release effort.
- Deployed and configured Linkerd service mesh across Kubernetes workloads, adding mTLS-based service-to-service security and giving the team visibility into service-to-service traffic.
- Deployed KEDA (Kubernetes Event-Driven Autoscaling) to automatically scale RabbitMQ consumer workers based on queue depth, keeping queue processing fast during traffic spikes without over-provisioning idle workers.
- Built Datadog and Grafana dashboards with alerting for Kubernetes workloads, AWS infrastructure, and business metrics, accelerating incident detection and mean time to resolution (MTTR).

### Evive | DevOps Engineer | Bengaluru, India | *May 2018 – Oct 2020*
*HR benefits administration platform serving Fortune 500 companies during open enrollment periods.*

- Served as the sole DevOps engineer for the MyEvive product team, owning cloud infrastructure, release deployments, and production support across staging and production environments.
- Provisioned and maintained compute capacity during open enrollment peak periods, keeping the MyEvive platform stable under increased traffic.
- Automated server configuration using custom SaltStack modules, so every new server came up configured correctly without manual steps.
- Wrote Python migration/ETL scripts to automate data-processing workflows and reduce manual developer effort.

---

## Education

**Master of Computer Applications**, Christ University — Bengaluru, India | 2015 – 2018  
**Bachelor of Computer Applications**, Jain University — Bengaluru, India | 2012 – 2015

---

## Publication

***Multi-key Modified Tiny Encryption Algorithm for Healthcare*** | Science Publishing Corporation | 2018
- Research paper on improving data security for autonomous medical devices. DOI: [doi.org/10.14419/ijet.v7i2.9894](https://doi.org/10.14419/ijet.v7i2.9894)
