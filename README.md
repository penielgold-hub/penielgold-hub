# Hi, I'm Dapo Olaomo 👋

I'm a **Software Developer and Open Source Contributor** working across **C++, Python, TypeScript/JavaScript, and Rust**.

I contribute to production open-source projects through **bug fixes, regression testing, backend/API development, authentication and authorization, developer tooling, accessibility, and software reliability**.

## ✅ Merged Open Source Contributions

**8 directly merged pull requests**, plus **1 upstream-merged contribution credited through a follow-up PR**, across ScoopInstaller, Soterika, FaveTeamz, DelegoLabs, and REA.

| Project | Merged PRs | Contribution |
| --- | --- | --- |
| [ScoopInstaller/Extras](https://github.com/ScoopInstaller/Extras) | [#18941](https://github.com/ScoopInstaller/Extras/pull/18941) | Fixed Aegisub portable archive extraction on Windows |
| [Soterika/aura-vault-protocol](https://github.com/soterika/aura-vault-protocol) | [#1067](https://github.com/soterika/aura-vault-protocol/pull/1067), [#819](https://github.com/soterika/aura-vault-protocol/pull/819), [#833](https://github.com/soterika/aura-vault-protocol/pull/833) | Event search, portfolio integration, form validation |
| [FaveTeamz/workload-governor](https://github.com/FaveTeamz/workload-governor) | [#819](https://github.com/FaveTeamz/workload-governor/pull/819), [#820](https://github.com/FaveTeamz/workload-governor/pull/820), [#932](https://github.com/FaveTeamz/workload-governor/pull/932) | Form validation, withdrawal safety, accessibility |
| [DelegoLabs/Delego-backend](https://github.com/DelegoLabs/Delego-backend) | [#462](https://github.com/DelegoLabs/Delego-backend/pull/462) | Checkout authorization and backend security |
| [morluto/rea](https://github.com/morluto/rea) | [#1138](https://github.com/morluto/rea/pull/1138) (follow-up to [my #1133](https://github.com/morluto/rea/pull/1133)) | npm 12 release-version lookup fix, cherry-picked and credited upstream |


### 🔹 [REA — npm 12 Release Lookup](https://github.com/morluto/rea)

**[PR #1138 — Upstream Follow-up](https://github.com/morluto/rea/pull/1138)** ✅ **Merged** · Based on **[my PR #1133](https://github.com/morluto/rea/pull/1133)** (closed without merging)

Fixed npm 12 release metadata handling for `rea update`: the npm registry's one-element JSON array response is now accepted alongside npm 11's string response. The maintainer follow-up cherry-picked my original commit `aa400d18` and explicitly retained author credit, then refined error handling and regression tests.

**Result:** The corrected implementation was merged upstream on October 8, 2026. My original PR #1133 was not itself merged.

**Tech:** TypeScript · Node.js · npm · CLI Tooling · Regression Testing

---

### 🔹 [ScoopInstaller/Extras](https://github.com/ScoopInstaller/Extras)

**[PR #18941 — Fix Aegisub Portable Archive Extraction](https://github.com/ScoopInstaller/Extras/pull/18941)** ✅ **Merged**

Fixed a production package-installation regression caused by an upstream Aegisub portable archive filename change.

The fix replaced reliance on the previous hard-coded nested archive filename with portable-archive discovery, while preserving the existing Scoop extraction flow.

**Result:** Repository CI, PR validation, lint checks, and review passed before maintainer approval and merge.

**Tech:** PowerShell · JSON · Windows · Package Management · CI/CD · Regression Debugging

---

## 🚀 Open Source Engineering

### 🔹 [Tenstorrent/tt-metal](https://github.com/tenstorrent/tt-metal)

Contributing fixes and regression coverage for AI/static-analysis defects involving tensor operations, model-training infrastructure, profiling, and performance tooling.

- **[PR #58663](https://github.com/tenstorrent/tt-metal/pull/58663)** — Fixed broadcasted LHS gradient handling for tensor addition.
- **[PR #58810](https://github.com/tenstorrent/tt-metal/pull/58810)** — Corrected Tracy device performance-counter names and added regression coverage.
- **[PR #59181](https://github.com/tenstorrent/tt-metal/pull/59181)** — Improved tensor metadata handling for cached profiler operations.
- **[PR #59187](https://github.com/tenstorrent/tt-metal/pull/59187)** — Improved three-tier nanoGPT vocabulary handling and associated testing.

**Tech:** C++ · Python · PyTorch · Testing · AI/ML Infrastructure · Performance Tooling

---

### 🔹 [Soterika/aura-vault-protocol](https://github.com/soterika/aura-vault-protocol)

Contributed backend and frontend improvements involving authentication, API infrastructure, event search, portfolio functionality, rate limiting, and application validation.

- **[Event Search — PR #1067](https://github.com/soterika/aura-vault-protocol/pull/1067)** — Implemented PostgreSQL full-text search for vault events with migrations, routes, services, pagination validation, authentication, and automated tests.
- **[User Portfolio — PR #819](https://github.com/soterika/aura-vault-protocol/pull/819)** — Connected the Vault Dashboard to the backend portfolio API with authentication, pagination, caching, and rate limiting.
- **[Form Validation — PR #833](https://github.com/soterika/aura-vault-protocol/pull/833)** — Improved form validation, accessibility behavior, and component test coverage.

**Tech:** TypeScript · Node.js · REST APIs · PostgreSQL · Authentication · Rate Limiting · Testing

---

### 🔹 [FaveTeamz/workload-governor](https://github.com/FaveTeamz/workload-governor)

Contributed frontend reliability, accessibility, validation, and user-experience improvements.

- **[PR #819 — Transaction Form Validation](https://github.com/FaveTeamz/workload-governor/pull/819)** — Prevented transaction submission while validation errors are present and improved accessibility associations.
- **[PR #820 — Withdrawal Safety](https://github.com/FaveTeamz/workload-governor/pull/820)** — Prevented duplicate withdrawal submissions while transactions are pending and added accessibility states and regression coverage.
- **[PR #932 — Toast Accessibility](https://github.com/FaveTeamz/workload-governor/pull/932)** — Added keyboard dismissal, focus/hover behavior, and accessibility regression coverage for toast notifications.

**Tech:** TypeScript · Frontend · Accessibility · Form Validation · Testing

---

### 🔹 [DelegoLabs/Delego-backend](https://github.com/DelegoLabs/Delego-backend)

Contributed backend security and authorization improvements to checkout and wallet-service flows.

- **[PR #462 — Checkout Service Authorization](https://github.com/DelegoLabs/Delego-backend/pull/462)** — Added service-to-service authentication, authenticated-user propagation, wallet ownership validation, focused authorization tests, and Kubernetes secret-based configuration.

**Tech:** TypeScript · Backend Security · Authentication · Authorization · Testing · Kubernetes

---

## 🔧 Additional Contributions

I have also worked on focused fixes and regression coverage across projects involving:

- Repository and schema integration
- API and authentication systems
- Failure-path and boundary testing
- Logging and error classification
- Smart-contract regression coverage
- CI and package-management issues
- Software reliability improvements

## 💻 Technical Stack

**Languages**

`C++` · `Python` · `TypeScript` · `JavaScript` · `Rust` · `PowerShell`

**Backend & Data**

`Node.js` · `REST APIs` · `PostgreSQL` · `Authentication` · `Authorization`

**Engineering**

`Git` · `GitHub` · `Testing` · `Regression Testing` · `CI/CD` · `Debugging`

**Areas of Interest**

`AI/ML Infrastructure` · `Backend Systems` · `Developer Tooling` · `Open Source` · `Software Reliability`

## 🌱 Currently Developing

- C++ and Python for AI/ML infrastructure
- Backend and API architecture
- Authentication and application security
- Production Rust development
- Automated and regression testing
- Open-source collaboration and code review

## 🎯 Current Focus

I am actively contributing to open-source projects with an emphasis on **production bug fixes, regression testing, AI/ML infrastructure, backend systems, authentication, developer tooling, and reliable software engineering**.

## 🤝 Open to Collaboration

I'm interested in open-source and engineering opportunities involving:

- C++ and Python
- TypeScript / Node.js
- Rust
- Backend APIs and services
- AI/ML infrastructure
- Testing and software reliability
- Developer tooling
- Production bug fixing

## 📫 Connect

**GitHub:** [github.com/penielgold-hub](https://github.com/penielgold-hub)

---

> *"Learning by building. Growing through open source."*
