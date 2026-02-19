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
  <img src="https://img.shields.io/github/followers/SBertrand-47?style=flat-square&label=followers&color=39FF14" />
  <img src="https://img.shields.io/github/stars/SBertrand-47?style=flat-square&label=stars&color=39FF14" />
  <img src="https://img.shields.io/github/last-commit/SBertrand-47/SBertrand-47?style=flat-square&label=last%20commit&color=39FF14" />
</p>

</div>

---

## 🧠 Core expertise and infrastructure

<table align="center">
  <tr>
    <td width="50%" valign="top">
      <h4>🔐 Trust and integrity</h4>
      <ul>
        <li><b>PKI:</b> digital signatures, certificate handling, revocation thinking</li>
        <li><b>Evidence chains:</b> verifiable audit trails built for scrutiny</li>
        <li><b>Security posture:</b> threat modeling, secure defaults, hardening</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 Applied intelligence</h4>
      <ul>
        <li><b>Computer vision:</b> YOLO, OpenCV, SLAM-adjacent work</li>
        <li><b>ML ops:</b> anomaly detection, classification, evaluation loops</li>
        <li><b>Robotics:</b> control loops, sim-to-real mindset</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>💳 Fintech rails</h4>
      <ul>
        <li><b>Deterministic logic:</b> exact money math, rounding rules, invariants</li>
        <li><b>KYC aware:</b> compliant onboarding flows and auditability</li>
        <li><b>Throughput:</b> low-latency APIs, caching, correctness under load</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏗️ System architecture</h4>
      <ul>
        <li><b>Scalability:</b> profiling, aggressive caching, sane invalidation</li>
        <li><b>Observability:</b> structured logs, traces, Sentry style feedback loops</li>
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
    EVID[Evidence Chains + Audit Logs]
    REVOKE[Revocation + Lifecycle]
  end

  subgraph PROD[Products]
    CL[CertiLect]
    TE[TrustEcho AI]
    RB[RemitBond]
    CK[Closekin]
  end

  subgraph RUNTIME[Runtime]
    API[Low-latency APIs]
    CACHE[Caching + Rate Limits]
    OBS[Observability]
  end

  CL --> PKI
  CL --> REVOKE
  CL --> EVID

  TE --> API
  TE --> OBS
  TE --> EVID

  RB --> API
  RB --> CACHE
  RB --> EVID

  CK --> API
  CK --> CACHE
  CK --> OBS

  PKI --> OBS
  EVID --> OBS
  API --> OBS
