# pogo-app

The intention is to learn react and react-native by creating a small pogo application that will compile various pieces of data from APIs, information pulled from the master build files, and information obtained from various pogo websites. 

Features:

* All Pokemon
  * search, sort, filter by stats, type, cp, level, moves, gen, etc.
  * group Pokemon into tiers based on attributes / types - [Example](https://rankedboost.com/pokemon-go/bug-type/)
  * show CP min/max range
  * show all moves for a pokemon and rank best to worst - [Example](https://pokemongo.gamepress.gg/pokemon/40)
  * show weather effects on pokemon
  * show strengths/weaknesses
  * (MAYBE - might be better left in battle calculator) show best/worst opponents for a pokemon, taking into account moves
  
* All Moves
  * search, sort, filter by type, DPS, DPE, etc.
  * Rank all moves overall as well as by type - group into tiers (show STAB bonuses as well) - [Example](https://pokemongo.gamepress.gg/pve-fast-moves)

* Enter data for a specific Pokemon for:
  * How much CP it will gain on its next power up
  * How much Stardust and Candy is required to power up from current to maximum within a Battle League
  * Max CP based on stats (show in min/max range and compare)
  * Weather effects
  * Level (should already have this, if not it should go in the IV calculator that may or may not be added)

* Nice to have. May not ever add these, but they aren't off the table.
  * Pokemon Tracker/Assistant (not live - personal) - [Example](https://pokeassistant.com/trainerstats/globalstats?locale=en)
  * IV Calculator - [Example 1](https://pokeassistant.com/main/ivcalculator), [Example 2](https://pokemongo.gamepress.gg/pokemongo-iv-calculator#/)
  * Evolution Calculator - [Example](https://pokeassistant.com/main/evolver?locale=en)
  * Battle Simulator - [Example](https://pokeassistant.com/main/index?locale=en)
  * Breakpoint Calculator - [Description](https://pokemongo.gamepress.gg/guide-breakpoints), [Example](https://pokemongo.gamepress.gg/breakpoint-calculator#/)
  * Bulkpoint Calculator - [Description](https://pokemongo.gamepress.gg/guide-bulkpoints), [Example](https://pokemongo.gamepress.gg/bulk-point-calculator#/)

### Notes:

* Open to suggestions for other features related to Pokemon or Moves. 
* Will not include anything related to the map (i.e finding pokemon, tracking nests, finding raids, etc). 
* Not interested (at this time) in adding anything related to Gyms, Stops, Raids, Catch Percentages, Ditto, Research, Items, Events, etc. 


## Getting Started
* Install CLI. I prefer Git Bash, which comes as part of [Git for Windows](https://gitforwindows.org/).
* Install the latest version of [Node](https://nodejs.org/en/).
* Install [Expo](npm install -g expo-cli).
  * Also install the Expo mobile app on your phone from the app store.
* Pull down the project from Github
* Run `npm install`


### Useful Links: 

* POGO
  * Initial API: [Intro](https://pogoapi.net/), [API Docs](https://pogoapi.net/documentation/)
  * [Stat Calculations 1](https://pokemongo.gamepress.gg/pokemon-stats-advanced)
  * [Stat Calculations 2](https://pokemongohub.net/post/wiki/pokemon-go-calculates-stats-max-cp/) (Not sure if this one is still accurate)
  * [CP Multiplier](https://pokemongo.gamepress.gg/cp-multiplier)
* React Native / Expo
  * [React native on GitHub](https://github.com/facebook/react-native)
  * [Getting Started with React Native](https://facebook.github.io/react-native/docs/getting-started.html)
  * [Expo Introduction](https://docs.expo.io/versions/v32.0.0/)

### Possible TODOs:

* Add Local Storage
* Add Redux
* ???

