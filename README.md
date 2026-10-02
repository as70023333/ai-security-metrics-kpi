# AI Security Metrics & KPI Pipeline (`ai-security-metrics-kpi`)

An open-source framework and automated pipeline for aggregating, calculating, and reporting **AI Security & Governance KPIs**. Designed for Security Architects, CISOs, and SecOps teams managing enterprise LLM applications and cloud AI infrastructure.

## Key Features
- **Guardrail Telemetry Processing:** Tracks Prompt Injection Resilience and Evasion attempts.
- **Shadow AI & Asset Coverage:** Maps cataloged vs. uncataloged AI endpoint queries.
- **SOC Efficiency Automation:** Measures Alert Signal-to-Noise Ratio (SNR) and MTTR improvements via SOAR playbooks.
- **Automated Reporting:** Generates executive Markdown & JSON briefs automatically via GitHub Actions.

## Quickstart
```bash
git clone [https://github.com/as70023333/ai-security-metrics-kpi.git](https://github.com/as70023333/ai-security-metrics-kpi.git)
cd ai-security-metrics-kpi
python3 src/collector.py
