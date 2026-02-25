# Important Links and APIs Used in Athena Research

Date anchored: 2026-02-25

## Official SMITE 2 (highest trust)

- News index: https://www.smite2.com/news/
- OB29 notes: https://www.smite2.com/news/open-beta-29-update-notes/
- OB28 notes: https://www.smite2.com/news/open-beta-28-update-notes/
- OB27 notes: https://www.smite2.com/news/open-beta-27-update-notes/
- OB26 notes: https://www.smite2.com/news/open-beta-26-update-notes/

## Official SMITE 2 CMS API

- Posts list (large page): https://webcms.hirezstudios.com/smite2/api/posts/?lng=en-US&pagination%5BpageSize%5D=200&populate=*
- OB29 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1365?populate=*
- OB28 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1363?populate=*
- OB27 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1359?populate=*
- OB26 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1356?populate=*
- OB29 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-29-update-notes&lng=en&populate=%2A
- OB28 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-28-update-notes&lng=en&populate=%2A
- OB27 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-27-update-notes&lng=en&populate=%2A

## Official SMITE 2 Wiki

- Athena: https://wiki.smite2.com/w/Athena
- Items index: https://wiki.smite2.com/w/Items
- Arena: https://wiki.smite2.com/w/Arena
- Conquest: https://wiki.smite2.com/w/Conquest
- Patch notes index: https://wiki.smite2.com/w/Patch_notes

## Wiki API endpoints used

- Parse Athena wikitext: https://wiki.smite2.com/api.php?action=parse&page=Athena&prop=wikitext&format=json
- Parse item wikitext example (Sovereignty): https://wiki.smite2.com/api.php?action=parse&page=Sovereignty&prop=wikitext&format=json
- Search endpoint example: https://wiki.smite2.com/api.php?action=query&list=search&srsearch=Athena&format=json
- Revision metadata example: https://wiki.smite2.com/api.php?action=query&prop=revisions&titles=Athena&rvprop=ids%7Ctimestamp%7Ccomment%7Cuser&rvlimit=1&format=json

## Build convergence sources

- SmiteSource Athena builds: https://smitesource.com/builds?god=athena
- SmiteSource Athena Support: https://smitesource.com/build/athena-support-vig6vx
- SmiteSource Athena Jungle: https://smitesource.com/build/athena-jungle-j3rpqr
- SmiteSource Immortal Athena: https://smitesource.com/build/immortal-athena-e08n0b
- SmiteSource Generic Support (Athena-relevant shell): https://smitesource.com/build/generic-support-build-active-items-op-l71b8d

## Supporting community references (lower trust)

- Steam official SMITE 2 news feed: https://steamcommunity.com/app/2437170/allnews/
- OB29 Steam announcement: https://steamcommunity.com/games/2437170/announcements/detail/515235451168098630
- SMITEFire Athena god page: https://www.smitefire.com/smite/god/athena-33
- SMITEFire OB29 mirror thread: https://www.smitefire.com/smite/forum/news/open-beta-29-the-dark-enchantress-update-59893

## Run notes

- Exa MCP was attempted first for web research in this run but returned response decode errors.
- Final source collection used direct retrieval from official endpoints and public pages listed above.
