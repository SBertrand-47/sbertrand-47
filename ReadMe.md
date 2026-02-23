<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:39FF14,100:0A0A0A&height=180&section=header&text=Bertrand%20S.&fontSize=44&fontColor=FFFFFF&animation=fadeIn" />
</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2600&pause=700&color=39FF14&center=true&vCenter=true&width=760&lines=Lead+Engineer+%40+CertiLect;Trust+Infrastructure+Architect;Applied+AI+%26+Autonomous+Systems;Fintech+Rail+Engineering;Security-first+systems+that+stay+boring+in+production" alt="Typing SVG" />

<p>
  <a href="https://sbertrandportfolio.netlify.app/"><img src="https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/bertrand-s-10b698206/"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

<p>
  <img src="https://img.shields.io/github/last-commit/SBertrand-47/SBertrand-47?style=flat-square&label=last%20commit&color=39FF14" />
</p>

</div>

---

## 🧠 Core expertise and infrastructure

<table align="center">
  <tr>
    <td width="50%" valign="top">
      <h4>🔐 Cryptography and trust</h4>
      <ul>
        <li><b>PKI:</b> digital signatures, certificate chains, verification flows</li>
        <li><b>Crypto primitives:</b> hashing, signatures, key handling, threat-aware design</li>
        <li><b>Tamper evidence:</b> integrity logs and verifiable records built to survive scrutiny</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 Applied intelligence</h4>
      <ul>
        <li><b>Computer vision:</b> YOLO, OpenCV, SLAM-adjacent work</li>
        <li><b>ML systems:</b> anomaly detection, classification, evaluation loops</li>
        <li><b>Robotics:</b> control loops, sim-to-real mindset</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>💳 Transactional systems</h4>
      <ul>
        <li><b>Deterministic logic:</b> exact money math, rounding rules, invariants</li>
        <li><b>Compliance aware:</b> KYC flows, sensitive data handling, least-privilege access</li>
        <li><b>Throughput:</b> low-latency APIs, caching, correctness under load</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏗️ System architecture</h4>
      <ul>
        <li><b>Scalability:</b> profiling, aggressive caching, sane invalidation</li>
        <li><b>Observability:</b> structured logs, traces, feedback-driven reliability</li>
        <li><b>DevOps:</b> AWS, GCP, Nginx, CI/CD</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🧭 Systems map

```mermaid
flowchart LR
  subgraph TRUST[Trust Layer]
    PKI[PKI Signing + Verification]
    CRYPTO[Hashes + Signatures + Key Handling]
    LIFECYCLE[Key Lifecycle: rotation + revocation + expiry]
    INTEGRITY[Integrity Records: tamper-evident logs]
  end

  subgraph DOMAINS[Domains shipped]
    DOCS[Verifiable documents + identity-bound artifacts]
    DETECT[Real-time detection + abuse resistance]
    TRANS[Transactional platforms + payout logic]
    PLAT[High-trust web platforms]
  end

  subgraph RUNTIME[Runtime]
    API[Low-latency APIs]
    CACHE[Caching + rate limiting]
    DATA[Data models + indexing]
    OBS[Observability]
  end

  DOCS --> PKI
  DOCS --> CRYPTO
  DOCS --> LIFECYCLE
  DOCS --> INTEGRITY

  DETECT --> API
  DETECT --> OBS
  DETECT --> INTEGRITY

  TRANS --> API
  TRANS --> CACHE
  TRANS --> DATA

  PLAT --> API
  PLAT --> CACHE
  PLAT --> OBS
  PLAT --> DATA

  CRYPTO --> OBS
  PKI --> OBS
  API --> OBS
  DATA --> OBS
