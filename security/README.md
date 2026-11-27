# Security model

Bezpečnost se nevynucuje pouze promptem. Musí být implementována v infrastruktuře a nástrojích.

## Základní vrstvy
- Proxmox ACL a oddělené API tokeny.
- SSH klíče a omezené účty/příkazy.
- Síťová segmentace a firewall.
- Správa tajných údajů mimo Git.
- Schvalování změn a auditní log.
- Read-only výchozí režim.
- Testovací/simulační prostředí pro nové automatizace.

Do repozitáře nepatří hesla, tokeny, privátní klíče ani recovery kódy. Používat secret manager nebo chráněné proměnné prostředí.
