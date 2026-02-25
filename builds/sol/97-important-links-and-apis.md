# Important Links and APIs Used in Sol Research

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

## Official SMITE 2 Wiki

- Sol: https://wiki.smite2.com/w/Sol
- Items index: https://wiki.smite2.com/w/Items
- Arena: https://wiki.smite2.com/w/Arena
- Conquest: https://wiki.smite2.com/w/Conquest
- Patch notes index: https://wiki.smite2.com/w/Patch_notes

## Wiki API endpoints used

- Parse Sol wikitext: https://wiki.smite2.com/api.php?action=parse&page=Sol&prop=wikitext&format=json
- Parse item wikitext example (Typhon's Fang): https://wiki.smite2.com/api.php?action=parse&page=Typhon%27s%20Fang&prop=wikitext&format=json
- Parse item wikitext example (Bancroft's Talon): https://wiki.smite2.com/api.php?action=parse&page=Bancroft%27s%20Talon&prop=wikitext&format=json
- Search endpoint example: https://wiki.smite2.com/api.php?action=query&list=search&srsearch=Sol&format=json
- Revision metadata example: https://wiki.smite2.com/api.php?action=query&prop=revisions&titles=Sol&rvprop=ids%7Ctimestamp%7Ccomment%7Cuser&rvlimit=1&format=json

## Build convergence sources

- SmiteSource Sol builds index: https://smitesource.com/builds?god=sol
- SmiteSource Sol ADC Crit (OB29-tagged page): https://smitesource.com/build/sol-adc-crit-b8dgal
- SmiteSource Sol ADC Vital Amplifier (OB29-tagged page): https://smitesource.com/build/sol-adc-vital-amplifier-egpadf
- SmiteSource Sol Top Damage (OB28-tagged page): https://smitesource.com/build/sol-top-dmg
- SmiteSource Sol Typhon's Build (mixed OB28/OB29 tags): https://smitesource.com/build/sol-typhons-build-0wl8to

## Supporting community references (lower trust)

- Steam official SMITE 2 news feed: https://steamcommunity.com/app/2437170/allnews/
- OB29 Steam announcement: https://steamcommunity.com/games/2437170/announcements/detail/515235451168098630
- SMITEFire Sol god page: https://www.smitefire.com/smite/god/sol-34
- Smitebrain Sol builds: https://smitebrain.com/gods/sol/builds
- Tacter SMITE 2 stats: https://www.tacter.com/smite-2/stats

## Run notes

- Exa MCP was attempted first for web research in this run but returned response decode errors.
- Final source collection used direct retrieval from official endpoints and public pages listed above.
