# HTB Write-ups — werkwijze

Deze map bevat twee templates:

- `HTB_WRITEUP_TEMPLATE.md` — gebruik deze als **werkdocument** in Obsidian of Visual Studio Code.
- `_template.html` — gebruik deze als **publicatie-template** voor de website.

## Aanbevolen workflow

1. Rond de HTB-machine af en bewaar je volledige technische notities privé.
2. Bekijk de resultaten van Superscanv2 en selecteer alleen bevindingen die onderdeel werden van de aanvalsketen.
3. Kopieer `HTB_WRITEUP_TEMPLATE.md` naar bijvoorbeeld `machine-naam.md`.
4. Schrijf eerst de korte Markdown-write-up. Richtlijn: ongeveer 500–900 woorden.
5. Controleer vóór publicatie op IP-adressen, flags, wachtwoorden, tokens, gevoelige screenshots en onnodige spoilers.
6. Kopieer `_template.html` naar bijvoorbeeld `machine-naam.html`.
7. Zet de definitieve tekst uit het Markdown-bestand in de bijbehorende HTML-secties.
8. Voeg op `index.html` in de sectie `HTB Write-ups` een nieuwe kaart toe die naar `writeups/machine-naam.html` verwijst.

## Wat blijft privé?

Je ruwe scanoutput, persoonlijke pentestnotities en complete commandohistorie hoeven niet op de website. De website laat alleen de relevante route, je redenering en je leerpunten zien.
