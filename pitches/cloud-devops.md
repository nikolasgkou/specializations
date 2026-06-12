# 💽 Cloud DevOps
**Specialization branch · Zone01 Athens · 6 months**

> This branch explores the field of DevOps through network deployment, server configuration, system and web security, and cloud computing.

## The branch in numbers
| | |
|---|---|
| Format | intensive piscine (~3–4 weeks) + 7 projects |
| Projects | 7 (3 solo · 4 team) |
| Core stack | Docker, Kubernetes (K3s), AWS, Terraform, Ansible |

## What you'll build
- A simulated, troubleshot multi-device network in Cisco Packet Tracer, applying networking devices, services, protocols and the OSI model.
- A hardened Ubuntu Server VM with custom partitioning, static IP, firewall, SSH, MySQL, WordPress and automated cron backups.
- A movie-streaming Flask, PostgreSQL and RabbitMQ microservices platform, with an Inventory API, a Billing API and an API gateway, each provisioned in its own Vagrant/VirtualBox VM and run under PM2.
- That same shared Inventory, Billing and API-gateway app re-platformed across stages: deployed on a two-node K3s cluster, then on AWS with Terraform, plus a GitLab CI/CD pipeline that scans images and ships to staging and production.

## The journey
| # | Project | What you build | Solo/Team |
|---|---|---|---|
| 1 | Piscine Scripting | Command line, Unix, shell scripting and Python sysadmin foundations | — |
| 2 | deep-in-net | Simulate and troubleshoot networks in Cisco Packet Tracer | Solo |
| 3 | deep-in-system | Configure and secure a production-like Ubuntu server with backups | Solo |
| 4 | crud-master | Build microservices platform with API gateway and RabbitMQ | Team (2) |
| 5 | play-with-containers | Containerize microservices with Docker Compose, networks and volumes | Solo |
| 6 | orchestrator | Deploy microservices on a two-node K3s Kubernetes cluster | Team (2) |
| 7 | cloud-design | Design and deploy scalable microservices on AWS with Terraform | Team (2) |
| 8 | code-keeper | Build CI/CD pipeline with GitLab, Terraform and Ansible | Team (2) |

## You'll learn
- Network configuration, protocols, the OSI model and Linux networking
- Server hardening with firewalls, SSH, users and partitioning
- Microservices design with Flask, PostgreSQL, RabbitMQ and an API gateway
- Containerization with Docker, Compose, networks and persistent volumes
- Kubernetes orchestration on a multi-node K3s cluster with StatefulSets
- Cloud deployment and automation with AWS, Terraform and Ansible

## It's a great fit if…
- You like infrastructure, servers and the command line more than building user interfaces.
- You enjoy automating deployments and reasoning about networking, scaling, monitoring and reliability.
- You are comfortable with cloud platforms, infrastructure as code and gluing many services together.
- You want to carry one microservices app across each stage, re-platforming it from VMs to the cloud.

---

## References & further reading
New to some of these tools? These are the official docs and starting points for the technologies used in this branch.

- **Docker** — containers and images. [docs.docker.com](https://docs.docker.com/)
- **Kubernetes** — container orchestration. [kubernetes.io/docs](https://kubernetes.io/docs/home/)
- **K3s** — lightweight Kubernetes. [docs.k3s.io](https://docs.k3s.io/)
- **Terraform** — infrastructure as code. [developer.hashicorp.com/terraform](https://developer.hashicorp.com/terraform/docs)
- **Ansible** — configuration management. [docs.ansible.com](https://docs.ansible.com/)
- **AWS** — the cloud platform. [docs.aws.amazon.com](https://docs.aws.amazon.com/)
- **Cisco Packet Tracer** — network simulation. [netacad.com/cisco-packet-tracer](https://www.netacad.com/cisco-packet-tracer)
- **Flask** — Python web microframework. [flask.palletsprojects.com](https://flask.palletsprojects.com/)
- **PostgreSQL** — relational database. [postgresql.org/docs](https://www.postgresql.org/docs/)
- **RabbitMQ** — message broker. [rabbitmq.com/docs](https://www.rabbitmq.com/docs)
- **GitLab CI/CD** — pipelines and deployment. [docs.gitlab.com/ci](https://docs.gitlab.com/ci/)
- **Vagrant** — scripted, reproducible virtual machines. [developer.hashicorp.com/vagrant](https://developer.hashicorp.com/vagrant/docs)
- **VirtualBox** — the VM provider Vagrant drives. [virtualbox.org/manual](https://www.virtualbox.org/manual/)
- **PM2** — process manager for the Node/Python services. [pm2.keymetrics.io](https://pm2.keymetrics.io/docs/usage/quick-start/)
- **Ubuntu Server** — the Linux server you install, partition and harden. [ubuntu.com/server](https://ubuntu.com/server/docs)
- **MySQL** — relational database backing the WordPress site. [dev.mysql.com/doc](https://dev.mysql.com/doc/)
- **WordPress** — the web application deployed on the hardened server. [wordpress.org/documentation](https://wordpress.org/documentation/)
