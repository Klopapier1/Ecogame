# Gem Tycoon

A single-file browser economy game. Open `index.html` in any browser, including on a phone. It has no build step and no dependencies.

You get 25 rounds and 1000 starting gold. Mines produce uncut gems or silver. Jewellers cut gems into sapphires or diamonds, goldsmiths craft rings and necklaces, mints strike silver into coins, and glassworks melt gems into stained glass. Each of those four needs a guild licence, and you can only join 2 guilds per game, so you have to specialise. Sticking to a single guild boosts its output by 25%. Every sale pushes prices down, every building costs upkeep, and each different kind of building (every mine site type counts as its own kind) adds overhead. Each game starts with a choice of perks, mines come as varied sites (some run dry), random events force decisions, and standing sell orders handle routine selling. The goal is to finish with the most gold. The full rules are in the in-game "Rules" panel. All the tunable numbers are in the `CFG` object at the top of the script.

The leaderboard (top 10) and the game in progress are saved in the browser's localStorage.
