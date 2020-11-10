![](https://i.imgur.com/9xdKOHE.png)

<sub>Image Credit: Mithra</sub>
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
* According to PHB (page 185):
> Characters who don’t eat or drink suffer the effects of exhaustion. Exhaustion caused by lack of food or water can’t be removed until the character eats and drinks the full required amount.  
 **Food**  
A character needs one pound of food per day and can make food last longer by subsisting on half rations. Eating half a pound of food in a day counts as half a day without food.  
A character can go without food for a number of days equal to 3 + his or her Constitution modifier (minimum 1). At the end of each day beyond that limit, a character automatically suffers one level of exhaustion.  
A normal day of eating resets the count of days without food to zero.  
**Water**  
A character needs one gallon of water per day, or two gallons per day if the weather is hot.  
A character who drinks only half that much water must succeed on a DC 15 Constitution saving throw or suffer one level of exhaustion at the end of the day. A character with access to even less water automatically suffers one level of exhaustion at the end of the day.  
If the character already has one or more levels of exhaustion, the character takes two levels in either case.  

* However, considering the length of EA and the usual amount of long rests a player usually takes, I've decided to tweak those numbers a little bit. The end result is as follows:
> Characters who don't eat before taking a long rest suffer the effects of exhaustion.  
A character who is `Hungry` or `Unsatisfied` receives one level of exhaustion after long resting.  
A character who is `Fed` counts as half-day. Being `Fed` to days in a row causes one level of exhaustion.
A character who is `Satiated` decreases on level of exhaustion after long resting.

* For the moment, I have no intention of implementing the **Water** part, but that might change in the future
* Following the PHB, exhaustion is cumullative and the effects are listed below:

| Level | Effect |
| :--: | :--: |
| 1 | Disadvantage on ability checks |
| 2 | Speed halved |
| 3 | Disadvantage on attack rolls and saving throws |
| 4 | Hit point maximum halved |
| 5 | Speed reduced to 0 |
| 6 | Death |

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
