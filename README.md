# Hi, I'm Carlos 👋

### Business Analyst | Data & AI | Homelab Enthusiast

📍 Auckland, New Zealand · 🌐 [carlos.nz](https://carlos.nz)

---

## 🧑‍💻 About me

- 📊 I turn messy processes and unreliable spreadsheets into data people can trust, with **15+ years** of hands-on technical experience.
- 🗄️ I work mostly with **SQL Server, T-SQL and Power BI**, and I automate the repetitive parts with **Python** and **n8n**.
- 🤖 I'm exploring **AI and automation**: Copilot Studio agents, local LLMs with Ollama, and AI-assisted development with Claude Code.
- 🖥️ I run a **five-node Proxmox homelab** to learn infrastructure by breaking, fixing and documenting things.
- 🎓 Studying a **Master of Business Informatics (Business Analytics)** at Yoobee Colleges, Auckland.
- 📜 Working towards **CBAP** (IIBA) and **DP-300 Azure Database Administrator** (Microsoft).

```python
from dataclasses import dataclass, field


@dataclass
class Profile:
    name: str = "Carlos"
    role: str = "Business Analyst, Data & AI"
    location: str = "Auckland, New Zealand"
    languages: list[str] = field(default_factory=lambda: ["Python", "T-SQL", "DAX"])
    studying: list[str] = field(default_factory=lambda: ["CBAP", "DP-300", "Master of Business Analytics"])
    homelab: str = "5x Proxmox nodes"

    def motto(self) -> str:
        return "Fewer manual steps, more reliable data."


if __name__ == "__main__":
    print(Profile().motto())
```

---

## 🛠️ Technical skills

### Data & reporting
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-1B6EC2?style=for-the-badge)
![SSRS](https://img.shields.io/badge/SSRS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

### Databases
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-336791?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_DP--300-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### Programming & automation
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

### AI
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

### Infrastructure & self-hosting
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/Rocky_Linux-10B981?style=for-the-badge&logo=rockylinux&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik_v3-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### Analysis, tooling & platforms
![BPMN](https://img.shields.io/badge/BABOK_%2F_BPMN-005AA7?style=for-the-badge)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Miro](https://img.shields.io/badge/Miro-050038?style=for-the-badge&logo=miro&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Business platforms:** Totvs RM · IBM Maximo · Zoho CRM · Ideagen Q-Pulse

---

## 🧪 Homelab

| Layer | What I run |
|---|---|
| **Compute** | Proxmox VE, five nodes (grown from one) |
| **Backups** | Proxmox Backup Server |
| **Network services** | Technitium DNS and DHCP for the internal network |
| **Edge** | Traefik v3 on Oracle Cloud, with Cloudflare in front of public services |
| **Workloads** | Dockerised, self-hosted applications on Linux (Ubuntu, Rocky) |

---

## 📌 Projects

| Project | Description | Stack |
|---|---|---|
| [**personal-website**](https://github.com/carlosleandrobh/personal-website) | My personal site: experience, projects, and notes from the homelab and self-hosted apps. Live at [carlos.nz](https://carlos.nz). | Python |
| [**BentoPDF**](https://bentopdf.carlos.nz) | Self-hosted, privacy-first PDF toolkit (merge, split, compress, convert) running in my homelab. Upstream: [alam00000/bentopdf](https://github.com/alam00000/bentopdf). | Docker, Traefik, Cloudflare |
| **Copilot Studio agent** | A Microsoft 365 agent built with Copilot Studio. *In progress.* | Copilot Studio, M365 |

---

## 📈 GitHub stats

<p align="center">
  <a href="https://github.com/carlosleandrobh">
    <img height="180" alt="Carlos's GitHub stats" src="https://github-stats-extended.vercel.app/api?username=carlosleandrobh&show_icons=true&theme=dark&include_all_commits=true&hide_border=true" />
  </a>
  <a href="https://github.com/carlosleandrobh">
    <img height="180" alt="Carlos's top languages" src="https://github-stats-extended.vercel.app/api/top-langs/?username=carlosleandrobh&layout=compact&theme=dark&hide_border=true&langs_count=6" />
  </a>
</p>

---

## 📫 Get in touch

[![Website](https://img.shields.io/badge/carlos.nz-0F172A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://carlos.nz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/carlosleandrobh)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carlosleandrobh@gmail.com)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/carlosleandrobh/carlosleandrobh/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/carlosleandrobh/carlosleandrobh/output/github-snake.svg" />
  <img alt="Snake animation eating my GitHub contribution graph" src="https://raw.githubusercontent.com/carlosleandrobh/carlosleandrobh/output/github-snake.svg" />
</picture>
