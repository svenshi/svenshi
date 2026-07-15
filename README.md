# Sven Shi

<p align="center"><strong>Network & Backend Engineer · Rust DNS Infrastructure · OpenWrt / RouterOS Tooling</strong></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:7c3aed&height=180&section=header&text=Sven%20Shi&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36" alt="Sven Shi profile banner" />
</p>

<p align="center">
  <a href="mailto:isvenshi@gmail.com"><img src="https://img.shields.io/badge/Email-isvenshi%40gmail.com-0ea5e9?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/svenshi"><img src="https://img.shields.io/badge/GitHub-svenshi-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <img src="https://komarev.com/ghpvc/?username=svenshi&style=for-the-badge&color=7c3aed" alt="Profile views" />
</p>

## 👨‍💻 About Me

I build infrastructure tools for people who care about **network control**, **operational clarity**, and **systems that can be debugged under pressure**.

- 🔭 Currently building the **OxiDNS ecosystem**: a Rust DNS engine plus router-side integrations and release tooling.
- 🧠 Focus areas: **DNS infrastructure**, **policy-based routing**, **backend architecture**, and **performance engineering**.
- 🛠️ Strength: turning messy network / operations problems into tools that are easier to deploy, reason about, and maintain.
- 🌏 Working style: pragmatic, production-oriented, and comfortable crossing backend, network, and UI boundaries when the product needs it.

## 🧭 Open Source Direction

```text
Core idea        Build a programmable DNS control plane for real network environments
Main users       Router / homelab / infrastructure operators who need transparent control
Current focus    OxiDNS engine, OpenWrt management, RouterOS routing workflows, repeatable builds
Design taste     Fast, explicit, debuggable, and configuration-driven
```

## 🚀 OxiDNS Ecosystem

This is the work I want visitors to remember: not isolated repos, but a connected toolkit that goes from DNS decision-making to router deployment.

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

## 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Shell" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/RouterOS-293239?style=for-the-badge&logo=mikrotik&logoColor=white" alt="RouterOS" />
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

## 📊 Profile Snapshot

```text
Primary theme    DNS infrastructure and practical network control
Main project     OxiDNS ecosystem
Languages        Rust, Java, JavaScript, Shell
Platforms        Linux, OpenWrt, RouterOS
Best fit         Network tooling, backend services, operator-facing infrastructure
```

> I keep this section text-based on purpose: it stays readable even when third-party GitHub stats services are slow, rate-limited, or unavailable.

## 🤝 Connect

If you are working on DNS, router-side networking, backend systems, or practical infrastructure tooling, feel free to reach out.

- 📫 Email: [isvenshi@gmail.com](mailto:isvenshi@gmail.com)
- 🐙 GitHub: [github.com/svenshi](https://github.com/svenshi)

<p align="center">
  <em>Programmable DNS. Practical routing. Infrastructure that operators can trust.</em>
</p>
