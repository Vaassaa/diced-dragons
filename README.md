# diced-dragons

A personal D&D 5e repository: the three 2014 core rulebooks and the 2024
Player's Handbook split into per-chapter PDFs for quick lookup at the table,
plus the working files for the **Vratikraj** campaign.

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
PHB2024/      Player's Handbook (2024), 7 chapters + 3 appendices + index

VGtM2016/     Volo's Guide to Monsters
XGtE2017/     Xanathar's Guide to Everything
MToF2018/     Mordenkainen's Tome of Foes
TCoE2020/     Tasha's Cauldron of Everything
FToD2021/     Fizban's Treasury of Dragons
MPMotM2022/   Mordenkainen Presents: Monsters of the Multiverse
BPCOTG2023/   Bigby Presents: Glory of the Giants

Homebrew/     Fan material: the Artificer class pages, a disease compilation
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

### PHB2024 — Player's Handbook (2024)

The 2024 revision of the Player's Handbook. The page ranges come from the
book's own bookmarks.

| File | Pages | Contents |
| --- | --- | --- |
| `PHB24_intro.pdf` | 1–5 | Cover, contents, Welcome to Adventure |
| `PHB24_chap1_playingTheGame.pdf` | 6–31 | Playing the Game |
| `PHB24_chap2_creatingCharacter.pdf` | 32–47 | Creating a Character |
| `PHB24_chap3_classes.pdf` | 48–175 | Character Classes |
| `PHB24_chap4_origins.pdf` | 176–197 | Character Origins (backgrounds, species) |
| `PHB24_chap5_feats.pdf` | 198–211 | Feats |
| `PHB24_chap6_equip.pdf` | 212–233 | Equipment |
| `PHB24_chap7_spells.pdf` | 234–342 | Spells |
| `PHB24_appA_multiverse.pdf` | 343–344 | Appendix A: The Multiverse |
| `PHB24_appB_creatureStats.pdf` | 345–358 | Appendix B: Creature Stat Blocks |
| `PHB24_appC_rulesGlossary.pdf` | 359–376 | Appendix C: Rules Glossary |
| `PHB24_index.pdf` | 377–387 | Index |

## Supplements

Seven supplement books, split the same way and for the same reason. The page
ranges were worked out from each book's own contents page and checked against
the chapter openings in the body; `tools/split_book.py` in the dmtools
checkout holds them and can redo the split.

Two of these are OCR'd scans whose page numbers come out damaged, and
**Bigby's has no text layer at all** — every page is a JPEG, so nothing in it
can be searched or extracted without OCR first.

| Directory | Book | Files | Pages |
| --- | --- | --- | --- |
| `VGtM2016/` | Volo's Guide to Monsters | 7 | 226 |
| `XGtE2017/` | Xanathar's Guide to Everything | 6 | 196 |
| `MToF2018/` | Mordenkainen's Tome of Foes | 8 | 258 |
| `TCoE2020/` | Tasha's Cauldron of Everything | 5 | 194 |
| `FToD2021/` | Fizban's Treasury of Dragons | 7 | 227 |
| `MPMotM2022/` | Mordenkainen Presents: Monsters of the Multiverse | 4 | 291 |
| `BPCOTG2023/` | Bigby Presents: Glory of the Giants (scanned) | 9 | 193 |

Each follows the core books' naming: `<PREFIX>_intro.pdf`, then
`<PREFIX>_chapN_<name>.pdf` and `<PREFIX>_appX_<name>.pdf`. As with the core
three, a part-divider page is kept with the chapter it opens.

The full-book PDFs are **still here** — unlike the core three, they have not
been deleted. Removing them is a one-way step and the split can always be
redone from them, so that is left as a deliberate choice rather than a side
effect of splitting.

## Vratikraj — campaign management

`Vratikraj/` is where the campaign of the same name is run from: everything the
DM needs between and during sessions lives here, separate from the rulebooks.

```
Vratikraj/
  cartography/   Maps of the campaign world
  sesh_info/     Per-session notes, one file per session
```
