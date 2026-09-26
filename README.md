<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&amp;logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&amp;logo=discord&amp;logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Equipment-Performance-Monitoring/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Equipment-Performance-Monitoring?style=flat-square" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Equipment-Performance-Monitoring/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Equipment-Performance-Monitoring?style=flat-square" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Equipment-Performance-Monitoring/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Equipment-Performance-Monitoring?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

![Awesome Equipment Performance Monitoring](assets/banner.svg)

# 🏭 Awesome Equipment Performance Monitoring

> **A curated ecosystem of SaaS platforms & open-source solutions for Equipment Performance Monitoring (EPM), Overall Equipment Effectiveness (OEE), Asset Performance Management (APM), Condition Monitoring, and Predictive Maintenance (PdM).**

---

## 📌 Executive Overview & SEO Keywords

**Equipment Performance Monitoring (EPM)** combines industrial IoT (IIoT) telemetry, machine protocol acquisition (OPC-UA, Modbus, MTConnect), time-series analytics, and AI/ML reliability modeling to optimize manufacturing uptime and asset yield. 

This repository serves as a comprehensive index for manufacturing engineers, maintenance directors, CTOS, and IoT architects seeking to evaluate commercial **APM/EPM SaaS suites** alongside community **open-source industrial observability building blocks**.

*Key Topics & Search Intent:* `Equipment Performance Monitoring` • `Asset Performance Management (APM)` • `Overall Equipment Effectiveness (OEE)` • `Predictive Maintenance (PdM)` • `Condition Monitoring` • `Industrial IoT (IIoT)` • `Smart Manufacturing` • `Machine Telemetry & SCADA`

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial APM Platforms](#-saas--commercial-apm-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🏗️ Recommended Architecture Stacks](#%EF%B8%8F-recommended-architecture-stacks)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)
- [📈 Star History](#-star-history)
- [💖 Support & Community](#-support--community)

---

## 🏢 SaaS & Commercial APM Platforms

> **Market Analysis & Industry Structure:** The global Equipment Performance Monitoring & APM market is estimated at **$5.2 Billion** (projected to reach **$16.8 Billion** by 2030 at a **15.4% CAGR**). The market is **moderately fragmented**, with established industrial conglomerate platforms (*Applied Materials, Siemens, GE Vernova, AspenTech*) occupying enterprise semiconductor and process plant strongholds, while agile specialized AI SaaS platforms (*C3 AI, Seeq, MachineMetrics, Litmus*) capture high-growth discrete and edge monitoring niches.

Below is a curated matrix of top enterprise SaaS platforms, **sorted by Company Size / Valuation / Revenue (descending)**:

| 🏢 Platform / SaaS Product | 💰 Company Valuation / Revenue | 🏷️ Starting Pricing | 🆓 Free Tier / Trial Limits | 🎯 Primary Focus & Domain |
| :--- | :--- | :--- | :--- | :--- |
| **[Applied SmartFactory](https://www.appliedmaterials.com/)** | **~$175 Billion** *(Valuation)* | **~$5,000 / line / month** | **14-day guided sandbox demo** for enterprise fabs | Semiconductor & high-tech fab automation, yield management, and equipment efficiency. |
| **[Siemens Insights Hub](https://www.siemens.com/)** | **~$150 Billion** *(Valuation)* | **~$250 / month** *(Basic IoT package)* | **30-day free trial** *(Up to 5 assets & 10GB storage limit)* | Industrial IoT & manufacturing intelligence platform (formerly MindSphere) for Siemens PLCs. |
| **[GE Digital APM](https://www.ge.com/digital/)** | **~$48 Billion** *(Valuation - GE Vernova)* | **~$1,200 / asset / year** | **30-day enterprise trial** *(Up to 10 asset profiles)* | Asset Performance Management suite for power generation, oil & gas, and heavy manufacturing. |
| **[Aspen Mtell](https://www.aspentech.com/)** | **~$15 Billion** *(Market Cap)* | **~$800 / asset / month** | **30-day proof-of-concept trial** environment | Prescriptive maintenance and failure prediction algorithms for chemical and process industries. |
| **[C3 AI Reliability](https://c3.ai/)** | **~$3.2 Billion** *(Market Cap)* | **~$0.55 / vCPU-hour** *(~$10k/mo node)* | **14-day developer trial** *(Up to 100 vCPU-hours limit)* | Enterprise AI reliability application for monitoring heavy machinery & equipment fleets. |
| **[PDF Solutions Exensio](https://www.pdf.com/)** | **~$1.4 Billion** *(Market Cap)* | **~$2,500 / module / month** | **14-day evaluation sandbox** environment | Big data analytics platform focused on semiconductor equipment health, test, and yield. |
| **[Seeq SaaS](https://www.seeq.com/)** | **~$750 Million** *(Est. Valuation)* | **~$500 / user / month** | **30-day full-feature trial** *(Up to 5 users & 100 time-series tags)* | Advanced time-series investigation and condition monitoring for continuous process manufacturing. |
| **[Litmus Edge](https://litmus.io/)** | **~$250 Million** *(Est. Valuation)* | **~$295 / edge device / month** | **30-day free trial** *(Up to 5 device connections limit)* | Industrial edge and data platform for collecting and normalizing machine telemetry across PLCs. |
| **[MachineMetrics](https://www.machinemetrics.com/)** | **~$180 Million** *(Est. Valuation)* | **~$200 / machine / month** | **14-day free trial** *(Up to 3 CNC machine connections)* | Automated machine monitoring and OEE tracking specialized in CNC and discrete manufacturing. |
| **[Braincube](https://braincube.com/)** | **~$120 Million** *(Est. Valuation)* | **~$1,500 / site / month** | **30-day interactive sandbox** with sample datasets | Edge & cloud industrial IoT platform for manufacturing process optimization and equipment APM. |

---

## 🔓 Open-Source GitHub Projects

Open-source technologies form the backbone of self-hosted equipment monitoring, time-series storage, edge gateways, and custom OEE dashboards.

Below is a curated index of leading open-source projects, **sorted by GitHub Stars_Count (descending)**:

| 📦 Repository & Link | ⭐ Star Rating Badge | 📝 Core Capabilities in EPM / IIoT Ecosystem |
| :--- | :--- | :--- |
| **[Home Assistant Core](https://github.com/home-assistant/core)** | [![Stars](https://img.shields.io/github/stars/home-assistant/core?style=social&color=white)](https://github.com/home-assistant/core/stargazers) | Open-source engine frequently used for lightweight sensor tracking, power telemetry, and condition triggers. |
| **[Grafana](https://github.com/grafana/grafana)** | [![Stars](https://img.shields.io/github/stars/grafana/grafana?style=social&color=white)](https://github.com/grafana/grafana/stargazers) | De facto standard open-source visualization dashboarding engine for equipment KPIs, real-time OEE, and sensor telemetry. |
| **[Prometheus](https://github.com/prometheus/prometheus)** | [![Stars](https://img.shields.io/github/stars/prometheus/prometheus?style=social&color=white)](https://github.com/prometheus/prometheus/stargazers) | Cloud-native time-series metrics collection and alerting engine paired with Grafana for equipment telemetry monitoring. |
| **[InfluxDB](https://github.com/influxdata/influxdb)** | [![Stars](https://img.shields.io/github/stars/influxdata/influxdb?style=social&color=white)](https://github.com/influxdata/influxdb/stargazers) | Purpose-built high-performance time-series database optimized for high-frequency machine sensors and industrial metrics. |
| **[Node-RED](https://github.com/node-red/node-red)** | [![Stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers) | Low-code flow programming editor ideal for wiring PLC protocols (Modbus, OPC-UA, MQTT) and building edge data pipelines. |
| **[ThingsBoard](https://github.com/thingsboard/thingsboard)** | [![Stars](https://img.shields.io/github/stars/thingsboard/thingsboard?style=social&color=white)](https://github.com/thingsboard/thingsboard/stargazers) | Open-source IoT platform offering out-of-the-box equipment telemetry dashboards, asset hierarchy, and rule engine alerts. |
| **[Telegraf](https://github.com/influxdata/telegraf)** | [![Stars](https://img.shields.io/github/stars/influxdata/telegraf?style=social&color=white)](https://github.com/influxdata/telegraf/stargazers) | Plugin-driven server agent for capturing equipment performance counters, MQTT topics, and system metrics. |
| **[Eclipse Mosquitto](https://github.com/eclipse/mosquitto)** | [![Stars](https://img.shields.io/github/stars/eclipse/mosquitto?style=social&color=white)](https://github.com/eclipse/mosquitto/stargazers) | Lightweight MQTT broker providing efficient pub/sub backbone for plant-floor machine-to-cloud telemetry. |
| **[KubeEdge](https://github.com/kubeedge/kubeedge)** | [![Stars](https://img.shields.io/github/stars/kubeedge/kubeedge?style=social&color=white)](https://github.com/kubeedge/kubeedge/stargazers) | Kubernetes-native edge computing infrastructure for orchestrating equipment monitoring microservices on shop floors. |
| **[EdgeX Foundry](https://github.com/edgexfoundry/edgex-go)** | [![Stars](https://img.shields.io/github/stars/edgexfoundry/edgex-go?style=social&color=white)](https://github.com/edgexfoundry/edgex-go/stargazers) | Linux Foundation vendor-neutral open edge IoT framework for unifying industrial machine protocol acquisition. |
| **[Apache StreamPipes](https://github.com/apache/streampipes)** | [![Stars](https://img.shields.io/github/stars/apache/streampipes?style=social&color=white)](https://github.com/apache/streampipes/stargazers) | Industrial IoT platform enabling non-developers to configure live stream analytics pipelines for machine telemetry. |
| **[Apache PLC4X](https://github.com/apache/plc4x)** | [![Stars](https://img.shields.io/github/stars/apache/plc4x?style=social&color=white)](https://github.com/apache/plc4x/stargazers) | Universal set of industrial protocol drivers (Modbus, Siemens S7, EtherNet/IP, OPC-UA) for direct PLC integration. |
| **[Scada-LTS](https://github.com/scada-lts/Scada-LTS)** | [![Stars](https://img.shields.io/github/stars/scada-lts/Scada-LTS?style=social&color=white)](https://github.com/scada-lts/Scada-LTS/stargazers) | Open-source SCADA project designed for equipment telemetry monitoring, alarm management, and process control. |

---

## 🏗️ Recommended Architecture Stacks

For organizations looking to build self-hosted equipment monitoring stacks, the following pipeline is recommended:

```mermaid
flowchart LR
    A["🔌 Machine / PLC Gateway<br/>(Apache PLC4X / EdgeX / Modbus)"] --> B["⚡ Edge Processing & Message Bus<br/>(Node-RED / Eclipse Mosquitto)"]
    B --> C["🗄️ Time-Series Storage<br/>(InfluxDB / Prometheus)"]
    C --> D["📊 Visualization & OEE Dashboarding<br/>(Grafana / ThingsBoard)"]
    C --> E["🔮 Anomaly & Failure Alerts<br/>(Python ML / Rule Engine)"]
```

---

## 🤝 How to Contribute

Contributions are welcome and appreciated! Follow these steps to submit additions:

1. 🍴 **Fork** this repository.
2. 📝 Edit `README.md` to add your proposed SaaS or open-source tool.
3. 📌 Follow the table format (include specific pricing, free limits, valuation/revenue, and Stars_Badges).
4. 🚀 Submit a **Pull Request** with a clear explanation of why the addition is valuable.

See [Awesome List Guidelines](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) for quality standards.

---

## ⚠️ Disclaimer

- This repository is a **community-curated index** provided for informational purposes only.
- Equipment monitoring, condition monitoring, and predictive maintenance applications impact industrial safety, operational downtime, and machinery longevity. Self-hosted setups require proper domain validation before production deployment.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Equipment-Performance-Monitoring&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Equipment-Performance-Monitoring&type=date&legend=top-left)

---

## 💖 Support & Community

Thank you for exploring **Awesome Equipment Performance Monitoring**! If you find this curated list valuable for your manufacturing, reliability engineering, or industrial IoT work:

- ⭐ **Star** this repository to help others discover it.
- 🔀 **Fork** it to keep your own reference copy.
- 📢 **Share** it with fellow reliability engineers and smart manufacturing practitioners.
- ☕ **Buy me a coffee**: Support ongoing curation and open-source industrial tooling via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).
