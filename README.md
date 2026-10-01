<p align="center">
  <img src="assets/banner.svg" alt="Awesome Demand Response Management Banner" width="100%" />
</p>

# ⚡ Awesome Demand Response Management ⚡

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License MIT" />
  <img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg" alt="Maintained" />
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🚀 **Curated List of Enterprise SaaS Platforms & Open-Source GitHub Projects for Demand Response Management, Virtual Power Plants (VPP), Distributed Energy Resource Management Systems (DERMS), and Grid Flexibility Orchestration.**

---

## 💡 Overview & Market Landscape

The global **Demand Response Management System (DRMS) & Virtual Power Plant (VPP) market** is projected to grow from **$3.5 Billion in 2023 to over $12.8 Billion by 2030** (CAGR ~20.5%). Driven by FERC Order 2222, grid decarbonization, and extreme weather events, utilities and energy aggregators are rapidly deploying software to orchestrate behind-the-meter resources.

📊 **Market Dynamics:** The sector is **moderately fragmented**, featuring a mix of utility-scale energy conglomerates (Enel X, Uplight), specialized high-growth aggregators (CPower, Leap, Voltus), and regional AI-native optimization vendors (AutoGrid, GridBeyond). No single player controls the market, making interoperability and open-source standards increasingly vital.

---

## 📋 Table of Contents

- [🏢 Enterprise SaaS & Hosted Platforms](#-enterprise-saas--hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)
- [💖 Support](#-support)
- [📈 Star History](#-star-history)

---

## 🏢 Enterprise SaaS & Hosted Platforms

Below is a curated comparison of leading commercial Demand Response, DERMS, and VPP aggregation platforms.

| 🏢 Platform | 💰 Pricing Tier | 🎁 Free Tier / Trial Limit | 📊 Company Size (Valuation / Revenue) | 📝 Key Capabilities & Focus |
| :--- | :--- | :--- | :--- | :--- |
| **[Enel X](https://www.enelx.com/)** | Custom Enterprise (Paid on grid earnings share / capacity payments) | 14-Day Enterprise Demo; no free tier | **$70B+ (Parent Enel Group Valuation) / $100B+ Revenue** | Largest global DR aggregator and VPP operator; orchestrates commercial & industrial flexible load across global energy markets. |
| **[Uplight](https://uplight.com/)** | Custom Utility Enterprise ($50,000+/yr base utility platform fees) | Custom Sandbox Demo upon request; no free plan | **$1.5B Valuation (Unicorn) / $150M+ Est. Revenue** | Comprehensive utility demand stack; manages 8.5 GW of flexible DER capacity across 80+ major utilities with edge control. |
| **[AutoGrid](https://www.auto-grid.com/)** | Enterprise SaaS (Starts ~$30,000/yr per MW program size) | 30-Day Utility Pilot Sandbox; no free tier | **Acquired by Schneider Electric ($80B+ valuation)** | AI-driven AutoGrid Flex™ platform powering real-time dispatch, peak load shaving, and behavioral DR programs worldwide. |
| **[CPower](https://cpowerenergy.com/)** | Performance Revenue Share (No upfront cost; revenue split on grid earnings) | 30-Day Site Energy Audit & Onboarding Evaluation | **$250M+ Revenue / PE-backed (LS Power)** | Leading US VPP platform managing 6.3+ GW capacity across 20,000 sites; delivered over $1B in grid revenue payouts to clients. |
| **[EnergyHub](https://www.energyhub.com/)** | Enterprise Utility SaaS ($25,000+/yr baseline utility contracts) | Demonstration Sandbox for Utilities; no free plan | **Acquired by Alarm.com ($3B+ Valuation)** | Leading residential DERMS connecting smart thermostats, EVs, and home batteries into utility grid service programs. |
| **[Voltus](https://www.voltus.co/)** | Shared Savings Model (0 upfront fee; ~20-30% share on DR revenues) | 14-Day DR Revenue Estimate Audit; no free tier | **$1B Valuation / ~$50M Est. Revenue** | C&I demand response aggregator operating across all North American ISO/RTO wholesale electricity markets. |
| **[GridBeyond](https://gridbeyond.com/)** | Custom SaaS / Shared Savings (Starts ~$15,000/yr for facility DR) | 30-Day ViewPoint Lens Trial Audit | **$300M+ Valuation / $45M+ Series C Funding** | AI-driven platform creating digital twins of industrial sites for automated wholesale DR dispatch and frequency response. |
| **[Leap](https://www.leap.energy/)** | API Platform Fee + Revenue Share (Starts ~$1,000/mo API access) | 30-Day Developer API Sandbox (Up to 10 test devices) | **$150M+ Valuation / $33M+ Venture Funding** | Software-only universal VPP API enabling smart home and building automation vendors to monetize energy flexibility. |
| **[Virtual Peaker](https://www.virtual-peaker.com/)** | Utility SaaS ($12,000/yr minimum per utility DR program) | 14-Day Utility Demo Account; no free tier | **$50M+ Valuation / $15M+ Funding** | Cloud-native DER management platform designed for public power utilities and electric cooperatives. |

---

## 🔓 Open-Source GitHub Projects

Demand Response Management features a vibrant open-source ecosystem, particularly for optimization modeling, microgrid energy management (EMS), and distribution market simulation.

*Sorted by GitHub Star Count (Descending)*

| 📦 Repository & Link | ⭐ Stars | 🛠️ Category | 📝 Description & Stack |
| :--- | :---: | :--- | :--- |
| **[PyPSA](https://github.com/pypsa/pypsa)** | [<img src="https://img.shields.io/github/stars/pypsa/pypsa?style=social&color=white" alt="PyPSA Stars"/>](https://github.com/pypsa/pypsa/stargazers) | Grid Simulation | **Python for Power System Analysis.** Open-source toolbox for simulating and optimizing modern power systems with high shares of variable renewables and demand-side flexibility. |
| **[OpenEMS](https://github.com/OpenEMS/openems)** | [<img src="https://img.shields.io/github/stars/OpenEMS/openems?style=social&color=white" alt="OpenEMS Stars"/>](https://github.com/OpenEMS/openems/stargazers) | Energy Management | **Modular Open-Source Energy Management System.** Reference EMS implementation with EEBus/jEEBus integration, BSI-compliant control signals (§14a EnWG), and microgrid control capabilities. |
| **[OpenStudio](https://github.com/NREL/OpenStudio)** | [<img src="https://img.shields.io/github/stars/NREL/OpenStudio?style=social&color=white" alt="OpenStudio Stars"/>](https://github.com/NREL/OpenStudio/stargazers) | Building Energy Model | **NREL Cross-Platform Building Energy Modeling Toolkit.** Supports demand-response controls, load shifting, and dynamic thermal storage simulation in buildings. |
| **[EVerest Core](https://github.com/EVerest/everest-core)** | [<img src="https://img.shields.io/github/stars/EVerest/everest-core?style=social&color=white" alt="EVerest Core Stars"/>](https://github.com/EVerest/everest-core/stargazers) | EV Smart Charging | **LF Energy EVerest.** Complete software stack for EV charging infrastructure supporting ISO 15118, OCPI, and smart charging DR signals. |
| **[GridLab-D](https://github.com/gridlab-d/gridlab-d)** | [<img src="https://img.shields.io/github/stars/gridlab-d/gridlab-d?style=social&color=white" alt="GridLab-D Stars"/>](https://github.com/gridlab-d/gridlab-d/stargazers) | Distribution Grid | **Power Distribution Simulation Tool.** Developed by US DOE/PNNL to simulate end-use demand response, smart metering, and distributed generation control. |
| **[FlexMeasures](https://github.com/FlexMeasures/flexmeasures)** | [<img src="https://img.shields.io/github/stars/FlexMeasures/flexmeasures?style=social&color=white" alt="FlexMeasures Stars"/>](https://github.com/FlexMeasures/flexmeasures/stargazers) | Energy Flexibility | **LF Energy Platform for Demand Response.** "Lego Mindstorms" for smart energy planning—provides real-time forecasting, scheduling, and optimization for behind-the-meter assets. |
| **[DPSim](https://github.com/sogno-platform/dpsim)** | [<img src="https://img.shields.io/github/stars/sogno-platform/dpsim?style=social&color=white" alt="DPSim Stars"/>](https://github.com/sogno-platform/dpsim/stargazers) | Real-time Simulator | **Dynamic Power System Simulator.** Part of LF Energy SOGNO project, simulating complex real-time grid response and VPP dynamic interactions. |
| **[DRAF](https://github.com/DrafProject/draf)** | [<img src="https://img.shields.io/github/stars/DrafProject/draf?style=social&color=white" alt="DRAF Stars"/>](https://github.com/DrafProject/draf/stargazers) | Decision Support | **Demand Response Analysis Framework.** MILP-based optimization framework using Pyomo/Gurobi for multi-energy hubs, battery storage, heat pumps, and EV fleets. |
| **[OpenGridGym](https://github.com/OpenGridGym/OpenGridGym)** | [<img src="https://img.shields.io/github/stars/OpenGridGym/OpenGridGym?style=social&color=white" alt="OpenGridGym Stars"/>](https://github.com/OpenGridGym/OpenGridGym/stargazers) | Market Simulation | **Open AI Toolkit for Distribution Markets.** PyTorch & OpenDSS-backed Gym environment for research on peer-to-peer electricity markets and AI-driven DR. |
| **[DDQN for Smart Grid DR](https://github.com/ShafaghAPashaki/Capacity-constrained-demand-response-in-smart-grid-using-deep-reinforcement-learning)** | [<img src="https://img.shields.io/github/stars/ShafaghAPashaki/Capacity-constrained-demand-response-in-smart-grid-using-deep-reinforcement-learning?style=social&color=white" alt="DDQN DR Stars"/>](https://github.com/ShafaghAPashaki/Capacity-constrained-demand-response-in-smart-grid-using-deep-reinforcement-learning/stargazers) | RL Research | **Double Deep Q-Network for Demand Response.** PyTorch implementation for capacity-constrained incentive demand response optimization in smart grids. |

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Help us expand this curated list of Demand Response & VPP tools:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` following the standard table formatting.
3. 🔍 Ensure pricing, free-tier limits, and star badges are accurate and formatted correctly.
4. 📬 Submit a **Pull Request** with a brief summary of your changes.

---

## ⚠️ Disclaimer

- This list is community-curated for informational and educational purposes.
- Demand response and grid management software involves compliance with energy regulators (FERC, NERC, ENTSO-E). Always verify official product documentation and security certifications before enterprise deployment.

---

## 💖 Support

If you find this repository helpful for your energy engineering, grid research, or VPP project, please consider supporting the project!

- ⭐ **Star** this repository to show your appreciation.
- 🔀 **Fork** and share it with fellow energy professionals and researchers.
- ☕ **Sponsor / Buy me a coffee**: Support ongoing open-source maintenance via [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Demand-Response-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Demand-Response-Management&type=date&legend=top-left)
