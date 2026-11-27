# Proxmox API adapter

Plánované rozhraní pro Proxmox VE API.

Požadavky:
- oddělené identity/tokeny pro read-only inventuru a schválené zápisy;
- minimální ACL rozsah;
- ověřování TLS certifikátu;
- timeouty, retry pouze pro bezpečné operace a rate limiting;
- redakce citlivých údajů v logu;
- explicitní allowlist podporovaných operací.

Konkrétní endpointy a oprávnění doplníme po ověření cílového prostředí.
