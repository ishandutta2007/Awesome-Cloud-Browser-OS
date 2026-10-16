# Awesome-Cloud-Browser-OS

## Top Cloud Browser OS Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Browser-Based Desktops, Cloud Workstations & Web-Native Operating Systems*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Browser OS**. These tools enable users to access a complete desktop environment—file manager, applications, storage, and development tools—entirely from a web browser, without installing anything on the local device.



**Examples** include Windows 365, Citrix, VMware Horizon, Amazon WorkSpaces, Microsoft Azure Virtual Desktop, Nutanix Frame, Parallels RAS, Kasm Workspaces, Shells, and Paperspace (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, browser-based desktops, and web-native operating systems—ideal for developers, system administrators, and organizations seeking transparent, vendor-independent cloud desktop infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Company / Parent | Company Size (Market Cap / Valuation / Revenue) | Pricing | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Windows 365](https://www.microsoft.com/en-us/windows-365)** | Microsoft | ~$3.1T Market Cap / $245B+ Annual Revenue | Starts at $28.00/user/month (Business tier, 2 vCPU / 4 GB RAM / 64 GB storage) | 30-day free trial; limited to 1 Cloud PC per tenant across select trial SKUs (max 300 users for Business edition) | Microsoft's Cloud PC service delivering full Windows desktops to any device via browser or Remote Desktop app. Integrated with Intune and Entra ID. |
| **[Microsoft Azure Virtual Desktop](https://azure.microsoft.com/en-us/products/virtual-desktop/)** | Microsoft | ~$3.1T Market Cap / $245B+ Annual Revenue | $0 user access fee with existing M365/Windows enterprise license (or $5.50/user/mo app-only, $10.00/user/mo desktop access for external users) + Azure consumption (starts ~$10–$15/user/month multi-session) | 30-day Azure Free Trial with $200 in Azure credits to provision session hosts, compute, and storage | Cloud VDI service offering multi-session Windows 10/11, FSLogix profile management, and App Attach for MSIX packaging. |
| **[Amazon WorkSpaces](https://aws.amazon.com/workspaces/)** | Amazon (AWS) | ~$2.0T Market Cap / $575B+ Annual Revenue | Starts at $21.00/user/month (AlwaysOn Linux) or $7.25/month + $0.22/hour (AutoStop metered); Windows bundles start at $28.00/month or $9.75/month + $0.30/hour | 3 billing cycles free trial; includes up to 2 Standard bundle WorkSpaces with 80 GB root / 50 GB user storage, capped at 40 hours of combined monthly usage | Fully managed desktop-as-a-service on AWS with Windows and Linux options, WorkSpaces Web browser access, and WorkSpaces Core. |
| **[VMware Horizon](https://www.vmware.com/products/horizon.html)** | Broadcom | ~$850B Market Cap / $50B+ Annual Revenue | Starts at ~$8.25/user/month (Horizon Apps / Term subscription, billed annually) | 60-day to 90-day evaluation trial (license key provided via Broadcom portal for non-production PoC testing) | Virtual desktop and application delivery platform featuring Horizon Cloud on Azure, App Volumes, and Dynamic Environment Manager. |
| **[Citrix Workspace](https://www.citrix.com/)** | Cloud Software Group (Vista & Evergreen) | ~$16.5B Private Acquisition Valuation / ~$3.2B Annual Revenue | Starts at ~$10.00/user/month (Citrix DaaS Standard via Cloud Marketplace, annual commitment) | 60-day trial for Citrix Cloud / DaaS capped at 25 end users | Enterprise workspace platform delivering virtual apps and desktops with HDX protocol optimization and zero-trust access controls. |
| **[Nutanix Frame](https://www.nutanix.com/products/frame)** | Nutanix | ~$14.5B Market Cap / ~$2.1B Annual Revenue | Starts at ~$24.00–$30.00/user/month (1-year term commitment or PAYG with 5-user minimum) | 30-day free trial (up to $25 in hosted infrastructure consumption or BYO cloud account on Azure/AWS/GCP) | Browser-based DaaS delivering Windows and Linux desktops without client installation. |
| **[Parallels RAS](https://www.parallels.com/products/ras/)** | Alludo (formerly Corel / KKR portfolio) | ~$1B+ Valuation (acquired by KKR) / ~$300M+ Annual Revenue | Starts at $99.99/concurrent user/year (~$8.33/concurrent user/month equivalent) | 30-day free trial with full feature access for up to 50 concurrent users | Application and virtual desktop delivery platform featuring HTML5 browser client and native client support across platforms. |
| **[Paperspace](https://www.paperspace.com/)** | DigitalOcean | ~$3.5B Market Cap / ~$750M+ Annual Revenue | Starts at $0.0045/hour (CPU Core instances) or $0.45/hour (GPU instances) + storage starting at $5.00/month; Gradient ML has a free tier | Free plan on Paperspace Gradient with 5 GB persistent storage, free CPU/entry GPU, capped at 6-hour runtime sessions (Core desktops have no free tier) | Cloud computing and GPU-accelerated virtual desktops featuring Gradient for ML workflows and Core for persistent virtual machines. |
| **[Kasm Cloud](https://kasm.com/)** | Kasm Technologies | ~$9.6M Estimated Private Valuation / ~$3M Annual Revenue | Starts at $10.00/month (Cloud Browser tier, 100 hrs/month) or $20.00/month (Cloud Desktop tier, 200 hrs/month) | Self-hosted Kasm Community Edition is free forever for up to 5 concurrent sessions; Cloud service has no free tier (entry paid plan starts at $10/mo) | Managed cloud streaming containerized browsers, desktops, and apps via web browser with SOC 2 Type II attestation. |
| **[Shells](https://shells.com/)** | Shells.com Inc. | ~$2.4M Venture Funding Raised / Early-Stage Startup | Starts at $4.95/month (Shells Lite plan, 10 hours/month) or $14.95/month (Basic plan, unlimited usage) | 7-day money-back guarantee with test run entry tier (Lite plan at $4.95 for 10 hours); no perpetual free tier | Personal cloud desktop provider offering browser-based access, persistent storage, and Linux/Windows environments. |



## Open-Source GitHub Projects



- **[Puter](https://github.com/HeyPuter/puter)**  

  **The Internet OS! Free, Open-Source, and Self-Hostable** (AGPL-3.0) . **The most widely adopted open-source cloud desktop**—**40,000+ GitHub stars**, **370 community contributors**, and **400,000+ downloads** . **Puter is a cloud operating system that runs in your browser**, providing a full desktop experience without installation . **Features**: **privacy-first approach**, **seamless cloud storage with file management** (Explorer app resembles Nautilus from GNOME), **app store with handcrafted apps** (Notepad, Spreadsheet, Camera, Voice Recorder, Terminal, Code editor, Judge0 IDE), **AI functionality baked into the terminal**, **static site hosting with free subdomains** (`puter.site`) . **Puter.js** enables developers to add **AI, databases, cloud storage, and serverless workers** to web apps without API keys or backend infrastructure . **Self-hosting via one-line command**: `curl -fsSL https://puter.com/selfhost | sh` (Linux/macOS) or `irm https://puter.com/selfhost?os=windows | iex` (Windows) . **The reference implementation for browser-based cloud operating systems** .



- **[Slime OS](https://github.com/mulai/slimeos)**  

  **Open Source, Cloud-First Operating System** (open-source) . **The most hardened open-source cloud OS architecture**—**three-component design**: **The Membrane** (hardened minimal Debian Linux local layer, boots cage/Wayland → FreeRDP stream, zero local user storage), **The Brain** (cloud VMs serving Windows xRDP or Linux desktops, wrapped in **WireGuard + Authelia zero-trust security**, deployable on AWS, GCP, or any VPS), and **The App** (Android launcher APK for legacy smartphones, Phase 2) . **Quickstart**: Flash Debian 13 netinstall to USB, boot with preseed URL for automated install, then deploy the Brain via Docker Compose on any Linux host (Ubuntu 22.04 LTS recommended) . **Only public ports required are UDP 51820 (WireGuard) and TCP 443 (HTTPS)**—RDP never touches the public internet . **The most security-focused open-source cloud desktop architecture** for legacy hardware recycling.



- **[Kasm Workspaces Community Edition](https://kasm.com/community-edition)**  

  **Open-source web-native rendering technology for digital workspaces** (open-source) . **All Workspaces images and container streaming technology available on Docker Hub and GitHub** . **Partners with Metasploit and Spiderfoot** for security tooling . **The most mature open-source containerized desktop streaming platform**—used by security professionals for covert communication channels and OSINT research .



- **[PC2 (Elacity)](https://github.com/Elacity/pc2.net)**  

  **The Internet OS! Free, Open-Source, and Self-Hostable** (open-source) . **The most cost-effective open-source cloud OS**—**runs on Raspberry Pi for $130 one-time hardware plus $24/year electricity** vs. Google Drive ($120/year) or Dropbox ($144/year forever) . **ROI: break even at 15 months, save $96/year thereafter** . **Key differentiation**: **WASM runs on YOUR node** (not their cloud), **your keys = your access, always**, **wallet IS your identity** . **Requirements**: Node.js 20.19+, 2GB RAM minimum (4GB recommended), 10GB storage . **The most sovereign open-source cloud OS** for users who want full ownership of their digital life.



- **[Vulos OS](https://github.com/vul-os/vulos)**  

  **Sovereign, web-native personal operating system** (open-source) . **The OS is the shell**—one React window-manager desktop is the whole surface, local or remote. **Native-first dispatch** routes every launch through five lanes: **web app** (host browser, ~zero server cost), **CPU app stream** (Xvfb + WebRTC), **GPU route** (BYO GPU peer), **compute worker** (batch), and **local-only** . **Reachability via a relay you choose**—the built-in **Vulos relay** by default, or **Pier**, an open self-hostable broker . **Backend is a single Go binary** embedding the React/JSX shell . **The most architecturally modern open-source cloud OS**—"You self-provision. Vulos does not host or run boxes for you—it is free, open-source software you run on your own hardware or a VPS you rent" .



- **[Open Web Desktop (OWD)](https://github.com/owdproject/client)**  

  **A framework for building web-based desktop experiences** (GPL-3) . **Built with TypeScript on Nuxt.js**. **Fully extendable through themes, apps, and modules**—bundled with **Pinia, VueUse, Mitt**, styled with **PrimeVue and Tailwind**, and **fully localizable with i18n support** . **Quick start**: `npm create owd` . **Themes available** ranging from popular OS designs (GNOME) to fully custom creations . **The most framework-friendly open-source web desktop** for developers who want to build custom cloud desktops with modern web tooling.



- **[OS.js Web Desktop](https://github.com/AnEntrypoint/osjs-webdesktop)**  

  **Complete, production-ready web desktop environment built on OS.js v3** (MIT) . **Features**: **full window manager** (draggable, resizable windows), **desktop icons**, **taskbar panel**, **mobile responsive**, **comprehensive file manager** with multiple view modes, **text editor and calculator**, and **polymorphic session system** (capture and restore entire desktop state as JSON) . **Session management**: `Ctrl+Shift+S` to download current session, `Ctrl+Shift+O` to upload and restore . **Technology stack**: Hyperapp, Webpack 5, Node.js with Express, connect-loki session storage . **The most complete open-source OS.js implementation** with production-ready session persistence.



- **[Gooroom Platform](https://gooroom.kr/)**  

  **Debian-based Linux distribution designed for cloud computing** (open-source) . **The most security-focused cloud browser platform**—**separate browser processes based on access source** (trusted/untrusted browsers), **Chromium security policies** (download blocking, URL blocking), and **cloud central management** . **Developed by the Ministry of Science and ICT and the National Security Research Institute** (South Korea) . **The most government-grade open-source cloud browser**—stores all data in cloud storage and utilizes web-based application services instead of locally installed software .



### Additional Strong Open-Source Options



- **[Web Desktop Environment (shmuelhizmi)](https://github.com/shmuelhizmi/web-desktop-environment)** — Web-based cross-platform desktop environment (open-source) . **275 GitHub stars, 45 forks** . **Note**: OpenSSF scorecard 3.1/10—review security posture before production use .

- **[Open Web Desktop Themes](https://github.com/topics/owd-themes)** — Community themes for OWD including GNOME and custom designs .

- Community **n8n** workflows for cloud desktop session automation and resource monitoring.



**Frameworks for building custom systems**: Combine **Puter** for the most feature-complete browser-based cloud OS with **Slime OS** for hardened zero-trust architecture, **Kasm Workspaces** for containerized desktop streaming, **PC2** for Raspberry Pi-based sovereign cloud, and **Vulos OS** for sovereign web-native personal computing—creating a comprehensive cloud browser OS stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud browser OS platforms handling user data and credentials must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and encryption.

- **Open-source cloud browser OS is mature and production-ready.** Puter (40K+ stars, 400K+ downloads) provides the most feature-complete browser-based desktop with file management, app store, and static hosting . Slime OS provides hardened zero-trust architecture with WireGuard and Authelia . **These are genuine alternatives to Windows 365 and Amazon WorkSpaces.**

- **The sovereignty distinction matters.** PC2's model is "your keys = your access, always" with WASM running on your node, not their cloud . Vulos OS explicitly states "You self-provision. Vulos does not host or run boxes for you" . **Cloud-hosted services provide convenience; self-hosted provides ownership.**

- **Security architecture varies dramatically.** Slime OS's WireGuard + Authelia zero-trust design means "RDP never touches the public internet" . Gooroom's separate browser processes for trusted/untrusted sources provide defense-in-depth . **Open-source cloud OS platforms should be evaluated on security architecture, not just feature lists.**

- **Hardware requirements are real.** Puter requires Node.js 16+ (23+ recommended), 2GB RAM minimum (4GB recommended), and 10GB disk space . PC2 runs on Raspberry Pi with 2GB RAM minimum . **Self-hosting requires appropriate infrastructure.**

- Self-hosted open-source solutions require proper security hardening, network configuration, and ongoing maintenance. **Cloud desktops are access points to your data**—compromise here undermines everything else.
