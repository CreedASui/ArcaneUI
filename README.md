# Arcane UI

A clean, smooth HUD for **Azeroth Survivors** ([wow.aethus.pl](https://wow.aethus.pl)), the World of Warcraft 1.12 roguelike. Dark glass, forged metal and a choice of looks for your skill bar, and it all steps aside while you pick your cards.

## Install

1. Download the latest `Arcane-<version>.zip` from [Releases](../../releases).
2. Unzip it into your game's `Interface/AddOns` folder. You should end up with `Interface/AddOns/Arcane/Arcane.toc`.
3. The folder must stay named `Arcane`: the game loads it by that name, and your settings are kept under it.

Click the **A** on the minimap's edge (or type `/arcane`) for the options.

## What's in it

**Your skill bar, three ways**
- **Classic:** Arcane's bronze sigil on the ends of the bar.
- **Hybrid:** a forged medallion with a gem in your class's color, and your class's crest.
- **Full Class:** your class's emblem, crest and colors across the whole UI.

**The run**
- **Boss timer:** a countdown to each boss in each zone's own colors, with the run's time.
- **Boss and mini-boss bars**, and **skulls** over bosses and guardians.
- **Loot pop-up:** each drop and the marks you earn, in its rarity's color.
- **Run summary** when a run ends.

**You and your party**
- **Your frame and party frames**, with your friends' shields and a right-click menu (inspect, follow, whisper).
- **Damage taken and heals** as numbers beside your hero, and **downed friends** marked for revival.

**Numbers and windows**
- **Damage numbers** in several motions and fonts, with optional backdrops behind crits.
- **Damage meter**, **Stats window**, **luck medallion**, **pet bar**, **talent window** and a dressed **character window**.

**Everything else**
- **Minimap** with the caches and the guardians' lairs, **nameplates**, a dressed **chat**, and the game's **notification messages** and **floating heal and buff text** in the UI's colors.

Every part can be turned on or off, sized and moved. **Languages:** English, French, German, Spanish, Portuguese, Chinese, Russian, Japanese, Korean, Polish and Turkish.

## Commands

| Command | What it does |
| --- | --- |
| `/arcane` (or `/aui`) | Opens the options (or click the A on the minimap's edge) |
| `/arcane move`, `/arcane lock` | Frees the frames to drag them, then locks them |
| `/arcane reset` | Puts every frame back in its place |
| `/arcane language <code>` | Picks the language |
| `/arcane timer ...`, `/arcane numbers ...` | The boss timer's and damage numbers' own settings |
| `/arcane talents` | Opens the talent window |
| `/arcane probe` | Prints what the game gives addons, for reporting what's missing |

## Releases

**Actions → Release → Run workflow**, type the new version (for example `0.8`). It sets the version, builds `Arcane-<version>.zip` with the `Arcane` folder inside and publishes the release with that version's entry from [CHANGELOG.md](CHANGELOG.md).

## Credits

Arcane UI is built on [Creed UI](https://github.com/CreedASui/CreedUI-for-AS-) for Azeroth Survivors; see [Arcane/ATTRIBUTION.md](Arcane/ATTRIBUTION.md) for its history. Its nameplates adapt Valorless's MIT-licensed [ASTinyPlates](https://github.com/Valorless/ASTinyPlates) (see `Arcane/ArcaneNameplates-LICENSE.txt`). The bundled fonts are made from Lora and Noto Sans CJK, and the damage numbers' fonts from Cinzel, Bangers, Creepster, Uncial Antiqua, Black Ops One and Pirata One, all under the SIL Open Font License (see `Arcane/Fonts/`).
