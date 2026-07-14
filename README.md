# Rafael Friederick

Backend engineer @ A3S Tecnologia · based in Salvador, Brazil.

Currently building **unnamed-lab** — a self-hosted Kubernetes platform on bare-metal Proxmox.
Go services, ArgoCD GitOps, observability stack (Prometheus / Grafana / Loki / Tempo),
CloudNativePG, Kong.

## Open source

Contributor to CNCF projects — merged upstream:

- **[kubernetes/minikube#22960](https://github.com/kubernetes/minikube/pull/22960)** — only warn against the
  virtualbox driver when the user explicitly asks for it, instead of when minikube auto-selects it
- **[kubernetes/minikube#22992](https://github.com/kubernetes/minikube/pull/22992)** — update cri-dockerd
  to v0.4.3 in the none-driver integration script
- **[argoproj/argo-cd#27769](https://github.com/argoproj/argo-cd/pull/27769)** — include resource context
  in failed normalization logs, so operators can tell *which* resource failed

In review: **[kubernetes/minikube#23037](https://github.com/kubernetes/minikube/pull/23037)** — move
per-machine sockets out of `MINIKUBE_HOME` so AF_UNIX paths fit in `sockaddr_un.sun_path`.

## Stack I operate in production

- **Go 1.25+** · Gin · pgx (no ORM) · hexagonal architecture
- **TypeScript / Node** · NestJS · Next.js · TypeORM · CQRS
- **Kubernetes (k3s)** · ArgoCD · cert-manager · MetalLB · Harbor
- **PostgreSQL 18** · Redis · RabbitMQ
- **Observability** · OpenTelemetry · Prometheus · Grafana · Loki · Tempo
- **IaC** · Terraform · Ansible

## Writing

Bilingual tutorials on distributed systems & observability — tracing (PT for now, EN coming).

## Reach out

[LinkedIn](https://linkedin.com/in/rafaelmfriederick)
