---
title: "Hack The Box - [MACHINE]"
difficulty: "[Easy / Medium / Hard]"
os: "[Linux / Windows]"
date: YYYY-MM-DD
tags:
  - HackTheBox
  - Pentesting
  - Cybersecurity
---

# Hack The Box - [MACHINE]

## Overview

**Machine:** [Naam]  
**Difficulty:** [Easy / Medium / Hard]  
**Operating System:** [Linux / Windows]

In deze lab lag de focus voornamelijk op **[bijvoorbeeld: web enumeration, SMB, privilege escalation]**.

`Recon → Enumeration → Initial Access → Privilege Escalation`

---

## Reconnaissance

Ik begon de machine met mijn **Superscanv2** workflow.

| Port | Service | Interessant omdat |
|---:|---|---|
| XX | HTTP | Webapplicatie aanwezig |
| XX | SSH | Mogelijke remote toegang |
| XX | [SERVICE] | [Waarom interessant] |

Niet iedere gevonden service bleek relevant. Daarom heb ik mij voornamelijk gericht op **[service]**.

---

## Enumeration

Tijdens verdere enumeratie van **[service/applicatie]** ontdekte ik:

- [Belangrijkste bevinding]
- [Interessante directory/share/configuratie]
- [Technologie of softwareversie]

> [Korte omschrijving van de belangrijkste aanwijzing.]

Hierdoor besloot ik verder onderzoek te doen naar **[kwetsbaarheid / configuratiefout / functionaliteit]**.

---

## Initial Access

Uit de enumeratie bleek dat **[korte omschrijving kwetsbaarheid]** aanwezig was.

`[kwetsbaarheid] → [effect] → initial access`

Hiermee verkreeg ik toegang tot het systeem als een gebruiker met beperkte rechten.

---

## Privilege Escalation

Na initial access begon ik met lokale enumeratie. Ik controleerde onder andere gebruikersrechten, SUID binaries / sudo-rechten, services, configuratiebestanden, cronjobs / scheduled tasks en interessante bestanden.

De belangrijkste ontdekking was **[bevinding]**.

Door **[korte uitleg van de misconfiguratie/kwetsbaarheid]** kon ik mijn rechten verhogen.

`Initial Access → [misconfiguratie] → Privilege Escalation → Administrator/Root`

---

## Attack Path

```text
Superscanv2
    ↓
Open services identificeren
    ↓
[Interessante service]
    ↓
Enumeration
    ↓
[Belangrijkste bevinding]
    ↓
Initial Access
    ↓
Lokale enumeratie
    ↓
[Privilege Escalation techniek]
    ↓
Administrator / Root
```

---

## Wat ik hiervan heb geleerd

Deze machine was vooral nuttig voor het oefenen van:

- **[techniek 1]**
- **[techniek 2]**
- **[techniek 3]**

> [1 à 2 zinnen over je belangrijkste leerpunt.]

---

## Gebruikte tools

`Superscanv2` • `[tool]` • `[tool]` • `[tool]`

---

**Disclaimer:** deze write-up is gemaakt voor educatieve doeleinden binnen een gecontroleerde Hack The Box-omgeving. IP-adressen, flags, wachtwoorden en andere gevoelige gegevens zijn bewust weggelaten.
