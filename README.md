# Derek Gannon

### Cyber Threat Intelligence Analyst · builder of the tooling, not just the reports

I produce tactical and strategic intelligence on nation-state activity — and I build the automation that scales it: enrichment engines, phishing analysis, detection generators, and reporting, wired together as tools an AI assistant can drive.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-server-0A7E8C)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-C4162A)
![Sigma](https://img.shields.io/badge/Sigma-008272)
![YARA](https://img.shields.io/badge/YARA-5A2A82)
![Suricata](https://img.shields.io/badge/Suricata-C8102E)
![STIX 2.1](https://img.shields.io/badge/STIX_2.1%20%2F%20MISP-13507A)

---

### Featured work

A small CTI toolkit that composes — **find → enrich → report** — each tool usable on its own or driven together through the Model Context Protocol (MCP).

**[cti-ioc-enrichment](https://github.com/FarfallaJ/cti-ioc-enrichment)** — a multi-source IOC enrichment & scoring engine and MCP server. Enriches IPs, domains, URLs, and hashes across 10 sources (VirusTotal, OTX, AbuseIPDB, GreyNoise, Shodan, urlscan, abuse.ch, plus keyless crt.sh / RDAP / InternetDB), returns a weighted verdict with typed attribution (malware, threat actors, ATT&CK techniques, CVEs), drafts Sigma / YARA / Suricata detections, exports schema-valid STIX 2.1 and MISP, and offers one-call triage. Bring-your-own-keys, vendor-neutral, tested, CI.

**[pathfinder](https://github.com/FarfallaJ/pathfinder)** — phishing & URL/email analysis. Unwraps and follows a suspicious link *without* a browser, flags typosquats, credential forms, and sketchy infrastructure, checks Google Safe Browsing and PhishTank, renders in headless Chromium for JavaScript-redirect and cloaking detection, and hands the indicators it discovers to the enrichment engine above. Also an MCP server.

Both ship as MCP tools, so an assistant can take a suspicious URL apart, enrich what it finds, and draft the report — one investigation, three tools.

---

### Focus

- Cyber threat intelligence — tactical and strategic, nation-state actors
- Detection engineering — Sigma, YARA, Suricata, ATT&CK coverage
- Interoperability — STIX 2.1 / MISP, so intelligence moves between platforms
- AI-augmented intelligence production — analyst-led, source-cited, built as agent tools
- Bridging CTI into AI-security engineering

---

### How I work

Automation handles the fan-out and the first-pass scoring; judgment, attribution, and estimative language stay with the analyst. Every verdict names its source, indicators are cited and dated, and detection rules ship as drafts to tune — never as deployment-ready truth.

---
