# Awesome-Equipment-Performance-Monitoring

# Top Equipment Performance Monitoring Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Machine Monitoring, OEE, Condition Monitoring, Predictive Maintenance, Industrial IoT Analytics & Asset Performance*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Equipment Performance Monitoring**. These systems collect machine and process data, calculate utilization and OEE, detect anomalies, support condition-based and predictive maintenance, and turn industrial telemetry into operational insight.

**Examples** include PDF Solutions Exensio, Applied SmartFactory, Siemens Insights Hub, Seeq, Litmus, MachineMetrics, C3 AI Reliability, Braincube, GE Digital APM, and Aspen Mtell (the category leaders).

**Open-source emphasis**: Enterprise equipment-performance and APM platforms are largely commercial. Strong open building blocks exist in the industrial IoT and observability stack—**Grafana**, **Prometheus**, **InfluxDB**, **Node-RED**, **ThingsBoard**, and community predictive-maintenance projects. This section expands those options and remains realistic about the commercial gap for deep domain models and multi-plant scale.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[PDF Solutions Exensio](https://www.pdf.com/)**  
  Semiconductor and high-tech manufacturing analytics platform focused on equipment and process performance, yield, and advanced data analysis.

- **[Applied SmartFactory](https://www.appliedmaterials.com/)**  
  Factory automation and equipment performance solutions from Applied Materials for semiconductor and related manufacturing environments.

- **[Siemens Insights Hub](https://www.siemens.com/)**  
  Industrial IoT and manufacturing intelligence platform (formerly MindSphere) for connecting assets, monitoring performance, analytics, and predictive use cases—especially strong in Siemens ecosystems.

- **[Seeq](https://www.seeq.com/)**  
  Advanced analytics platform for process manufacturing—time-series investigation, monitoring, and insights on industrial data without heavy data science overhead.

- **[Litmus](https://litmus.io/)**  
  Industrial edge and data platform for collecting, normalizing, and contextualizing machine data for monitoring and analytics applications.

- **[MachineMetrics](https://www.machinemetrics.com/)**  
  Machine monitoring platform specialized in CNC and discrete manufacturing—utilization, cycle time, downtime reasons, and production visibility.

- **[C3 AI Reliability](https://c3.ai/)**  
  AI-driven reliability and predictive maintenance application for industrial assets and fleets.

- **[Braincube](https://braincube.com/)**  
  Industrial IoT and AI platform for process optimization, equipment performance, and manufacturing intelligence.

- **[GE Digital APM](https://www.ge.com/digital/)**  
  Asset Performance Management suite covering condition monitoring, reliability, and predictive maintenance for industrial equipment.

- **[Aspen Mtell and related APM / process analytics platforms](https://www.aspentech.com/)**  
  Prescriptive maintenance and equipment health solutions from AspenTech and similar process-industry analytics vendors.

## Open-Source GitHub Projects
- **[Grafana](https://github.com/grafana/grafana)**  
  Leading open-source visualization and dashboarding platform widely used for equipment KPIs, OEE boards, and real-time machine monitoring.

- **[Prometheus](https://github.com/prometheus/prometheus)**  
  Open-source metrics collection and alerting system often paired with Grafana for industrial and equipment telemetry.

- **[InfluxDB and Telegraf](https://github.com/influxdata)**  
  Open time-series database and collection agents popular for high-frequency machine and sensor data.

- **[Node-RED](https://github.com/node-red/node-red)**  
  Flow-based open tool for wiring machine data, protocols, and simple analytics—excellent for edge and plant-floor prototypes.

- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  
  Open-source IoT platform for device management, data collection, visualization, and rule-based monitoring of industrial assets.

- **[Eclipse Mosquitto and MQTT open stacks](https://github.com/)**  
  Open MQTT brokers and clients used as the backbone for machine-to-cloud and edge data flows.

- **[Open predictive-maintenance and RUL projects](https://github.com/)**  
  Community ML notebooks and pipelines (often using NASA CMAPSS and similar datasets) for remaining useful life and failure prediction prototypes.

- **[Protocol and edge open collectors (Modbus, OPC-UA, MTConnect)](https://github.com/)**  
  Open gateways and agents that connect PLCs, CNCs, and industrial equipment to open analytics stacks.

- **[OEE and production open calculators](https://github.com/)**  
  Simple open tools and spreadsheets for calculating availability, performance, quality, and overall equipment effectiveness.

- **[Documentation and industrial-observability open playbooks](https://github.com/)**  
  Guides for building self-hosted machine-monitoring stacks with Grafana, Prometheus, InfluxDB, and Node-RED.

### Additional Strong Open-Source Options
- Building a plant monitoring stack with **Telegraf/InfluxDB + Grafana** or **Prometheus + Grafana** for utilization and condition dashboards.
- Using **Node-RED** and **ThingsBoard** for edge collection, rules, and operator-facing views.
- Accepting that deep process models, semiconductor-grade analytics, multi-plant APM, certified predictive models, and enterprise reliability workflows still favor commercial platforms (Siemens Insights Hub, Seeq, MachineMetrics, C3 AI, GE Digital APM, Aspen Mtell, PDF Solutions, etc.).
- Focusing open-source efforts on data ownership, flexible dashboards, and lower cost for discrete manufacturing and internal reliability teams.

**Frameworks for building custom systems**: Connect machines via open protocol collectors → store time-series in InfluxDB or Prometheus → visualize OEE and condition metrics in Grafana → add simple anomaly rules or ML prototypes → escalate alerts to maintenance systems. Suitable for plants with engineering capacity. Most large manufacturers still adopt commercial equipment-performance and APM platforms for scale, domain models, and support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Equipment monitoring and predictive maintenance affect safety, uptime, and production. Incorrect models or incomplete monitoring can create operational risk. Open-source stacks require skilled operation and validation. This list is not engineering or safety advice.

---
**Made for manufacturing engineers, reliability teams, and open industrial IoT advocates.**
Let's keep machines visible, maintenance smarter, and core monitoring as open as practical.
