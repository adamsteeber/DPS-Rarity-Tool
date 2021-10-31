# DPS-Rarity-Tool
A simple XCEL tool to check the rarity of https://www.damnedpiratessociety.io/ NFTs

**ONLY EDIT THE PIRATE ID CELL**

Rarity is split into two categories: items and skills.

Item Rarity Percentile is calculated by taking the sum of [rarity scores](https://raritytools.medium.com/ranking-rarity-understanding-rarity-calculation-methods-86ceaeb9b98c) of each *item* in a pirate and percent-ranking that sum against all other pirates. The higher percent, the more rare.

Skill Rarity Percentile is calculated by taking each of a pirate's skills and percent-ranking them against the skills of other pirates. Then the sum of the inverses of 1 minus the percentiles of each skill for a pirate is taken and percent-ranked against all other pirates. The higher percent, the more skiled/more rare.
