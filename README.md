# Sven Shi

<p align="center"><strong>Network & Backend Engineer · Rust DNS Infrastructure · OpenWrt / RouterOS Tooling</strong></p>

<p align="center">
  <img src="assets/profile-banner.svg" alt="Sven Shi profile banner" width="900" />
</p>

<p align="center">
  <em>Programmable DNS · Practical routing · Infrastructure that operators can trust</em>
</p>

<p align="center">
  <a href="mailto:isvenshi@gmail.com"><img src="https://img.shields.io/badge/Email-isvenshi%40gmail.com-0ea5e9?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/svenshi"><img src="https://img.shields.io/badge/GitHub-svenshi-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
</p>

<p align="center">
  <a href="#-oxidns-ecosystem">OxiDNS Ecosystem</a> ·
  <a href="#-engineering-focus">Engineering Focus</a> ·
  <a href="#-profile-snapshot">Profile Snapshot</a> ·
  <a href="#-connect">Connect</a>
</p>

---

## 👨‍💻 About Me

I build infrastructure tools for people who care about **network control**, **operational clarity**, and **systems that can be debugged under pressure**.

At the moment, my public work is centered on **OxiDNS**: a programmable DNS engine and its surrounding router-side tooling. I want the profile to make one thing obvious: I am interested in practical infrastructure, not toy demos.

**What I bring:**

- Deep interest in DNS, routing behavior, and network operations.
- Backend engineering experience for reliable APIs and maintainable services.
- A product-minded approach to operator experience: configuration, logs, deployment, and recovery matter.
- Willingness to cross layers when needed: Rust core, Java backend, shell automation, RouterOS / OpenWrt integration, and UI glue.

## 🧭 Open Source Direction

```text
Thesis           DNS can be a practical control plane for network behavior
Main users       Router / homelab / infrastructure operators who need transparent control
Current focus    OxiDNS engine, OpenWrt management, RouterOS routing workflows, repeatable builds
Design taste     Fast, explicit, debuggable, configuration-driven, and operator-friendly
```

---

## 🚀 OxiDNS Ecosystem

> Not isolated repos — a connected toolkit that goes from DNS decision-making to router deployment.

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/svenshi/oxidns">OxiDNS</a></h3>
      <p>A high-performance, programmable DNS engine in Rust with flexible pipeline-based routing.</p>
      <p><strong>Role:</strong> the core engine for DNS policy orchestration, network-aware routing, and production-oriented performance.</p>
      <p>
        <img src="https://img.shields.io/github/stars/svenshi/oxidns?style=social" alt="OxiDNS stars" />
        <img src="https://img.shields.io/github/downloads/svenshi/oxidns/total?color=0ea5e9" alt="OxiDNS downloads" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/svenshi/luci-app-oxidns">luci-app-oxidns</a></h3>
      <p>LuCI management app for running and managing OxiDNS on OpenWrt.</p>
      <p><strong>Role:</strong> makes OxiDNS easier to deploy, configure, and operate from router-oriented environments.</p>
      <p>
        <img src="https://img.shields.io/github/stars/svenshi/luci-app-oxidns?style=social" alt="luci-app-oxidns stars" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/svenshi/oxidns-bypass">oxidns-bypass</a></h3>
      <p>A practical traffic bypass and policy-routing solution based on OxiDNS and RouterOS.</p>
      <p><strong>Role:</strong> turns DNS decisions into a deployable network routing workflow for real RouterOS environments.</p>
      <p>
        <img src="https://img.shields.io/github/stars/svenshi/oxidns-bypass?style=social" alt="oxidns-bypass stars" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/svenshi/oxidns-build-template">oxidns-build-template</a></h3>
      <p>A build template for packaging and distributing OxiDNS more consistently.</p>
      <p><strong>Role:</strong> supports repeatable builds and lowers the friction for releasing or adapting OxiDNS deployments.</p>
    </td>
  </tr>
</table>

### Repository Curation

I intentionally keep the front page focused:

- **Showcase:** active infrastructure projects around **DNS**, **OpenWrt**, and **RouterOS**.
- **Support:** build templates and integration helpers that make the ecosystem easier to ship.
- **Hidden from the spotlight:** forks, archived repositories, experiments, and one-off utilities that do not represent my current technical direction.

---

## 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Shell" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
</p>

## 🎯 Engineering Focus

```text
Network Systems       DNS engines, policy routing, RouterOS / OpenWrt integration
Backend Engineering   Java / Spring Boot, API design, service reliability
Performance           Rust, efficient implementation, production-oriented tuning
Troubleshooting       Logs, stack traces, packet / routing behavior, root-cause analysis
Product Thinking      Operator experience, configuration clarity, maintainable workflows
```

## 🧩 How I Think About Tools

Good infrastructure software should be:

- **Explicit:** behavior should be visible from configuration and logs.
- **Composable:** small pieces should connect into real deployment workflows.
- **Operational:** easy to run, upgrade, debug, and recover.
- **Fast where it matters:** performance should support reliability, not just benchmarks.

---

## 📌 Profile Snapshot

```text
Identity         Network / backend engineer building operator-facing infrastructure
Primary theme    DNS infrastructure and practical network control
Main project     OxiDNS ecosystem
Languages        Rust, Java, JavaScript, Shell
Platforms        Linux, OpenWrt, RouterOS
Best fit         Network tooling, backend services, router-side integrations
```

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=svenshi&theme=tokyo-night&hide_border=true" alt="Sven's GitHub contribution graph" />
</p>

---

## 🤝 Connect

Good reasons to reach out:

- You are building or using DNS / router-side networking tools.
- You care about practical infrastructure, not just benchmark demos.
- You want to discuss OxiDNS, OpenWrt / RouterOS integration, or backend reliability.

📫 Email: [isvenshi@gmail.com](mailto:isvenshi@gmail.com) · 🐙 GitHub: [github.com/svenshi](https://github.com/svenshi)

<p align="center">
  <sub>Designed around clarity, control, and operational trust.</sub>
</p>