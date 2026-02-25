# OB29 Cross-God Expansion Notes (Discordia, Athena, Sol, Kukulkan, Medusa)

Generated: 2026-02-25 (UTC)

## Scope

- Build a shared baseline for five gods newly added to this research track: `Discordia`, `Athena`, `Sol`, `Kukulkan`, `Medusa`.
- Anchor conclusions to official SMITE 2 patch notes (OB27-OB29) plus SMITE 2 wiki god pages.
- Treat **OB29** as current patch context.

## Patch Context (OB29 Anchor)

- Current patch: **OB 29 - The Dark Enchantress Update** (published `2026-02-23`).
- Recent chain:
  1. OB29 (`2026-02-23`)
  2. OB28 (`2026-02-09`)
  3. OB27 (`2026-01-27`)
- OB29 system shifts relevant to this god set:
  - Conquest role bonuses were added/updated (`Support`, `Jungle`, `Solo`, `Mid`, `Carry` role-specific value loops).
  - Multiple starters moved to adaptive stat behavior (Strength vs Intelligence decision logic).
  - Several broad item tuning updates landed (for example Brawler's Beat Stick stat reduction, Death Metal rework, and relic upgrade tuning).

## Cross-God Snapshot

| God | Wiki role + release date | OB27-OB29 direct god balance signal | OB29 practical read |
|---|---|---|---|
| Discordia | Mid, released 2026-01-13 | **Yes**: OB27 nerfs and OB28 nerfs | Still playable control mage, but with lower long-range safety and lower self-cooldown tempo than pre-OB27 |
| Athena | Support, released 2024-05-02 | **No direct mention** in OB27/OB28/OB29 | Stable support baseline; OB29 support role economy/sustain context is the bigger lever |
| Sol | Mid, released 2024-05-30 | **No direct mention** in OB27/OB28/OB29 | Stable mage baseline; OB29 adaptive starter/system shifts likely matter more than direct god tuning |
| Kukulkan | Mid, released 2024-05-02 | **Yes**: OB27 Aspect nerf (`Aspect of the Squall`) | Aspect pressure/control profile is toned down vs pre-OB27; default/non-aspect baseline is relatively more attractive |
| Medusa | Carry, released 2024-12-10 | **Yes**: OB27 nerf (`Viper Shot` DoT) | Lane pressure from ability poke is lower than pre-OB27; value skews more toward clean carry fundamentals |

## God-by-God Notes

### Discordia

- Wiki kit anchors: `Contest of Gods`, `Unruly Magic`, `Strife`, `Erratic Behavior`, `Golden Apple of Discord`.
- OB27 changes (official):
  - Passive scaling and lifesteal reduced.
  - `Erratic Behavior` cooldown and cooldown-reduction values reduced.
- OB28 changes (official):
  - `Erratic Behavior` range reduced.
  - `Golden Apple of Discord` max range reduced.
- OB29: no direct Discordia-specific adjustment found.
- Meta implication: OB27+OB28 stack into a clear reduction in safety/range control compared with early-release Discordia.

### Athena

- Wiki kit anchors: `Preemptive Strike`, `Confound`, `Shield Wall`, `Defender of Olympus`.
- OB27-OB29: no direct Athena-specific adjustment found in official notes.
- Meta implication: evaluate Athena mainly through OB29 system context (Support role value and teamfight structure), not new kit tuning.

### Sol

- Wiki kit anchors: `Unstable Manifestation`, `Radiance`, `Stellar Burst`, `Disapparate`, `Supernova`.
- OB27-OB29: no direct Sol-specific adjustment found in official notes.
- Meta implication: Sol profiles as a stability pick in this patch window; system-level starter/item context should drive most build variance.

### Kukulkan

- Wiki kit anchors: `Power of the Wind Jewel`, `Zephyr`, `Slipstream`, `Whirlwind`, `Spirit of the Nine Winds`.
- OB27 change (official):
  - `Aspect of the Squall` nerfed (`Zephyr` slow reduced; `Slipstream` protections interaction reduced).
- OB28/OB29: no direct Kukulkan-specific adjustment found.
- Meta implication: aspect-centric control setups are less oppressive than before; safer baseline paths gain relative value.

### Medusa

- Wiki kit anchors: `Sidewinder`, `Viper Shot`, `Acid Spray`, `Lacerate`, `Petrify`.
- OB27 change (official):
  - `Viper Shot` damage-over-time reduced.
- OB28/OB29: no direct Medusa-specific adjustment found.
- Meta implication: ability poke edge is trimmed; consistent carry positioning and objective DPS become a larger share of her value.

## Meta Assumptions (Explicit)

1. `New gods` here means **new expansion scope for this research pack**, not necessarily newly released in OB29 itself.
2. Conquest role updates in OB29 are assumed to shift value more than direct god tuning for `Athena` and `Sol` (because no direct OB27-OB29 god balance changes were found for them).
3. Discordia/Kukulkan/Medusa are assumed to carry forward OB27/OB28 nerf context into OB29 unless explicitly reverted (no revert found in OB29 notes).
4. Build and matchup recommendations remain medium-confidence until reinforced with patch-locked high-quality Conquest/Arena build datasets for each god.

## Confidence and Limits

- High confidence:
  - Patch identity/date anchoring.
  - Presence/absence of direct god mentions in OB27/OB28/OB29 notes.
  - Wiki role/release-date/kit anchor extraction.
- Medium confidence:
  - Forward-looking meta impact interpretation from system-level changes.
- Known limit:
  - This pass does not include a pro-only or tournament-only feed for these five gods in OB29.

## Source List

### Official patch/news

- https://www.smite2.com/news/
- https://www.smite2.com/news/open-beta-29-update-notes/
- https://www.smite2.com/news/open-beta-28-update-notes/
- https://www.smite2.com/news/open-beta-27-update-notes/
- https://www.smite2.com/news/open-beta-26-update-notes/

### Official content API (used for reliable extraction of patch text/timestamps)

- https://webcms.hirezstudios.com/smite2/api/posts/?filters[slug][$eq]=open-beta-29-update-notes&lng=en-US&populate=*
- https://webcms.hirezstudios.com/smite2/api/posts/?filters[slug][$eq]=open-beta-28-update-notes&lng=en-US&populate=*
- https://webcms.hirezstudios.com/smite2/api/posts/?filters[slug][$eq]=open-beta-27-update-notes&lng=en-US&populate=*
- https://webcms.hirezstudios.com/smite2/api/posts/?filters[slug][$eq]=open-beta-26-update-notes&lng=en-US&populate=*

### SMITE 2 wiki god pages

- https://wiki.smite2.com/w/Discordia
- https://wiki.smite2.com/w/Athena
- https://wiki.smite2.com/w/Sol
- https://wiki.smite2.com/w/Kukulkan
- https://wiki.smite2.com/w/Medusa
