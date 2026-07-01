# Basically Extra Social Time (B.E.S.T.)

Mods for The Legend of Heroes: Trails of Cold Steel games that ensure it's possible to fully bond with all the characters.
Tested on XSEED and NISA PC versions of the games.

For Cold Steel II, make sure to download [B.R.U.H.](https://github.com/TheShufflingFool/Black-Records-Unrestricted-Hunt) for an even better experience.

## Features
* increased the amount of available bonding points to ensure watching all bonding events is possible (aka "Max Bonding Points")
* increased the amount of available tickets for festival attractions - enough to spend time with each available character once - and adjusted time of day jumps accordingly (where applicable)
* changed the cost of Max Bonding Points bonus option to 0 when starting New Game+ in CS1 and CS2
* updated the system messages to account for increased amounts of bonding points and tickets (all messages in English, some messages in Japanese and French)
* unlocked an extra final bonding event option in CS1
* added an extra message at the end of CS4 (English text language only)

For exact numbers of bonding points and tickets, refer to [the table at the bottom](#amount-adjustments).

## Installation

### RECOMMENDED METHOD
1. Download the latest release of AdmiralCurtiss' [SenPatcher](https://github.com/AdmiralCurtiss/SenPatcher) and use it to patch your game.
2. Download the latest release of `ExtraSocialTime_CS(1/2/3/4).p3a` ([here](https://github.com/TheShufflingFool/Basically-Extra-Social-Time/releases/latest)).
3. Locate the game's main directory:
   * for Steam version, right-click on `The Legend of Heroes: Trails of Cold Steel (II/III/IV)` and select Manage → Browse local files
   * for GOG version, right-click on `The Legend of Heroes: Trails of Cold Steel (II/III/IV)` and select Manage installation → Show folder
4. Locate the `mods` folder. If it can't be found, start and quit the game.
5. Move or copy `ExtraSocialTime_CS(1/2/3/4).p3a` to the `mods` folder.
6. To uninstall, delete `ExtraSocialTime_CS(1/2/3/4).p3a` from the `mods` folder.

### UNSUPPORTED METHOD
If, for some reason, you can't or don't want to use SenPatcher, follow these steps:
1. Go to the latest release ([here](https://github.com/TheShufflingFool/Basically-Extra-Social-Time/releases/latest)) and download `Source code (zip)`.
2. Locate the game's main directory:
   * for Steam version, right-click on `The Legend of Heroes: Trails of Cold Steel (II/III/IV)` and select Manage → Browse local files
   * for GOG version, right-click on `The Legend of Heroes: Trails of Cold Steel (II/III/IV)` and select Manage installation → Show folder
3. Open the downloaded file, enter the folder for the game you want to mod and extract the `data` folder into the game's main directory (you can just drag and drop or copy and paste).
4. When prompted to merge folders and replace files, accept all changes.
5. To uninstall, verify integrity of game's files.

## FAQ
* **How do I know I installed the mod correctly?**  
  <ins>RECOMMENDED METHOD ONLY</ins>: You should see a new line regarding modded files in the main menu in the bottom right corner (or, if you have other mods and it was already there, the number of modded files should change). If it doesn't appear (or the number doesn't change), make sure you downloaded the correct file (you want the .p3a one, not any of the archives) and placed it inside the correct folder.
  <img width="1280" height="720" alt="bruh_installed" src="https://github.com/user-attachments/assets/6bc3aa58-ae1d-4d05-86aa-02d734efccfe" />
  If you use other mods and the amount of bonding points/tickets doesn't change, it's highly likely there is a compatibility issue. You can try editing `order.txt` inside the `mods` folder and moving `ExtraSocialTime_CS(1/2/3/4).p3a` to the top of the list. That should unlock the extra bonding points but might override changes from the other mods.

* **I'm in the middle of my playthrough. Do I have to start a new game to use the mod?**  
  No, it can be installed at any point. However, you want to do it BEFORE starting a free day/festival - if you already received the bonding points/tickets, the mod won't work until the next time.

* **I have the mod but I'm still missing a few bonding points/tickets. Did I do something wrong?**  
  Unlike NG+, the mod may not give you all the required bonding points/tickets right off the bat. You're still required to work for them, so go do some side content and you'll find what you need.
  
* **Will this work on Steam Deck?**  
  As far as I know, yes. I don't own one so I can't test it myself but, seeing that other mods work on it, I don't see why this one wouldn't.
  
* **What's with the silly name, AGAIN?**  
  Considering the number of people looking for Clear Data save files, it's obviously the best mod for first playthroughs. \</s>

## Amount adjustments
These are the amounts of bonding points/tickets you should start with with the mod installed.

### CS1 & CS2
| Date | Morning | Evening |
| ----: | :---: | :---: |
| 4/18 | 3 | 2 |
| 5/23 | 4 | 2 |
| 6/15 | 6 | N/A |
| 6/20 | 7 | 2 |
| 7/18 | 7 | 2 |
| 8/22 | 8 | 3 |
| 9/19 | 8 | 3 |
| 10/23 | 12 | N/A |
| 12/4 | 5 | N/A |
| 12/8 | 6 | N/A |
| 12/12 | 15 | N/A |
| 12/18 | 12 | N/A |
| 12/22 | 12 | N/A |
| 12/26 | 12 | N/A |

### CS3 & CS4
| Date | Morning | Evening |
| ----: | :---: | :---: |
| 4/16 | 3 | 2 |
| 5/14 | 5 | 2 |
| 6/11 | 5 | 4 |
| 7/4 | 5 | N/A |
| 7/9 | 6 | 4 |
| 7/17 | 13 | N/A |
| 8/20 | 4 | N/A |
| 8/22 | 4 | N/A |
| 8/24 | 5 | N/A |
| 8/26 | 5 | N/A |
| 8/27 | 7 | N/A |
| 8/29 | 7 | N/A |
| 8/31 | 16 | N/A |
