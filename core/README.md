# Core

Provider-neutral společné jádro ekosystému.
- contracts/ – vstupy, výstupy a rozhraní mezi agenty a adaptéry.
- workflows/ – standardní pracovní postupy.
- models/ – doménové modely uzlů, CT, VM, storage a síťových objektů.
- policies/ – společné policy reference; skutečné vynucení je externí.
- events/ – standardizované události a auditní záznamy.

Jádro nesmí obsahovat přihlašovací údaje ani klientsky specifické instrukce.
