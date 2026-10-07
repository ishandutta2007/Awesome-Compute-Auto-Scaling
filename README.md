# Awesome-Compute-Auto-Scaling ⚙️ 📈 🚀

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Compute Auto Scaling Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Compute-Auto-Scaling"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Compute-Auto-Scaling?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Compute-Auto-Scaling/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Compute-Auto-Scaling?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Compute-Auto-Scaling/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Compute-Auto-Scaling?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Compute Auto Scaling Ecosystem ⚡

**Curated List of Commercial Auto Scaling Platforms & Open-Source Autoscaling Tools**  
*Focused on Dynamic Capacity Management, Predictive Scaling, Kubernetes Autoscaling, Rightsizing & Self-Hosted Autoscaling Engines* 💡

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary 🔍

Welcome to the ultimate curated directory of **compute auto scaling platforms**, **open-source autoscaling frameworks**, and **capacity optimization engines**. Whether you are looking for enterprise-grade commercial solutions (such as *Azure VMSS*, *AWS EC2 Auto Scaling*, *Google Compute Engine MIGs*, and *IBM Turbonomic*), or self-hostable open-source alternatives (like *KEDA*, *Kubernetes Cluster Autoscaler*, *Karpenter*, *VPA*, and *StormForge AppSymphony*), this list covers category leaders, predictive scaling, event-driven scaling, and privacy-respecting capacity management. 🚀

**Key Market Context:** 📊
- **Auto scaling is essential for cloud cost efficiency** — dynamic capacity management aligns infrastructure resources with fluctuating real-time demand to eliminate over-provisioning. ⚡
- **Native auto scaling services are free** — Hyperscalers (AWS, Azure, GCP) charge zero management fees for autoscaling engines; users pay strictly for consumed underlying compute resources. ☁️
- **Kubernetes-native event-driven autoscaling** (KEDA, Karpenter, VPA, Cluster Autoscaler) is the cloud-native standard, enabling scale-to-zero and microsecond pod rightsizing. ☸️

---

## 📑 Table of Contents 📖

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms 🌐

> 💡 **Market Size & Structure Analysis:**  
> The global **Compute Auto Scaling & Cloud Infrastructure Optimization Market** is estimated at **$6.2 Billion in 2026** (growing at a ~24% CAGR). The market structure is **moderately fragmented**: cloud hyperscalers (AWS, Azure, GCP) dominate native VM scale set controls through bundled free features, while specialized AI-driven FinOps and Kubernetes rightsizing platforms (Cast AI, Spot by NetApp, IBM Turbonomic, Granulate) capture high-margin enterprise workloads requiring multi-cloud predictive scaling and automated spot instance fallback.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Virtual Machine Scale Sets](https://azure.microsoft.com/en-us/products/virtual-machine-scale-sets/)** 🔷 | Microsoft | ~$3.90 Trillion | **Free management service** (Pay only for consumed VM instances, storage, and networking bandwidth) | **Free forever** management plane; Includes Azure Free Account with **750 hours/month** of B1s VMs for 12 months | **Azure-native auto scaling** — **Scheduled and metric-based scaling** with CPU, network, and disk metrics. **Automatic distribution across Availability Zones** for high availability. **Up to 1,000 VMs per scale set**. **Autoscale rules** with configurable min/max limits. ⚡ |
| **[AWS EC2 Auto Scaling](https://aws.amazon.com/ec2/autoscaling/)** ☁️ | Amazon | ~$2.0 Trillion | **Free management service** (Pay only for EC2 compute instances and CloudWatch alarms used) | **Free forever** management plane; Includes AWS Free Tier with **750 hours/month** of t2.micro/t3.micro instances for 12 months | **AWS-native auto scaling** — **Dynamic scaling** based on CloudWatch metrics, schedules, or predictive ML policies. **Step scaling** allows different adjustments based on alarm breach size. **Spot Instances** with capacity-optimized allocation. **Warm pools** for faster scale-out. 🚀 |
| **[Google Compute Engine MIGs](https://cloud.google.com/compute/docs/autoscaler)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **Free management service** (Pay only for active Compute Engine virtual machine instances used) | **Free forever** management plane; Includes GCP Free Tier with **1 e2-micro instance/month** in select US regions | **GCP-native auto scaling** — **Target utilization metrics** (CPU, HTTP load balancing, Cloud Monitoring) and **schedule-based scaling**. **Up to 128 scaling schedules per MIG**. **Predictive autoscaling** with initialization period. **Scale to zero** with minNumReplicas=0. 🎯 |
| **[IBM Turbonomic](https://www.ibm.com/products/turbonomic)** ⚙️ | IBM | ~$200 Billion | **$18.75/month** for Cloud edition (or **$225/year usage-based** for Standard edition) | **30-day free trial** with full feature access and unlimited optimization recommendations | **Application resource management** — **Public cloud optimization**, **Kubernetes optimization** (EKS, AKS, GKE), and **application/database resource optimization**. **SLO-driven optimization** and **enterprise SSO**. Percentage of cloud spend or per MVS pricing for larger deployments. 📊 |
| **[Granulate](https://granulate.io/)** ⚡ | Intel | ~$100 Billion | **$0.002 per vCPU hour** for autonomous continuous optimization | **14-day free trial** for up to 100 workloads with full automated tuning | **Autonomous workload optimization** — **No code changes required**. Continuous ML-driven CPU and memory tuning for Linux kernel and runtime environments. 🧠 |
| **[Spot by NetApp](https://spot.io/)** 🟢 | NetApp | ~$20 Billion | **Median buyer cost: $109,384/year** (Standard starting packages from **$0.02 per optimized node-hour**) | **14-day free trial** for Spot Eco and Ocean with full self-serve cluster analysis | **Cloud automation and optimization** — **Continuous analytics** for infrastructure optimization. **Spot instance management** with interruption prediction. **Ocean** for Kubernetes worker node management. **Savings-based billing** aligns fees with achieved value. 🌊 |
| **[Cast AI](https://cast.ai/)** 🎯 | Cast AI | Private (~$350 Million) | **Growth: $1,000/month** (up to 2,000 CPUs) or **Enterprise: $5,000/month** | **Free Monitoring Tier** forever (unlimited clusters, read-only rightsizing recommendations) | **Kubernetes automation** — **Automated cluster autoscaling** with continuous rebalancing, container live migration, and workload right-sizing. Consumption unit: **$0.01 per overage CPU hour**. Realized savings tracked via node autoscaler and workload autoscaler. 🤖 |
| **[Morpheus Data](https://morpheusdata.com/)** 🔮 | Morpheus Data | Private (~$250 Million) | **$1,500/year per node** for standard enterprise hybrid cloud control plane | **30-day free trial** for up to 25 managed hybrid cloud compute nodes | **Cloud management platform** — **Self-service provisioning with policy guardrails**. **Custom pricing engine** with USN currency support for chargeback. **Cloud costing analytics** and billing reports. 🛡️ |
| **[Densify](https://www.densify.com/)** 📊 | Densify | Private (~$150 Million) | **$15/month per container instance** / node analyzed | **14-day free trial** with automated cloud resource analysis report | **Cloud and container optimization** — **Optimization-as-code** with ML technology. **AWS, Azure, GCP, and Kubernetes analysis APIs**. **Container recommendations** per cluster. Makes applications self-aware of precise resource requirements. 📈 |
| **[Kubecost](https://www.kubecost.com/)** 💰 | IBM (Kubecost) | Private (~$100 Million) | **Free Tier available**; Business edition starts at **$499/month** | **Free forever** for unlimited clusters up to 250 cores / $100K monthly spend (EKS-optimized bundle is free with no spend cap) | **Kubernetes cost monitoring** — **Real-time cost allocation** by cluster, node, namespace, controller, service, or pod. **EKS-optimized bundle is free** with full Kubernetes spend features, no $100K cap. **Savings recommendations** for rightsizing. 💵 |

---

## 🔓 Open-Source GitHub Projects 🛠️

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[Kubernetes Autoscaler](https://github.com/kubernetes/autoscaler)** [![Stars](https://img.shields.io/github/stars/kubernetes/autoscaler?style=social&color=white)](https://github.com/kubernetes/autoscaler/stargazers)  
  **Official Kubernetes Autoscaling Framework (Cluster Autoscaler & Vertical Pod Autoscaler)**, Apache-2.0 licensed. **Automatically adjusts cluster node capacity** when pods fail to schedule or nodes are underutilized, while **VPA automatically tunes container CPU and memory requests**. **Works with AWS, Azure, GCP, and bare-metal providers**. ⚙️ ☸️

- **[KEDA](https://github.com/kedacore/keda)** [![Stars](https://img.shields.io/github/stars/kedacore/keda?style=social&color=white)](https://github.com/kedacore/keda/stargazers)  
  **Kubernetes Event-driven Autoscaling**, Apache-2.0 licensed. **CNCF Graduated project** — the **de facto standard for event-driven autoscaling** in Kubernetes. **Scale-to-zero** for event-driven workloads. **50+ built-in scalers** for Cron, CPU, Kafka, RabbitMQ, Redis, PostgreSQL, and AWS SQS. **No external dependencies** — runs on cloud and edge. Integrates natively with **Horizontal Pod Autoscaler (HPA)**. 🎯 ⚡

- **[Karpenter](https://github.com/kubernetes-sigs/karpenter)** [![Stars](https://img.shields.io/github/stars/kubernetes-sigs/karpenter?style=social&color=white)](https://github.com/kubernetes-sigs/karpenter/stargazers)  
  **Just-in-time Kubernetes Node Autoscaler**, Apache-2.0 licensed. Built by AWS and SIG-Autoscaling, Karpenter provides **high-speed, grouping-free node provisioning** that rapidly evaluates unschedulable pods and launches optimal EC2/cloud compute instances in seconds. 🚀 🐺

- **[OpenCost](https://github.com/opencost/opencost)** [![Stars](https://img.shields.io/github/stars/opencost/opencost?style=social&color=white)](https://github.com/opencost/opencost/stargazers)  
  **Open-source cost monitoring for Kubernetes**, Apache-2.0 licensed. **CNCF Sandbox project** providing real-time cost allocation and efficiency tracking by cluster, node, namespace, controller, and pod. **Multi-cloud monitoring for AWS, Azure, GCP**. Built-in MCP server for AI agent access. 🌱 💰

- **[Goldilocks](https://github.com/FairwindsOps/goldilocks)** [![Stars](https://img.shields.io/github/stars/FairwindsOps/goldilocks?style=social&color=white)](https://github.com/FairwindsOps/goldilocks/stargazers)  
  **VPA recommendations dashboard**, Apache-2.0 licensed. **Web dashboard for viewing VPA recommendations** across all namespaces. Identifies workloads with **mismatched resource requests**. **The easiest way to start rightsizing Kubernetes workloads**. 🐻 📊

- **[KRR (Kubernetes Resource Recommender)](https://github.com/robusta-dev/krr)** [![Stars](https://img.shields.io/github/stars/robusta-dev/krr?style=social&color=white)](https://github.com/robusta-dev/krr/stargazers)  
  **Prometheus-based Kubernetes resource recommendations**, Apache-2.0 licensed. **Popular open-source VPA alternative** — scrapes Prometheus metrics and generates CPU/memory rightsizing recommendations without requiring VPA installation. **HTML reports** with per-namespace breakdowns. 🎯 📈

- **[Kubecost Free Chart](https://github.com/kubecost/cost-analyzer-helm-chart)** [![Stars](https://img.shields.io/github/stars/kubecost/cost-analyzer-helm-chart?style=social&color=white)](https://github.com/kubecost/cost-analyzer-helm-chart/stargazers)  
  **Kubernetes cost monitoring and optimization Helm chart**, Apache-2.0 licensed. **EKS-optimized bundle is free** with no spend cap. **Savings recommendations** for rightsizing. **ETL feature** aggregates metrics for namespace-level, pod-level, and deployment-level visibility. 💰 📊

- **[Kube-downscaler](https://github.com/hjacobs/kube-downscaler)** [![Stars](https://img.shields.io/github/stars/hjacobs/kube-downscaler?style=social&color=white)](https://github.com/hjacobs/kube-downscaler/stargazers)  
  **Scale down Kubernetes resources during off-hours**, Apache-2.0 licensed. **Reduces costs by scaling down non-production workloads** (deployments, statefulsets) during nights and weekends. **Configurable time windows and cron expressions**. 🌙 💤

- **[StormForge AppSymphony (formerly Optimize Live)](https://github.com/thestormforge)** [![Stars](https://img.shields.io/github/stars/thestormforge?style=social&color=white)](https://github.com/thestormforge/stargazers)  
  **ML-powered Kubernetes Rightsizing & Autoscaling Engine**, Apache-2.0 licensed components. Automatically analyzes telemetry from Datadog or Prometheus to continuously adjust HPA target utilization and resource requests. 🤖 ⚡

- **[Skuber / Custom Controller Autoscalers](https://github.com/skuber/skuber)** [![Stars](https://img.shields.io/github/stars/skuber/skuber?style=social&color=white)](https://github.com/skuber/skuber/stargazers)  
  **Reactive Scala-based Kubernetes Client & Auto-scaler framework**, Apache-2.0 licensed. Designed for custom event-driven reactive microservice auto-scaling controllers. 🔮 💻

---

## 🛠️ How to Contribute 🤝

Contributions are welcome! Follow these steps to submit new auto scaling platforms or open-source autoscaling software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History 📈

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Compute-Auto-Scaling&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Compute-Auto-Scaling&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship 💖

If you find this compute auto scaling repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow SREs, platform engineers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer ℹ️

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Native auto scaling services are free** — AWS EC2 Auto Scaling, Azure VMSS, and GCP MIGs charge nothing for the autoscaling service itself; you pay only for the underlying compute resources. ☁️
- **Spot by NetApp has a median buyer cost of $109,384/year**. **Cast AI Growth is $1,000/month** with a **$0.01 per overage consumption unit**. **IBM Turbonomic Cloud is $18.75/month** for unlimited optimization. 💰
- **Kubecost EKS-optimized bundle is free** with no spend cap, unlike the standard free tier which has a **$100K spend limit**. 📊
- **Open-source autoscaling tools (KEDA, Karpenter, VPA, Cluster Autoscaler) are not turnkey** — they require **Kubernetes expertise and ongoing maintenance**. **Always validate scaling behavior with a proof-of-concept** before production deployment. ⚙️

---

<p align="center">
  <b>Made with ❤️ for SREs, platform engineers, and open-source autoscaling advocates.</b>
</p>
