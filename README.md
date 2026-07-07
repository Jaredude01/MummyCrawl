[![Build Status](https://github.com/crawl/crawl/workflows/Build/badge.svg)](https://github.com/crawl/crawl/actions/)

# Mummy Crawl Stone Soup

Mummy Crawl Stone Soup is a game of dungeon exploration, combat and magic, involving mummies of necromantic skills, and worshipping Kiku. To win, you'll need to be kind of good at tactics and strategy, and prevail against whelming odds.

After killing many mummy characters I modified the mummy species for some cathartic dungeonblasting.
Those modifications led me to trying different things to familiarize myself with how crawl works so I can contribute at some point in the future.

## Changes from dungeon crawl
* Necromancer starts with Kiku and all the of the necromancy spells I care about.

* Modified the Lucky mutation to give 1/3 chance of changing items into artifacts at level 1 and 2/3 at level 2.
* Created Royal Tastes mutation to only allow equipping artifacts.

* Gave Mummy the Megawait ability, wait 6000 turns to regenerate the current floor.

* Gave the mummy great aptitudes and mutations while I'm testing stuff, I expect I'll probably tone that down at some point.
* Removed all species except Mummy.
* Created Lesser Mummy which is the same as regular DCSS Mummy.
* Created Greater Mummy for overpowered romps.

## Planned Changes
* Tomb replaces the dungeon exit and you must bring the orb of zot to a special Kiku altar inside to beat the game.
* Create some sort of system to give mummies the mutations of other species as the game progresses.
* Maybe give mummies inherent Wu Jian movement for fun
* Rework malevolence system and add flavor
* Something for mummies to do with potions
* Add unique enemies
* New P god?

## License and history information

Crawl is licensed as GPLv2+. See [LICENSE](LICENSE) for the full text.

Crawl is a descendant of Linley's Dungeon Crawl. The final alpha of Linley's Dungeon Crawl (v4.1) was released by Brent Ross in 2005. Since 2006, the Dungeon Crawl Stone Soup team has continued development. [CREDITS.txt](crawl-ref/CREDITS.txt) contains a full list of contributors.

Crawl uses the following open source packages; thanks to their developers:

* The Lua scripting language, for in-game functionality and user macros ([license](crawl-ref/docs/license/lualicense.txt)).
* The PCRE library, for regular expressions ([license](crawl-ref/docs/license/pcre_license.txt)).
* The SQLite library, as a database engine ([license](https://www.sqlite.org/copyright.html)).
* The SDL and SDL_image libraries, for tiles display ([license](crawl-ref/docs/license/lgpl.txt)).
* The libpng library, for tiles image loading ([license](crawl-ref/docs/license/libpng-LICENSE.txt)).

Thank you, and have fun crawling!
