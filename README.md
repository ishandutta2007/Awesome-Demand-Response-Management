# Awesome-Demand-Response-Management

## Top Demand Response Management Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Virtual Power Plants, DER Orchestration, Demand Response Programs & Grid Flexibility*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Demand Response Management**. These tools help utilities, aggregators, and commercial energy users orchestrate flexible demand, build virtual power plants (VPPs), and participate in grid services markets.



**Examples** include AutoGrid, Uplight, Enel X, CPower, Virtual Peaker, GridPoint, EnergyHub, Leap, Voltus, and GridBeyond (the category leaders).



**Open-source emphasis**: Demand Response Management has a **growing open-source ecosystem** driven by LF Energy and academic research. **FlexMeasures** is the leading open-source energy flexibility platform, providing forecasting, scheduling, and optimization for behind-the-meter assets . **DRAF (Demand Response Analysis Framework)** provides MILP-based optimization for local multi-energy hubs . **VPP-Sim** delivers a modular, MLOps-ready framework for developing and evaluating ML-driven VPP strategies . **OpenEMS** is the established open-source energy management system, now integrating EEBus for secure grid control . **OpenGridGym** enables AI-friendly distribution market simulation . This section documents these production-grade and research-grade solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AutoGrid](https://www.auto-grid.com/)**

  **AI-driven demand response and DER optimization platform.** The **AutoGrid Flex™** platform powers behavioral demand response programs, including a program across Delhi NCR covering **85,000+ enrolled residential and commercial customers** . Provides real-time granular demand response optimization and control, enabling full demand-side participation in electricity markets . Deployed by utilities worldwide for peak load shaving and network hotspot support.



- **[Uplight](https://uplight.com/)**

  **Integrated demand-side portfolio platform for utilities.** The **Uplight Demand Stack** combines energy efficiency, rates, and demand response to deliver measurable grid capacity . **Uplight Flex** is an Edge DERMS providing advanced tools to aggregate, orchestrate, and optimize DERs at the grid edge . **Proven scale**: 500k+ devices managed and **8.5 GW of flexible capacity** worldwide, with AI-powered forecasts running every 15 minutes at **97% accuracy** . Trusted by **80+ utilities including 8 of the 10 largest in North America** . Delivered **40 MW in a single VPP event** .



- **[Enel X](https://www.enelx.com/)**

  **World leader in demand response and one of the largest VPP aggregators in North America.** Operates the **largest demand response VPP globally and locally** . Orchestrates commercial and industrial businesses to reduce energy consumption during grid stress events, with participants paid both for availability and for reduction . **Partnership with Leap** (December 2025) expands C&I DER enrollment across utility programs in Washington, Arizona, and Tennessee Valley .



- **[CPower](https://cpowerenergy.com/)**

  **Leading VPP platform connecting energy assets to demand response and on-bill programs.** Manages **6.3 GW of capacity across ~20,000 sites** in the U.S., with **$1 billion+ paid out in grid revenue to customers since 2015** . **Customer-Powered Grid™** vision enables DER flexibility for capacity, energy, ancillary services, and demand charge management . Grew total monetized MW by **38% over the last three years** .



- **[Leap](https://www.leap.energy/)**

  **Software-only platform for building and scaling VPPs.** Manages **400,000+ energy sites and devices** across U.S. energy markets, empowering **100+ technology partners** . **API-powered solution** enables smart building and smart home providers to offer grid services under their own brand, with no additional hardware required . **Partnership with Enel** (December 2025) expands C&I DER access to utility programs nationwide .



- **[GridBeyond](https://gridbeyond.com/)**

  **AI-powered demand response and energy optimization platform.** **Point** platform with **ViewPoint Lens** provides asset-level performance and revenue visibility during DR events, launching in ERCOT and SPP markets . **AI platform** creates digital twins of customer sites for energy-saving scenario modeling and automated DR actions . Strong enrollment in **PJM's Emergency Load Response Program (ELRP)** , extending year-round from 2027/28 .



- **[Virtual Peaker](https://www.virtual-peaker.com/)**

  Cloud-based DER management platform for utilities. Orchestrates residential and commercial demand response programs with device-level control.



- **[EnergyHub](https://www.energyhub.com/)**

  DER management platform connecting utilities with smart thermostats, EVs, batteries, and other devices for demand response and VPP programs.



- **[Voltus](https://www.voltus.co/)**

  Demand response aggregator and platform for commercial and industrial customers. Manages demand response participation across North American markets.



## Open-Source GitHub Projects



### Energy Flexibility & Optimization Platforms



- **[FlexMeasures](https://github.com/FlexMeasures/flexmeasures)**

  **The leading open-source energy flexibility platform, developed by Seita Energy Flexibility and contributed to LF Energy.** Acts as the "Lego Mindstorms" of smart energy planning—combining out-of-the-box algorithms, UIs, and APIs with modularity for smart orchestration of behind-the-meter assets . **Key capabilities**: Forecasting, scheduling, and optimization for energy flexibility; supports use cases including domestic buildings with heat pumps and EVs, neighborhood shared facilities with grid constraints, office buildings with multiple EVs, and large industrial plants with heat buffering . **Already adopted by smart energy startups worldwide** including Thiink Inc (U.S.) and iRasus Technologies (India) . **Python-based**.



- **[DRAF (Demand Response Analysis Framework)](https://github.com/DrafProject/draf)**

  **Analysis and decision support framework for local multi-energy hubs focusing on demand response.** Uses **(mixed integer) linear programming optimization** with pandas, Plotly, and Matplotlib . **Key features**: Time series analysis tools (`DemandAnalyzer`, `PeakLoadAnalyzer`); **component templates** for battery storage, EV, CHP, heat pump, PV, wind turbine, thermal storage, fuel cell, electrolyzer, hydrogen storage, and more; parameter preparation tools for electricity prices (via elmada) and carbon emission factors; **multi-objective optimization** supporting Pyomo and GurobiPy solvers . **Runs on Windows, macOS, and Linux**. Install via conda environment.



### VPP Development Frameworks



- **[VPP-Sim](https://dipot.ulb.ac.be/dspace/bitstream/2013/412118/3/paper.pdf)**

  **Modular open-source framework for developing and deploying ML-driven strategies in Virtual Power Plants.** **MLOps-ready** with containerized microservices architecture orchestrated via Docker Compose and Kubernetes manifests . **Technology stack**: FastAPI backend (Python); React + TypeScript frontend; **Apache Kafka** for real-time data streaming; **TimescaleDB** for time-series data; **MLflow** for ML lifecycle management (tracking, models, reproducibility); **PuLP** for optimization solver . **Core contribution**: Bridges the gap between forecasting research and downstream economic impact by connecting state-of-the-art forecasting (LSTM, Temporal Fusion Transformer) with economic optimization and dispatch . **Supports evaluating how a better ML model or control strategy tangibly impacts VPP operational performance** .



### Grid Simulation & Market Design



- **[OpenGridGym](https://par.nsf.gov/servlets/purl/10451506)**

  **Open-source AI-friendly toolkit for distribution market simulation.** Python-based framework enabling researchers to **swap out market mechanisms while keeping the same physical grid model**, and vice-versa . **Key features**: Modular architecture with base classes for Grid, Market, and Agents; leverages existing simulation tools like **OpenDSS** for grid modeling; **AI/ML-friendly** with PyTorch and CVXPY readily available; inspired by OpenAI Gym with templates and use cases . **Enables questions like**: Should local markets be peer-to-peer or DLMP-based? What role does AI play in future electricity markets? .



- **[Deep Reinforcement Learning for Capacity-Constrained Demand Response](https://github.com/ShafaghAPashaki/Capacity-constrained-demand-response-in-smart-grid-using-deep-reinforcement-learning)**

  **Open-source implementation of Double Deep Q-Network (DDQN) for incentive-based demand response in smart grids.** **Python 3.10+** with PyTorch . Provides a research foundation for applying RL to demand response optimization.



### Energy Management Systems



- **[OpenEMS](https://github.com/OpenEMS/openems)**

  **Established open-source energy management system (EMS) with new EEBus integration.** **Fraunhofer ISE, FENECON, and OpenEMS Association** developed an **open-source reference implementation for EMS** enabling secure and interoperable communication between metering systems, control boxes, and decentralized energy assets . **jEEBus library** (SHIP, SPINE, LPC/LPP use cases) now available on GitHub . **Validated in Fraunhofer ISE's Digital Grid Lab**: Control command per §14a EnWG successfully transmitted over the entire iMSys communication chain to an OpenEMS-based EMS . **FENECON** will roll out EEBus interface to its FEMS software for all users . **Enables BSI-compliant control signal implementation** .



### Additional Strong Open-Source Options



- **Energy Flexibility**: **FlexMeasures** (LF Energy, forecasting + scheduling + optimization) , **DRAF** (MILP optimization, component templates) .

- **VPP Development**: **VPP-Sim** (MLOps-ready, ML + economic optimization) .

- **Grid Simulation**: **OpenGridGym** (AI-friendly market simulation) , **DDQN for DR** (reinforcement learning) .

- **Energy Management**: **OpenEMS** (EEBus integration, BSI-compliant control) .

- **Energy Communities**: **RESCHOOL EMS** (100% open source EMS for energy communities, CIM/IEC 62325 data models) .



**Frameworks for building custom systems**: Combine **FlexMeasures** for energy flexibility forecasting and scheduling, **DRAF** for multi-energy hub optimization, **VPP-Sim** for ML-driven VPP strategy development with MLOps, **OpenEMS** for device-level energy management with EEBus communication, and **OpenGridGym** for market design simulation. Add **PostgreSQL/TimescaleDB** for time-series persistence and **Docker/Kubernetes** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Demand response platforms handle sensitive grid and energy consumption data; ensure compliance with FERC, NERC, and applicable regional energy regulations.

- **Open-source reality**: The open-source ecosystem for demand response management is **growing and research-active** at the **optimization and simulation layers** (**FlexMeasures**, **DRAF**, **VPP-Sim**, **OpenGridGym**) and **mature at the energy management layer** (**OpenEMS** with EEBus) . However, **commercial platforms** (AutoGrid, Uplight, Enel X, CPower, Leap, GridBeyond) provide **utility-grade DERMS, real-time market dispatch, regulatory compliance, and the device aggregation networks** that open-source alternatives require significant integration and market access to match. The open-source path is most viable for **behind-the-meter optimization, VPP research, market simulation, and organizations with strong energy engineering capacity**.



---



**Made for utility demand response managers, DER aggregators, energy flexibility researchers, and grid operators.**

Let's make demand response management more open, transparent, and grid-friendly.
