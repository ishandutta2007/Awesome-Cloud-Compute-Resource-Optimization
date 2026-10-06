# Awesome-Cloud-Compute-Resource-Optimization ⚙️ 📉

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Cloud Compute Resource Optimization Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Cloud Compute & Resource Optimization Ecosystem

**Curated List of Commercial Rightsizing Platforms & Open-Source Kubernetes Autoscaling Tools**  
*Focused on VM Rightsizing, Kubernetes Resource Optimization, Spot Instance Automation, Predictive Autoscaling & Self-Hosted Capacity Management*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary

Welcome to the ultimate curated directory of **cloud compute optimization platforms**, **open-source Kubernetes rightsizing tools**, and **autonomous capacity management frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *AWS Compute Optimizer*, *Cast AI*, and *Turbonomic*), or self-hostable open-source alternatives (like *Karpenter*, *Infracost*, *KEDA*, and *VPA*), this list covers category leaders, bin-packing engines, and privacy-respecting resource optimization.

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

> [!NOTE]  
> **Market Size & Market Structure**: The global Cloud FinOps and Compute Resource Optimization market size is estimated at **$12.5 Billion** and is projected to grow to **$28 Billion by 2030** (CAGR ~17.5%). The sector is **moderately fragmented**, featuring native hyperscaler tools alongside fast-growing specialized Kubernetes autoscaling automation vendors.

The cloud compute optimization market spans **free native cloud tools** (AWS Compute Optimizer) that provide baseline recommendations at no cost, and **specialized platforms** that charge per-instance, per-vCPU-hour, or as a percentage of savings realized.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap (Size) | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/)** ☁️ | Amazon | **~$2.0 Trillion** | **$0.0003360215/resource/hour** (Enhanced metrics) | **Free forever** for 14-day standard recommendations | **AWS-native rightsizing** — ML-based recommendations for EC2, Auto Scaling groups, EBS, Lambda, and RDS. Identifies Graviton migration opportunities. |
| **[IBM Turbonomic](https://www.ibm.com/products/turbonomic)** ⚙️ | IBM | **~$200 Billion** | **$18.75/instance/month** (Cloud tier) | **30-day free trial** with full feature access | **Application resource management (ARM)** — Public cloud optimization, Kubernetes optimization (EKS, AKS, GKE), and database tuning. |
| **[Intel Granulate](https://granulate.io/)** ⚡ | Intel (Acquired) | **~$100 Billion** | **$0.003/core/hour** (cloud) | **14-day free trial** with telemetry analysis | **Autonomous workload optimization** — Continuous ML-driven CPU and memory tuning with no code changes required. |
| **[Spot by NetApp](https://spot.io/)** 🟢 | NetApp / Flexera | **~$20 Billion** | **$1.415/100 vCPU hours** | **Free tier: up to 20 VMs** managed continuously | **Cloud automation and optimization** — Ocean for Kubernetes node management, Elastigroup for VM Spot adoption, and Eco for commitment management. |
| **[Densify](https://www.densify.com/)** 📊 | Densify | **Private (~$500M)** | **$5,000/month** (up to 2,000 instances) | **14-day free trial** available upon request | **Optimization-as-code** — Container and cloud instance optimization leveraging ML technology. |
| **[Cast AI](https://cast.ai/)** 🎯 | Cast AI | **Private (~$300M)** | **Growth: $1,000/month + $5/vCPU/month** | **Free (Monitoring tier)**: unlimited clusters, read-only recommendations | **Kubernetes automation** — Autonomous autoscaling, Spot instance management with interruption prediction, and pod bin-packing. |
| **[Sedai](https://www.sedai.io/)** 🤖 | Sedai | **Private (~$150M)** | **$10/instance/month** | **14-day free trial** with read-only cost telemetry | **Autonomous cloud management** — Predictive autoscaling, SLO-backed CPU/RAM rightsizing, and AWS Lambda optimization. |
| **[Kubecost Enterprise](https://www.kubecost.com/)** 💰 | IBM (Kubecost) | **Private (~$100M)** | **$499/month** (Enterprise starter) | **Free tier**: 250 cores or $100K spend cap over 30 days (EKS free bundle) | **Kubernetes cost monitoring & rightsizing** — Real-time cost allocation, savings recommendations, and multi-cluster visibility. |
| **[Akamas](https://www.akamas.io/)** 🎛️ | Akamas | **Private (~$50M)** | **$1,500/month** (Starter tier) | **30-day free trial** with sample optimization scenarios | **AI-powered performance & capacity tuning** — Automates JVM, Kubernetes, and OS parameter tuning. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[Kubernetes Core](https://github.com/kubernetes/kubernetes)** [![Stars](https://img.shields.io/github/stars/kubernetes/kubernetes?style=social&color=white)](https://github.com/kubernetes/kubernetes/stargazers) 📈  
  **Production-Grade Container Scheduling and Management**, Apache-2.0 licensed. **112k+ stars**. Contains the core Horizontal Pod Autoscaler (HPA) controller and scheduling bin-packing primitives.

- **[Infracost](https://github.com/infracost/infracost)** [![Stars](https://img.shields.io/github/stars/infracost/infracost?style=social&color=white)](https://github.com/infracost/infracost/stargazers) 💵  
  **Cloud cost estimates for Terraform in pull requests**, Apache-2.0 licensed. **12.6k+ stars**. Shift-left cloud cost optimization tool that gives engineers real-time cost impact before launching infrastructure.

- **[KEDA (Kubernetes Event-driven Autoscaling)](https://github.com/kedacore/keda)** [![Stars](https://img.shields.io/github/stars/kedacore/keda?style=social&color=white)](https://github.com/kedacore/keda/stargazers) 🌊  
  **Kubernetes Event-driven Autoscaling**, Apache-2.0 licensed. **8.1k+ stars**. CNCF graduated project allowing fine-grained autoscaling including scale-to-zero for event-driven workloads.

- **[Karpenter](https://github.com/kubernetes-sigs/karpenter)** [![Stars](https://img.shields.io/github/stars/kubernetes-sigs/karpenter?style=social&color=white)](https://github.com/kubernetes-sigs/karpenter/stargazers) 🚀  
  **Kubernetes Node Autoscaling Engine**, Apache-2.0 licensed. **6.5k+ stars**. High-performance node autoscaler built to rapidly launch right-sized EC2/cloud instances without nodegroup overhead.

- **[Kubernetes Autoscaler & VPA](https://github.com/kubernetes/autoscaler)** [![Stars](https://img.shields.io/github/stars/kubernetes/autoscaler?style=social&color=white)](https://github.com/kubernetes/autoscaler/stargazers) 📊  
  **Cluster Autoscaler & Vertical Pod Autoscaler**, Apache-2.0 licensed. **7.8k+ stars**. Official Kubernetes autoscaler suite providing Cluster Autoscaler for node management and VPA for container request/limit tuning.

- **[KRR (Kubernetes Resource Recommender)](https://github.com/robusta-dev/krr)** [![Stars](https://img.shields.io/github/stars/robusta-dev/krr?style=social&color=white)](https://github.com/robusta-dev/krr/stargazers) 🎯  
  **Prometheus-based Kubernetes resource recommendations**, Apache-2.0 licensed. **3.2k+ stars**. Lightweight CLI tool that analyzes Prometheus metrics to generate container CPU/memory rightsizing suggestions without requiring VPA.

- **[Crane (FinOps Platform)](https://github.com/gocrane/crane)** [![Stars](https://img.shields.io/github/stars/gocrane/crane?style=social&color=white)](https://github.com/gocrane/crane/stargazers) 🏗️  
  **FinOps platform for Cloud Native Resource Optimization**, Apache-2.0 licensed. **4.2k+ stars**. Provides cost monitoring, predictive autoscaling (Time Series Forecasting), and resource rightsizing for Kubernetes clusters.

- **[OpenCost](https://github.com/opencost/opencost)** [![Stars](https://img.shields.io/github/stars/opencost/opencost?style=social&color=white)](https://github.com/opencost/opencost/stargazers) 🌱  
  **Open-source cost monitoring for Kubernetes**, Apache-2.0 licensed. **4.1k+ stars**. CNCF Sandbox project providing real-time cost allocation by cluster, node, namespace, controller, and pod.

- **[Goldilocks](https://github.com/FairwindsOps/goldilocks)** [![Stars](https://img.shields.io/github/stars/FairwindsOps/goldilocks?style=social&color=white)](https://github.com/FairwindsOps/goldilocks/stargazers) 🐻  
  **VPA recommendations dashboard**, Apache-2.0 licensed. **2.2k+ stars**. Provides a clean web UI dashboard to visualize Vertical Pod Autoscaler resource recommendations across namespaces.

- **[StormForge Optimize Live Controller](https://github.com/thestormforge/optimize-controller)** [![Stars](https://img.shields.io/github/stars/thestormforge/optimize-controller?style=social&color=white)](https://github.com/thestormforge/optimize-controller/stargazers) ⚡  
  **Machine learning powered Kubernetes rightsizing**, Apache-2.0 licensed. **650+ stars**. Automates continuous container resource configuration and HPA tuning using ML algorithms.

- **[Kaytu CLI](https://github.com/kaytu-io/kaytu)** [![Stars](https://img.shields.io/github/stars/kaytu-io/kaytu?style=social&color=white)](https://github.com/kaytu-io/kaytu/stargazers) 💻  
  **Cloud workload efficiency analyzer**, Apache-2.0 licensed. **574 stars**. CLI tool for multi-cloud workload analysis, rightsizing recommendations, and cost reduction.

- **[Kubecost Helm Chart](https://github.com/kubecost/cost-analyzer-helm-chart)** [![Stars](https://img.shields.io/github/stars/kubecost/cost-analyzer-helm-chart?style=social&color=white)](https://github.com/kubecost/cost-analyzer-helm-chart/stargazers) 💰  
  **Kubernetes cost monitoring stack**, Apache-2.0 licensed. **520+ stars**. Official Helm installation chart for Kubecost cost analyzer and optimization dashboard.

- **[AI-Powered Cloud Platform (Go)](https://github.com/ameypant13/AI-Powered-Cloud-Platform)** [![Stars](https://img.shields.io/github/stars/ameypant13/AI-Powered-Cloud-Platform?style=social&color=white)](https://github.com/ameypant13/AI-Powered-Cloud-Platform/stargazers) 🤖  
  **AI-driven cloud resource optimization prototype**, MIT licensed. **180+ stars**. Prometheus metric collector and statistical clustering engine for automated workload rightsizing.

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new compute optimization platforms or open-source rightsizing software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Compute-Resource-Optimization&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this cloud compute optimization repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow SREs, platform engineers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **AWS Compute Optimizer is free for 14-day recommendations** — enhanced metrics cost **$0.0003360215/resource/hour** (~$0.25/month per continuously running instance).
- **Spot by NetApp (Flexera) savings-optimization dimensions** bill at variable unit rates based on achieved compute efficiency.
- **Turbonomic Standard tier** bills as a percentage of managed cloud spend or per MVS.
- **Kubecost Free tier** supports 250 cores or $100K spend over 30 days (EKS bundle offers unlimited cores for EKS).
- Open-source solutions (Karpenter, KRR, KEDA, VPA, Goldilocks) provide self-hosted transparency, but always benchmark recommendations before applying to production. ⚙️

---

<p align="center">
  <b>Made with ❤️ for SREs, platform engineers, and open-source compute optimization advocates.</b>
</p>
