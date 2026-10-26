# Fedor Batonogov

Senior DevOps Engineer & Team Lead building bare-metal Kubernetes platforms and
infrastructure tooling. Moscow 🇷🇺

From bare-metal provisioning with Proxmox and Talos to platform architecture and delivery.
I lead a team of three across planning, mentoring, architecture, and processes.

[Projects](#projects) · [Upstream contributions](#upstream-contributions) · [Contact](#contact)

## Projects

- **[Pine](https://github.com/batonogov/pine)** — a native macOS workspace for
  developers running CLI coding agents across multiple projects: a cross-project
  Agent Inbox, editor and terminal panes, LSP, and Git context. Zero Electron.
  [Releases](https://github.com/batonogov/pine/releases) · `Swift` `SwiftUI` `AppKit`

- **Terraform providers** — manage [3x-ui](https://github.com/batonogov/terraform-provider-threexui)
  inbounds and clients, [Remnawave](https://github.com/batonogov/terraform-provider-remnawave)
  users and nodes, and [Synology DSM](https://github.com/batonogov/terraform-provider-synology-dsm)
  users, shares, and certificates as code. `Go` `Terraform Plugin Framework`

- **[Xray Health Exporter](https://github.com/batonogov/xray-health-exporter)** —
  probes Xray-core tunnels with real traffic and exposes per-tunnel availability
  and TTFB metrics to Prometheus. `Go` `Prometheus`

## Upstream contributions

Selected merged changes in projects I use:

- **Cozystack** — [custom CA support for a self-hosted Talos Image Factory in CDI](https://github.com/cozystack/cozystack/pull/3797).
- **Terraform Provider Harbor** — [reliable LDAP group membership lifecycle](https://github.com/goharbor/terraform-provider-harbor/pull/592),
  including drift detection, import, update, and destroy.
- **SeaweedFS** — [resource-scoped authorization for delegated service-account creation](https://github.com/seaweedfs/seaweedfs/pull/11736).
- **NetBird Helm chart** — [correct OAuth callback URLs and configuration rollouts on upgrades](https://github.com/helmforgedev/charts/pull/1533).
- **SwiftTerm** — [independent hyperlink underline colors across rendering paths](https://github.com/migueldeicaza/SwiftTerm/pull/772).

## A bit of my story

I started in tech support back in 2008, then spent years working with AV and
conference systems — Crestron, Bosch, simultaneous interpretation. The turning
point came when a colleague and I built our own meeting-room control system in
Python and deployed it with Docker Swarm — a home-grown Crestron alternative.
After that I switched jobs and became a full-time DevOps engineer.

Off duty, you'll probably find me on a PlayStation 5 or a Nintendo Switch.

## How I work

Coding agents are part of my daily loop, from scoping and implementation to tests and review.
Architecture, trade-offs, and production responsibility stay human-owned.

## Stack

Terraform · OpenTofu · Kubernetes · Talos · Argo CD · Ansible · Go · Swift ·
Prometheus · Grafana · Vault · Proxmox · Linux

## Contact

For infrastructure conversations, open-source collaboration, or Pine feedback:

- Telegram: [@fedor_batonogov](https://t.me/fedor_batonogov)
- Email: [fedor@batonogov.ru](mailto:fedor@batonogov.ru)
