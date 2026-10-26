<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Armando Melo — Technical Lead at Braz Móvel. Full Stack Developer and Software Engineer." src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="mailto:josearmando10067@gmail.com"><img alt="Email" src="https://img.shields.io/badge/josearmando10067%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <img alt="Technical Lead at Braz Móvel" src="https://img.shields.io/badge/Technical_Lead-Braz_M%C3%B3vel-3E63DD?style=flat-square">
  <img alt="Itabaiana, Sergipe, Brazil" src="https://img.shields.io/badge/Itabaiana%2C_Sergipe-Brazil-009C3B?style=flat-square&logo=googlemaps&logoColor=white">
</p>

<br>

## Hi, I'm Armando 👋

I lead the technical team at **Braz Móvel**, a mobile virtual network operator (MVNO) running on Vivo's network in Brazil. Day to day, that means keeping carrier incidents within SLA, supporting the internet providers that resell our lines, and building the software that makes all of it measurable.

My path is not the usual one. I hold bachelor's degrees in **Business Administration** and **Law**, and trained as a **Full Stack Developer** and **Software Engineer** at Alura. That mix shapes how I build: I read an SLA like a contract, a process like a cost, and a feature like something a team will live with every day.

## What I do

- **Lead the technical team** at Braz Móvel — incident escalation with the carrier, partner support and the tooling behind both.
- **Build internal platforms end to end** — Node.js and Express back ends, React and TypeScript front ends, deployed and operated on Linux.
- **Integrate the systems an operator runs on** — carrier portal APIs, the Opa Suite support platform and the ERPs our partner providers use.
- **Put AI to work where it earns its place** — generated text goes through deterministic validation before it reaches a carrier or a partner.

## Featured project

### [AXL](https://github.com/Mrpapaco1/AXL) — SLA audit & NOC operations platform

<sub>Running in production at the NOC where I work. The [public version](https://github.com/Mrpapaco1/AXL) replaces every company and personal detail with fictional data · ▶ **[Live demo](https://mrpapaco1.github.io/AXL/)**</sub>

<a href="https://mrpapaco1.github.io/AXL/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/axl-radar-dark.png">
    <img alt="AXL Radar: team notice, shift timeline and the queue of tickets that need the analyst's action (fictional data)" src="assets/axl-radar-light.png">
  </picture>
</a>

AXL audits every carrier incident Braz Móvel opens against a five-business-day SLA, flags the ones that stop moving, and drafts the follow-up an analyst would write. It also turns support chats into team productivity metrics and gives each partner provider a window into its own tickets.

- **SLA radar** — a live queue ordered by deadline, with business-day countdowns and automatic detection of tickets that stopped moving.
- **AI-drafted follow-ups** — written in the analyst's voice, one specific question per case, always reviewed by a person before sending.
- **Team analytics** — first-contact resolution, recurrence and top offenders from support chats, plus a monthly executive report.
- **Automated portability re-checks** against the carrier API, with per-run caps and a kill switch.
- **Partner portal** — strict per-partner data isolation, append-only audit trail, rate limiting and signed links.
- **Knowledge base** — step-by-step integration guides for the partner ERPs (IXC, Hubsoft, SGP and Atlaz).

<table>
  <tr>
    <td align="center" width="25%"><h3>700+</h3><sub>automated tests guarding the business rules</sub></td>
    <td align="center" width="25%"><h3>9</h3><sub>color themes, contrast-checked against WCAG</sub></td>
    <td align="center" width="25%"><h3>5</h3><sub>runtime dependencies on the back end</sub></td>
    <td align="center" width="25%"><h3>6</h3><sub>background routines, each with its own lock</sub></td>
  </tr>
</table>

`Node.js 24` `Express 5` `React 19` `TypeScript` `Vite` `Tailwind CSS` `TanStack Query` `Vitest` `Linux` `systemd`

## Tech stack

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
      <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>Back end</b></td>
    <td>
      <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
      <img alt="Express" src="https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white">
      <img alt="REST APIs" src="https://img.shields.io/badge/REST_APIs-0B1220?style=flat-square&logo=openapiinitiative&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>Front end</b></td>
    <td>
      <img alt="React" src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white">
      <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
      <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
      <img alt="TanStack Query" src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>Testing</b></td>
    <td>
      <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white">
      <img alt="Testing Library" src="https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>Operations</b></td>
    <td>
      <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
      <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white">
      <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
      <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>AI</b></td>
    <td>
      <img alt="LLM integration" src="https://img.shields.io/badge/LLM_integration-6E56CF?style=flat-square">
      <img alt="Prompt engineering" src="https://img.shields.io/badge/Prompt_engineering-6E56CF?style=flat-square">
    </td>
  </tr>
</table>

## Education

<table>
  <tr><td>💻 <b>Full Stack Developer</b></td><td>Alura</td></tr>
  <tr><td>🧩 <b>Software Engineer</b></td><td>Alura</td></tr>
  <tr><td>⚖️ <b>Law</b></td><td>Bachelor of Laws (LL.B.)</td></tr>
  <tr><td>📊 <b>Business Administration</b></td><td>Bachelor's degree</td></tr>
</table>

## How I build

- **Decisions live next to the code.** Every module opens by saying what problem it solves and why it exists.
- **Business rules are tested, not trusted.** If a rule decides what an analyst sees, it has a test.
- **Every external side effect has an off switch.** Turning a routine off should never require a deploy.
- **Real customer data never leaves production.** Demos, screenshots and fixtures use invented data.

## Let's talk

📫 [josearmando10067@gmail.com](mailto:josearmando10067@gmail.com) &nbsp;·&nbsp; 📍 Itabaiana, Sergipe — Brazil (UTC−3)
