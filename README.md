![](https://i.imgur.com/9xdKOHE.png)

<sub>Image Credit: [Mithra](https://github.com/thekeatonfox)</sub>
=======

# DISCLAIMER
* The main goal behind an Early Access is to provide meaningful feedback to the developers. To do so, Larian implemented an automatic telemetry that will provide data for them automatically as you play
* Since modding BG3 is not yet officially supported by Larian Studios, you might encounter unexpected problems that it's not in their current scope to fix. **PLEASE DISABLE AUTOMATIC TELEMETRY** and don't post bug reports on their official platforms, as you're playing an unsuported mod
* How to disable telemetry:

| ![](https://i.imgur.com/8BSSPiW.png) | ![](https://i.imgur.com/huTu79h.png) |
|:---:|:---:|

# Description
* This mod's main objective is to repurpose food in BG3, removing the healing factor and implementing a Hunger system.

# Features
## Food
* Removes all healing from food
* Food provides some level of satiation:
  - Small snacks (like apple and carrots) provide 1 level
  - Big snacks (like cheese and sausages) provide 2 levels
  - Small meals (like fries and soup) provide 4 levels
  - Big meals (like chicken, pork head and even Goodberry) provide 8 levels
* Long resting consumes all levels of satiation and gives a status based on the level consumed
  - A character who was `Hungry` (level 0) or `Unsatisfied` (level 1 to 3) receives one level of `Exhaustion`
  - A character who was `Fed` (level 4 to 7) becomes `Starving`. At the first day, this status does nothing, but after another starving day, it will increase on level of `Exhaustion`
  - A character who was `Satiated` (level 8) has their `Exhaustion` level decreased by one and removes `Starving` (if applicable)
* The `Exhaustion` levels follow the exact rules from the PHB. Each level also applies the effects of all previous ones, and they are as follows:

| Level | Effect |
| :--: | :--: |
| 1 | Disadvantage on ability checks |
| 2 | Speed halved |
| 3 | Disadvantage on attack rolls and saving throws |
| 4 | Hit point maximum halved |
| 5 | Speed reduced to 0 |
| 6 | Death |

## Hit Dice
* Short resting puts the characters in a standby mode and provides them with 2 new spells
  - Regain Hit Points: spend 1 Hit Die to recover it's value plus the character's Constitution Modifier
  - End Short Rest: Ends the short rest standby mode
* Long resting recharges half the character's level worth of Hit Dice (rounded up)

# Installing
* Download the latest `.pak` file from [Releases](https://github.com/ZerdBG3/DnDontStarve/releases) and place it under `\Documents\Larian Studios\Baldur's Gate 3\Mods` (Create the `Mods` folder if it doesn't exist)
* Use Laughing Leader's [Mod Manager](https://github.com/LaughingLeader/BG3ModManager) to set up your mod profile

# Error
* **IMPORTANT:** When loading the game, you'll get a notification regarding an invalid story set-up. Since the mod doesn't have any story files, the fallback to the main story allows the game to load correctly. Tl;dr: ignore the error warning you'll get
* If you're very annoyed by this warning message, you can also use [this mod](https://www.nexusmods.com/baldursgate3/mods/13) to suppress the warning message

# Discord
* Feel free to join my Discord server: https://discord.gg/jJUxKgw

# Attribution
- [Baldur's Gate 3](https://store.steampowered.com/app/1086940/Baldurs_Gate_3/), a game by [Larian Studios](http://larian.com/)
