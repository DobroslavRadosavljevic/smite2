# Important Links and APIs Used in Kukulkan Research

Date anchored: 2026-02-25

## Official SMITE 2 (highest trust)

- News index: https://www.smite2.com/news/
- OB29 notes: https://www.smite2.com/news/open-beta-29-update-notes/
- OB28 notes: https://www.smite2.com/news/open-beta-28-update-notes/
- OB27 notes: https://www.smite2.com/news/open-beta-27-update-notes/

## Official SMITE 2 CMS API

- Posts list: https://webcms.hirezstudios.com/smite2/api/posts/?lng=en-US&pagination%5BpageSize%5D=200&populate=*
- OB29 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1365?populate=*
- OB28 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1363?populate=*
- OB27 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1359?populate=*
- OB29 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-29-update-notes&lng=en&populate=%2A
- OB28 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-28-update-notes&lng=en&populate=%2A
- OB27 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-27-update-notes&lng=en&populate=%2A

## Official SMITE 2 Wiki

- Kukulkan: https://wiki.smite2.com/w/Kukulkan
- Items index: https://wiki.smite2.com/w/Items
- Arena: https://wiki.smite2.com/w/Arena
- Conquest: https://wiki.smite2.com/w/Conquest
- Patch notes index: https://wiki.smite2.com/w/Patch_notes

## Wiki API endpoints used

- Parse Kukulkan wikitext: https://wiki.smite2.com/api.php?action=parse&page=Kukulkan&prop=wikitext&format=json
- Parse item wikitext example (Book of Thoth): https://wiki.smite2.com/api.php?action=parse&page=Book%20of%20Thoth&prop=wikitext&format=json
- Search endpoint example: https://wiki.smite2.com/api.php?action=query&list=search&srsearch=Kukulkan&format=json
- Revision metadata example: https://wiki.smite2.com/api.php?action=query&prop=revisions&titles=Kukulkan&rvprop=ids%7Ctimestamp%7Ccomment%7Cuser&rvlimit=1&format=json

## Build convergence sources

- SmiteSource Kukulkan builds: https://smitesource.com/builds?god=kukulkan
- SmiteSource Mages (OB29): https://smitesource.com/build/mages-0kpstp
- SmiteSource Kukulkan Solo (OB29): https://smitesource.com/build/kukulkan-solo
- SmiteSource Kuku Aspect (Ranked, OB29): https://smitesource.com/build/kuku-aspect-ranked-mvpa83
- SmiteSource General Int (OB28): https://smitesource.com/build/general-int
- SmiteSource Kuku Aspect Solo (OB28): https://smitesource.com/build/kuku-aspect-solo
- SmiteSource Kuku Aspect (OB27): https://smitesource.com/build/kuku-aspect-prmg24

## Supporting community references (lower trust)

- Steam official SMITE 2 news feed: https://steamcommunity.com/app/2437170/allnews/
- OB29 Steam announcement: https://steamcommunity.com/games/2437170/announcements/detail/515235451168098630
- SMITEFire Kukulkan god page: https://www.smitefire.com/smite/god/kukulkan-13
- Smitebrain Kukulkan builds: https://smitebrain.com/gods/kukulkan/builds

## Run notes

- Exa MCP was attempted first for web research in this run but returned response decode errors.
- Final source collection used direct retrieval from official endpoints and public pages listed above.
