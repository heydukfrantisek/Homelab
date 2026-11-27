# Automation

Automatizace budou rozdělené podle rizika:
- Read-only: inventura, reporty, health checks.
- Low-risk write: pouze po návrhu a schválení.
- High-risk: mazání, migrace, storage, síť, reboot/shutdown – zvláštní potvrzení a rollback plán.

Každá automatizace musí mít popis, vstupy, oprávnění, dry-run, idempotenci, timeout, ověření výsledku a testy.
