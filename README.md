# AI Red Team Portfolio — Antonio Toudji

**AI Security Engineer | LLM Red Teamer | OWASP GenAI Contributor**

> I build AI systems. I break them. I secure them.

---

## About

Specialized in offensive security of LLM systems, AI agents, and automated workflows.
I find critical vulnerabilities in chatbots, APIs, and AI agents before attackers do.

- 📧 antonio.redteam1@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/antonio-toudji-70346b341)
- 🌐 [Portfolio](https://antohack879.github.io/AI-RedTeam-Portfolio)

---

## Proven Results

| Target | Vulnerability | CVSS | AIVSS | Platform |
|--------|--------------|------|-------|----------|
| Banking AI Assistant | Prompt Injection — full guardrail bypass + admin key exfiltration | 9.8 | CRITICAL | TryHackMe |
| E-commerce LLM API | System command injection via LLM newsletter API — Full RCE | 9.8 | CRITICAL | PortSwigger |
| E-commerce AI Agent | Indirect Prompt Injection — account takeover without user interaction | 9.1 | CRITICAL | PortSwigger |
| E-commerce LLM Chat | Insecure Output Handling — XSS + Indirect Injection — account deletion | 9.8 | CRITICAL | PortSwigger Expert |
| WhatsApp AI Chatbot | PII exposure + company structure leak — real production system | 8.5 | CRITICAL | Real World |
| NéoBank AI Chatbot | LLM02 — Insecure Output Handling — silent data exfiltration via pixel tracking | 8.8 | CRITICAL | Personal Research |

---

## Write-ups

### PortSwigger Labs

| Lab | Vulnerability | Level | Write-up |
|-----|--------------|-------|---------|
| Exploiting LLM APIs | System command injection via LLM API | Practitioner | [Read](writeups/portswigger/writeup_llm_api_en.md) |
| Indirect Prompt Injection | Account takeover without user interaction | Practitioner | [Read](writeups/portswigger/writeup_indirect_injection.md) |
| Insecure Output Handling | XSS + Indirect Injection — chained attack | Expert | [Read](writeups/portswigger/writeup_xss_output_handling_en.md) |

### TryHackMe Labs

| Lab | Vulnerability | Level | Write-up |
|-----|--------------|-------|---------|
| BankGPT | Prompt Injection — context replacement | Easy | [Read](writeups/tryhackme/bankgpt.md) |

### Personal Research

| Target | Vulnerability | Level | Write-up |
|--------|--------------|-------|---------|
| NéoBank AI Chatbot | LLM02 — Insecure Output Handling — silent exfiltration via unsanitized Markdown rendering | Advanced | [Read](writeups/research/LLM02-chatbot-exfil/README.md) |

### Real World Audits

| Target | Type | Write-up |
|--------|------|---------|
| Confidential | Production chatbot security audit | [Read](writeups/realworld/vanguard_ops_audit_fr.md) |

### Personal Projects

| Project | Description | Write-up |
|---------|------------|---------|
| LLM Security Challenge | Gamified prompt injection platform — 12 levels | [Read](writeups/projects/llm-security-challenge.md) |

---

## Reports

Professional penetration test reports available in `/reports`:

- `AI_Pentest_Report_BankGPT_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_LLMAPIExploit_EN_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_IndirectInjection_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_XSS_OutputHandling_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_LLM02_ChatbotExfil_AntonioTOUDJI.pdf`

---

## Skills

**Offensive AI Security:**
Prompt Injection (Direct & Indirect) • Jailbreak • System Command Injection via LLM
• Insecure Output Handling • XSS via LLM • RAG Poisoning • Memory Poisoning
• Agent Hijacking • Tool Manipulation • PII Extraction • Pixel Tracking Exfiltration

**Frameworks:**
OWASP LLM Top 10 • AIVSS v0.8 • MITRE ATLAS • CVSS v4.0 • Burp Suite

**Build:**
n8n • LangChain • OpenAI API • Claude API • Python • FastAPI • PostgreSQL • AI Agent Architecture

**Platforms:**
PortSwigger Web Security Academy • TryHackMe • HackTheBox • OWASP GenAI Project (contributor)

---

## Folder Structure

```
AI-RedTeam-Portfolio/
├── writeups/
│   ├── portswigger/
│   │   ├── writeup_llm_api_en.md
│   │   ├── writeup_indirect_injection.md
│   │   └── writeup_xss_output_handling_en.md
│   ├── tryhackme/
│   │   └── bankgpt.md
│   ├── research/
│   │   └── LLM02-chatbot-exfil/
│   │       ├── README.md
│   │       └── demo/
│   │           └── neobank_chatbot.html
│   ├── realworld/
│   │   └── vanguard_ops_audit_fr.md
│   └── projects/
│       └── llm-security-challenge.md
├── reports/
│   ├── AI_Pentest_Report_BankGPT_AntonioTOUDJI.pdf
│   ├── AI_Pentest_Report_LLMAPIExploit_EN_AntonioTOUDJI.pdf
│   ├── AI_Pentest_Report_IndirectInjection_AntonioTOUDJI.pdf
│   ├── AI_Pentest_Report_XSS_OutputHandling_AntonioTOUDJI.pdf
│   └── AI_Pentest_Report_LLM02_ChatbotExfil_AntonioTOUDJI.pdf
└── README.md
```

---

> Available for remote engagements: AI security audits, LLM red teaming, penetration test reports.
>
> **I don't just audit — I secure.**
>
> 📧 antonio.redteam1@gmail.com
