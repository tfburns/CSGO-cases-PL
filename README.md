# Expected profit-loss of CS:GO case openings

YouTuber 3kliksphilip recently posted a video titled "Case Unboxing Millionaire #2", wherein he showed a single run simulation of him 'unboxing' cases for the first-person-shooter computer game Counter Strike: Global Offensive. These cases are digital items which, when opened, unlock a decorative weapon 'skin'. These skins can be used by players in the game to show off to their friends. Such skins have deveoped quite a market for themselves and can be bought and sold for hundreds or even thousands of dollars through various online marketplaces.

The following analysis calculates the expected profit or loss for a given case, "eSports 2013 Case", per opening. It costs $20 to open, and can contain skins worth between a few dollars to around $300. 3kliksphilip challenged his viewers to estimate his profit or loss from opening this case up until he unlocked a knife skin, the rarest skin to obatin. I have calculated this expected value to be a loss of $5720.96.

All analysis and data pre-processing occurs in the Jupyter notebook `CSGO-cases.ipynb`, and data is read from `prices_v4.json`.
