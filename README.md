# Awesome-Internet-Of-Things-IOT-Platform

## Top Internet of Things (IoT) Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Device Management, MQTT Brokers, Edge Computing, Telemetry Ingestion, Industrial IoT (IIoT) & Smart Automation*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Internet of Things (IoT) Platforms**. These tools handle device provisioning, secure bidirectional communication (MQTT, CoAP, HTTP, LoRaWAN, LwM2M), real-time telemetry ingestion, rule-based automation, over-the-air (OTA) firmware updates, and interactive operational dashboards.



**Examples** include Zoho IoT, AWS IoT Core, Azure IoT Hub, Google Cloud IoT, PTC ThingWorx, Particle, Hologram, Cisco IoT Control Center, Software AG Cumulocity IoT, and Samsara (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, high-throughput MQTT messaging, edge gateways, smart home/building automation, and industrial telemetry pipelines — ideal for embedded engineers, IoT architects, DevOps teams, and makers building sovereign connected device infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS IoT Core](https://amazon.com)**  

  Managed cloud IoT service enabling billions of connected devices to securely interact with cloud applications via MQTT, HTTPS, and LoRaWAN.



- **[Microsoft Azure IoT Hub](https://microsoft.com)**  

  Cloud-hosted managed service acting as a central message hub for bidirectional communication between IoT applications and edge devices.



- **[Zoho IoT](https://zoho.com)**  

  Low-code end-to-end IoT platform designed for industrial automation, smart buildings, energy management, and connected asset monitoring.



- **[PTC ThingWorx](https://ptc.com)**  

  Enterprise Industrial IoT (IIoT) platform offering rapid application development, digital twins, predictive analytics, and factory connectivity.



- **[Cumulocity IoT (Software AG)](https://cumulocity.com)**  

  Cloud-native, self-service IoT device management and application enablement platform supporting edge-to-cloud industrial analytics.



- **[Particle](https://particle.io)**  

  Integrated edge-to-cloud IoT platform combining cellular/Wi-Fi hardware modules, global connectivity, device management, and OTA updates.



- **[Samsara](https://samsara.com)**  

  Connected operations cloud platform providing real-time GPS fleet telemetry, AI safety cameras, equipment monitoring, and site visibility.



- **[Cisco IoT Control Center](https://cisco.com)**  

  Enterprise cellular connectivity management platform automating global SIM provisioning, billing, diagnostics, and security for IoT deployments.



- **[Hologram](https://hologram.io)**  

  Global cellular IoT connectivity and SIM management platform providing multi-carrier coverage, fleet APIs, and usage monitoring.



- **[Blynk (Cloud)](https://blynk.io)**  

  Low-code IoT cloud platform offering drag-and-drop mobile/web dashboards, device provisioning, and OTA firmware management for connected hardware.



## Open-Source GitHub Projects



- **[ThingsBoard](https://github.com)**  

  Flagship open-source IoT platform for device management, data collection, processing, and customizable real-time visualization via MQTT, CoAP, and HTTP.



- **[Home Assistant](https://github.com)**  

  World's most active open-source smart home and local IoT automation platform supporting thousands of device integrations without cloud dependencies.



- **[EMQX](https://github.com)**  

  Massively scalable, distributed open-source MQTT broker engineered to handle tens of millions of concurrent IoT device connections with sub-millisecond latency.



- **[Eclipse Mosquitto](https://github.com)**  

  Lightweight, battle-tested open-source MQTT message broker ideal for everything from single-board computers (Raspberry Pi) to enterprise IoT servers.



- **[Node-RED](https://github.com)**  

  Low-code, flow-based programming tool widely used in IoT and IIoT for wiring together hardware devices, MQTT brokers, APIs, and cloud services.



- **[Eclipse Ditto](https://github.com)**  

  Open-source Digital Twin framework for IoT enabling applications to manage state, metadata, and access control of physical devices via APIs.



- **[Eclipse Hono](https://github.com)**  

  Cloud-native open-source IoT connectivity layer providing uniform remote service interfaces across MQTT, HTTP, AMQP, CoAP, and LoRaWAN.



- **[Eclipse Kapua](https://github.com)**  

  Modular open-source IoT cloud platform providing device registry, broker services, data management, and edge integration for Eclipse Kura.



- **[Eclipse Kura](https://github.com)**  

  Java/OSGi-based open-source IoT edge framework offering field protocol drivers (Modbus, OPC-UA, S7), store-and-forward, and remote gateway management.



- **[EdgeX Foundry](https://github.com)**  

  Vendor-neutral open-source industrial IoT edge computing framework connecting south-bound OT sensors/PLCs to north-bound cloud analytics.



- **[Mainflux / Magistrala](https://github.com)**  

  Modern, scalable open-source IoT middleware written in Go featuring multi-protocol messaging, fine-grained access control, and event sourcing.



- **[Kaa IoT (Open Core / Community)](https://github.com)**  

  Flexible open-source enterprise IoT middleware platform supporting device configuration, data collection, analytics, and OTA notifications.



- **[OpenRemote](https://github.com)**  

  100% open-source IoT asset management platform designed for smart cities, energy grids, fleet tracking, and building automation.



- **[ChirpStack](https://github.com)**  

  Complete open-source LoRaWAN Network Server stack providing gateway management, device provisioning, and MQTT/HTTP/InfluxDB integrations.



- **[Mender](https://github.com)**  

  Open-source over-the-air (OTA) software and firmware updater engineered for robust, atomic A/B updates on embedded Linux and microcontroller fleets.



- **[Eclipse hawkBit](https://github.com)**  

  Domain-independent open-source backend framework for rolling out software updates to constrained edge devices and IoT controllers.



- **[ESPHome](https://github.com)**  

  Open-source system for controlling ESP8266/ESP32/RP2040 microcontrollers via simple YAML configuration files with seamless MQTT and Home Assistant integration.



- **[openHAB](https://github.com)**  

  Vendor-agnostic open-source home and building automation platform written in Java supporting hundreds of industrial and consumer IoT bindings.



- **[InfluxDB](https://github.com)**  

  High-performance open-source time-series database purpose-built for ingesting, querying, and downsampling high-frequency IoT sensor telemetry.



- **[TimescaleDB](https://github.com)**  

  Open-source time-series SQL database built on PostgreSQL enabling relational joins alongside massive IoT sensor data ingestion.



### Additional Strong Open-Source Options



- **[Industrial Protocol Gateways (`PLC4X`, `node-opcua`, `Modbus` bridges)](https://github.com)** for connecting legacy factory PLCs and SCADA systems to modern IoT brokers.

- **[High-Throughput MQTT Brokers (`NanoMQ`, `VerneMQ`, `HiveMQ Community Edition`)](https://github.com)** for edge-to-cloud message routing and QUIC/MQTT 5.0 support.

- **[Embedded Real-Time Operating Systems (`Zephyr RTOS`, `FreeRTOS`, `RIOT-OS`)](https://github.com)** for building secure, connected microcontroller firmware.

- **[IoT Visualization & Monitoring (`Grafana`, `QuestDB`, `Telegraf`)](https://github.com)** for collecting, transforming, and visualizing real-time sensor metrics.

- Many community **Docker Compose & Kubernetes Helm charts** for deploying scalable MQTT + Time-Series + ThingsBoard IoT stacks.



**Frameworks for building custom systems**: Combine **EMQX** or **Eclipse Mosquitto** with **ThingsBoard / Node-RED**, **InfluxDB / TimescaleDB**, and **Grafana** alongside **Mender** for a complete, self-hosted industrial and consumer IoT platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- IoT and Industrial IoT platforms controlling physical hardware or critical infrastructure must implement strict device authentication (mTLS/X.509 certificates), network segmentation, and secure boot.

- Self-hosted open-source IoT platforms require proper broker clustering, persistent message queuing, and rate limiting to handle telemetry spikes.



---



**Made for embedded engineers, IoT architects, industrial automation teams, and hardware makers.**  

Let's make connected device infrastructure more interoperable, resilient, and open.
