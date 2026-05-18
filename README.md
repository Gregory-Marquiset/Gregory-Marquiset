Après une carrière dans l'animation socio-culturelle en tant qu'animateur puis directeur, je me suis reconverti dans le développement logiciel et je me spécialise aujourd'hui en **Site Reliability Engineering**.

Fort d'une solide expérience en algorithmique **C/C++** et systèmes **Linux**, je conçois et opère des systèmes **fiables**, **mesurables** et **maintenables sous contrainte réelle**. Mes intérêts :

- **Observabilité** — métriques, logs, alerting (Prometheus, Grafana, ELK)
- **Automatisation & IaC** — Terraform, Ansible, scripts d'opérations
- **CI/CD & GitOps** — GitHub Actions, Argo CD
- **Sécurité opérationnelle** — HashiCorp Vault, WAF, hardening
- **Orchestration & conteneurisation** — Docker, Kubernetes (K3s / K3d)
- **Fiabilité** — SLI/SLO, error budgets, disaster recovery, health checks

Curieux et polyvalent, j'aime optimiser les workflows, résoudre des problématiques techniques complexes, et partager mes connaissances au sein des équipes.

## 📦 Ce que tu trouveras ici

- Des dépôts liés à mes projets de l'**école 42**
- Mes exercices / avancées sur **roadmap.sh** (DevOps)
- Quelques **projets personnels** autour de l'outillage, l'automatisation et l'apprentissage

---

<h2 align="center">Projets école 42</h2>

<h3 align="center">📅 Prochain</h3>

- **Cloud-1** — déploiement d'une infrastructure **AWS** reproductible : provisioning via **Terraform**, configuration via **Ansible**, automatisation de bout en bout et durcissement sécurité (IAM, VPC, groupes de sécurité).

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

<h3 align="center">🛰️ Récents</h3>

- [Inception of Things](https://github.com/Gregory-Marquiset/jjg_inception_of_things)
  - Objectif : mettre en place un environnement Kubernetes minimaliste avec **K3s** et **K3d**, déploiement d'applications conteneurisées, gestion d'Ingress, et workflow GitOps via **Argo CD**.
  - Responsabilités : conception de l'architecture, automatisation de l'installation (scripts), configuration Kubernetes (namespaces, deployments, services, ingress), mise en place d'Argo CD et gestion des versions applicatives.
  - Notions : virtualisation avec Vagrant, orchestration Kubernetes (K3s/K3d), conteneurisation Docker, Ingress Controller, GitOps, CI/CD, déploiement automatisé via repository GitHub, scripting Bash.

![Vagrant](https://img.shields.io/badge/Vagrant-1868F2?style=for-the-badge&logo=vagrant&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?style=for-the-badge&logo=k3s&logoColor=black)
![K3d](https://img.shields.io/badge/K3d-0A0A0A?style=for-the-badge&logo=docker&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-000000?style=for-the-badge&logo=git&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)

- [Transcendence](https://github.com/Gregory-Marquiset/llmcg_transcendence)
  - Objectif : réaliser à 5 une application web complète (frontend + backend + base de données), déployée via conteneurisation et lançable en une seule commande, avec support multi-utilisateurs et interactions en temps réel.
  - Responsabilités : Project Owner / DevOps — observabilité, sécurité, CI/CD, disaster recovery.
  - Notions : CI/CD via **GitHub Actions** (workflows, rulesets, tests unitaires en Bash), métriques **Prometheus** + **Grafana**, logs **ELK** (Elasticsearch, Logstash, Kibana), secrets management via **HashiCorp Vault**, durcissement **WAF** (ModSecurity), **watchdog Bash** (health checks HTTP, détection de pannes, auto-healing), procédure de **Disaster Recovery** testée, documentation et backlogs.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=for-the-badge&logo=logstash&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-0A0A0A?style=for-the-badge&logo=githubactions&logoColor=white)

- [Inception](https://github.com/Gregory-Marquiset/gm_inception)
  - Objectif : monter un site WordPress via Nginx et MariaDB en architecture microservices, avec services annexes comme Adminer et Portainer.
  - Notions : Docker, Docker Compose, et tous les systèmes associés.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- [Webserv](https://github.com/Gregory-Marquiset/mcg_webserv)
  - Objectif : projet en trinôme pour recréer un serveur web en C++.
  - Responsabilités : implémentation des tests unitaires et CGI.
  - Notions : protocole HTTP, communication client-serveur, CGI.

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

---

<h2 align="center">Projets roadmap.sh</h2>

<h3 align="center">🛰️ Récents</h3>

- [Server performance stats](https://github.com/Gregory-Marquiset/roadmap_sps)
  - Objectif : script **Bash** portable (exécutable sur n'importe quel serveur **Linux**) pour afficher rapidement les statistiques essentielles de performance et aider au diagnostic.
  - Notions : monitoring basique Linux, analyse CPU/RAM/disque, inspection des processus (top CPU / top mémoire), debugging et compréhension des performances serveur.

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

<h2 align="center">Projets personnels</h2>

<h3 align="center">🚀 En cours</h3>

- [DevSecOps Platform](https://github.com/Gregory-Marquiset/marquis_devsecops_platform)
  - Objectif : application web sécurisée (frontend + backend + base de données) en architecture microservices, déployée via Docker et orientée DevSecOps, avec authentification OAuth 2.0, chat en temps réel via WebSockets et observabilité complète.
  - Responsabilités : Product Owner / DevSecOps / Développeur Full-Stack.
  - Notions : architecture microservices (NestJS, Next.js, PostgreSQL + Prisma), sécurisation applicative (ModSecurity/WAF, HashiCorp Vault, JWT), CI/CD via GitHub Actions (lint, security scans Trivy/Snyk, tests unitaires et Bash), métriques personnalisées (Prometheus + Grafana), logs ELK (Elasticsearch, Logstash, Kibana), authentification OAuth 2.0 (Google), chat temps réel (Socket.io) et documentation technique complète.

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=for-the-badge&logo=logstash&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-0A0A0A?style=for-the-badge&logo=githubactions&logoColor=white)

<h3 align="center">🛰️ Récents</h3>

- [strudel_prod](https://github.com/Gregory-Marquiset/marquis_strudel_prod)
  - Objectif : environnement de **live coding musical** reproductible et portable basé sur **Strudel**, permettant de composer et performer directement depuis le navigateur, sans dépendre d'une installation locale de Node, pnpm ou tooling.
  - Notions : live coding (Strudel / Tidal-like patterns), application web statique, conteneurisation **Docker**, build multi-stage (Node → nginx), déploiement production local, reproductibilité des environnements, automatisation via Makefile.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Strudel](https://img.shields.io/badge/Strudel-ff4f81?style=for-the-badge)

---
