# Core Rules — AD&D 2nd Edition Data Layer {#mainpage}

This library, **Core Rules**, is a modern C++ re-implementation of the data model
that underpinned TSR / Wizards of the Coast's *Advanced Dungeons & Dragons
CD-ROM Core Rules* software. It reads, writes, and reasons about the same
characters, monsters, spells, items, and encounter data that the original
product stored, exposing them through a clean, documented API (the **Drakein**
interface) for use by the Drakein Campaign Toolkit and related tools.

The rest of this reference documents that API and its implementation. This page
describes the original product the data comes from, and the copyrights that
govern it.

---

## The original product

**Advanced Dungeons & Dragons: CD-ROM Core Rules** was TSR's electronic edition
of the AD&D 2nd Edition rules — a Windows CD-ROM that delivered the core
rulebooks as hyperlinked, searchable text alongside a suite of play aids.

### Release history

| Release | Year | Published by | Notes |
|---|---|---|---|
| **Core Rules 1.0** | 1996 | **TSR, Inc.** | Original release. Developed for TSR by the startup Evermore Entertainment (Victor Penman, Project Manager). |
| **Core Rules 2.0** | 1999 | **Wizards of the Coast** | Major update, released after WotC's 1997 acquisition of TSR. Added the *Player's Option* line and *DM Option: High-Level Campaigns*. |
| **Core Rules 2.0 Expansion** | 1999 | **Wizards of the Coast** | The final release. A separately-sold add-on (requiring Core Rules 2.0) that folded in eleven volumes of the *Complete Handbook* / *Complete Book* series. |

Wizards of the Coast acquired TSR, Inc. in 1997; WotC is today a subsidiary of
Hasbro, Inc.

### Rulebooks included

Core Rules shipped the full text of the primary AD&D 2nd Edition rulebooks,
including the *Player's Handbook*, *Dungeon Master's Guide*, *Monstrous Manual*,
*Tome of Magic*, and the *Arms and Equipment Guide*, plus a Key Topics rules
summary. Version 2.0 added the *Player's Option: Combat & Tactics*, *Skills &
Powers*, and *Spells & Magic* volumes, and *DM Option: High-Level Campaigns*.
The 2.0 Expansion added the *Complete Handbook* series (Bard, Druid, Fighter,
Paladin, Priest, Ranger, Thief, Wizard) and the *Complete Book* series (Dwarves,
Elves, Gnomes & Halflings).

### Software tools

Beyond the rulebooks, the product bundled a set of utilities whose data formats
this library reproduces:

- a **character generator** for rapid PC creation, plus tools to enter
  manually-rolled characters,
- **NPC / monster** generation,
- random **treasure** and **encounter** generators, and
- a **map builder**.

Content was distributed as Rich Text Format documents and hyperlinked Windows
Help files.

---

## Copyright & trademark notices

> *Advanced Dungeons & Dragons* and the *CD-ROM Core Rules* product, including
> all rules text, monsters, spells, items, artwork, and other content
> reproduced or modeled by this library, are:
>
> **Copyright © 1996 TSR, Inc.**
> **Copyright © 1999 Wizards of the Coast, Inc.**
>
> *Advanced Dungeons & Dragons*, *AD&D*, *Dungeons & Dragons*, *D&D*, *TSR*, and
> all related product names, logos, and marks are trademarks of Wizards of the
> Coast LLC (a subsidiary of Hasbro, Inc.), successor-in-interest to TSR, Inc.
> All rights reserved.

### About this project

This is an independent, non-commercial project. It is **not** created,
endorsed, sponsored by, or affiliated with Wizards of the Coast LLC, Hasbro,
Inc., or the former TSR, Inc. It contains no copyrighted rules text, artwork, or
data from the original product; it implements the *file formats and data
structures* used to store campaign data so that owners of the original CD-ROM
can continue to work with their own saved data on modern systems.

The Core Rules library source code and this documentation are the work of the
project's authors and are covered by the project's own license. All references
to the AD&D game and the CD-ROM Core Rules product are made for
interoperability and identification purposes only.
