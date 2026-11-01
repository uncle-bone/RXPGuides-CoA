# RXPGuides-CoA

**RestedXP-inspired leveling guide development for Ascension Conquest of Azeroth — Conquest Reborn (WoW 3.3.5a).**

> **Development status:** Early research and compatibility work. A playable, fully tested addon has **not** been released yet.

RXPGuides-CoA aims to bring the familiar step-by-step leveling guide experience to the custom Conquest Reborn client. The project focuses on a dedicated 3.3.5a guide engine, accurate custom quest data, map navigation, and support for the realm's 21 classes and specializations.

## Planned features

- **Guided leveling:** quest pickup, objectives, turn-ins, automatic step progression, and saved guide position.
- **Navigation:** map and minimap waypoints, direction assistance, and compatibility with Mapster/Magnify and Questie-X.
- **CoA-aware routes:** custom zones, quest prerequisites, optional branches, and level-scaling behavior where verified.
- **Class support:** recognition of all 21 Conquest of Azeroth classes and their specializations.
- **Guide coverage:** research-backed Vanilla, Burning Crusade, Wrath of the Lich King, and custom CoA content; no Cataclysm+ content.
- **Interface compatibility:** Blizzard default UI, DragonUI, and ElvUI.
- **Performance:** load only needed guide data, minimize redundant quest scanning, and offer clickable settings.
- **Research transparency:** distinguish client-tested routes from database-backed or unverified guide steps.

These are **development goals**, not claims of finished functionality.

## First custom-zone research: Pale Reach

The initial research package includes **237 quest records**, **134 prerequisite relationships**, and **41 coordinate records**. A draft guide checklist exists, but quest order, availability, objective details, and navigation require in-game testing. Source summaries disagree on how many distinct quests have coordinates, so this must be reconciled. Pale Reach level scaling from 18–60 applies **only when scaling is enabled**.

## Roadmap

See [ROADMAP.md](ROADMAP.md) for milestones: backport and test the guide engine, implement reliable quest progression and navigation, normalize the CoA guide database, build and verify Pale Reach, then expand coverage.

## Research and upstream projects

- [RestedXP / RXPGuides](https://github.com/RestedXP/RXPGuides) — original guide platform.
- [CoA-Research](https://github.com/downingwow/CoA-Research) — collected Conquest of Azeroth research.
- Questie-X and Zygor-CoA research extracts — quest, map, and guide validation inputs.

## Maintainer and attribution

**Maintainer:** Uncle Bone  
**Repository:** https://github.com/uncle-bone/RXPGuides-CoA

This is an independent community development project and is not endorsed by RestedXP. Any reuse of upstream source or assets must comply with applicable licensing and distribution permissions; required upstream and third-party notices must be preserved.
