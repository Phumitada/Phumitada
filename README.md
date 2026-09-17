# Hi, I'm Phumitada
Computer Engineering Student @ Kasetsart University
Full-stack Developer · DevOps Engineer

---

## Tech Stack

**Development**:

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Infrastructure & Platform Engineering**:

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![KubeBuilder](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![BuildKit](https://img.shields.io/badge/BuildKit-1D63ED?style=flat&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat&logo=digitalocean&logoColor=white)

---

## Projects

### Internal PaaS v2 — Self-Hosted Developer Platform
> Custom Kubernetes operator and GitOps pipeline powering a self-service PaaS — dogfooded to host itself

- Custom Kubernetes Operator (Go, kubebuilder/controller-runtime) — `Application` and `Database` CRDs reconciling Deployment, Service, Ingress/TLS, StatefulSet, PVC, and Secret resources
- End-to-end GitOps pipeline (Node.js, BullMQ) — generates Kubernetes manifests from application state, commits to a dedicated Git repo, and auto-provisions ArgoCD `Application` resources via an `ApplicationSet` git-directory generator
- Migrated the build pipeline from Docker-socket-dependent builds to a rootless, mTLS-secured BuildKit deployment, removing a root-equivalent container-escape risk
- Self-hosted the platform on its own infrastructure — proven end-to-end from GitHub webhook through build, registry push, GitOps sync, and reconciliation to a live production domain
- Kubernetes · Go · kubebuilder · ArgoCD · BuildKit · Docker · PostgreSQL · Redis · BullMQ · Prisma · Express · React · TypeScript

**[Live Platform](https://idp.phumitada.com)** · **[KubeBuilder-Controller](https://github.com/Phumitada/IDP-Controller)** · **[Developer-Portal](https://github.com/Phumitada/Internal-PaaS)** 

---

### Hotel Booking System
> Full-stack Agoda-inspired booking platform — containerized and deployed on production VPS

- REST API · JWT Auth · Refresh Token Rotation · Role-based Access
- Omise Payment Gateway (Credit Card + PromptPay QR)
- Docker · nginx · SSL · CI/CD with GitHub Actions · Grafana Monitoring
- PostgreSQL · Prisma · Redis · Express · React · TypeScript

**[Live Demo](https://hotel.phumitada.com)** · `john@example.com / password123` · **[Repository](https://github.com/Phumitada/Hotel-Booking-System-DevOps)**

---

### Disease Surveillance System
> Real-time heatmap dashboard tracking disease reports across 77 provinces of Thailand

- Interactive Thailand heatmap with risk-level color coding and filtering
- Optimized from N+1 (200k+ queries) to 3 queries per request via in-memory aggregation
- Docker · nginx · SSL · CI/CD with GitHub Actions · Grafana Monitoring
- PostgreSQL · Prisma · JWT Auth · Express · React · TypeScript

**[Live Demo](https://diseases-map.phumitada.com)** · `admin_siriraj / admin123` · **[Repository](https://github.com/Phumitada/Diseases-Map-DevOps)**

---

## Contact

phumitada@gmail.com · 081-131-5967 · Bangkok, Thailand
