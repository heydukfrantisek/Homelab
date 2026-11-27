# Architektura

~~~mermaid
flowchart TD
 U[Uživatel] --> M[Manager]
 M --> C[Coder]
 M --> A[Auditor]
 M --> O[Monitor]
 C --> W[Change workflow]
 A --> W
 W --> P[Externí policy a schválení]
 P --> API[Proxmox API adapter]
 P --> SSH[SSH adapter]
 API --> PV[Proxmox VE]
 SSH --> PV
 PV --> T[Monitoring a telemetrie]
 T --> O
~~~

Vrstvy: uživatelské rozhraní, role agentů, společné workflow, externí bezpečnostní policy, integrační adaptéry, monitoring a auditní evidence. Konkrétní technologie a nasazení budou rozhodnuty samostatně.