# ClearCloud

Open tooling for the ClearCloud products, made in France. Website: [clearcloud.fr](https://clearcloud.fr)

## CheckOps — CRA & NIS2 vulnerability compliance

Turn the SBOMs and scanner results you already produce into CRA and NIS2 reporting. [checkops.eu](https://checkops.eu) · [Documentation](https://docs.checkops.eu)

| Repository | What it is |
| --- | --- |
| [checkops-cli](https://github.com/clearcloud-fr/checkops-cli) | CLI: send SBOMs and scan results, cloud configuration audit with your own read-only keys |
| [checkops-helm-charts](https://github.com/clearcloud-fr/checkops-helm-charts) | Helm charts (Kubernetes agent) — `charts.checkops.eu` |
| [checkops-integrations](https://github.com/clearcloud-fr/checkops-integrations) | Terraform/OpenTofu module for Scaleway, AWS ECR template, CI examples |

## OKStatus — uptime monitoring and status pages

[okstatus.eu](https://okstatus.eu)

| Repository | What it is |
| --- | --- |
| [okstatus-agent](https://github.com/clearcloud-fr/okstatus-agent) | Private monitoring agent — runs in your own network, outbound HTTPS only |
| [okstatus-helm-charts](https://github.com/clearcloud-fr/okstatus-helm-charts) | Helm charts — `charts.okstatus.eu` |
| [okstatus-grafana](https://github.com/clearcloud-fr/okstatus-grafana) | Grafana dashboard and Prometheus alerting rules |
| [terraform-provider-okstatus](https://github.com/clearcloud-fr/terraform-provider-okstatus) | Terraform provider |

Tip: filter the repository list by product with `props.project:checkops` or `props.project:okstatus`.
