<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     ANIMATED HEADER BANNER                      -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:003333,100:008080&height=220&section=header&text=Mohammed%20Uzair%20Shaikh&fontSize=52&fontAlignY=38&animation=twinkling&fontColor=e0ffff&desc=AI%20Security%20Engineer%20%E2%80%A2%20Threat%20Intelligence%20%E2%80%A2%20Post-Quantum%20Cryptography&descAlignY=60&descSize=16&descAlign=50" alt="Header" />

<!-- TYPING SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=3500&pause=1200&color=008080&center=true&vCenter=true&multiline=false&width=750&lines=The+quantum+future+isn't+coming+%E2%80%94+it's+already+being+harvested.;Building+post-quantum+defenses+before+the+breach.;Breaking+things+ethically+since+2022.;CTI+%7C+PQC+%7C+Adversarial+AI+%7C+Zero-Trust+Architecture." alt="Typing SVG" />
</a>

<br/>

<!-- PROFILE VIEWS + FOLLOWERS + LAST UPDATED -->
<img src="https://komarev.com/ghpvc/?username=uzx-02&color=008080&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views"/>
&nbsp;
<img src="https://img.shields.io/github/followers/uzx-02?label=FOLLOWERS&style=flat-square&color=008080&labelColor=0a0a0a" alt="Followers"/>
&nbsp;
<img src="https://img.shields.io/badge/STATUS-ACTIVE-008080?style=flat-square&labelColor=0a0a0a" alt="Status"/>
&nbsp;
<img src="https://img.shields.io/badge/TLP-CLEAR-lightgrey?style=flat-square&labelColor=0a0a0a" alt="TLP:CLEAR"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      OPERATIONAL OVERVIEW                        -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## `> whoami`

```yaml
operator: Mohammed Uzair Shaikh
role: AI Security Engineer · Threat Intelligence Analyst · PQC Researcher
location: Mumbai, India
clearance: UNCLASSIFIED // TLP:CLEAR
education: B.Sc. (Hons.) AIML — University of Mumbai [2025–2029]
           Diploma in AIML Engineering               [2022–2025]

focus_areas:
  - Post-Quantum Cryptography (ML-KEM / FIPS 203)
  - Cyber Threat Intelligence & OSINT
  - Adversarial AI & LLM Security
  - Zero-Trust Infrastructure Design
  - PhaaS / eCrime Ecosystem Forensics

motto: "The quantum future isn't coming — it's already being harvested."
```

<div align="center">

<a href="https://linkedin.com/in/mohammed-uzair-shaikh">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:uzair.shaikh.sec@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
&nbsp;
<a href="https://github.com/uzx-02">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      RECOGNITION                                  -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🏆 Recognition

<div align="center">

|            Medal            | Project                              | Issued By                       |   Year   |
| :-------------------------: | ------------------------------------ | ------------------------------- | :------: |
|    🥉 **2nd Runner Up**     | QuMail — Quantum-Secure Email Client | HackToon 1.0, AIKTC             | Mar 2026 |
| 🎖️ **Top 8 / 1,000+ Teams** | Quantum-AI Hybrid Defense System     | Aavishkar, University of Mumbai | Dec 2025 |

> _The Aavishkar project was independently rated at **Graduate / PhD level** for research maturity and novel hardware-seeded quantum integration — competing across all Engineering & Technology teams of Mumbai University._

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     FEATURED ENGINEERING                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚡ Featured Engineering

<!-- ─── PROJECT 1: QuMail ─── -->
<details open>
<summary><b>📧 QuMail — Quantum-Secure Email Client</b> &nbsp;|&nbsp; <code>Public</code> &nbsp;<a href="https://github.com/uzx-02/QuMail">→ View Repo</a></summary>

<br/>

> _Open-source PQC implementation for civilian communications, aligned with **ISRO Problem Statement PS 25179** and India's CII PQC deadline of Dec 31, 2028._

**QuMail adds a transparent post-quantum encryption layer to Gmail & Yahoo — zero changes required from recipients.**

**Architecture Flow:**

```mermaid
graph LR
    A([📤 Sender]) -->|KME Request| B{Virtual KME Node\nETSI GS QKD 014}
    B -->|256-bit Quantum Key| C[[TQR Encrypt\nML-KEM FIPS 203\nAES-256-GCM]]
    C -->|MIME Wrap + OAuth2| D[(SMTP Relay\nGmail · Yahoo)]
    D -->|IMAP Fetch| E([📥 Recipient])
    E -->|KME Lookup| F[[TQR Decrypt]]
    F --> G([✅ Plaintext Inbox])

    style A fill:#003333,color:#e0ffff,stroke:#008080
    style G fill:#003333,color:#e0ffff,stroke:#008080
    style B fill:#001a1a,color:#00cccc,stroke:#008080
    style C fill:#001a1a,color:#00cccc,stroke:#008080
    style F fill:#001a1a,color:#00cccc,stroke:#008080
```

| Layer                    | Technology              | Standard        |
| ------------------------ | ----------------------- | --------------- |
| **Tier 1 — Quantum OTP** | Quantum One-Time Pad    | Custom          |
| **Tier 2 — Symmetric**   | QKD-seeded AES-256-GCM  | NIST            |
| **Tier 3 — PQC KEM**     | ML-KEM (Kyber)          | FIPS 203        |
| **Key Infrastructure**   | Virtual KME + Cloud Run | ETSI GS QKD 014 |

🏆 **2nd Runner Up — HackToon 1.0, AIKTC**

</details>

---

<!-- ─── PROJECT 2: Advanced Encryption Tool ─── -->
<details>
<summary><b>🔐 Advanced Encryption Tool (AET)</b> &nbsp;|&nbsp; <code>Public</code> &nbsp;<a href="https://github.com/uzx-02/advanced-encryption-tool">→ View Repo</a></summary>

<br/>

> _A production-grade, cross-platform desktop file encryption utility built on strict zero-trust architecture._

**AET is a zero-trust file vault — every operation is cryptographically isolated, no plaintext persists.**

```
┌─────────────────────────────────────────────────────┐
│              ZERO-TRUST FILE ENCRYPTION             │
├──────────────────┬──────────────────────────────────┤
│  Key Derivation  │  Argon2id (memory-hard KDF)      │
│  Encryption      │  AES-256-GCM (authenticated)     │
│  Architecture    │  Strict separation per operation │
│  Platform        │  Cross-platform desktop utility  │
│  Threat Model    │  Hostile environment, no trust   │
└──────────────────┴──────────────────────────────────┘
```

</details>

---

<!-- ─── PROJECT 3: CTI Reports ─── -->
<details>
<summary><b>🕵️ Cyber Threat Intelligence — OSINT Reports</b> &nbsp;|&nbsp; <code>Public</code> &nbsp;<a href="https://github.com/uzx-02/threat-intelligence">→ View Repo</a></summary>

<br/>

> _Independent CTI research tracking PhaaS ecosystems, AiTM campaigns, and live threat infrastructure. All reports mapped to **MITRE ATT&CK v19**, exported with **STIX 2.1** compatible IOCs._

**Featured Investigation: `CTI-2026-IG-001` — WIXXI TOOLS**

```
┌─────────────────────────────────────────────────────────────────┐
│  INVESTIGATION: WIXXI TOOLS — PhaaS Ecosystem Forensics         │
│  Classification: TLP:CLEAR  |  Confidence: HIGH                 │
├─────────────────────────────────────────────────────────────────┤
│  INFRASTRUCTURE                                                 │
│  ├─ 68-domain Anycast Cluster — mapped and documented           │
│  ├─ Live Telegram C2 workflow — extracted and analyzed          │
│  └─ Programmatic AI-scraper evasion (no-ai, no-scraping tags)   │
│                                                                 │
│  TTPs (MITRE ATT&CK v19)                                        │
│  ├─ AiTM session cookie interception → MFA bypass               │
│  ├─ Adversary-in-the-Middle phishing proxy infrastructure       │
│  └─ Telegram-based C2 exfiltration channels                     │
│                                                                 │
│  IOC — STIX 2.1 (ACTIVE REFERENCE)                              │
│  [file:hashes.SHA256 =                                          │
│  '5f5ee6cccae791f9cc3d34020422c5cb49dd9f20522e53e71955ce472...']│
│  Valid-from: 2025-07-01  |  Status: ACTIVE REFERENCE            │
└─────────────────────────────────────────────────────────────────┘
```

</details>

---

<!-- ─── PROJECT 4: Quantum-AI Hybrid Defense System ─── -->
<details>
<summary><b>🧠 Quantum-AI Hybrid Defense System</b> &nbsp;|&nbsp; <code>Restricted — Research</code></summary>

<br/>

> _A research-grade, four-layer cybersecurity architecture defeating both classical and post-quantum threats. Hardware entropy → BB84 QKD → Neuro-Symbolic AI → Quantum-signed transactions._

```
LAYER ARCHITECTURE
══════════════════════════════════════════════════════════

  [ Layer 1 ]  Hardware Root of Trust
               ESP32 Zener diode avalanche noise TRNG
               Von Neumann debiasing + CSPRNG hot-failover

       ↓
  [ Layer 2 ]  BB84 QKD Simulation
               Physics-accurate protocol implementation
               QBER eavesdrop detection
               Decoy State Protocol (PNS attack mitigation)

       ↓
  [ Layer 3 ]  Neuro-Symbolic AI Anomaly Engine
               Isolation Forest anomaly detection
               Symbolic rule engine: XSS · SQLi · Impossible Travel

       ↓
  [ Layer 4 ]  Quantum-Signed Transactions
               HMAC-SHA256 from quantum-derived keys
               Quantum Bank PoC — MITB attack blocked & logged

══════════════════════════════════════════════════════════
```

> \*Repository access restricted to protect ongoing research. Full documentation and code audit available for **academic or professional review upon request.\***

🎖️ **Top 8 / 1,000+ Engineering Teams — Aavishkar, University of Mumbai · Dec 2025**
📜 **Rated at Graduate / PhD level** by independent academic reviewers.

</details>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     TECH ARSENAL                                  -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚔️ Technical Arsenal

<div align="center">

<!-- Skill Icons: https://skillicons.dev -->

**Languages & Core**

[![Skills](https://skillicons.dev/icons?i=python,rust,bash,linux,git,docker,gcp&theme=dark)](https://skillicons.dev)

**AI / ML Stack**

[![Skills](https://skillicons.dev/icons?i=tensorflow,sklearn&theme=dark)](https://skillicons.dev)

</div>

<br/>

<div align="center">

| Domain                | Competencies                                                         | Frameworks & Tools                       |
| --------------------- | -------------------------------------------------------------------- | ---------------------------------------- |
| 🛡️ **Cybersecurity**  | SOC Analysis · Threat Hunting · CTI · VAPT · DFIR · Malware Analysis | SIEM · OpenCTI · MISP · MITRE ATT&CK v19 |
| 🔐 **Cryptography**   | Post-Quantum (ML-KEM) · QKD · AES-GCM · Argon2id · TRNG              | `cryptography` · `liboqs` · FIPS 203     |
| 🕵️ **Threat Intel**   | OSINT · PhaaS Forensics · AiTM Analysis · STIX 2.1 · IOC Mapping     | MISP · OpenCTI · Maltego · Shodan        |
| 🧠 **AI / ML**        | Applied ML · LLM Security · Adversarial AI · Neuro-Symbolic          | Python · Scikit-Learn · Isolation Forest |
| ⚙️ **Infrastructure** | Zero-Trust Architecture · SSR · CI/CD                                | Linux · Docker · GCP · Git · Rust        |

</div>

<br/>

<div align="center">

<!-- Shields badges for cybersecurity-specific tools without skill icon equivalents -->

![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK_v19-black?style=flat-square&logo=target&logoColor=red)
![STIX 2.1](https://img.shields.io/badge/STIX_2.1-003366?style=flat-square)
![NIST FIPS 203](https://img.shields.io/badge/NIST_FIPS_203-004080?style=flat-square)
![ETSI QKD](https://img.shields.io/badge/ETSI_GS_QKD_014-005f73?style=flat-square)
![TLP:CLEAR](https://img.shields.io/badge/TLP-CLEAR-lightgrey?style=flat-square)
![OSINT](https://img.shields.io/badge/OSINT-informational?style=flat-square)
![Zero Trust](https://img.shields.io/badge/Zero--Trust_Architecture-008080?style=flat-square)

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     GITHUB STATS                                  -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=uzx-02&show_icons=true&theme=dark&bg_color=0a0a0a&border_color=008080&icon_color=008080&title_color=00cccc&text_color=c9d1d9&ring_color=008080&hide_border=false&include_all_commits=true&count_private=true" alt="GitHub Stats"/>
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=uzx-02&layout=compact&theme=dark&bg_color=0a0a0a&border_color=008080&title_color=00cccc&text_color=c9d1d9&hide_border=false&langs_count=8" alt="Top Languages"/>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=uzx-02&theme=dark&background=0a0a0a&border=008080&ring=008080&fire=00cccc&currStreakLabel=00cccc&sideLabels=c9d1d9&dates=6e7681&v=2" alt="GitHub Streak"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     TROPHIES                                      -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=uzx-02&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=6" alt="GitHub Trophies"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     CONTRIBUTION SNAKE                            -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/uzx-02/uzx-02/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/uzx-02/uzx-02/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/uzx-02/uzx-02/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     CURRENTLY EXPLORING                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🔭 Current Intel Feed

```
[ ACTIVE RESEARCH THREADS ]

  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░

  ⬡  Post-Quantum × Classical Hybrid Migration Paths
     Gaps, breakthroughs, and what survives RSA's end

  ⬡  Adversarial AI & LLM Security
     Prompt injection, model inversion, red-teaming LLMs

  ⬡  SOC Detection Engineering
     Hands-on threat hunting and custom SIEM rule development

  ⬡  Autonomous Security Tooling (AI Agents)
     Building agentic workflows for threat response automation

  ⬡  Open Source Contributions
     Building in public — starting now

  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     OPEN TO COLLABORATE                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🤝 Open to Collaborate On

<div align="center">

| Area                              | What I Bring                                                              |
| --------------------------------- | ------------------------------------------------------------------------- |
| 🔐 **Post-Quantum Cryptography**  | PQC library integration, ML-KEM, QKD simulation, FIPS 203 implementations |
| 🕵️ **CTI & Threat Hunting**       | OSINT, STIX IOC production, MITRE ATT&CK mapping, PhaaS forensics         |
| 🧠 **AI/ML Security**             | Adversarial ML, LLM red-teaming, prompt injection, neuro-symbolic AI      |
| 🛡️ **Detection Engineering**      | SIEM rules, anomaly detection, SOC automation, IR playbooks               |
| ⚙️ **Open-Source Security Tools** | Linux security automation, CTI tooling, zero-trust architectures          |

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                       OPERATOR NOTE                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚡ Operator Note

> _When I'm not hunting threats or building quantum defenses, I'm gaming — and yes, I play to win._
> _The obsessive pattern recognition that makes a good CTF player makes a good gamer. Turns out they're the same skill._

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                         FOOTER                                    -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:008080,100:0a0a0a&height=120&section=footer&animation=twinkling" alt="Footer"/>

_`// EOF — All research conducted legally and ethically. All IOCs are public reference only.`_
