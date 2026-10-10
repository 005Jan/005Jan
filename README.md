<h1 align="center">Jan Camps Atmetller</h1>

<p align="center">
  <b>IT Systems Technician · ASIX Student · Barcelona</b><br>
  Windows infrastructure & process automation at NeodataMeat · self-hosted infrastructure and applications in my own time
</p>

<p align="center">
  <a href="mailto:jcamps0005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/jan-camps-atmetller-422630354/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://005jan.github.io"><img src="https://img.shields.io/badge/Portfolio_&_CV-000000?style=flat&logo=githubpages&logoColor=white" alt="Portfolio"/></a>
</p>

---

### About me

I'm a systems technician working in a corporate environment, focused on **Windows Server, Active Directory
and process automation with the Microsoft Power Platform**. In my own time I run a small self-hosted
infrastructure on Linux and build complete applications on top of it, from the data model to
deployment, with a focus on security, backups and keeping things running.

- 🖥️ **Junior Systems Technician at NeodataMeat**: infrastructure, ERP/CRM administration and internal automation
- 🎓 Studying the **Higher Degree in ASIX** (Network Systems Administration) at Salesians Sarrià, Barcelona
- 🐧 Running a **self-hosted Linux server**: reverse proxy, VPN, password manager, encrypted backups and monitoring
- 🔒 Growing in **networking and cybersecurity** (FortiGate 7.6 Operator, ethical hacking)
- 🌍 Catalan & Spanish (native) · English (professional working)

---

### Experience

**Junior Systems Technician**, NeodataMeat · *Mar 2025 – Present*
- User, group and GPO administration with Active Directory; Windows Server management and maintenance
- Process automation with Power Automate; administration of Microsoft Dynamics AX/BC and CRM
- Virtualised environment management, IT helpdesk and technical support

**Systems Technician (DUAL internship)**, NeodataMeat · *Jun 2024 – Feb 2025*
- Incident resolution, hardware configuration and inventory, software deployment and maintenance
- Technical documentation of internal processes

### Education

- **CFGS ASIX**: Network Computer Systems Administration · Salesians Sarrià · *in progress*
- **CFGM SMX**: Microcomputer Systems and Networks · *2023 – 2025*

---

### Featured Projects

#### 🖧 HomePi: self-hosted infrastructure · *private repository*
A Raspberry Pi 4 (ARM64) home server that hosts my projects under my own domain, run like a small production environment.
- **Traefik** reverse proxy with automatic HTTPS (Let's Encrypt), **WireGuard** VPN for remote access, **Vaultwarden** password manager, Portainer and Watchtower for container management
- Custom firewall rules in Docker's `DOCKER-USER` chain; public-URL health checks with **Telegram alerts** on failure and recovery
- **Nightly backups** to an external disk, with secrets encrypted with GPG; backups verified by actually restoring them into throwaway containers
- Web dashboard and Telegram bot to check status, restart services and **restore backups with two-step confirmation**
- Pre-commit hooks that block hard-coded secrets before they reach GitHub

`Linux` `Docker` `Traefik` `WireGuard` `Bash` `GPG` `Raspberry Pi`

#### 🧠 Kovia: multi-user AI personal assistant · *private repository*
A web app and installable PWA where users manage expenses, calendar, habits, reminders, nutrition and news
by talking to an **AI agent with 23 tools**, in text or by voice.
- **Multi-tenant by design:** per-user data isolation enforced in PostgreSQL with **Row-Level Security**
- Agent loop on **Claude (AWS Bedrock)** with SSE streaming and prompt caching; **Whisper** transcription; receipt-to-expense with vision
- **Background workers** for reminders, cron tasks and a personalised morning briefing via Web Push
- ~7.5k lines of TypeScript, verified end to end, self-hosted on a Raspberry Pi 4 behind Traefik with automatic HTTPS

`Next.js 16` `React 19` `TypeScript` `Fastify` `Supabase` `Claude (Bedrock)` `Docker`

#### 💶 [Ajuts](https://github.com/005Jan/ajuts): public grants finder
Reads Spain's National Grants Database (BDNS) every day and shows each user the open calls that match their profile and region, sorted by deadline.
- **Deterministic scoring, no LLM**, so it can run for years without watching a quota; eligibility thresholds extracted from the call's PDF
- Incremental sync that recovers gaps after downtime; grouped Telegram notifications that never repeat or flood
- Invitation-only multi-user app: **Argon2id** passwords, CSRF protection, personal data encrypted at rest (Fernet); 85 automated tests

`Python` `FastAPI` `SQLAlchemy` `HTMX` `SQLite` `Docker`

#### 🔥 [HabitForge](https://github.com/005Jan/HabitForge): self-hosted habit-tracking PWA
A multi-user habit tracker installable on mobile and fully functional offline.
- Real **Web Push (VAPID)** with a prioritised reminder system: streak at risk, last chance and weekly summary, at most one notification per hour
- REST API on Express + MariaDB; frontend in **vanilla JavaScript** with a hand-written service worker; Docker Compose + Traefik

`Node.js` `Express` `MariaDB` `Web Push` `Nginx` `Docker`

---

### Tech Stack

**Systems & Infrastructure**<br>
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-003087?style=flat&logo=microsoft&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat&logo=vmware&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat&logo=wireguard&logoColor=white)
![Fortinet](https://img.shields.io/badge/FortiGate-EE3124?style=flat&logo=fortinet&logoColor=white)

**Cloud & AI**<br>
![AWS](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_(basic)-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Development**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Databases**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_/_Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Business Platforms & Automation**<br>
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat&logo=powerautomate&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat&logo=powerapps&logoColor=white)
![Dynamics](https://img.shields.io/badge/Dynamics_AX/BC/CRM-002050?style=flat&logo=dynamics365&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=flat&logo=uipath&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat&logo=microsoft&logoColor=white)

---

### Courses & Certifications

**Cybersecurity:** FortiGate 7.6 Operator · Getting Started in Cybersecurity 3.0 · Technical Introduction to Cybersecurity 3.0 ·
Introduction to the Threat Landscape 3.0 (Fortinet) · Ethical Hacking (Salesians Sarrià)<br>
**Other:** Internet of Things (IoT) · Power BI · Microsoft Copilot · Google: AI and Productivity · ChatGPT Fundamentals (Santander Open Academy)

---

<p align="center"><i>Open to opportunities in systems administration, infrastructure and automation. Feel free to reach out.</i></p>
