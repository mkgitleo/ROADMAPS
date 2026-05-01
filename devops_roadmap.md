# 🚀 Complete DevOps Mastery Roadmap
### Learn DevOps in the Correct Order — From Zero to Senior Engineer

> **Golden Rule:** Learn by DOING. Every concept must have a hands-on project.
> **Timeline:** 10–12 months of consistent daily practice (2–3 hours/day)

---

## ✅ CORRECT ORDER OF TECHNOLOGIES

```
1.  Linux & Command Line
2.  Networking Basics
3.  Git & Version Control
4.  Programming / Scripting (Python + Bash)
5.  Docker & Containers
6.  CI/CD Pipelines
7.  Cloud Platform (AWS)
8.  Infrastructure as Code — Terraform
9.  Configuration Management — Ansible
10. Kubernetes (K8s)
11. Monitoring & Observability (Prometheus + Grafana + ELK)
12. DevSecOps & Security
13. GitOps (ArgoCD)
14. Advanced Topics & Capstone Project
```

---

## 📍 PHASE 1 — Foundation (Month 1–2)

---

### 🔷 1. Linux & Command Line (Week 1–2)
> Everything in DevOps runs on Linux. This is non-negotiable.

| Topic | What to Learn |
|---|---|
| Navigation | ls, cd, pwd, mkdir, rm, cp, mv |
| Permissions | chmod, chown, user groups |
| Processes | ps, kill, top, htop, systemctl |
| Networking | ping, curl, wget, ssh, netstat |
| Shell Scripting | bash scripts, loops, conditions, functions |
| Package Managers | apt, yum, dnf |
| Cron Jobs | Schedule automated tasks |
| Text Editors | vim, nano basics |
| File System | /etc, /var, /home, /tmp structure |
| Logs | /var/log, journalctl, tail -f |

**🛠️ Project:** Write a bash script that:
- Monitors disk usage
- Sends alert if disk > 80%
- Auto-cleans /tmp folder
- Logs everything to a file

**📚 Resources:**
- https://linuxjourney.com (Free)
- https://overthewire.org/wargames/bandit (Fun hacking practice)
- Book: "The Linux Command Line" by William Shotts

---

### 🔷 2. Networking Basics (Week 2–3)
> You need this to understand how servers talk to each other.

| Topic | What to Learn |
|---|---|
| OSI Model | All 7 layers and their purpose |
| Protocols | TCP/IP, UDP, HTTP, HTTPS, FTP, SSH |
| DNS | How domain name resolution works |
| IP Addressing | IPv4, IPv6, subnetting, CIDR notation |
| Ports | Common ports (22, 80, 443, 3306, 5432) |
| Firewalls | iptables, ufw, security groups |
| Load Balancing | Round robin, least connections |
| VPN | Tunneling concepts |

**🛠️ Project:** Set up a Linux server, configure firewall rules, host a simple HTML page

---

### 🔷 3. Git & Version Control (Week 3–4)
> DevOps without Git is impossible.

| Topic | What to Learn |
|---|---|
| Basics | init, clone, add, commit, push, pull |
| Branching | branch, checkout, merge, rebase |
| Strategies | GitFlow, trunk-based development |
| Collaboration | Pull Requests, code reviews, forks |
| Advanced | cherry-pick, stash, reset, revert |
| GitHub/GitLab | Repositories, Actions, webhooks |

**🛠️ Project:**
- Create a GitHub repo
- Practice GitFlow branching strategy
- Create your first Pull Request and merge it

**📚 Resources:**
- https://learngitbranching.js.org (Interactive & Free)
- https://git-scm.com/doc

---

## 📍 PHASE 2 — Scripting & Automation (Month 2)

---

### 🔷 4. Python + Bash Scripting
> Automate EVERYTHING. This separates good DevOps from great DevOps.

**Bash — Focus On:**
- Variables, arrays, loops (for, while)
- Conditionals (if/else, case)
- Functions
- File I/O
- Error handling (exit codes)
- Cron automation

**Python — Focus On:**
- Variables, data types, functions
- File handling (read/write)
- os, sys, subprocess modules
- requests module (HTTP calls)
- JSON handling
- Boto3 (AWS SDK — very important later)
- Paramiko (SSH automation)

**🛠️ Projects:**
1. Bash: Auto-deploy script that pulls from Git and restarts a service
2. Python: Script that monitors a website and sends email if it's down
3. Python + AWS Boto3: List all EC2 instances and their statuses

---

## 📍 PHASE 3 — Containers (Month 3)

---

### 🔷 5. Docker & Containerization
> The most important DevOps skill after Linux. Learn it deeply.

| Topic | What to Learn |
|---|---|
| Concepts | What is a container vs VM |
| Dockerfile | FROM, RUN, COPY, EXPOSE, CMD, ENTRYPOINT |
| CLI | build, run, exec, logs, ps, stop, rm |
| Networking | Bridge, host, none networks |
| Volumes | Persistent storage, bind mounts |
| Docker Compose | Multi-container apps (yaml syntax) |
| Registry | Docker Hub, push & pull images |
| Optimization | Multi-stage builds, .dockerignore |

**🛠️ Projects:**
1. Dockerize a Node.js / Python Flask app
2. Use Docker Compose: App + Database + Redis
3. Optimize a Docker image from 800MB → under 100MB

**📚 Resources:**
- https://docs.docker.com/get-started
- Play with Docker: https://labs.play-with-docker.com (Free browser lab)

---

## 📍 PHASE 4 — CI/CD Pipelines (Month 4)

---

### 🔷 6. CI/CD — Continuous Integration & Delivery

#### Start with: GitHub Actions (easiest)

| Topic | What to Learn |
|---|---|
| Concepts | What is CI/CD and why it matters |
| Workflows | .github/workflows YAML syntax |
| Triggers | push, pull_request, schedule, workflow_dispatch |
| Jobs & Steps | runners, actions marketplace |
| Secrets | Managing API keys securely in pipelines |
| Artifacts | Storing build outputs |
| Environments | dev, staging, production gates |

#### Then Learn: Jenkins (industry standard)

| Topic | What to Learn |
|---|---|
| Setup | Install Jenkins on EC2 / Docker |
| Jenkinsfile | Declarative & scripted pipelines |
| Plugins | Git, Docker, Slack, AWS plugins |
| Architecture | Master-agent setup |
| Blue Ocean | Modern Jenkins UI |

**🛠️ Projects:**
1. GitHub Actions: On every push → Build Docker image → Push to Docker Hub → Deploy
2. Jenkins: Full pipeline for a Java/Python app with testing stages
3. Add Slack notifications to your pipeline on success/failure

---

## 📍 PHASE 5 — Cloud Platform (Month 5)

---

### 🔷 7. AWS — Amazon Web Services
> Start with AWS. It has 33% market share and most job postings require it.

#### Must-Know Core Services:

| Service | Purpose |
|---|---|
| **EC2** | Virtual machines (servers) |
| **S3** | Object storage (files, images, backups) |
| **VPC** | Virtual private network / networking |
| **IAM** | Users, roles, permissions (CRITICAL) |
| **RDS** | Managed relational databases |
| **Route 53** | DNS management |
| **CloudWatch** | Monitoring and logs |
| **ELB** | Elastic Load Balancer |
| **Auto Scaling** | Automatically scale EC2 instances |

#### DevOps-Specific Services:

| Service | Purpose |
|---|---|
| **ECS** | Run Docker containers |
| **EKS** | Managed Kubernetes |
| **ECR** | Container image registry |
| **CodePipeline** | AWS CI/CD service |
| **Lambda** | Serverless functions |
| **CloudFormation** | AWS-native IaC |
| **Systems Manager** | Remote server management |

**🛠️ Projects:**
1. Host a static website on S3 with CloudFront CDN
2. Deploy a Dockerized app on EC2 with Auto Scaling + ELB
3. Set up a VPC with public + private subnets + NAT Gateway
4. Create IAM roles for EC2 to access S3 without credentials

**🏆 Certification:** AWS Cloud Practitioner → AWS Solutions Architect Associate

**📚 Resources:**
- https://skillbuilder.aws (AWS free training)
- https://www.freecodecamp.org (Free AWS tutorials)
- Use AWS Free Tier for practice!

---

## 📍 PHASE 6 — Infrastructure as Code (Month 6)

---

### 🔷 8. Terraform — Infrastructure as Code

| Topic | What to Learn |
|---|---|
| HCL Syntax | Variables, outputs, locals, data sources |
| Core Commands | init, plan, apply, destroy, validate |
| Providers | AWS, Azure, GCP providers |
| Resources | EC2, S3, VPC, RDS in Terraform |
| State Management | terraform.tfstate, remote state (S3 backend) |
| Modules | Reusable infrastructure components |
| Workspaces | dev / staging / prod environments |
| Import | Import existing infrastructure |
| Terragrunt | DRY Terraform configurations |

**🛠️ Projects:**
1. Provision an entire AWS environment with Terraform:
   - VPC + Subnets + Security Groups
   - EC2 instance with auto-configured web server
   - RDS database
   - S3 bucket for state storage
2. Create reusable Terraform modules
3. Use Terraform workspaces for dev/prod environments

**🏆 Certification:** HashiCorp Terraform Associate

---

## 📍 PHASE 7 — Configuration Management (Month 7)

---

### 🔷 9. Ansible — Configuration Management

| Topic | What to Learn |
|---|---|
| Architecture | Agentless, SSH-based, control node |
| Inventory | Static & dynamic inventory files |
| Playbooks | YAML syntax, tasks, plays |
| Modules | apt, yum, copy, template, service, file |
| Variables | vars, group_vars, host_vars |
| Templates | Jinja2 templating |
| Roles | Structured, reusable playbooks |
| Galaxy | Community roles repository |
| Handlers | Trigger actions on change |
| Ansible Vault | Encrypt sensitive data |

**🛠️ Projects:**
1. Provision 5 servers automatically (install nginx, docker, configure firewall)
2. Deploy a web app using Ansible roles
3. Combine Terraform + Ansible: Terraform creates servers, Ansible configures them

---

## 📍 PHASE 8 — Kubernetes (Month 8)

---

### 🔷 10. Kubernetes (K8s) — Container Orchestration

| Topic | What to Learn |
|---|---|
| Architecture | Master node, worker nodes, etcd |
| Core Objects | Pods, Deployments, Services, ConfigMaps, Secrets |
| Networking | ClusterIP, NodePort, LoadBalancer, Ingress |
| Storage | PersistentVolume, PersistentVolumeClaim |
| Scaling | HorizontalPodAutoscaler (HPA) |
| Rolling Updates | Zero-downtime deployments |
| StatefulSets | Databases in Kubernetes |
| DaemonSets | Run on every node |
| kubectl | All essential commands |
| Helm | Kubernetes package manager |
| Namespaces | Environment isolation |
| RBAC | Role-based access control |

**🛠️ Projects:**
1. Deploy a microservices app (3 services) on local Kubernetes (minikube/kind)
2. Set up an Ingress controller with SSL
3. Configure HPA — auto-scale based on CPU usage
4. Deploy on AWS EKS with Terraform
5. Package your app with Helm charts

**🏆 Certification:** CKA — Certified Kubernetes Administrator

**📚 Resources:**
- https://kubernetes.io/docs/tutorials
- https://killercoda.com (Free K8s browser labs)
- https://killer.sh (CKA exam simulator)

---

## 📍 PHASE 9 — Monitoring & Observability (Month 9)

---

### 🔷 11. Monitoring Stack

#### Prometheus + Grafana (Metrics)

| Topic | What to Learn |
|---|---|
| Prometheus | Scraping metrics, targets, alertmanager |
| PromQL | Query language for metrics |
| Exporters | node_exporter, blackbox_exporter |
| Alert Rules | CPU, memory, disk alerts |
| Grafana | Dashboards, panels, data sources |
| Grafana Alerts | Slack/email notifications |

#### ELK Stack (Logging)

| Tool | Purpose |
|---|---|
| **Elasticsearch** | Store and index logs |
| **Logstash** | Collect and transform logs |
| **Kibana** | Visualize and search logs |
| **Filebeat** | Lightweight log shipper |

**🛠️ Projects:**
1. Set up Prometheus + Grafana on Kubernetes with Helm
2. Create dashboards for CPU, memory, network, pod health
3. Set up ELK stack, ship Nginx logs, create Kibana visualizations
4. Configure PagerDuty/Slack alerts for critical metrics

---

## 📍 PHASE 10 — Security (Month 10)

---

### 🔷 12. DevSecOps — Security

| Topic | What to Learn |
|---|---|
| HashiCorp Vault | Secrets management, dynamic credentials |
| Container Scanning | Trivy, Snyk — scan for vulnerabilities |
| SAST | Static code analysis (SonarQube) |
| IAM Best Practices | Least privilege, MFA, roles |
| Network Policies | K8s network segmentation |
| SSL/TLS | Let's Encrypt, cert-manager in K8s |
| OWASP Top 10 | Common web vulnerabilities |
| Compliance | CIS benchmarks, SOC2 basics |

**🛠️ Projects:**
1. Integrate Trivy scanning into your CI/CD pipeline
2. Set up HashiCorp Vault and inject secrets into K8s pods
3. Run SonarQube analysis in Jenkins pipeline

---

## 📍 PHASE 11 — GitOps & Advanced (Month 11)

---

### 🔷 13. GitOps with ArgoCD

| Topic | What to Learn |
|---|---|
| GitOps Principles | Git as single source of truth |
| ArgoCD | Install, configure, sync apps |
| App of Apps | Manage multiple apps |
| Sync Policies | Auto-sync, self-heal |
| FluxCD | Alternative GitOps tool |

**🛠️ Projects:**
1. Set up ArgoCD on Kubernetes
2. Deploy apps automatically when you push to GitHub
3. Implement multi-environment GitOps (dev/staging/prod)

---

## 📍 PHASE 12 — Capstone Project (Month 12)

---

### 🔷 Final Capstone Project

Build this complete project to prove mastery:

```
📦 E-commerce Microservices Platform

Architecture:
├── 4 microservices (User, Product, Order, Notification)
├── Each service in its own Docker container
├── Kubernetes cluster on AWS EKS (via Terraform)
├── Helm charts for all services
├── GitHub Actions CI/CD pipeline
│   ├── Code push → Tests run
│   ├── Docker image built & pushed to ECR
│   └── ArgoCD deploys to K8s automatically
├── Ansible for initial server configuration
├── Prometheus + Grafana monitoring dashboards
├── ELK stack for centralized logging
├── HashiCorp Vault for secrets
├── SSL certificates via cert-manager
└── Auto-scaling with HPA
```

This project covers EVERY DevOps skill and will impress any interviewer.

---

## 🏆 Certifications — In This Exact Order

| Order | Certification | Month | Importance |
|---|---|---|---|
| 1st | AWS Cloud Practitioner (CLF-C02) | Month 5 | 🔴 Must Have |
| 2nd | AWS Solutions Architect Associate (SAA-C03) | Month 6 | 🔴 Must Have |
| 3rd | HashiCorp Terraform Associate | Month 7 | 🟡 High Value |
| 4th | CKA — Certified Kubernetes Administrator | Month 9 | 🔴 Must Have |
| 5th | AWS DevOps Engineer Professional (DOP-C02) | Month 12 | 🟡 High Value |
| 6th | Docker Certified Associate | Month 4 | 🟢 Good to Have |

---

## 🗓️ Month-by-Month Study Plan

| Month | Focus | Goal |
|---|---|---|
| Month 1 | Linux + Networking | Be comfortable in terminal |
| Month 2 | Git + Python + Bash | Automate basic tasks |
| Month 3 | Docker | Containerize any app |
| Month 4 | CI/CD (GitHub Actions + Jenkins) | Build full pipeline |
| Month 5 | AWS Core Services | Deploy on cloud, get CCP cert |
| Month 6 | Terraform | Provision infra as code, get SAA cert |
| Month 7 | Ansible | Auto-configure servers, get Terraform cert |
| Month 8 | Kubernetes | Orchestrate containers, start CKA prep |
| Month 9 | Monitoring (Prometheus + Grafana + ELK) | Full observability, get CKA cert |
| Month 10 | DevSecOps | Secure everything |
| Month 11 | GitOps + ArgoCD | Automated delivery |
| Month 12 | Capstone Project + Job Hunt | Get hired! |

---

## 📚 Best Free Learning Resources

| Technology | Resource | Link |
|---|---|---|
| Linux | Linux Journey | https://linuxjourney.com |
| Linux Practice | OverTheWire Bandit | https://overthewire.org |
| Git | Learn Git Branching | https://learngitbranching.js.org |
| Docker | Docker Docs | https://docs.docker.com |
| Docker Practice | Play with Docker | https://labs.play-with-docker.com |
| Kubernetes | Official Tutorial | https://kubernetes.io/docs/tutorials |
| K8s Practice | Killercoda | https://killercoda.com |
| AWS | Skill Builder | https://skillbuilder.aws |
| Terraform | HashiCorp Tutorials | https://developer.hashicorp.com/terraform/tutorials |
| Full Roadmap | roadmap.sh | https://roadmap.sh/devops |

---

## 💡 Daily Study Routine (2–3 hours/day)

```
⏰ 30 min  — Review previous day's concepts
⏰ 60 min  — Learn new theory (docs, videos)
⏰ 60 min  — Hands-on practice / project work
⏰ 30 min  — Document what you learned (GitHub / notes)
```

---

## 🧠 Key Mindsets for Success

1. **Build projects** — employers want proof, not just certificates
2. **Break things on purpose** — then fix them. That's how you learn.
3. **Document everything** — maintain a GitHub portfolio
4. **Contribute to open-source** — great for resume
5. **Join communities** — Reddit r/devops, DevOps Discord servers
6. **Never skip Linux** — go back if you're weak here
7. **Automate everything** — if you do it twice, script it

---

## 🎯 Job-Ready Skills Checklist

- [ ] Comfortable in Linux terminal
- [ ] Can write Bash and Python scripts
- [ ] Can Dockerize any application
- [ ] Built a CI/CD pipeline from scratch
- [ ] Deployed apps on AWS
- [ ] Written Terraform for cloud infra
- [ ] Configured servers with Ansible
- [ ] Deployed on Kubernetes
- [ ] Set up Prometheus + Grafana monitoring
- [ ] Implemented secrets management
- [ ] GitHub portfolio with 5+ DevOps projects
- [ ] At least 2 certifications

---

*Created: May 2026 | DevOps Mastery Roadmap*
