# SOC 101 Notes

Personal study notes for entry-level **SOC (Security Operations Center) analyst** skills: email forensics, network analysis, Windows & Linux investigation, SIEM/Splunk, threat intelligence, and YARA.

> Unofficial notes taken while studying the **SOC 101** course by [TCM Security](https://academy.tcm-sec.com). Not affiliated with or endorsed by TCM Security. Written in my own words for learning. If you want the real material, take the course.

**Author:** NIZARSEC

## Table of Contents

Everything is in one file: [`SOC_101_notes.md`](SOC_101_notes.md)

1. [Email Forensics](SOC_101_notes.md#email-forensics) — headers, SPF/DKIM/DMARC, phishing red flags
2. [Network Analysis Methodology](SOC_101_notes.md#network-analysis-methodology) — Wireshark workflow and filters
3. [IDS / IPS](SOC_101_notes.md#ids--ips) — detection methods
4. [Snort](SOC_101_notes.md#snort) — modes, rule syntax, example rules
5. [Endpoint Security](SOC_101_notes.md#endpoint-security) — EDR, XDR, DLP, UEBA
6. [Windows Network Analysis](SOC_101_notes.md#windows-network-analysis)
7. [Windows Process Analysis](SOC_101_notes.md#windows-process-analysis) — legitimate process properties
8. [Windows Registry](SOC_101_notes.md#windows-registry) — persistence locations
9. [Windows Autoruns](SOC_101_notes.md#windows-autoruns)
10. [Windows Services](SOC_101_notes.md#windows-services)
11. [Windows Scheduled Tasks](SOC_101_notes.md#windows-scheduled-tasks)
12. [Windows Event Logs](SOC_101_notes.md#windows-event-logs) — Security, System and Sysmon event IDs
13. [Linux Network Analysis](SOC_101_notes.md#linux-network-analysis)
14. [Linux Process Analysis](SOC_101_notes.md#linux-process-analysis)
15. [Linux CronJobs](SOC_101_notes.md#linux-cronjobs)
16. [SIEM](SOC_101_notes.md#siem) — components, deployment models, CLI log analysis
17. [Splunk (SPL)](SOC_101_notes.md#splunk-spl)
18. [Threat Intelligence](SOC_101_notes.md#threat-intelligence)
19. [YARA](SOC_101_notes.md#yara)
20. [References](SOC_101_notes.md#references)

## Notes on Use

- All content is defensive and educational. Example paths, domains and hashes are placeholders.
- Found a mistake? Please open an issue or a pull request.
