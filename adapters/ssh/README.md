# SSH adapter

SSH je doplňkový, omezený kanál pro diagnostiku a operace, které nejsou vhodné pro API.

Zásady:
- dedikovaná identita, žádné sdílené root heslo;
- omezené příkazy a oprávnění;
- přednost read-only příkazům;
- audit příkazů a výstupů s redakcí tajných údajů.
