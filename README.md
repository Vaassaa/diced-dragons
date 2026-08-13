# diced-dragons

A personal D&D 5e (2014 ruleset) repository: the three core rulebooks split into
per-chapter PDFs for quick lookup at the table, plus the working files for the
**Vratikraj** campaign.

## Why the books are split

The full rulebooks are large, slow to open, and awkward to search on a laptop or
tablet mid-session. Each book is therefore stored as one PDF per chapter, so you
can open just the section you need — combat, spells, treasure — without loading
several hundred pages. The original full-book PDFs are not kept in the repo.

## Repository layout

```
PHB2014/      Player's Handbook, 14 chapters
DMG2014/      Dungeon Master's Guide, 9 chapters + 4 appendices + index
MM2014/       Monster Manual, 4 sections + index
Vratikraj/    Campaign management for the Vratikraj campaign
```

### PHB2014 — Player's Handbook

| File | Contents |
| --- | --- |
| `PHB_chap1_intro.pdf` | Introduction |
| `PHB_chap2_races.pdf` | Races |
| `PHB_chap3_classes.pdf` | Classes |
| `PHB_chap4_backgrounds.pdf` | Personality and Background |
| `PHB_chap5_equip.pdf` | Equipment |
| `PHB_chap6_customOpt.pdf` | Customization Options |
| `PHB_chap7_usingAbS.pdf` | Using Ability Scores |
| `PHB_chap8_adventuring.pdf` | Adventuring |
| `PHB_chap9_combat.pdf` | Combat |
| `PHB_chap10_spellcasting.pdf` | Spellcasting |
| `PHB_chap11_spells.pdf` | Spells |
| `PHB_chap12_conditions.pdf` | Conditions |
| `PHB_chap13_mythology.pdf` | Gods of the Multiverse |
| `PHB_chap14_creatureStats.pdf` | Creature statistics |

### DMG2014 — Dungeon Master's Guide

| File | Pages | Contents |
| --- | --- | --- |
| `DMG_intro.pdf` | 1–6 | Cover, credits, contents, introduction |
| `DMG_chap1_worldOfYourOwn.pdf` | 7–42 | A World of Your Own |
| `DMG_chap2_creatingMultiverse.pdf` | 43–68 | Creating a Multiverse |
| `DMG_chap3_creatingAdventures.pdf` | 69–88 | Creating Adventures |
| `DMG_chap4_creatingNPCs.pdf` | 89–98 | Creating Nonplayer Characters |
| `DMG_chap5_adventureEnvironments.pdf` | 99–124 | Adventure Environments |
| `DMG_chap6_betweenAdventures.pdf` | 125–132 | Between Adventures |
| `DMG_chap7_treasure.pdf` | 133–232 | Treasure (incl. magic items) |
| `DMG_chap8_runningTheGame.pdf` | 233–262 | Running the Game |
| `DMG_chap9_dmWorkshop.pdf` | 263–289 | Dungeon Master's Workshop |
| `DMG_appA_randomDungeons.pdf` | 290–301 | Appendix A: Random Dungeons |
| `DMG_appB_monsterLists.pdf` | 302–309 | Appendix B: Monster Lists |
| `DMG_appC_maps.pdf` | 310–315 | Appendix C: Maps |
| `DMG_appD_dmInspiration.pdf` | 316 | Appendix D: Inspirational Reading |
| `DMG_index.pdf` | 317–320 | Index |

Part-divider pages are kept with the chapter that follows them.

### MM2014 — Monster Manual

The Monster Manual has no chapters, so it is split along its actual structure.

| File | Pages | Contents |
| --- | --- | --- |
| `MM_sec1_intro.pdf` | 1–12 | Cover, contents, introduction (how to read a stat block) |
| `MM_sec2_monsters.pdf` | 13–317 | Monsters A–Z |
| `MM_sec3_appA_miscCreatures.pdf` | 318–342 | Appendix A: Miscellaneous Creatures |
| `MM_sec4_appB_npcs.pdf` | 343–351 | Appendix B: Nonplayer Characters |
| `MM_index.pdf` | 352–354 | Index of stat blocks |

## Vratikraj — campaign management

`Vratikraj/` is where the campaign of the same name is run from: everything the
DM needs between and during sessions lives here, separate from the rulebooks.

```
Vratikraj/
  cartography/   Maps of the campaign world
  sesh_info/     Per-session notes, one file per session
```

- **`cartography/`** — hand-drawn / generated maps of the setting.
  `Divocina.pdf` is the wilderness map.
- **`sesh_info/`** — a numbered record of each session (`sesh1.pdf`,
  `sesh2.pdf`, …): what happened, who was there, loose threads to pick up next
  time. Add a new file per session rather than editing old ones, so the campaign
  log stays chronological.

New campaigns get their own top-level folder following the same pattern.

## Notes

- The rulebook PDFs were split page-exactly, without re-encoding, so image and
  text quality matches the originals.
- Page numbers in the tables above are PDF page numbers, not printed page
  numbers (they differ by a page or two in the MM).
