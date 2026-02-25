# Important Links and APIs Used in Medusa Research

Date anchored: 2026-02-25

## Official SMITE 2 (highest trust)

- News index: https://www.smite2.com/news/
- OB29 notes: https://www.smite2.com/news/open-beta-29-update-notes/
- OB28 notes: https://www.smite2.com/news/open-beta-28-update-notes/
- OB27 notes: https://www.smite2.com/news/open-beta-27-update-notes/

## Official SMITE 2 CMS API

- Posts list (bulk): https://webcms.hirezstudios.com/smite2/api/posts/?lng=en-US&pagination%5BpageSize%5D=200&populate=*
- OB29 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-29-update-notes&lng=en&populate=%2A
- OB28 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-28-update-notes&lng=en&populate=%2A
- OB27 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-27-update-notes&lng=en&populate=%2A
- OB29 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1365?populate=*
- OB28 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1363?populate=*
- OB27 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1359?populate=*

## Official SMITE 2 Wiki

- Medusa: https://wiki.smite2.com/w/Medusa
- Arena: https://wiki.smite2.com/w/Arena
- Conquest: https://wiki.smite2.com/w/Conquest
- Patch notes index: https://wiki.smite2.com/w/Patch_notes
- Items index: https://wiki.smite2.com/w/Items

## SMITE 2 Wiki API endpoints used

- Parse Medusa wikitext: https://wiki.smite2.com/api.php?action=parse&page=Medusa&prop=wikitext&format=json
- Search endpoint (Medusa query): https://wiki.smite2.com/api.php?action=query&list=search&srsearch=Medusa&format=json
- Revision metadata (Medusa latest revision): https://wiki.smite2.com/api.php?action=query&prop=revisions&titles=Medusa&rvprop=ids%7Ctimestamp%7Ccomment%7Cuser&rvlimit=1&format=json

## Build convergence sources

- SmiteSource Medusa builds index: https://smitesource.com/builds?god=medusa
- SmiteSource Medusa Mid (Ranked) (OB29-tagged): https://smitesource.com/build/medusa-mid-ranked-vamhwr
- SmiteSource Poatan Medusa (OB29-tagged): https://smitesource.com/build/poatan-medusa-fail-not-remake-fsqb34

## Supporting community references (lower trust)

- SMITEFire Medusa page: https://www.smitefire.com/smite/god/medusa-83
- Smitebrain Medusa builds: https://smitebrain.com/gods/medusa/builds
- Tacter SMITE 2 stats: https://www.tacter.com/smite-2/stats

## Run notes

- Exa MCP was attempted first in this run and returned decode-response errors on search and crawl calls.
- Final source collection used direct retrieval from official endpoints/pages and supporting public references above.
