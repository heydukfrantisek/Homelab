# Change lifecycle

Každá změna infrastruktury prochází jednotným životním cyklem:
1. Request – požadavek a očekávaný výsledek.
2. Discovery – read-only inventura a ověření cílového prostředí.
3. Impact analysis – závislosti, dostupnost, bezpečnost a možnost návratu.
4. Plan – přesný rozsah změny a ověřovací kritéria.
5. Review – kontrola Managerem/Auditorem a schválení člověkem.
6. Execution – provedení schváleného plánu adaptérem s minimálními oprávněními.
7. Verification – kontrola výsledného stavu.
8. Record – auditní záznam a aktualizace dokumentace.

Pokud se skutečný stav liší od předpokladů, workflow se zastaví a vrátí do Discovery.
