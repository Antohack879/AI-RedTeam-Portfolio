# AI Red Team Portfolio — Antonio TOUDJI

> **AI Security Engineer | LLM Red Teamer | OWASP GenAI Contributor**  
> I build AI systems. I break them. I secure them.

---

## About

Specialized in offensive security of LLM systems, AI agents and automation workflows.  
I find critical vulnerabilities in AI chatbots, APIs, and agents before attackers do.

**Contact:** antonio.redteam1@gmail.com  
**LinkedIn:** linkedin.com/in/antonio-toudji-70346b341  
**Portfolio:** antohack879.github.io/AI-RedTeam-Portfolio

---

## Proven Results

| Target | Vulnerability | CVSS | AIVSS | Platform |
|--------|--------------|------|-------|----------|
| AI Banking Assistant | Prompt Injection — full guardrail bypass + admin key exfiltration | 9.8 | CRITICAL | TryHackMe |
| E-commerce LLM API | OS Command Injection via LLM newsletter API — full RCE | 9.8 | CRITICAL | PortSwigger |
| E-commerce Agent | Indirect Prompt Injection — zero-interaction account takeover | 9.1 | CRITICAL | PortSwigger |
| E-commerce LLM Chat | Insecure Output Handling — XSS + Indirect Injection — account deletion | 9.8 | CRITICAL | PortSwigger Expert |
| WhatsApp AI Chatbot | PII Exposure + Corporate Structure Leak — real production system | 8.5 | CRITICAL | Real World |

---

## Write-Ups

### PortSwigger Labs

| Lab | Vulnerability | Level | Write-Up |
|-----|--------------|-------|----------|
| LLM API Exploitation | OS Command Injection via LLM API | Practitioner | [Read](writeups/portswigger/writeup_llm_api_en.md) |
| Indirect Prompt Injection | Zero-interaction account takeover | Practitioner | [Read](writeups/portswigger/writeup_indirect_injection.md) |
| Insecure Output Handling | XSS + Indirect Injection — chained attack | **Expert** | [Read](writeups/portswigger/writeup_xss_output_handling_en.md) |

### TryHackMe Labs

| Lab | Vulnerability | Level | Write-Up |
|-----|--------------|-------|----------|
| BankGPT | Prompt Injection — Context Override | Easy | [Read](writeups/tryhackme/bankgpt.md) |

### Real World Audits

| Target | Type | Write-Up |
|--------|------|----------|
| Confidential | Production chatbot security audit | [Read](writeups/realworld/vanguard_ops_audit_fr.md) |

### Personal Projects

| Project | Description | Write-Up |
|---------|-------------|----------|
| LLM Security Challenge | 12-level gamified prompt injection platform | [Read](writeups/projects/llm-security-challenge.md) |

---

## Reports

Professional pentest reports available in [/reports](reports/) :

- `AI_Pentest_Report_BankGPT_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_LLMAPIExploit_EN_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_IndirectInjection_AntonioTOUDJI.pdf`
- `AI_Pentest_Report_XSS_OutputHandling_AntonioTOUDJI.pdf`


---

## Skills

**Offensive AI Security:**
Prompt Injection (Direct & Indirect) • Jailbreaking • OS Command Injection via LLM  
Insecure Output Handling • XSS via LLM • RAG Poisoning • Memory Poisoning  
Agent Hijacking • Tool Manipulation • PII Extraction

**Frameworks:**
OWASP LLM Top 10 • AIVSS v0.8 • MITRE ATLAS • CVSS v4.0 • Burp Suite

**Build:**
n8n • LangChain • OpenAI API • Claude API • Python • AI Agent Architecture

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
│   │   └── writeup_xss_output_handling_en.md  ← NEW Expert
│   ├── tryhackme/
│   │   └── bankgpt.md
│   ├── realworld/
│   │   └── vanguard_ops_audit_fr.md  ← NEW Real World
│   └── projects/
│       └── llm-security-challenge.md
├── reports/
│   ├── AI_Pentest_Report_BankGPT_AntonioTOUDJI.pdf
│   ├── AI_Pentest_Report_LLMAPIExploit_EN_AntonioTOUDJI.pdf
│   ├── AI_Pentest_Report_IndirectInjection_AntonioTOUDJI.pdf
│   ├── AI_Pentest_Report_XSS_OutputHandling_AntonioTOUDJI.pdf  ← NEW
│   └──
└── index.html
```

---

*Available for remote contracts — AI security audits, LLM red teaming, pentest reports.*  
*antonio.redteam1@gmail.com*
