# Awesome-Serverless-Application-Registry

## Top Serverless Application Registry Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Application Catalogs, Container Registries & Self-Hosted Artifact Hubs*  

**Last updated: October 2026**



This repository tracks notable **commercial application registries** and **open-source projects** that package, discover, and distribute serverless applications, containers, and Helm charts. These tools serve as the distribution layer for cloud-native software — from public marketplaces to self-hosted registries.



**Examples** include AWS Serverless Application Repository, GitHub Container Registry, Artifact Hub, Docker Hub, Bitnami Application Catalog, Red Hat Ecosystem Catalog, GitLab Package Registry, Helm Hub, Cloudsmith, and Quay.io (the category leaders).



**Open-source emphasis**: Application registries are a strong open-source domain. **Harbor** leads as the CNCF container registry with security scanning. **Artifact Hub** aggregates Helm charts and Kubernetes packages. **Distribution** (Docker Registry) is the reference implementation. **ChartMuseum**, **zot**, and **ORAS** provide specialized registries. **Nexus**, **Artipie**, and **Pulp** deliver universal artifact management. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Serverless Application Repository](https://aws.amazon.com/serverless/serverlessrepo/)**  

  **AWS's public marketplace for serverless applications** — discover, deploy, and publish SAM applications . **One-click deployment** to AWS accounts . **Best for AWS serverless applications** .



- **[GitHub Container Registry](https://github.com/features/packages)**  

  **GitHub's container and package registry** — integrated with GitHub Actions and repositories . **Free for public packages** . **Best for GitHub-centric workflows** .



- **[Docker Hub](https://hub.docker.com/)**  

  **The world's largest container registry** — 100,000+ public images . **Free tier with rate limits**; paid for private repos . **The reference for container distribution** .



- **[Artifact Hub](https://artifacthub.io/)**  

  **CNCF's hub for cloud-native packages** — Helm charts, Operators, and policies . **The central discovery point for Kubernetes artifacts** . **Best for finding Helm charts** .



- **[Bitnami Application Catalog](https://bitnami.com/stacks)**  

  **The most comprehensive application catalog** — 200+ ready-to-deploy applications . **Best for quick application deployment** .



- **[Red Hat Ecosystem Catalog](https://catalog.redhat.com/)**  

  **Red Hat's certified container and operator catalog** — enterprise-grade with support . **Best for OpenShift users** .



- **[GitLab Package Registry](https://docs.gitlab.com/ee/user/packages/)**  

  **GitLab's package and container registry** — integrated with CI/CD . **Best for GitLab users** .



- **[Cloudsmith](https://cloudsmith.com/)**  

  **Cloud-native artifact management** — 25+ package formats with global CDN . **Free tier available** . **Best for multi-format artifact hosting** .



- **[Quay.io](https://quay.io/)**  

  **Red Hat's container registry** — security scanning and geo-replication . **Best for enterprise container registries** .



## Open-Source GitHub Projects



### Container Registries



- **[Harbor](https://github.com/goharbor/harbor)**  

  **The leading open-source container registry**, Apache-2.0 licensed with **25,000+ GitHub stars** . **CNCF graduated project** — vulnerability scanning, RBAC, replication, and image signing . **The de facto open-source Docker Hub alternative** . **Best for enterprise container registries** .



- **[Distribution (Docker Registry)](https://github.com/distribution/distribution)**  

  **The reference implementation of the Docker Registry**, Apache-2.0 licensed with **8,000+ GitHub stars** . **The foundation for Docker Hub and most registries** . **Best for self-hosted Docker registry** .



- **[zot](https://github.com/project-zot/zot)**  

  **OCI-native container registry**, Apache-2.0 licensed . **Minimal, scalable, and production-ready** . **Supports OCI artifacts, image signing, and vulnerability scanning** . **Best for lightweight OCI registry** .



- **[Quay](https://github.com/quay/quay)**  

  **Red Hat's container registry**, Apache-2.0 licensed . **Security scanning and geo-replication** . **Best for enterprise container registries** .



- **[Portus](https://github.com/SUSE/Portus)**  

  **Authorization and authentication for Docker Registry** (archived) . **Historically significant** . **Best for legacy Docker Registry management** .



### Helm & Kubernetes Application Registries



- **[Artifact Hub](https://github.com/artifacthub/hub)**  

  **CNCF's hub for cloud-native packages**, Apache-2.0 licensed with **2,000+ GitHub stars** . **Helm charts, Operators, and policies** . **The central discovery point for Kubernetes artifacts** . **Best for finding Helm charts** .



- **[ChartMuseum](https://github.com/helm/chartmuseum)**  

  **Helm chart repository server**, Apache-2.0 licensed with **3,000+ GitHub stars** . **Self-hosted Helm chart repository** . **Best for private Helm charts** .



- **[Harbor (Helm support)](https://github.com/goharbor/harbor)** — Already listed. **Supports Helm charts as OCI artifacts** .



- **[Kubeapps](https://github.com/vmware-tanzu/kubeapps)**  

  **Kubernetes application dashboard**, Apache-2.0 licensed . **Deploy and manage Helm charts and Operators** . **Best for Kubernetes application management** .



### Universal Artifact Repositories



- **[Nexus Repository OSS](https://github.com/sonatype/nexus-public)**  

  **The most widely deployed open-source artifact repository**, EPL-1.0 licensed . **Supports Maven, npm, NuGet, PyPI, Docker, RubyGems, Go, and more** . **Best for enterprises needing a proven artifact repository** .



- **[Artipie](https://github.com/artipie/artipie)**  

  **Open-source, self-hosted universal artifact registry**, MIT licensed . **Supports Maven, npm, PyPI, Docker, NuGet, RubyGems, Go, Helm, Debian, RPM, and more** — one binary for all package types . **Best for organizations wanting a single self-hosted registry for all languages** .



- **[Pulp](https://github.com/pulp/pulp)**  

  **Open-source repository management platform**, GPL-2.0 licensed . **Supports RPM, Debian, Python, Ansible, and container content** . **Best for Linux distribution package management** .



- **[JFrog Artifactory OSS](https://github.com/jfrog/artifactory-oss)**  

  **Open-source version of JFrog Artifactory** (limited to OSS languages), Apache-2.0 licensed . **Supports Maven, Gradle, npm, PyPI, NuGet, Docker, and more** . **Best for teams wanting a lighter Artifactory experience** .



### OCI & Specialized Registries



- **[ORAS](https://github.com/oras-project/oras)**  

  **OCI Registry as Storage**, Apache-2.0 licensed with **1,500+ GitHub stars** . **Push arbitrary artifacts to OCI registries** . **The standard for non-container artifacts in OCI registries** . **Best for storing arbitrary artifacts** .



- **[ORAS CLI](https://github.com/oras-project/oras)** — Already listed. **CLI for OCI artifacts** .



- **[Cosign](https://github.com/sigstore/cosign)**  

  **Container signing and verification**, Apache-2.0 licensed with **4,000+ GitHub stars** . **Sign and verify container images and artifacts** . **Best for supply chain security** .



- **[Syft](https://github.com/anchore/syft)**  

  **SBOM generation for containers and filesystems**, Apache-2.0 licensed . **Generates Software Bill of Materials** . **Best for supply chain visibility** .



- **[Grype](https://github.com/anchore/grype)**  

  **Vulnerability scanning for containers**, Apache-2.0 licensed . **Scans images and filesystems for CVEs** . **Best for container security** .



### Additional Strong Open-Source Options



- **GitLab Container Registry** — Integrated with GitLab .

- **Gitea Package Registry** — Integrated with Gitea .

- **Forgejo Package Registry** — Integrated with Forgejo .

- **Verdaccio** — Private npm registry .

- **Devpi** — Private PyPI .

- **BaGet** — Private NuGet .

- **Docker Registry UI** — Web UI for Docker Registry .

- **Portainer** — Container management with registry features .

- **Kraken** — Uber's P2P Docker registry .

- **Dragonfly** — P2P file distribution for registries .



**Frameworks for building custom application registry solutions**: Combine **Harbor** for enterprise container registry with security scanning . Use **Artifact Hub** for discovering Helm charts and Kubernetes packages . Deploy **ChartMuseum** for private Helm repositories . Choose **zot** or **Distribution** for lightweight OCI registries . Integrate **Nexus** or **Artipie** for universal artifact management . Use **ORAS** for storing arbitrary artifacts in OCI registries . Integrate **Cosign**, **Syft**, and **Grype** for supply chain security . Note that true commercial application registries with managed infrastructure, global CDN, and vendor-supported SLAs (Docker Hub, GitHub Container Registry, AWS Serverless Application Repository) remain primarily commercial territory; open-source stacks provide strong registry, discovery, and security foundations that require integration for complete application distribution.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Application registries distribute software that may contain malicious code. **Supply chain attacks are a real threat** — use signed artifacts, scan for vulnerabilities, and generate SBOMs .

- **Public registries are not curated for security** — Docker Hub, npm, and PyPI have all experienced malicious package incidents. Use private registries with security scanning for production .

- **Self-hosted registries require infrastructure** — storage, backup, high availability, and security are your responsibility. Harbor and Nexus are mature but require operational expertise .

- **License considerations**: Harbor uses Apache-2.0, Nexus uses EPL-1.0, Pulp uses GPL-2.0, and zot uses Apache-2.0. Verify licensing against your use case before committing .

- The open-source ecosystem provides strong registry, discovery, and security foundations, but **managed infrastructure, global CDN, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for platform engineers, DevOps teams, and organizations seeking application registry sovereignty.**  

Let's make serverless application registries more open, transparent, and secure.
