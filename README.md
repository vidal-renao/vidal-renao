<div align="center">

# Vidal Reñao Lopelo

### IT Infrastructure & AI Solutions Engineer

**Enterprise IT. AI in Production. Full-Stack Delivery.**

*7+ years enterprise IT · AI systems live in production · Direct client delivery from brief to go-live*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vidalrenao-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/vidalrenao)
[![Portfolio](https://img.shields.io/badge/Portfolio-vidal--renao.com-111827?logo=vercel&logoColor=white&style=for-the-badge)](https://vidal-pro-portfolio.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-vidal--renao-181717?logo=github&logoColor=white&style=for-the-badge)](https://github.com/vidal-renao)
[![CCNA](https://img.shields.io/badge/Cisco-CCNA_Certified-1BA0D7?logo=cisco&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/vidalrenao)

*Basel, Switzerland · Available immediately across CH/LI*

</div>

---

## About

IT Infrastructure & AI Solutions Engineer based in Basel. I design and deploy end-to-end digital systems — from Microsoft 365 enterprise environments and hybrid networks to AI-integrated SaaS platforms running in production.

**VIDAL ECOSYSTEM** is my technical consultancy for the Swiss and European SME market: cloud migrations, AI-powered business tooling, and full-stack product delivery. Direct client engagement from briefing to go-live.

> MCP Server live on Vercel · Autonomous audit pipelines · Claude Vision OCR · 500+ enterprise users managed · CCNA certified

---

## Production Systems

Six systems in production — real clients, no mock data.

| Project | Stack | Metrics | Status |
|---|---|---|---|
| **[HelpDesk AI](https://github.com/vidal-renao/ticket-system)** | Next.js 15 · Supabase · Claude AI | Multi-tenant RBAC · SLA enforcement · nDSG compliant | `Production` |
| **[Ticket Auditor](https://github.com/vidal-renao/vidal-helpdesk-mcp)** | Vercel Edge · GitHub Actions · Composio | <11s full audit cycle · 7 MCP tools live · nDSG compliant | `Production` |
| **[MatchPoint AI](https://github.com/vidal-renao/matchpoint-ai)** | Next.js 16 · Claude AI · Supabase | AI CV parsing · 4D match scoring · WhatsApp alerts | `Production` |
| **[Invoice Auto](https://github.com/vidal-renao/invoice-auto)** | Next.js 16 · Claude Vision AI · Supabase | AI OCR extraction · Auto invoice generation · EUR/CHF | `Production` |
| **[Parcel Tracker SaaS](https://github.com/vidal-renao/parcel-tracker)** | Next.js 14 · Node.js · PostgreSQL | 3-tier RBAC · Digital signature · 6 languages | `Production` |
| **[D'NAMAR GmbH](https://github.com/vidal-renao/limpiezas-najip-maritza)** | Next.js 16 · Tailwind 4 · Supabase | 100/100 Lighthouse · DE/EN/ES · Google Search Console | `Production` |

---

## Ticket Auditor — Autonomous Audit Pipeline

> Autonomous audit infrastructure on HelpDesk AI. Full cycle in under 11 seconds.

```
GitHub Actions (hourly cron)
  → POST /api/cron/audit  [Bearer token auth]
    → Vercel Edge Function
      → Supabase query  [tickets · SLA · org stats]
        → Composio AI orchestration
          → Resend  [branded executive HTML report]
```

**MCP Server on Vercel SSE** — 7 tools exposed: `create_ticket`, `get_ticket_status`, `list_tickets`, `prioritize_incident`, `suggest_solution`, `update_ticket_status`, `generate_report`. Claude reads live business context without direct DB access. Swiss nDSG compliant.

---

## Skills

### ☁️ Cloud & Identity

![Microsoft 365](https://img.shields.io/badge/Microsoft_365-0078D4?logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?logo=microsoftazure&logoColor=white)
![Intune](https://img.shields.io/badge/Intune-0078D4?logo=microsoft&logoColor=white)
![Autopilot](https://img.shields.io/badge/Autopilot-0078D4?logo=microsoft&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?logo=windows&logoColor=white)

### 🤖 AI & Automation

![Claude AI](https://img.shields.io/badge/Claude_AI-D97757?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Server-16a34a?logoColor=white)
![Composio](https://img.shields.io/badge/Composio-111827?logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)

### 💻 Development

![Next.js](https://img.shields.io/badge/Next.js_16-black?logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)

### 🔧 Infrastructure

![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Debian-A81D33?logo=debian&logoColor=white)
![CCNA](https://img.shields.io/badge/CCNA-VLANs_·_VPN_·_TCP/IP-1BA0D7?logo=cisco&logoColor=white)

---

## Infrastructure & Enterprise Labs

| Repository | What it covers |
|---|---|
| **[M365 Graph Dashboard](https://github.com/vidal-renao/m365-graph-dashboard)** | Microsoft Graph API · OAuth/MSAL · M365 data access |
| **[Graph Employee Onboarding](https://github.com/vidal-renao/graph-employee-onboarding)** | PowerShell automation · HR lifecycle · GitHub Actions CI/CD |
| **[M365 Enterprise Lab](https://github.com/vidal-renao/m365-enterprise-lab)** | AD DS · DNS/DHCP · GPOs · domain-joined clients |
| **[Intune Autopilot Lab](https://github.com/vidal-renao/intune-autopilot-lab)** | Device enrollment · compliance policies · Autopilot OOBE |
| **[Hybrid Identity Automation](https://github.com/vidal-renao/hybrid-identity-ticket-automation)** | Entra ID · on-prem AD sync · identity lifecycle |

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=vidal-renao&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vidal-renao&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=vidal-renao&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

**Available for direct client mandates and agency collaboration across Switzerland and Liechtenstein.**

[Portfolio](https://vidal-pro-portfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/vidalrenao) · [GitHub](https://github.com/vidal-renao)

</div>
