# Important Links and APIs Used in Discordia Research

Date anchored: 2026-02-25

## Official SMITE 2 (highest trust)

- News index: https://www.smite2.com/news/
- OB29 notes: https://www.smite2.com/news/open-beta-29-update-notes/
- OB28 notes: https://www.smite2.com/news/open-beta-28-update-notes/
- OB27 notes: https://www.smite2.com/news/open-beta-27-update-notes/

## Official SMITE 2 CMS API

- Posts list (large page size): https://webcms.hirezstudios.com/smite2/api/posts/?lng=en-US&pagination%5BpageSize%5D=200&populate=*
- OB29 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1365?populate=*
- OB28 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1363?populate=*
- OB27 direct post id: https://webcms.hirezstudios.com/smite2/api/posts/1359?populate=*
- OB29 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-29-update-notes&lng=en&populate=%2A
- OB28 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-28-update-notes&lng=en&populate=%2A
- OB27 by slug filter: https://webcms.hirezstudios.com/smite2/api/posts/?filters%5Bslug%5D%5B%24eq%5D=open-beta-27-update-notes&lng=en&populate=%2A

## Official SMITE 2 Wiki

- Discordia: https://wiki.smite2.com/w/Discordia
- Patch notes index: https://wiki.smite2.com/w/Patch_notes
- SMITE 2 Open Beta 29: https://wiki.smite2.com/w/SMITE_2_Open_Beta_29
- SMITE 2 Open Beta 28: https://wiki.smite2.com/w/SMITE_2_Open_Beta_28
- SMITE 2 Open Beta 27: https://wiki.smite2.com/w/SMITE_2_Open_Beta_27
- Items index: https://wiki.smite2.com/w/Items
- Arena: https://wiki.smite2.com/w/Arena
- Conquest: https://wiki.smite2.com/w/Conquest

## Wiki API endpoints used

- Parse Discordia wikitext: https://wiki.smite2.com/api.php?action=parse&page=Discordia&prop=wikitext&format=json
- Discordia revision metadata: https://wiki.smite2.com/api.php?action=query&prop=revisions&titles=Discordia&rvprop=ids%7Ctimestamp%7Ccomment%7Cuser&rvlimit=1&format=json
- Parse OB29 wiki patch page: https://wiki.smite2.com/api.php?action=parse&page=SMITE%202%20Open%20Beta%2029&prop=wikitext&format=json
- Parse OB28 wiki patch page: https://wiki.smite2.com/api.php?action=parse&page=SMITE%202%20Open%20Beta%2028&prop=wikitext&format=json
- Parse OB27 wiki patch page: https://wiki.smite2.com/api.php?action=parse&page=SMITE%202%20Open%20Beta%2027&prop=wikitext&format=json
- Search endpoint example: https://wiki.smite2.com/api.php?action=query&list=search&srsearch=Discordia&format=json

## Build convergence sources

- SmiteSource Discordia builds index: https://smitesource.com/builds?god=discordia
- Mid Build (Open Beta 29 tag): https://smitesource.com/build/mid-build
- 1 shot disco (Open Beta 28 tag): https://smitesource.com/build/1-shot-disco
- Discordia AA INT Build (Open Beta 28 tag): https://smitesource.com/build/discordia-aa-int-build-lka6pr
- Int discordia aspect (Open Beta 28 tag): https://smitesource.com/build/int-discordia-aspect

## Supporting community references (lower trust)

- Steam official SMITE 2 news feed: https://steamcommunity.com/app/2437170/allnews/
- OB29 Steam announcement: https://steamcommunity.com/games/2437170/announcements/detail/515235451168098630
- SMITEFire Discordia god page: https://www.smitefire.com/smite/god/discordia-92
- Smitebrain Discordia builds: https://smitebrain.com/gods/discordia/builds
- Tacter SMITE 2 stats: https://www.tacter.com/smite-2/stats

## Run notes

- Exa MCP was attempted first for web research in this run but returned response decode errors.
- Final source collection used direct retrieval from official endpoints and public pages listed above.
