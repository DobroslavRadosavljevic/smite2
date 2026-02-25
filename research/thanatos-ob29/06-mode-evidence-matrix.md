# Mode Evidence Matrix (Thanatos Builds)

Date anchored: **2026-02-25**

## How this was extracted

- Source: [SmiteSource Thanatos build index](https://smitesource.com/builds?god=thanatos)
- Method: parsed embedded `initialBuilds.builds[]` payload and collected `patchShortName`, `roles`, `gameModes`, and `slug`.
- Purpose: verify whether current-patch signal is Conquest-only or has solid Arena-specific support.

## Extracted build metadata


| Build ID | Slug                               | Patch | Roles                 | Game Modes                      |
| -------- | ---------------------------------- | ----- | --------------------- | ------------------------------- |
| 1276     | `thanatos-jungle`                  | OB29  | Jungle                | Conquest                        |
| 1125     | `thanatos-jungle-5b8p6i`           | OB28  | Jungle                | Conquest                        |
| 1223     | `throat-goat-thanatos-build`       | OB28  | Jungle                | Conquest                        |
| 1203     | `reaper-thanatos`                  | OB28  | Jungle                | Conquest                        |
| 909      | `max-damage-jungle-build-1wcusg`   | OB27  | Jungle                | Conquest                        |
| 908      | `core-jungle-build-btcko5`         | OB27  | Jungle                | Conquest                        |
| 924      | `protection-scaling-damage-33pmji` | OB27  | Solo                  | Conquest, Arena, Joust, Assault |
| 1003     | `rob-zombie-u2aaxk`                | OB27  | Jungle                | Joust                           |
| 986      | `than-solo-cuz8g2`                 | OB27  | Solo                  | Conquest                        |
| 955      | `hp-tankatos-0khh4n`               | OB27  | Jungle, Solo, Support | All                             |


## Key takeaway

- The strongest and newest direct signal for Thanatos is still **Conquest Jungle (OB29)**.
- There is **no dedicated OB29 Arena-only Thanatos build** in this extracted set.
- Arena recommendations in this pack are therefore **OB29-adjusted adaptations** built from:
  - OB29 item/system context
  - Thanatos kit mechanics from wiki
  - older multi-mode Thanatos build patterns

## Source links

- [SmiteSource - Thanatos builds](https://smitesource.com/builds?god=thanatos)
- [SmiteSource - Thanatos Jungle (OB29)](https://smitesource.com/build/thanatos-jungle)
- [SMITE 2 Wiki - Thanatos](https://wiki.smite2.com/w/Thanatos)

