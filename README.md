# Azure M1 — AKS three-tier app (Postgres + ingress + cert-manager + Helm)

A real three-tier application (React frontend, Node API, PostgreSQL) on **Azure Kubernetes Service**: **ingress-nginx** for HTTP routing, **cert-manager** + Let's Encrypt for free TLS, **Helm** for app packaging, and **Azure Database for PostgreSQL Flexible Server** (private, VNet-integrated). Infrastructure is **Terraform**; images come from **ACR** pulled via managed identity; secrets come from **Key Vault** via the CSI driver.

> Work in progress. Built as a hands-on learning project. The largest junior→mid jump in the ladder.

## Status

| Session | Scope | Status |
|---|---|---|
| 1 | Terraform: VNet + AKS + ACR + Log Analytics | in progress |
| 2 | Postgres Flexible Server (private, VNet-integrated) + Key Vault | |
| 3 | App images (frontend/api) built to ACR | |
| 4 | ingress-nginx + cert-manager + TLS | |
| 5 | Helm chart for the 3 tiers + CSI secrets | |
| 6 | HPA + verification + teardown | |

## License

MIT — see [LICENSE](LICENSE).
