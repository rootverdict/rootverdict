## Aryan Hirapara

**M.Sc. Digital Forensics & Information Security — National Forensic Sciences University**
Blue-team & detection engineering · network forensics · detection-as-code

I build evidence-backed security tooling and contribute fixes to open-source
blue-team platforms. Every project below ships with tests, CI, and reproducible
evidence artifacts.

### Projects

| Project | What it does | Stack |
|---|---|---|
| [detfuzz](https://github.com/rootverdict/detfuzz) | Evidence-backed detection-resilience testing for PowerShell/Sigma rules — safe mutations correlated against Sysmon telemetry, 98 unit tests, signed release | Python · pySigma · Sysmon |
| [NetTrace](https://github.com/rootverdict/NetTrace) | Offline malware-traffic analysis — PCAP parsing, beaconing/DGA detection, MITRE ATT&CK mapping, PDF reports. Validated on 12 real malware captures | Python · Scapy |
| [soc-automation-lab](https://github.com/rootverdict/soc-automation-lab) | End-to-end SOC pipeline: Wazuh detection → n8n SOAR triage → VirusTotal → Velociraptor forensics, with an 18-case analyst casebook | Wazuh · n8n · Velociraptor |
| [MalForge](https://github.com/rootverdict/MalForge) | Sandbox-report → detection-rule pipeline: Cuckoo/CAPE JSON → Sigma → Wazuh, with stable rule IDs and risk scoring | Python · Sigma |
| [signalbudget](https://github.com/rootverdict/signalbudget) | Cost-aware telemetry planning — Pareto frontier over ingest cost vs. hash-verified detection coverage | Python (zero-dep) |
| [vigilant-api](https://github.com/rootverdict/vigilant-api) | Black-box API security scanner — OpenAPI-driven BOLA/IDOR/SSRF/JWT testing with forensic evidence output | Python · OpenAPI |

### Open-source contributions

- **[Panther](https://github.com/panther-labs/panther-analysis)** — fixed a Kubernetes IOC detection query (Snowflake clause ordering) · **merged**
- **[Wazuh](https://github.com/wazuh/wazuh)** — corrected RestrictAnonymous registry checks in Windows CIS policies
- **[IntelMQ](https://github.com/certtools/intelmq)** — CSV formula-injection fix in spreadsheet exports
- **[IRIS](https://github.com/dfir-iris/iris-web)** · **[TheHive4py](https://github.com/TheHive-Project/TheHive4py)** — session-handling fix / API documentation
