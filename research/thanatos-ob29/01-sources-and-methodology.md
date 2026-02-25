# Sources and Methodology

## Research approach

- Deep browse focus on `https://wiki.smite2.com` for Thanatos and item pages.
- Official patch verification from SMITE 2 official content backend.
- Meta convergence check from current patch-labeled community build pages.
- Mode split validation (Conquest vs Arena) from parsed build metadata.
- Cross-validation pass to separate strong claims from weak claims.

## Parallelization

Research was split across multiple parallel agents:

1. Thanatos wiki god profile extraction
2. Offensive item pool extraction
3. Situational/counter item extraction
4. Latest patch chain and balance context
5. External meta build convergence
6. Claim-level sanity check

## Primary sources used

### Official patch sources (highest trust)

- [SMITE 2 News](https://www.smite2.com/news/)
- [OB 29 - The Dark Enchantress Update](https://www.smite2.com/news/open-beta-29-update-notes/)
- [OB 28 - The Third Lotus Prince Update](https://www.smite2.com/news/open-beta-28-update-notes/)
- [OB27 - The Great Teacher Update](https://www.smite2.com/news/open-beta-27-update-notes/)

### Official CMS API (used for reliable extraction)

The official news page is client-rendered. To avoid missing content from empty server HTML shells, patch notes were extracted from:

- `https://webcms.hirezstudios.com/smite2/api/posts/?filters[slug][$eq]=<slug>&lng=en-US&populate=*`

Validated slugs:

- `open-beta-29-update-notes`
- `open-beta-28-update-notes`
- `open-beta-27-update-notes`

### SMITE 2 wiki sources (god + item mechanics)

- [Thanatos](https://wiki.smite2.com/w/Thanatos)
- [The Crusher](https://wiki.smite2.com/w/The_Crusher)
- [Titan's Bane](https://wiki.smite2.com/w/Titan%27s_Bane)
- [Heartseeker](https://wiki.smite2.com/w/Heartseeker)
- [Jotunn's Revenge](https://wiki.smite2.com/w/Jotunn%27s_Revenge)
- [The Reaper](https://wiki.smite2.com/w/The_Reaper)
- [Patch Notes Index](https://wiki.smite2.com/w/Patch_notes)

### Current meta/community references

- [SmiteSource - Thanatos god page](https://smitesource.com/god/thanatos)
- [SmiteSource - Thanatos builds index](https://smitesource.com/builds?god=thanatos)
- [SmiteSource - Thanatos Jungle (Open Beta 29, ManicDynamo)](https://smitesource.com/build/thanatos-jungle)
- [SMITEFire Thanatos page](https://www.smitefire.com/smite/god/thanatos-43)
- [SMITEFire Thanatos jungle guide](https://smitefire.com/smite/guide/thanatos-jungle-32121)
- [Tacter SMITE 2 stats](https://www.tacter.com/smite-2/stats)

### Mode-specific extraction method

SmiteSource builds are rendered through embedded Next.js state. For mode checks, the run parsed `initialBuilds.builds[]` from the embedded payload and extracted:

- `patch.patchShortName`
- `roles[]`
- `gameModes[]`
- `gods[]` including `godSlug == "thanatos"`

This produced a verifiable Conquest-vs-Arena evidence matrix in `06-mode-evidence-matrix.md`.

## Evidence grading used in this pack

- High: official patch/API + direct wiki stat/mechanic entries
- Medium: patch-labeled meta/community build convergence
- Low-Medium: creator opinions and non-patch-locked recommendations

## Extraction limits and known gaps

- Some Exa crawl calls returned decode errors during this run.
- `smite2.live` pro build pages were blocked from this environment (`HTTP 403`), so pro-only coverage is incomplete.
- Some community pages are JS-heavy, requiring fallback parsing from embedded state.
- No high-trust public feed with dedicated OB29 Thanatos Arena-only builds was found, so Arena recommendations are lower-confidence adaptations.

## Date anchor

All conclusions are anchored to data available on **2026-02-25**.
