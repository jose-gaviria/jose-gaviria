<div align="center">
  <img src="assets/hero.svg" alt="Jose Manuel Gaviria — Full-Stack Developer · Local AI · Computer Vision · Automation" width="100%" />
</div>

<div align="center">

### Full-Stack Developer · Local AI · Computer Vision · Automation

`Python` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `React` &nbsp;·&nbsp; `Node.js` &nbsp;·&nbsp; `Docker`

I build complete systems that connect software, automation and applied AI<br />
to real operational problems.

**[ View projects ](#main-projects)** &nbsp;&nbsp; **[ GitHub ](https://github.com/jose-gaviria?tab=repositories)** &nbsp;&nbsp; **[ Contact ](#contact)**

<sub>[Projects](#main-projects) · [Stack](#what-i-do) · [Experience](#experience--education) · [Contact](#contact)</sub>

</div>

<br />

## Main projects

<br />

<a href="https://github.com/jose-gaviria/zero-yarvis">
  <img src="assets/projects/zero-yarvis.svg" alt="ZERO / YARVIS — local-first AI assistant" width="100%" />
</a>

### ZERO / YARVIS

**Local-first AI desktop assistant.** Wake-word detection, speech recognition, local LLM inference,
retrieval, typed desktop actions and verification — running on the machine that owns the data.

`Python` · `Local AI` · `RAG` · `Speech` · `Testing` · `CI`

**315 tests passing · GitHub Actions verified**

**[View project →](https://github.com/jose-gaviria/zero-yarvis)**

<details>
<summary>Architecture &amp; engineering</summary>

<br />

- Typed tool contracts: every desktop action is declared, validated and executed through one path.
- Execution journal and verification predicates — an action is only reported as done once its effect is checked.
- Voice pipeline: wake word, speech-to-text, local model inference, speech synthesis.
- Retrieval over a local index, so answers stay grounded in the user's own documents.
- Verified in CI on every push, with the full test suite.

</details>

<br />

<a href="https://github.com/jose-gaviria/biometric-attendance-payroll">
  <img src="assets/projects/biometric-attendance-payroll.svg" alt="Biometric Attendance &amp; Payroll — offline face recognition and Colombian payroll" width="100%" />
</a>

### Biometric Attendance &amp; Payroll

**Offline facial attendance and Colombian payroll system.** Workers clock in by looking at a camera;
shifts become a payroll settlement under Colombian labour rules. One Docker container, no cloud.

`TypeScript` · `React` · `Node.js` · `Python` · `OpenCV` · `Docker`

**Face recognition · Attendance · Payroll · Offline deployment · CI**

**[View project →](https://github.com/jose-gaviria/biometric-attendance-payroll)**

<details>
<summary>Architecture &amp; engineering</summary>

<br />

- Three supervised processes in one image: two Express services and a Python vision engine.
- Two SQLite databases with distinct owners — biometric profiles apart from workers and shifts.
- Detection, quality validation, landmarks, embeddings and cosine matching with threshold and margin.
- No face image is stored; embeddings never reach the browser.
- Non-root, read-only container; model weights provisioned from pinned sources and verified by SHA-256.
- CI runs the Node suites and the Python face-engine suite against the real models.

</details>

<details>
<summary>Stated limits</summary>

<br />

- Identification does not implement certified liveness or anti-spoofing; the active challenge exists only at enrolment.
- Biometric accuracy is not claimed — the tests verify behaviour, not population accuracy.
- Payroll parameters are tied to a documented reference period and expire when the law changes.

</details>

<br />

## More work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Parking Management Platform</h4>
      <p>Parking operations end to end: tickets, tariffs, payments, shifts and audit trails.</p>
      <p><code>Next.js</code> <code>NestJS</code> <code>Prisma</code> <code>PostgreSQL</code></p>
      <p><a href="https://github.com/jose-gaviria/parking-management-platform">View →</a></p>
    </td>
    <td width="50%" valign="top">
      <h4>Heikamfy Sport</h4>
      <p>Sports ecommerce with headless catalogue, payments and order integration.</p>
      <p><code>Next.js</code> <code>TypeScript</code> <code>Shopify</code> <code>Mercado Pago</code></p>
      <p><a href="https://github.com/jose-gaviria/heikamfy-sport">View →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Llanogrande Visitor Control</h4>
      <p>Visitor access and warehouse control with roles, QR identification and traceability.</p>
      <p><code>Next.js</code> <code>TypeScript</code> <code>Supabase</code></p>
      <p><a href="https://github.com/jose-gaviria/llanogrande-visitor-control">View →</a></p>
    </td>
    <td width="50%" valign="top">
      <h4>Emaus WhatsApp Commerce</h4>
      <p>WhatsApp commerce operations with automation, analytics and containerized services.</p>
      <p><code>Node.js</code> <code>PostgreSQL</code> <code>Docker</code> <code>WhatsApp Cloud API</code></p>
      <p><a href="https://github.com/jose-gaviria/emaus-whatsapp-commerce">View →</a></p>
    </td>
  </tr>
</table>

<br />

## What I do

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Full stack</h4>
      <p>React · Next.js · Node.js · APIs · Databases</p>
    </td>
    <td width="50%" valign="top">
      <h4>Python &amp; applied AI</h4>
      <p>Python · Local AI · RAG · Speech · FastAPI</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Computer vision</h4>
      <p>OpenCV · MediaPipe · Face recognition</p>
    </td>
    <td width="50%" valign="top">
      <h4>Systems &amp; automation</h4>
      <p>Docker · CI/CD · n8n · Git · Automation</p>
    </td>
  </tr>
</table>

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,react,nextjs,nodejs,fastapi,opencv,postgres,sqlite,docker,git,github&perline=13" alt="Python, TypeScript, JavaScript, React, Next.js, Node.js, FastAPI, OpenCV, PostgreSQL, SQLite, Docker, Git, GitHub" />
</div>

<br />

## Engineering proof

- **ZERO / YARVIS — 315 tests passing**, verified by GitHub Actions.
- **Biometric system — Node and Python suites verified in CI**, including the face engine against the real models.
- **Dockerized offline deployment validated**: three services recovered after restart, data preserved, no external network.
- **Model weights provisioned by SHA-256** against a manifest, not vendored into the repository.

<br />

## Experience &amp; education

**Agencia Dinamo** — Programmer &amp; IT Support Assistant · Jan 2025–Present

<details>
<summary>Responsibilities</summary>

<br />

- Build and refine web, automation and internal operational solutions.
- Automate repetitive workflows with n8n and connected services.
- Test, document and support software used by internal teams.
- Troubleshoot Windows environments, software and day-to-day IT requirements.

</details>

**Politécnico ASDI** — Computer Systems Technical Diploma · In progress

<br />

## Contact

<div align="center">

**Interested in building software, automation or applied AI systems?**

[josegaviria1515@gmail.com](mailto:josegaviria1515@gmail.com) &nbsp;·&nbsp; [github.com/jose-gaviria](https://github.com/jose-gaviria)

<sub>El Retiro, Antioquia, Colombia</sub>

</div>
