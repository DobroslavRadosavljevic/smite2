# Track H: Source Quality Audit, Contradiction Checks, and Confidence Bounds

Date anchored: **2026-02-25 (UTC)**

## Scope and method

Audited files:
- `01-sources-and-methodology.md`
- `02-patch-context-ob29.md`
- `03-thanatos-kit-and-item-synergy.md`
- `04-best-build-and-variants.md`
- `05-practical-gameplan-and-swaps.md`
- `06-mode-evidence-matrix.md`
- `README.md`

Validation method:
1. Re-verify patch facts directly from first-party CMS API payloads.
2. Re-verify god/item mechanics from wiki raw wikitext entries.
3. Re-check SmiteSource build index/build-page metadata for patch/mode/role consistency.
4. Re-grade SMITEFire and Tacter as lower-tier context-only sources.
5. Cross-check each substantive claim for internal contradiction and overreach.

## Source hierarchy (strict)

### Tier 0 (highest): first-party structured patch data

- [OB29 CMS API payload](https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-29-update-notes&lng=en-US&populate=*)
- [OB28 CMS API payload](https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-28-update-notes&lng=en-US&populate=*)
- [OB27 CMS API payload](https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-27-update-notes&lng=en-US&populate=*)

Use for:
- Patch identity/date truth
- Buff/nerf/system changelog assertions
- Contradiction resolution when lower tiers disagree

### Tier 1: first-party patch pages

- [OB29 patch page](https://www.smite2.com/news/open-beta-29-update-notes/)
- [OB28 patch page](https://www.smite2.com/news/open-beta-28-update-notes/)
- [OB27 patch page](https://www.smite2.com/news/open-beta-27-update-notes/)

Use for:
- Human-readable corroboration of Tier 0 facts

### Tier 2: official-domain wiki structured entries

- [Thanatos](https://wiki.smite2.com/w/Thanatos)
- [The Crusher](https://wiki.smite2.com/w/The_Crusher)
- [Titan's Bane](https://wiki.smite2.com/w/Titan%27s_Bane)
- [Heartseeker](https://wiki.smite2.com/w/Heartseeker)
- [Jotunn's Revenge](https://wiki.smite2.com/w/Jotunn%27s_Revenge)
- [The Reaper](https://wiki.smite2.com/w/The_Reaper)
- [Bumba's Cudgel](https://wiki.smite2.com/w/Bumba%27s_Cudgel)
- [Bumba's Hammer](https://wiki.smite2.com/w/Bumba%27s_Hammer)
- [Bloodforge](https://wiki.smite2.com/w/Bloodforge)
- [Death's Toll](https://wiki.smite2.com/w/Death%27s_Toll)
- [Brawler’s Beat Stick](https://wiki.smite2.com/w/Brawler%E2%80%99s_Beat_Stick)

Use for:
- Current kit/item mechanics and stat lines
- Never to override Tier 0/1 patch-change truth

### Tier 3: structured community build metadata

- [SmiteSource Thanatos builds index](https://smitesource.com/builds?god=thanatos)
- [SmiteSource OB29 Thanatos Jungle](https://smitesource.com/build/thanatos-jungle)
- [SmiteSource OB28 Thanatos Jungle](https://smitesource.com/build/thanatos-jungle-5b8p6i)
- [SmiteSource OB27 mixed-mode Thanatos build](https://smitesource.com/build/protection-scaling-damage-33pmji)

Use for:
- Patch/mode/role market signal
- Build-shell direction, not hard proof of global optimality

### Tier 4: community guide/opinion hubs

- [SMITEFire Thanatos page](https://www.smitefire.com/smite/god/thanatos-43)
- [SMITEFire Thanatos jungle guide](https://smitefire.com/smite/guide/thanatos-jungle-32121)

Use for:
- Idea bank only

### Tier 5 (lowest): aggregate stat surfaces with opaque methodology for this use case

- [Tacter SMITE 2 stats](https://www.tacter.com/smite-2/stats)

Use for:
- Broad directional context only

## Confidence tiers and labeling rules

| Tier | Score band | Meaning | Label rule |
|---|---:|---|---|
| A | 0.90-1.00 | First-party verified, contradiction-free | Can be factual default truth |
| B | 0.75-0.89 | Strong evidence, bounded assumptions | Can be **best-supported default** if scope is explicit |
| C | 0.55-0.74 | Partial evidence + extrapolation | Must be called **adaptation** |
| D | 0.35-0.54 | Heavy extrapolation/situational | Adaptation only; no "best" wording |
| E | 0.00-0.34 | Not supportable | Do not assert |

## Contradiction register

### C-01 (High): absolute claim vs caveat

Conflict:
- `04-best-build-and-variants.md:3` says "absolute best default build".
- `README.md:43` says recommendations are not mathematically absolute.

Resolution:
- Replace absolute language with **best-supported default**.

### C-02 (Medium): convergence wording overstates evidence breadth

Conflict:
- `04-best-build-and-variants.md:16` and `04-best-build-and-variants.md:80` imply strong OB29 convergence.
- `06-mode-evidence-matrix.md:16-31` shows one direct OB29 Thanatos Conquest entry and no OB29 Arena-only entry.

Resolution:
- Replace "convergence" with "strongest available single-source OB29 signal".

### C-03 (Medium): evidence buckets are too coarse

Conflict:
- `01-sources-and-methodology.md:75-77` merges official patch/API with wiki in one "High" bucket.

Resolution:
- Enforce Tier 0-5 hierarchy so wiki/community never inherit first-party authority weight.

### C-04 (Low-Medium): one swap example is weakly reproducible

Conflict:
- `05-practical-gameplan-and-swaps.md:50` includes `Mantle of Discord` but direct wiki page lookup returns no stable page at `/w/Mantle_of_Discord`.

Resolution:
- Keep as situational adaptation only (Tier C/D confidence), or replace with currently verifiable defensive alternatives.

## Claim-by-claim cross-check

| ID | Track ref(s) | Claim | Best evidence | Contradiction status | Confidence | Classification |
|---|---|---|---|---|---:|---|
| P-01 | `02:5-12` | Current patch is OB29; prior chain OB28 then OB27 | Tier 0 + Tier 1 | None | 0.99 (A) | Factual default |
| P-02 | `02:18` | OB29 has no direct Thanatos kit/stat change | Tier 0 (OB29 content scan) | None | 0.95 (A) | Factual default |
| P-03 | `02:22` | OB28 had Thanatos/Thor ultimate warning audio pass | Tier 0 + Tier 1 | None | 0.96 (A) | Factual default |
| P-04 | `02:28-30` | OB29 jungle role buff and kill sustain + Bumba jungle-only removal | Tier 0 + Tier 1 | None | 0.97 (A) | Factual default |
| P-05 | `02:31` | OB29 adaptive stat selection logic changed | Tier 0 + Tier 1 | None | 0.94 (A) | Factual default |
| P-06 | `02:32-34` | OB29 includes Brawler nerf, Blinking Abyss nerf, Death Metal rework | Tier 0 + Tier 1 | None | 0.95 (A) | Factual default |
| K-01 | `03:5-8` | Thanatos uses health costs; burst execute profile | Tier 2 | None | 0.86 (B) | Factual default |
| K-02 | `03:11-24` | Passive heal/CDR + Scent penetration/move speed + execute threshold framing | Tier 2 | None | 0.84 (B) | Factual default |
| K-03 | `03:35-78` | Item stats/passives for Crusher/Titan/Heartseeker/Jotunn/Reaper/Bumba/Bloodforge | Tier 2 | None | 0.85 (B) | Factual default |
| M-01 | `06:16-31` | Strongest newest direct Thanatos signal is OB29 Conquest Jungle | Tier 3 | None | 0.82 (B) | Best-supported default (mode-scoped) |
| M-02 | `06:31-35` | No dedicated OB29 Arena-only Thanatos build in extracted set | Tier 3 | None | 0.79 (B) | Evidence bound (not global absence proof) |
| B-01 | `04:5-12,14-20` | Conquest shell is the top practical default | Tier 3 + Tier 0 context | Soft conflict (C-01/C-02 wording) | 0.76 (B) | **Best-supported default** |
| B-02 | `04:24-39` | Arena default is current best practical recommendation | Tier 3 indirect + Tier 0/2 context | No hard conflict; evidence gap explicit | 0.61 (C) | **Adaptation** |
| B-03 | `04:45-71` | Snowball and safer variants are generally useful mode options | Tier 2 + Tier 3 + expert extrapolation | None | 0.58 (C) | Adaptation |
| G-01 | `05:7-41` | Conquest/Arena tactical gameplans are broadly correct | Tier 2 + expert extrapolation | None | 0.54 (D) | Adaptation |
| G-02 | `05:47-63` | Universal swap matrix and slot-order replacement rules are broadly optimal | Mostly expert extrapolation | Soft reproducibility issue (C-04) | 0.45 (D) | Adaptation |
| R-01 | `README:7-39` | Summary ranking (Conquest higher confidence than Arena) | Aggregated from P/K/M/B claims | None | 0.80 (B) | Best-supported default + adaptation split |
| R-02 | `README:43` | "Not mathematically absolute" caveat | Methodological statement | Conflicts with `04:3` only | 0.92 (A) | Factual default |

## Best-supported default vs adaptation boundary

### Best-supported default (can be asserted)

- **Conquest Jungle OB29 shell** as the highest-confidence recommendation in this pack, scoped to current public evidence and patch window.

### Adaptation (must be labeled as adaptation)

- Arena build recommendations.
- Conquest/Arena variants and swap matrix rules.
- Any "if-behind" or matchup-dependent slot replacement heuristic.

### Not supportable

- Any "absolute best for all lobbies/skill brackets" wording.

## Source-quality findings by family

| Source family | Quality notes | Grade |
|---|---|---:|
| SMITE 2 CMS/API | Strongest for dates/changelogs; reproducible; machine-parseable | A |
| SMITE 2 news pages | High authority corroboration, but CMS extraction is cleaner for auditing | A- |
| SMITE 2 wiki | Useful for mechanics/stats; community-editable and includes historical sections requiring careful reading | B+ |
| SmiteSource builds | Useful patch+mode+role signal; client-heavy rendering and single-source dependence constrain certainty | B |
| SMITEFire | Patch references are mixed with older guide inventory; quality varies by author/date | C |
| Tacter stats | Shows aggregate signals (for example lastUpdated + sample count), but build-slot methodology is opaque for this decision | C- |

## Final recommendation wording for this pack

Use:
- "best-supported default" for Conquest OB29 shell.
- "evidence-backed adaptation" for Arena and swap/variant logic.

Avoid:
- "absolute best"
- "meta convergence" unless at least two independent Tier <= 3 sources agree on the same patch+mode+role shell.
