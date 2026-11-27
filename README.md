# Awesome-Macos-System-Monitoring-Performance-Analytics

## Top macOS System Monitoring & Performance Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Resource Tracking, Thermal Management & Storage Analytics*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **macOS System Monitoring & Performance Analytics**. These tools provide real-time visibility into CPU, GPU, memory, disk, network, battery, temperature, and fan metrics—helping users diagnose slowdowns, prevent overheating, and understand what their Mac is actually doing.

**Examples** include iStat Menus, CleanMyMac X, DaisyDisk, Sensei, Stats, Activity Monitor, TG Pro, Menubar Stats, Monity, MacBooster, and Jarvis322/macos-sysdata (the category leaders and notable projects).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted system monitoring, transparent performance analytics, and privacy-respecting menu bar utilities—ideal for power users, developers, and anyone who wants deep system visibility without subscriptions or telemetry.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[iStat Menus](https://bjango.com/mac/istatmenus/)**  
  The gold standard for macOS system monitoring, offering real-time CPU, GPU, memory, disk, network, temperature, fan, and battery data in a highly customizable menu bar interface; available via Setapp or direct purchase [citation:1][citation:9].

- **[CleanMyMac X](https://macpaw.com/cleanmyapp)**  
  All-in-one Mac utility that combines system monitoring with cleanup, malware removal, and performance optimization; includes real-time CPU, memory, and battery widgets in the menu bar.

- **[DaisyDisk](https://daisydiskapp.com/)**  
  Visual disk space analyzer that provides an interactive sunburst map of storage usage, making it easy to identify large files and folders for deletion.

- **[Sensei](https://cindori.com/sensei)**  
  Mac performance and optimization app with monitoring dashboards, hardware health tracking, and cleanup tools; available on Setapp Marketplace [citation:1].

- **[TG Pro](https://www.tunabellysoftware.com/tgpro/)**  
  Thermal management and fan control specialist for Macs, with comprehensive temperature sensor monitoring, automated fan rules, and overheating alerts; free version available, paid upgrade for advanced control [citation:1][citation:9].

- **[Activity Monitor](https://support.apple.com/guide/activity-monitor/)**  
  Apple's built-in system monitor for CPU, memory, energy, disk, and network usage; essential for basic diagnostics but limited in historical data and customization.

- **[Menubar Stats (by Marcel Dierkes)**  
  Lightweight menu bar monitor for CPU, memory, disk, and network activity; simpler than iStat Menus but sufficient for at-a-glance monitoring.

- **[Monity](https://www.monityapp.com/)**  
  Menu bar system monitor with customizable widgets for CPU, memory, disk, network, battery, and temperature; includes notification alerts for threshold breaches.

- **[MacBooster](https://www.macbooster.net/)**  
  Mac cleaning and optimization suite with system monitoring features, including real-time CPU, memory, and disk usage tracking alongside malware scanning and privacy tools.

- **[Jarvis322/macos-sysdata](https://github.com/Jarvis322/macos-sysdata)**  
  Menu bar app that exposes and deletes items inside macOS System Data storage item-by-item, showing every command before it runs; requires Full Disk Access for protected locations [citation:4][citation:12].

## Open-Source GitHub Projects

- **[Stats (exelban/stats)](https://github.com/exelban/stats)**  
  The most popular open-source macOS system monitor, providing CPU, GPU, memory, disk, network, battery, fan, and sensor modules in the menu bar; free, actively maintained, and compatible with macOS 12+ [citation:3][citation:9].

- **[AirStats](https://github.com/byrencheema/airstats)**  
  Ultra-lightweight menu bar monitor claiming 0.046% CPU usage, displaying CPU, memory, GPU, network, disk, battery, and thermals; includes a desktop widget and Homebrew installation [citation:7].

- **[MacMonitor](https://github.com/ryyansafar/MacMonitor)**  
  Apple Silicon-focused system monitor with menu bar and desktop widget, featuring per-core CPU tracking, GPU power via IOReport, thermal sensors, and battery health; requires a one-time privileged helper installation for power data [citation:11].

- **[Mectrics](https://github.com/farukkamcici/mectrics)**  
  Privacy-first menu bar monitor with alert rules, attention log, and a headless CLI for automation; includes CPU, memory, GPU, network, disk, battery, temperature, and fan monitoring with zero telemetry [citation:15].

- **[SysWatch](https://github.com/matthart1983/syswatch)**  
  Terminal-based system diagnostics tool for macOS and Linux, with tabbed views for CPU, memory, disks, processes, GPU, power, services, and network; supports session recording, replay, and anomaly insights .

- **[Vulcan](https://github.com/Gui-Oba/Vulcan)**  
  Real-time macOS system monitor with a web-based dashboard (FastAPI + React), featuring CPU heatmaps, network traffic geolocation, energy/carbon footprint estimation, and a digital twin visualization [citation:10].

- **[SystemPulse](https://pypi.org/project/systempulse/)**  
  Python-based CLI monitoring tool with live dashboard, snapshot, history, alerts, and Prometheus export; includes network speed testing and GPU support via nvidia-smi [citation:2].

- **[SysDock](https://pypi.org/project/sysdock/)**  
  Cross-platform terminal monitor with live dashboard, Docker container metrics, firewall status, and a built-in HTTP API; available as a native macOS app or via pipx [citation:6].

### Additional Strong Open-Source Options

- **[macOS-sysdata](https://github.com/Jarvis322/macos-sysdata)** — Already listed under SaaS for its release availability, but the source is open and Swift-based [citation:4].
- **htop / btop** — Terminal process viewers available via Homebrew, useful for lightweight CLI monitoring.
- **iStat Server** — Legacy remote monitoring server from Bjango (discontinued but archived).
- **powermetrics** — Apple's built-in CLI tool for detailed power and thermal data, often wrapped by GUI monitors.
- **asitop** — Python-based Apple Silicon power and thermal monitor using powermetrics under the hood.

**Frameworks for building custom systems**: Combine **Stats** or **AirStats** for menu bar visibility, **SysWatch** or **SystemPulse** for terminal-based diagnostics, **MacMonitor** if you need IOReport-level GPU power data, and **Prometheus + Grafana** for long-term metric collection via SystemPulse's exporter. For storage analysis, **DaisyDisk** is the commercial standard, while **du** and **ncdu** (Homebrew) serve as open CLI alternatives.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- System monitoring tools may request Accessibility, Full Disk Access, or privileged helper permissions; review what each app accesses before granting.
- Fan control features (especially in TG Pro and iStat Menus) are model-dependent and may not work reliably on all Apple Silicon Macs [citation:1][citation:9].
- Open-source projects vary in maintenance activity and macOS version compatibility; verify current support status before relying on them for critical diagnostics.

---

**Made for Mac power users, developers, IT administrators, and anyone who wants to understand their machine's behavior.**  
Let's make macOS system monitoring more open, transparent, and privacy-respecting.
