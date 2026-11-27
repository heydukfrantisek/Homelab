# Proxmox Homelab Intelligence Ecosystem

Modulární ekosystém pro správu, automatizaci, monitoring a audit Proxmox VE s využitím specializovaných AI agentů.

> Projekt je ve fázi základní kostry. Konkrétní technologie, adresace, oprávnění a provozní parametry se budou doplňovat až po ověření prostředí.

## Cíle
- Jednotné řízení Proxmox prostředí přes bezpečné a auditovatelné workflow.
- Specializovaní agenti: Manager, Coder, Auditor a později další role.
- Oddělení společného jádra od adaptérů pro GitHub Copilot, Kilo a Proxmox.
- Monitoring stavu infrastruktury a služeb.
- Změny řízené návrhem, kontrolou, schválením a ověřením.
- Uživatelská dokumentace bez instalačních postupů.

## Principy
1. Human-in-the-loop: rizikové operace vyžadují výslovné schválení.
2. Least privilege: oprávnění se vynucují mimo instrukce agenta.
3. Read-first: před změnou nejprve inventura a ověření stavu.
4. Auditable by default: každá změna má důvod, rozsah, schválení a výsledek.
5. Provider-neutral core: společná pravidla nejsou závislá na jednom AI klientovi.
6. No secrets in Git: hesla, tokeny a privátní klíče se do repozitáře neukládají.

## Struktura
- core/ – společné kontrakty, workflow a modely.
- agents/ – role a odpovědnosti AI agentů.
- adapters/ – integrace Copilot, Kilo, Proxmox API a SSH.
- monitoring/ – sběr metrik, health checks a alerting.
- automation/ – schvalované automatizační úlohy.
- security/ – bezpečnostní model a policy.
- docs/ – uživatelská dokumentace a architektura.
- operations/ – provozní evidence, změny a incidenty.
- schemas/ – strojově čitelné datové kontrakty.
- tests/ – testy, fixtures a bezpečnostní scénáře.

## Stav projektu
| Oblast | Stav |
|---|---|
| Základní repozitář a struktura | Inicializováno |
| Role agentů a workflow | Návrh |
| Proxmox API/SSH adaptéry | Plánováno |
| Monitoring | Plánováno |
| Bezpečnostní policy | Návrh |
| Testy a simulace | Plánováno |

Začněte v docs/README.md. Technické instrukce pro agenty a adaptéry jsou oddělené od uživatelské dokumentace.
