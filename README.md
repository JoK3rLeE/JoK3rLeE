<!--
  GitHub Profile README
  Maintainer: JoK3rLeE
-->

<div align="center">

  <img src="https://github.com/JoK3rLeE/JoK3rLeE/blob/main/img/HelloThere.png" alt="Hello there" width="100%" />

  # Jason Jiang Yee
  ### Android Platform • Linux Kernel • Embedded Systems

  **Independent Android developer focused on keeping capable hardware alive through low-level software engineering.**

  <p>
    <a href="https://github.com/JoK3rLeE"><img src="https://img.shields.io/badge/GitHub-JoK3rLeE-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
    <a href="https://github.com/JoK3rLeE?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Explore-2ea44f?style=for-the-badge&logo=github" alt="Repositories" /></a>
  </p>

</div>

---

## 👨‍💻 About Me

Hi, I'm **Jason**, also known as **[@JoK3rLeE](https://github.com/JoK3rLeE)**.

I work primarily on Android platform development and Linux kernel engineering, with a particular focus on Qualcomm-based Xiaomi devices. My ongoing work revolves around the **Xiaomi Mi 9 (cepheus)** and its **Snapdragon 855 / SM8150** platform.

I enjoy working below the application layer: understanding hardware interfaces, adapting kernel subsystems, maintaining device configurations, debugging platform issues, and bringing newer Android releases to aging hardware.

My approach is engineering-led: investigate the underlying implementation, keep changes traceable, and validate functionality on real hardware wherever possible.

## 🛠️ Technical Focus

| Area | Focus |
|---|---|
| **Linux Kernel** | Qualcomm SM8150, kernel development, subsystem integration, driver work and backports |
| **Android Platform** | Android bring-up, device configuration, framework and hardware integration |
| **Device Trees** | Xiaomi device trees, common platform configuration, product and vendor integration |
| **Kernel Security** | KernelSU Next, SUSFS integration, SELinux policy and security-related changes |
| **Hardware Support** | Touchscreen, fingerprint / FOD, display, charging, NFC and other device interfaces |
| **Display Engineering** | Panel configuration, refresh-rate experiments, HBM and DC-dimming integration |
| **Recovery** | Custom recovery device configuration and maintenance |

## 📱 Main Platform — Xiaomi Mi 9 (cepheus)

The Mi 9 is the primary device behind much of my Android development work.

| Component | Platform |
|---|---|
| Device | Xiaomi Mi 9 — `cepheus` |
| SoC | Qualcomm Snapdragon 855 |
| Platform | Qualcomm SM8150 |
| CPU | Qualcomm Kryo 485 |
| GPU | Adreno 640 |
| Display | 6.39-inch AMOLED, 1080 × 2340 |

### Main Development Repositories

| Project | Description | Branch |
|---|---|---|
| [Linux Kernel — SM8150](https://github.com/JoK3rLeE/android_kernel_xiaomi_sm8150) | Main Mi 9 kernel development tree | `17-ksun` |
| [Mi 9 Device Tree](https://github.com/JoK3rLeE/android_device_xiaomi_cepheus) | Device-specific Android configuration | `17.0` |
| [SM8150 Common Device Tree](https://github.com/JoK3rLeE/device_xiaomi_sm8150-common) | Shared platform configuration | `17.0` |
| [Mi 9 Device Tree (legacy)](https://github.com/JoK3rLeE/device_xiaomi_cepheus/tree/sixteen) | Earlier device configuration line | `sixteen` |
| [Mi 9 Vendor](https://github.com/JoK3rLeE/proprietary_vendor_xiaomi_cepheus) | Proprietary device blobs | See repository |
| [SM8150 Common Vendor](https://github.com/JoK3rLeE/vendor_xiaomi_sm8150-common) | Shared proprietary platform components | See repository |
| [Xiaomi Hardware](https://github.com/JoK3rLeE/hardware_xiaomi) | Xiaomi-specific hardware interfaces and components | `cnb` |
| [Frameworks Native](https://github.com/JoK3rLeE/frameworks_native) | Android native framework work | `17` |

### Kernel Development

My kernel work focuses on maintaining and extending the SM8150 platform, including:

- Kernel maintenance and adaptation for newer Android platform releases.
- Driver and hardware-interface debugging for the Xiaomi Mi 9.
- KernelSU Next and SUSFS-related integration and compatibility work.
- SELinux and platform security policy investigation.
- Display, touchscreen, fingerprint and charging subsystem improvements.
- Evaluating upstream changes, backports and cross-device implementations.

**Kernel source:** [android_kernel_xiaomi_sm8150](https://github.com/JoK3rLeE/android_kernel_xiaomi_sm8150)

> Development status varies by feature and branch. Experimental work should not be assumed to be production-ready.

## 🔬 Other Projects

| Repository | Description |
|---|---|
| [SM8150 Kernel — 5.4](https://github.com/JoK3rLeE/kernel_xiaomi_sm8150-5.4) | Kernel 5.4 platform development and porting work |
| [CAF MSM 5.4](https://github.com/JoK3rLeE/caf_msm-5.4) | Qualcomm CAF kernel source |
| [OrangeFox / Recovery Tree](https://github.com/JoK3rLeE/twrp_cepheus) | Custom recovery device tree for cepheus |
| [AnyKernel3](https://github.com/JoK3rLeE/AnyKernel3) | Kernel packaging and installation tooling |

## 📦 ROM Builds

Some of my device builds and releases are archived on SourceForge:

- **Project Infinity X — Xiaomi Mi 9:** [Download archive](https://sourceforge.net/projects/device-xiaomi-cepheus/files/infinity-x/)
- **Evolution X — Xiaomi Mi 9:** [Download archive](https://sourceforge.net/projects/device-xiaomi-cepheus/files/17.0/)

Build availability and maintenance status are determined by the respective release pages. These links are provided as project history and download references, not as a guarantee of current support.

## 🧰 Tools & Technologies

<div align="center">

  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Qualcomm-3253DC?style=flat-square&logo=qualcomm&logoColor=white" alt="Qualcomm" />
  <img src="https://img.shields.io/badge/ARM64-0091BD?style=flat-square&logo=arm&logoColor=white" alt="ARM64" />

</div>

## 📊 GitHub Activity

<div align="center">

  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JoK3rLeE&show_icons=true&hide_border=true&rank_icon=github" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JoK3rLeE&layout=compact&hide_border=true" alt="Most used languages" />

  <br />

  <img src="https://streak-stats.demolab.com?user=JoK3rLeE&hide_border=true" alt="GitHub contribution streak" />

</div>

## 🤝 Collaboration

I'm interested in collaborating on:

- Android device bring-up and maintenance.
- Qualcomm kernel development and subsystem debugging.
- Device tree, vendor and hardware integration.
- Kernel security and compatibility work.
- Reviving and extending support for older Android devices.

Feel free to explore my repositories, review the code, or open an issue or pull request on the relevant project.

---

<div align="center">

  **Thanks for visiting. Build, break, understand, improve.**

  <sub>Maintained by Jason Jiang Yee · <a href="https://github.com/JoK3rLeE">@JoK3rLeE</a></sub>

</div>
