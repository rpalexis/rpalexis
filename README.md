### Rulx Philome Alexis

DevSecOps — Infrastructure as Code (Terraform/OpenTofu), Kubernetes (Talos Linux), software supply-chain security (sigstore). Security enthusiast, currently sharpening the offensive side through CTFs.

I contribute to open source. Latest work: a missing SDN BGP-controller resource for [bpg/terraform-provider-proxmox](https://github.com/bpg/terraform-provider-proxmox) — the widely used Terraform provider for Proxmox VE — and an initContainers fix that shipped in [grafana/helm-charts](https://github.com/grafana/helm-charts).

I also own and operate **[AS214587](https://rulx.dev/blog/my-ipv6-only-asn/)**, a personal IPv6-only network (RIPE ASN, announced prefixes, BGP transit) — I write about it and the rest of the homelab on [rulx.dev](https://rulx.dev).

## Open source contributions

| Project | PR | Status | Scope |
|---|---|---|---|
| [bpg/terraform-provider-proxmox](https://github.com/bpg/terraform-provider-proxmox) | [#3183](https://github.com/bpg/terraform-provider-proxmox/pull/3183) | merged | feat(sdn): new resource `proxmox_sdn_controller_bgp` (17 files, +1526/-7) |
| [bpg/terraform-provider-proxmox](https://github.com/bpg/terraform-provider-proxmox) | [#3182](https://github.com/bpg/terraform-provider-proxmox/pull/3182) | merged | docs: unattended install option for the Proxmox test VM |
| [grafana/helm-charts](https://github.com/grafana/helm-charts) | [#3631](https://github.com/grafana/helm-charts/pull/3631) | merged | tempo-distributed: adding missing init-containers in components |
| [tstromberg/sigstore-the-local-way](https://github.com/tstromberg/sigstore-the-local-way) | [#20](https://github.com/tstromberg/sigstore-the-local-way/pull/20) | merged | documentation: sigstore installation walkthrough |
| [ecelestin/ecelestin-Moncash-sdk-php](https://github.com/ecelestin/ecelestin-Moncash-sdk-php) | 7 commits | co-author | PHP SDK for MonCash (Digicel Haiti mobile payments) — initial SDK structure, refactor, sandbox endpoints fix (2019) |

Earlier days: 30+ PRs and issues on [GFDRR/sms-lapli](https://github.com/GFDRR/sms-lapli) and [EMSEsih/attendances](https://github.com/EMSEsih/attendances) — open-source civic tech projects (SMS rain-alert platform, Django apps).

## CTF — Red Team & DFIR

[Huntress CTF 2025](https://github.com/rpalexis/huntress-ctf-2025) — day-by-day progress and writeups: `telestealer`, `netsupport`, `trapped` and more, focused on malware analysis and forensics.

Also co-authoring the shared writeups journal [jdel/huntress-ctf-2025](https://github.com/jdel/huntress-ctf-2025) — `snooze`, `arika`, `spaguetti`, `day22` and others.

## What I'm currently building

- [terraform-provider-proxmox](https://github.com/rpalexis/terraform-provider-proxmox) — working fork for active upstream contributions (`feat/add-missing-sdn-controler-bgp`)
- [demo-talos-deployment](https://github.com/rpalexis/demo-talos-deployment) — modular, declarative Talos Linux cluster deployment (patch-based config engine, GitOps-style environments)
- [sigstore-the-local-way](https://github.com/rpalexis/sigstore-the-local-way) — hands-on sigstore/cosign walkthrough for local software signing
- [observability](https://github.com/rpalexis/observability) — Grafana / Loki / kube-prometheus-stack homelab lab, incl. Chaos Mesh experiments

## Stack

![Terraform](https://img.shields.io/badge/Terraform%2FOpenTofu-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

[![Website](https://img.shields.io/badge/rulx.dev-080b11?style=flat-square&logo=astro&logoColor=F76E7C)](https://rulx.dev)
[![Notes](https://img.shields.io/badge/notes%20RSS-FFA500?style=flat-square&logo=rss&logoColor=white)](https://rulx.dev/rss.xml)
[![AS214587](https://img.shields.io/badge/AS214587-IPv6%20only-0A8080?style=flat-square)](https://rulx.dev/blog/my-ipv6-only-asn/)
