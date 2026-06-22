<div align="center">

<img src="./assets/banner.svg" alt="Awesome PDKs Banner" width="800">

# 🚀 Awesome-PDKs
### 🌟 Top Open-Source PDKs & Tools Ecosystem

[![Awesome](https://awesome.re/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

**Curated List of Commercial & Open-Source Process Design Kits & EDA Tools**  
*Focused on Semiconductor Manufacturing & Chip Design*  
**Last updated: March 2026**

</div>

This repository tracks notable **commercial PDKs** and **open-source projects** for **Process Design Kits (PDKs)** and related EDA tools. These resources enable chip designers to create physical layouts, simulate performance, and prepare designs for fabrication across various technology nodes.

**Examples** include TSMC N3, Intel 16, Samsung 4LPP, Tower Semiconductor SBC18 (commercial) and SkyWater SKY130, GlobalFoundries GF180MCU, IHP SG13G2 (open-source leaders). Tools listed here emphasize **open access**, reproducibility, and support for analog, digital, and mixed-signal design.

**Open-source emphasis**: This section is heavily expanded with every major active open-source PDK and EDA tool for self-hosting, local development, full customization, and academic/independent chip fabrication — ideal for researchers, startups, and open-source hardware communities.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📚 Table of Contents
- [Commercial / Proprietary PDKs](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## 💼 Commercial / Proprietary PDKs

### 🏭 Major Foundry PDKs

| Product | Description | Pricing | Free Tier Limit | Company Size (Market Cap) |
|---------|-------------|---------|-----------------|---------------------------|
| **[TSMC N3 (3nm Node)](https://tsmc.com/)** | Industry-leading advanced node PDK for high-performance, low-power chip design. | Custom / NDA | N/A | ~$700B+ |
| **[Samsung 4LPP (4nm Low Power Plus)](https://semiconductor.samsung.com/)** | Advanced low-power process optimized for mobile and high-efficiency applications. | Custom / NDA | N/A | ~$350B+ |
| **[Intel 16 (16nm Node)](https://intel.com/)** | Mature and widely available process for high-volume digital and mixed-signal designs. | Custom / NDA | N/A | ~$180B+ |
| **[Tower Semiconductor SBC18 (0.18µm Node)](https://towersemi.com/)** | Reliable specialty process for analog, power management, and RF designs. | Custom / NDA | N/A | ~$3.5B+ |

### 🔬 Advanced Nodes

**Other notable mentions**: GlobalFoundries, UMC, and various specialty process nodes.

## 🌐 Open-Source GitHub Projects

### 🛠️ Dedicated Open PDKs & EDA Tools

- **[SkyWater SKY130 (130nm Node)](https://github.com/google/skywater-pdk)** [![GitHub stars](https://img.shields.io/github/stars/google/skywater-pdk?style=social&color=white)](https://github.com/google/skywater-pdk/stargazers)  
  The most popular open-source PDK, developed in collaboration with Google and SkyWater Technology. Fully manufacturable and widely used for open-source chip tapeouts.

- **[OpenLane](https://github.com/The-OpenROAD-Project/OpenLane)** [![GitHub stars](https://img.shields.io/github/stars/The-OpenROAD-Project/OpenLane?style=social&color=white)](https://github.com/The-OpenROAD-Project/OpenLane/stargazers)  
  End-to-end open-source RTL-to-GDSII flow based on OpenROAD, widely used with SkyWater SKY130.

- **[KLayout](https://github.com/KLayout/klayout)** [![GitHub stars](https://img.shields.io/github/stars/KLayout/klayout?style=social&color=white)](https://github.com/KLayout/klayout/stargazers)  
  High-performance open-source layout viewer and editor with excellent scripting support for PDK development.

- **[OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD)** [![GitHub stars](https://img.shields.io/github/stars/The-OpenROAD-Project/OpenROAD?style=social&color=white)](https://github.com/The-OpenROAD-Project/OpenROAD/stargazers)  
  Complete open-source RTL-to-GDSII flow for automated chip design, tightly integrated with open PDKs.

- **[Caravel](https://github.com/efabless/caravel)** [![GitHub stars](https://img.shields.io/github/stars/efabless/caravel?style=social&color=white)](https://github.com/efabless/caravel/stargazers)  
  Open-source SoC harness and management framework for MPW (Multi-Project Wafer) shuttles.

- **[Magic VLSI](https://github.com/RTimothyEdwards/magic)** [![GitHub stars](https://img.shields.io/github/stars/RTimothyEdwards/magic?style=social&color=white)](https://github.com/RTimothyEdwards/magic/stargazers)  
  Classic open-source VLSI layout tool with strong support for open PDKs and interactive editing.

- **[GlobalFoundries GF180MCU (180nm Node)](https://github.com/google/gf180mcu-pdk)** [![GitHub stars](https://img.shields.io/github/stars/google/gf180mcu-pdk?style=social&color=white)](https://github.com/google/gf180mcu-pdk/stargazers)  
  Open-source PDK for 180nm process, suitable for analog, mixed-signal, and IoT designs.

- **[efabless Open PDK](https://github.com/efabless/open_pdks)** [![GitHub stars](https://img.shields.io/github/stars/efabless/open_pdks?style=social&color=white)](https://github.com/efabless/open_pdks/stargazers)  
  Community-driven open PDK initiatives and shuttle programs built on SkyWater technology.

- **[Analog Circuit Tools (xschem, ngspice)](https://github.com/StefanSchippers/xschem)** [![GitHub stars](https://img.shields.io/github/stars/StefanSchippers/xschem?style=social&color=white)](https://github.com/StefanSchippers/xschem/stargazers)  
  Open-source schematic capture and simulation tools commonly used with open PDKs.

- **[IHP SG13G2 (130nm Node)](https://github.com/IHP-GmbH/IHP-SG13G2)** [![GitHub stars](https://img.shields.io/github/stars/IHP-GmbH/IHP-SG13G2?style=social&color=white)](https://github.com/IHP-GmbH/IHP-SG13G2/stargazers)  
  High-performance open-source BiCMOS PDK from IHP for RF and high-speed applications.

### 🔧 Additional Strong Open-Source Options

- **[IHP Open PDK](https://github.com/IHP-GmbH)** — Additional IHP process nodes and tools.
- **[GlobalFoundries Open PDK variants](https://github.com/google)** — Community maintained extensions.
- **[Alliance CAD](https://github.com/Alliance-CAD)** — Complete open-source VLSI design suite.
- **[Coriolis](https://github.com/tas-y/pdk)** — Open-source physical design tools.
- **[Spice simulators** (ngspice, Xyce) with PDK support.
- Many community **Sky130** forks, custom cells, and educational PDK projects.

**Recommended Toolchains**: **OpenROAD + OpenLane** with **SkyWater SKY130** for full open-source chip design from RTL to GDSII.

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Open PDKs may have usage restrictions for commercial tapeouts. Always check foundry shuttle programs and licenses.
- Chip fabrication involves significant costs even with open PDKs.

---

**Made for chip designers, hardware engineers, researchers, and open-source silicon enthusiasts.**  
Let's make semiconductor design more accessible, transparent, and open.