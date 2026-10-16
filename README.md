# Awesome-Cloud-Browser-OS

# Top Cloud Browser OS Ecosystem

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

- **[Windows 365](https://www.microsoft.com/en-us/windows-365)**  
  Microsoft's Cloud PC service delivering full Windows desktops to any device via browser or Remote Desktop app. Integrated with Intune for management and Entra ID for identity.

- **[Citrix Workspace](https://www.citrix.com/)**  
  Enterprise workspace platform delivering virtual apps and desktops. Features **Citrix DaaS**, **HDX protocol** for optimized performance, and **zero-trust access controls**.

- **[VMware Horizon](https://www.vmware.com/products/horizon.html)**  
  Virtual desktop and app delivery platform. Features **Horizon Cloud on Azure**, **App Volumes**, and **Dynamic Environment Manager** for personalized workspaces.

- **[Amazon WorkSpaces](https://aws.amazon.com/workspaces/)**  
  Fully managed desktop-as-a-service (DaaS) on AWS. Features **Windows and Linux desktops**, **WorkSpaces Web** for browser-based access, and **WorkSpaces Core** for third-party VDI management.

- **[Microsoft Azure Virtual Desktop](https://azure.microsoft.com/en-us/products/virtual-desktop/)**  
  Microsoft's cloud VDI service with **multi-session Windows 10/11**, **FSLogix profile management**, and **App Attach** for MSIX packaging.

- **[Nutanix Frame](https://www.nutanix.com/products/frame)**  
  **Browser-based DaaS** delivering Windows and Linux desktops from any cloud. **The most browser-native commercial cloud desktop**—no client installation required.

- **[Parallels RAS](https://www.parallels.com/products/ras/)**  
  **Application and desktop delivery platform** with browser access. Features **HTML5 client** and **native client support** for all platforms.

- **[Kasm Cloud](https://kasm.com/)**  
  **Managed version of Kasm Workspaces**. Streams containerized browsers, desktops, and applications via web browser with **SOC 2 Type II attestation** .

- **[Shells](https://shells.com/)**  
  Personal cloud desktop provider. Features **browser-based access**, **persistent storage**, and **Linux/Windows environments**.

- **[Paperspace](https://www.paperspace.com/)**  
  Cloud computing platform with **GPU-accelerated virtual desktops**. Features **Gradient** for ML workloads and **Core** for virtual machines. Acquired by DigitalOcean.

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
