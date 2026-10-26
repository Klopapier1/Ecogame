# Gem Tycoon

A single-file browser economy game. Open `index.html` in any browser, including on a phone. It has no build step and no dependencies.

You get 25 rounds and 1000 starting gold. Mines produce uncut gems or silver, jewellers cut gems into sapphires or diamonds, and goldsmiths craft rings and necklaces. Every sale pushes prices down, and every building costs upkeep. Each game starts with a choice of perks, mines come as varied sites (some run dry), random events force decisions, and standing sell orders handle routine selling. The goal is to finish with the most gold. The full rules are in the in-game "Rules" panel. All the tunable numbers are in the `CFG` object at the top of the script.

The leaderboard (top 10) and the game in progress are saved in the browser's localStorage.
