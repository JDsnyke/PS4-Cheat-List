# PS4 Cheat Code / Offset List
![GitHub last commit](https://img.shields.io/github/last-commit/JDsnyke/PS4-Cheat-List.svg) ![GitHub issues](https://img.shields.io/github/issues/JDsnyke/PS4-Cheat-List.svg) ![GitHub pull requests](https://img.shields.io/github/issues-pr/JDsnyke/PS4-Cheat-List.svg) ![GitHub repo size in bytes](https://img.shields.io/github/repo-size/JDsnyke/PS4-Cheat-List.svg) ![license](https://img.shields.io/github/license/JDsnyke/PS4-Cheat-List.svg)

List of PS4 cheat codes / offsets found for either [PS4Cheater](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/) or [NetCheatPS4](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/) :scroll:

## Table of Contents

* [Disclaimer](#disclaimer)

* [Information](#information)

* [Guides / Tutorials](#guides--tutorials)

* [Program / Tool Links](#program--tool-links)

* [Cheat Usage and Template](#cheat-usage-and-template)

* [Contributions](#contributions)

* [Pull / Push Request Rules](#pull--push-request-rules)

* [List](#list)

* [Community](#community)

* [Contact Me](#contact-me)

* [Donate](#donate)

* [License](#license)

## Disclaimer

All codes belong to their respective owners. I am merely gathering them here for ease of use.

I do not and cannot guarantee the accuracy nor the reliability of either these programs / software nor of these codes / offsets.

I nor the original publishers of these codes are to be blamed for any issues that arise with their use.

In other words, __USE AT YOUR OWN RISK__!

## Information

Original threads found [here](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/), [here](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/) and [here](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/) on the [psxhax](https://www.psxhax.com/) forum.

Also huge thread found [here](http://www.maxconsole.com/forums/ps4-game-cheat-codes.266/) and [here](https://playstationhax.xyz/forums/forum/163-ps4-cheat-codes-for-ps4cheater/) at [maxconsole](http://www.maxconsole.com/) and [playstationhax](https://playstationhax.xyz/) forums respectively.

## Guides / Tutorials

* How to jailbreak your PS4 : [HERE](https://gbatemp.net/threads/aio-ps4-exploit-guide.497858/) and [HERE](https://www.youtube.com/watch?v=-JEeyT-zH64)

* How to change your avatar / profile pic on a jailbroken PS4 : [HERE](https://www.youtube.com/watch?v=_8YEaihW3dI)

* How to create custom themes for a jailbroken PS4 : [HERE](https://www.psxhax.com/threads/making-a-ps4-theme-pkg-for-4-05-4-55-tutorial-by-mangekyou222.4907/) and [HERE](https://www.youtube.com/watch?v=8Gyg6TIxfLw)

* How to dump PS4 game disc's into PKG files : [HERE](https://playstationhax.xyz/forums/topic/4260-how-to-rebuild-your-fake-signed-patched-raw-ps4-game-dump/)

* How to run PS4 pkg's from a USB drive : [HERE](https://www.youtube.com/watch?v=nGa2ZKd2_Qc)

* How to install game updates (disc only) on a jailbroken PS4 : [HERE](https://www.youtube.com/watch?v=-6HzmOes8mw)

* How to find game offsets / cheats for PS4 : [HERE](https://www.youtube.com/watch?v=GFOSc-bVbyg)

## Program / Tool Links

* PS4Cheater : [GITHUB](https://github.com/hurrican6/PS4_Cheater/releases) or [THREAD](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/)

* NetCheatPS4 : [GITHUB](https://github.com/BISOON/netCheatAPI-for-PS4) or [THREAD](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/)

* PS4 Cheat Manager : [0.1.3](http://www26.zippyshare.com/v/c1uzaoQR/file.html)

* PS4 Trainer Utility : [0.9.3](http://www94.zippyshare.com/v/bfxSG6cx/file.html) or [THREAD](https://www.psxhax.com/threads/ps4-trainer-utility-community-edition-tuce-v0-9-by-zerofox.4847/)

## Cheat Usage and Template

* Currently the easiest way to use cheats are to use the [cht](https://github.com/JDsnyke/PS4-Cheat-List/tree/master/cht/) files on [PS4Cheater](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/)

* The codes in the [list](#list) below are the corresponding addresses you should keep an eye out for on PS4Cheater and NetCheatPS4

* The NetCheatPS4 format :

    ```
    0 FFFFFF (Address) FF (Value)
    ```

* The PS4Cheater format : listed similarly to NetCheatPS4 format in order to maintain uniformity

* Some offsets like this ```0xFFFFFF``` have been listed as ```0 FFFFFF``` in order to maintain uniformity

* The CHT File format as of PS4Cheater 1.2 :

    ```
    1.2|eboot.bin
    data|FF (?)|FFFFFF (Address)|4 bytes|FF (Value)|0 or 1|Name (eg: Money)|
    data|FF (?)|FFFFFF (Address)|4 bytes|FF (Value)|0 or 1|Name (eg: Potions)|
    ```

    ```
    1.2|eboot.bin
    data|25|7CD9A0|4 bytes|99|0|Apples|
    ```

* The end goal should be to use these codes / offsets to generate user friendly cht files!

## Contributions

I will update at my pace.

What I have here is mostly incomplete and untested.

Feel free to [Fork](https://github.com/JDsnyke/PS4-Cheat-List/fork) and maintain your own versions. (Or even Push your Changes!)

## Pull / Push Request Rules

* Ensure you stay up to date with my repo and vice versa

* Please don't change the 'format' of the README.md unnecessarily (keep a uniform document across all forks)

* Maintain an alphabetical order

* Add relevant Title ID and Patch versions

* Add source next to game title

* If available, upload the relevant cht files and link it next to the game title

## List

> Tip - search using Ctrl + F on Windows or Command + F on Mac

> Tip - visit the included source links if you have any doubts

> Tip - save cht files easily by hovering over [CHT File] --> pressing 'right click' and then 'save link as'

> Tip - cht files can be found [here](https://github.com/JDsnyke/PS4-Cheat-List/tree/master/cht/) or next to specific game titles

* Atelier Sophie : The Alchemist of the Mysterious Book (CUSA05034 - Ver 1.0.1 - Firm 4.55 - PS4Cheater 1.4.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-18#post-85386) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-19#post-85614) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Atelier_Sophie_MB_(CUSA05034-Ver_1.0.1).cht) [[Wiki Guide]](https://www.ign.com/wikis/atelier-sophie-the-alchemist-of-the-mysterious-book)

    ```
    Money

    0 1E30E3A0

    Sophie Max All

    0 1E30E3C8

    Monika Max All

    0 1E30EB68

    Oskar Max All

    0 1E30EF38

    Julio Max All

    0 1E30F308

    Corneria Max All

    0 1E30FAA8

    Leon Max All

    0 1E310248
    ```

* Bloodborne (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-12#post-65721) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-13#post-65949
) [[Wiki Guide]](https://www.ign.com/wikis/bloodborne)

    ```
    Blood Echo [1]

    0 2082674C4
    0 208A674C4
    0 20840C06C
    ```

    ```
    Blood Echo [2]

    0 207C0C08C
    0 2082674E4
    0 21369B7D8
    0 225B03FF8
    0 311F17738
    0 311F17740
    0 311F197F0
    ```

* Bloodborne Game of the Year Edition (CUSA03173 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73944) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Bloodborne_GOTY_(CUSA03173-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/bloodborne)

    ```
    Blood Echo

    0 2082674C4
    ```

* Call of Duty : Black Ops 3 (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/) [[Wiki Guide]](https://www.ign.com/wikis/call-of-duty-black-ops-3)

    ```
    Player State

    0 21A8164

    Index

    0 17010

    Freeze (0x01 - frozen) (0x00 - unfrozen)

    0 21A8167

    Flag (0x04 - default) (0x05 - godmode) (0x06 - spectate) (0x07 - spectate w/ godmode)

    0 21A8180

    Location X, Y, Z

    0 21A8190

    Killstreak 1, 2 and 3

    0 21A87AC
    0 21A87B0
    0 21A87B4

    Primary Ammo Reserve

    0 21A87B8

    Secondary Ammo Reserve

    0 21A87BC

    Ammo 1, 2, 3, 4, 5 and 6

    0 21A87F4
    0 21A87F8
    0 21A87FC
    0 21A8800
    0 21A8804
    0 21A8808

    UAV (0x00 - default) (0x02 - scramble uav)

    0 21A88E4

    Vision (0x00 - default) (0x80 - thermal)

    0 21A88E9

    Body State (0x00 - default) (0x01 - cloak) (0x02 - hologram)

    0 21A88F9

    Name

    0 21BED64

    Zombies Primary Ammo Reserve

    0 21A87AC

    Zombies Secondary Ammo Reserve

    0 21A87B4

    Zombies Ammo

    0 21A87E8

    Zombies Points

    0 21BEE14
    ```

* Call of Duty : Ghosts (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/) [[Wiki Guide]](https://www.ign.com/wikis/call-of-duty-ghosts)

    ```
    FPS (80, 78, 10, 01)

    0 81B09A

    FPS String

    0 BDEDE5

    Name

    0 1F0F29C

    Primary Weapon

    0 1F0C26C

    Primary Ammo - Clip

    0 1F0C454

    Primary Ammo - Stock

    0 1F0C3D4

    Secondary Ammo - Clip

    0 1F0C460

    Secondary Ammo - Akimbo Clip

    0 1F0C464

    Grenade Ammo

    0 1F0C43C

    Tactical Ammo

    0 1F0C448
    ```

* Call of Duty : Infinite Warfare (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/) [[Wiki Guide]](https://www.ign.com/wikis/call-of-duty-infinite-warfare)

    ```
    Player State

    0 3D3E540

    Index

    0 6CC8

    Location X, Y, Z

    0 3D3E560

    Name

    0 3D430FC

    Radar (0x00 - scramble uav) (0x02 - default)

    0 3D431B4

    Primary Reserve Ammo

    0 3D3EDEC

    Secondary Reserve Ammo

    0 3D3EE04

    Ammo 1, 2 and 3

    0 3D3EF54
    0 3D3EF78
    0 3D3F008

    Zombies Reserve Ammo 1 and 2

    0 3D3EE04
    0 3D3EE4C

    Zombies Ammo 1 and 2

    0 3D3EF78
    0 3D3EFC0
    ```

* Call of Duty : Modern Warfare Remastered (CUSAXXXXX - Ver 1.0.7 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-62317) [[Wiki Guide]](https://www.ign.com/wikis/call-of-duty-4-modern-warfare/Remaster)

    ```
    Name

    0 7347322

    Scoreboard Score, Kills, Deaths and Assists - 0x2 Bytes (FF FF = 65535)

    0 73473CE
    0 73473D0
    0 73473D2
    0 73473D4

    Ammo - 0x3 Bytes (FF FF FF = Infinite)

    Primary Ammo Clip

    0 7342E28

    Primary Ammo Reserve

    0 7342D5C

    Secondary Ammo Clip

    0 7342DF8

    Secondary Ammo Reserve

    0 7342D44

    Grenade Ammo

    0 7342E10

    Tactical Ammo

    0 7342E40

    Grenade Launcher Attachment (uses Tactical Ammo)

    0 7342E58

    Perk Ammo

    0 7342E58
    ```

* Crash Bandicoot N Sane Trilogy (CUSA07399 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2 & 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-18#post-71778) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-12#post-82472) [[CHT File 1.2]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Crash_Bandicoot_N_Sane_Trilogy_(CUSA07399-Ver_1.0.0).cht) [[CHT File 1.4]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Crash_Bandicoot_N_Sane_Trilogy_V2_(CUSA07399-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/crash-bandicoot-remasters)

    ```
    Apples [1]

    0 2587CD9A0

    Boxes [2] [CHT File 1.4]

    Address's are not available (currently), please use cht file instead.
    ```

* Dark Souls 3 - Fire Fades Edition (CUSA07439 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-5#post-78521) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-8#post-78146) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dark_Souls_3_FFE_(CUSA07439-Ver_X.X.X).cht) [[Wiki Guide]](https://www.ign.com/wikis/dark-souls-3)

    ```
    Souls

    0 203AF9D1C
    0 203DA9B34

    Ember

    0 203DAA568

    Estus Flask

    0 203AFA73C
    0 203DAA4E8

    Estus Shard

    0 203DAA728

    Undead Bone Shard

    0 203DAAB38

    Titanite (reinforce materials)

    0 203DAA628
    0 203DAAE78
    0 203DAAFC8
    0 203DAB828
    0 203DAB838
    0 203DABA18
    ```

* Dark Souls 3 - Game of the Year (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-2#post-73360) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dark_Souls_3_(CUSAXXXXX-Ver_X.X.X).cht) [[Wiki Guide]](https://www.ign.com/wikis/dark-souls-3)

    ```
    Souls

    1 9A9B34
    1 3E17670
    1 3E1A8EC
    1 3E1A8F0
    1 6CCA1A8
    1 6CCA1AC
    ```

* Dead Island : Definitive Edition (CUSAXXXXX - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/dead-island-definitive-edition-cheat-codes.46586/#post-363244) [[2]](https://playstationhax.xyz/forums/topic/4414-dead-island-definitive-edition-ps4-cheater-455-cheat-codes/) [[Wiki Guide]](https://www.ign.com/wikis/dead-island)

    ```
    Cash

    0 401F882DF8
    ```

* Dead Rising 1 HD Remake (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/dead-rising-1-hd-remake-cheat-codes.46552/) [[2]](https://playstationhax.xyz/forums/topic/4379-dead-rising-1-hd-remake-ps4-cheater-cheat-codes/) [[Wiki Guide]](https://www.ign.com/wikis/dead-rising)

    ```
    PP

    0 21E28928C
    ```

* Devil May Cry : Definitive Edition (CUSA01013 - Ver 1.0.0 - Firm 4.55 - PS4 Trainer Utility) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-7#post-82860) [[Wiki Guide]](https://www.ign.com/wikis/dmc-devil-may-cry)

    ```
    Red Orbs

    0 21AEFC450
    ```

* Diablo 3 (CUSA00433 - Ver X.X.X - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-64673) [[Wiki Guide]](https://www.ign.com/wikis/diablo-3)

    ```
    Gold (address changes on restart)

    0 20C71D3CC
    ```

* Digimon Cyber Sleuth (CUSA02966 - Ver 1.0.0 - Firm X.XX - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-47#post-83365) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-18#post-85469) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Digimon_Cyber_Sleuth_(CUSA02966-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/digimon-story-cyber-sleuth/)

    ```
    Address's are not available (currently), please use cht file instead.

    20k XP

    0 XXXXXX

    Money

    0 XXXXXX

    Memory Up

    0 XXXXXX

    HP Capsule B

    0 XXXXXX

    HP Spray C

    0 XXXXXX

    Medical Spray

    0 XXXXXX
    ```

* Dragon Quest Builders (CUSA05235 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.3) [[1]](https://github.com/JDsnyke/PS4-Cheat-List/issues/3#issuecomment-374686806) [[2]](https://github.com/JDsnyke/PS4-Cheat-List/issues/3#issuecomment-374695459) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dragon_Quest_Builders_(CUSA05235-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/dragon-quest-builders)

    ```
    Infinite HP

    1 21129A198

    Always Max Hunger

    1 21129A19C

    Set Days Elapsed To 1 (Part 1)

    0 21129A194

    Set Days Elapsed To 1 (Part 2)

    0 21129A1A4

    Set Attack Value

    1 2112AD870

    Set Defense Value

    1 2112AD872

    Infinite Item 1

    1 2112B2902

    Infinite Item 2

    1 2112B2906

    Infinite Item 3

    1 2112B290A

    Infinite Item 4

    1 2112B290E

    Infinite Item 5

    1 2112B2912

    Infinite Item 6

    1 2112B2916

    Infinite Item 7

    1 2112B291A

    Infinite Item 8

    1 2112B291E

    Put Best Sword in Slot 15

    0 2112B2974

    Put Best Hammer in Slot 16

    0 2112B2978
    ```

* Dragon Quest Heroes (CUSA02769 - Ver X.X.X - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-6#post-74099) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dragon_Quest_Heroes_(CUSA02769-Ver_X.X.X).cht) [[Wiki Guide]](https://www.ign.com/wikis/dragon-quest-heroes/)

    ```
    Money

    0 1FFB40

    Minimedals

    0 1FFB44

    Aila Max EXP

    0 1F45C8

    Aurora Max EXP

    0 1F4424

    Luceus Max EXP

    0 1F44B0

    Alena Max EXP

    0 1F4654

    Doric Max EXP

    0 1F4654

    Kiryl Max EXP

    0 1F46E0
    ```

* Dying Light (CUSAXXXXX - Ver X.X.X - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-47#post-83326) [[Wiki Guide]](https://www.ign.com/wikis/dying-light)

    ```
    Health

    0 402DC54B14
    0 402DC54B18
    ```

* FIFA 15 (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-9#post-63548) [[Wiki Guide]](https://www.ign.com/wikis/fifa-15)

    ```
    Money

    0 50030671D0 3B9AC9FF
    ```

* Final Fantasy XII (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/ff-xii-zodiac-cheat-codes.46554/) [[2]](https://playstationhax.xyz/forums/topic/4377-ff-xii-zodiac-ps4-cheater-405-cheat-codes/) [[Wiki Guide]](https://www.ign.com/wikis/final-fantasy-xii)

    ```
    Vaan EXP

    0 66B384D4 (high probability of being the address to watch out for)
    0 66E999E0
    0 66E9C350
    0 22EEB96FF
    0 22EEB98FF
    0 22EEB99FF

    Vaan Health

    0 66B384D8
    0 66E99A00
    0 66E9C370
    0 68954B10

    Gil (not static)

    0 6B707E4C

    Potions

    0 66B3CA88
    ```

* Final Fantasy XV (CUSAXXXXX - Ver X.X.X - Firm X.XX - PS4Cheater 1.2 [1] and NetCheatPS4 [2]) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-17#post-71001) [[2]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-10#post-63601) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Final_Fantasy_XV_(CUSAXXXXX-Ver_X.X.X).cht) [[Wiki Guide]](https://www.ign.com/wikis/final-fantasy-15)

    ```
    Money [2]

    0 50030671D0

    Infinite Ability Points [2]

    0 50030671DC

    All Characters Max Exp [2]

    0 5002EC06C0
    0 5002ECB7C0
    0 5002ED68C0
    0 5002EE19C0

    Items (In Location Order - 1, 2, 3 ... 10) [1]

    0 310620C
    0 3106214
    0 310621C
    0 3106224
    0 310622C
    0 3106234
    0 310623C
    0 3106244
    0 310624C
    0 3106254

    Ingredients (In Location Order - 1, 2, 3 ... 10) [1]

    0 3106C0C
    0 3106C14
    0 3106C1C
    0 3106C24
    0 3106C2C
    0 3106C34
    0 3106C3C
    0 3106C44
    0 3106C4C
    0 3106C65

    Treasures (In Location Order - 1, 2, 3 ... 10) [1]

    0 3107414
    0 310741C
    0 3107424
    0 310742C
    0 3107434
    0 310743C
    0 3107444
    0 310744C
    0 3107454
    0 310745C

    Auto Parts (In Location Order - 1, 2, 3 ... 10) [1]

    0 3107C0C
    0 3107C14
    0 3107C1C
    0 3107C24
    0 3107C2C
    0 3107C34
    0 3107C3C
    0 3107C44
    0 3107C4C
    0 3107C54

    Leisure Goods (In Location Order - 1, 2, 3 ... 10) [1]

    0 310840C
    0 3108414
    0 310841C
    0 3108424
    0 310842C
    0 3108434
    0 310843C
    0 3108444
    0 310844C
    0 3108454

    Key Items (In Location Order - 1, 2, 3 ... 10) [1]

    0 310640C
    0 3106414
    0 310641C
    0 3106424
    0 310642C
    0 3106434
    0 310643C
    0 3106444
    0 310644C
    0 3106454
    ```

* Fl4tout : Total Insanity (CUSA07458 - Ver 1.0.3 - Firm 4.55 - PS4Cheater 1.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-4#post-77659) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Fl4tout_Total_Insanity_(CUSA07458-Ver_1.0.3).cht)

    ```
    Cash

    0 301D1D1C8
    ```

* God Eater 2 : Rage Burst (CUSA03370 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-72994) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/God_Eater_2_Rage_Burst_(CUSA03370-Ver_1.0.0).cht)

    ```
    Money

    0 14919EB90
    ```

* God of War 3 (CUSA01715 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-12#post-82472) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-47#post-83300) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/God_of_War_3_(CUSA01715-Ver_1.0.0).cht)

    ```
    Address's are not available (currently), please use cht file instead.

    Life

    0 XXXXXX

    Souls

    0 XXXXXX

    Magic

    0 XXXXXX

    Special Sword

    0 XXXXXX
    ```

* Gravity Rush (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-12#post-64486)

    ```
    Gems

    0 264522937
    ```

* Gravity Rush (CUSA01113 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-12#post-82472) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Gravity_Rush_(CUSA01113-Ver_1.0.0).cht)

    ```
    Address's are not available (currently), please use cht file instead.

    Gems

    0 XXXXXX

    Life

    0 XXXXXX
    ```

* Gravity Rush 2 (CUSA03694 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-2#post-58385)

    ```
    Gems

    0 01E7A2AC
    0 01E7A2B0
    ```

* Horizon Zero Dawn (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-9#post-65171) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-11#post-65434) [[Wiki Guide]](https://www.ign.com/wikis/horizon-zero-dawn/)

    ```
    Arrows [1]

    0 F5CF09E84

    Metal Pieces [1]

    0 24CEDAF84
    0 25CF2D9B4

    Skills [2]

    0 200E9E81F
    0 200EA0ECB
    0 25CF8212C
    0 25D915190
    0 264C68899
    ```

* Horizon Zero Dawn (CUSA07320 - Ver 1.0.0 - Firm X.XX - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-49#post-83844) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Horizon_Zero_Dawn_(CUSA07320-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/horizon-zero-dawn/)

    ```
    Address's are not available (currently), please use cht file instead.

    Test Health

    0 XXXXXX

    Precision Arrows

    0 XXXXXX

    Fire Arrows

    0 XXXXXX
    ```

* inFAMOUS : Second Son (CUSA00004 - Ver 1.0.0 - Firm 4.05 - PS4Cheater 1.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-6#post-81863)

    ```
    Shards

    0 21A36DD8

    Bombs

    0 27216DD4
    ```

* Kingdom Hearts 2.8 (CUSA05787 - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/kingdom-hearts-2-8-cheat-codes.46553/) [[2]](https://playstationhax.xyz/forums/topic/4378-kingdom-hearts-28-ps4-cheater-405-cheat-codes/)

    ```
    Sora Munny

    0 2F65C44C

    Sora EXP

    0 2F6A3DA0

    Meow Wow EXP

    0 2F654524
    ```

* Kingdom Hearts 2.8 (CUSA05787 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/kingdom-hearts-2-8-cheat-codes.46585/) [[2]](https://playstationhax.xyz/forums/topic/4415-kingdom-hearts-28-ps4-cheater-455-cheat-codes/) [[3]](https://github.com/Weysincha) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Kingdom_Hearts_2.8_(CUSA05787-Ver_1.0.0).cht)

    ```
    Sora Munny (Set the Values when you in the Option Menu)

    0 D5844C

    Ability Links

    0 D5052C

    Main Character EXP - Sora

    0 D9FDA0

    Main Character EXP - Ryku

    0 D583CC
    ```

* LEGO Batman 3 Beyond Gotham (CUSA00580 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-54#post-84995) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/LEGO_Batman_3_Beyond_Gotham_(CUSA00580-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/lego-batman-3-beyond-gotham)

    ```
    Coins

    1 230647BE8
    ```

* LEGO Marvel Super Heroes (CUSA00044 - Ver X.X.X - Firm X.XX - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-53#post-84751) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/LEGO_Marvel_Super_Heroes_(CUSA00044-Ver_X.X.X).cht) [[Wiki Guide]](https://www.ign.com/wikis/lego-marvel-super-heroes)

    ```
    Coins

    0 23039D820
    ```

* LEGO Star Wars The Force Awakens (CUSA03397 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-54#post-85043) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/LEGO_Star_Wars_The_Force_Awakens_(CUSA03397-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/lego-star-wars-the-force-awakens/)

    ```
    Coins

    0 21C743660
    ```

* Middle Earth: Shadow of Mordor GOTY Edition (CUSA02152 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4.3) [[1]](https://github.com/JDsnyke/PS4-Cheat-List/issues/3#issuecomment-377993228) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-54#post-85280) [[3]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-55#post-85422) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Shadow_of_Mordor_GOTY_(CUSA02152-Ver 1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/middle-earth-shadow-of-mordor)

    ```
    Note : Please use the 'First Save Slot' for this game. Using other slots may cause issues.

    Note : Disregard duplicates in the cht file. They were meant as backups by the author.
    ```

    ```
    Address's are not available (currently), please use cht file instead.

    Attribute Points / Currency (Set your amount, kill 1, go back to Main Menu, reload your save)

    0 XXXXXX

    Exp (Go to Pause Menu, set your exp, go out from Pause Menu then back in)

    0 XXXXXX

    Skill Points (Set your amount, kill 1, go back to Main Menu, reload your save)

    0 XXXXXX

    Tier Points (Go to Pause Menu, set your exp go out from Pause Menu then back in)

    0 XXXXXX

    Inf Arrows

    0 XXXXXX

    Inf Focus

    0 XXXXXX

    Inf HP

    0 XXXXXX
    ```

* Mortal Kombat X Standard Edition (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-12#post-65610)

    ```
    No Money Krypt

    0 037688A4
    0 037688A8
    0 037688D0
    ```

* NieR Automata (CUSA04551 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73436) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-21#post-85750) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/NieR_Automata_(CUSA04551-Ver_1.0.0).cht)

    ```
    Money

    0 458C5810

    EXP (Set Exp 9999999 -> To get Max LvL 99)

    0 458CD9C0

    Medium Recovery (Minimum 1 MR required first)

    1 458C5828

    Health (Lock Max HP) [2]

    0 454034C0
    ```

* Nioh (CUSA07123 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-5#post-80457) [[2]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-6#post-80490) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Nioh_(CUSA07123-Ver_X.X.X).cht)

    ```
    Spirit Iron Fragment

    0 16003A90

    HQ Tamahagane

    0 16005458
    0 160048A0

    HQ Wood

    0 16004968
    0 16004A30

    HQ Lacquer

    0 160040D0
    0 16004260

    HQ Ingot

    0 160039C8
    0 160059D0

    HQ Leather Cord

    0 160052C8
    0 16004580

    HQ Leather Kozane

    0 16004710
    0 160047D8

    HQ Iron Kozane

    0 16004328
    0 160044B8

    Iron Chunk

    0 16004198

    Demon Horn

    0 16004D50

    Great Centipede Fang

    0 16005520

    Bangasa Rib

    0 16005070

    Spirit Stone

    0 15FE18A8

    Small Spirit Stone

    0 15FE02B8

    Large Spirit Stone

    0 15FE2A88

    Guardian Spirit Talisman

    0 160170B8

    Slot Talisman

    0 16017310

    Arrow

    0 15FEB238

    Special Arrow

    0 15FE3E08

    Rifle Ammo

    0 15FE65D8

    Special Rifle Ammo

    0 15FE2268

    Hand Cannon Ammo

    0 15FE60F8

    Special Hand Cannon Ammo

    0 15FE3448

    Glory

    0 161CFB8C
    ```

* Persona 5 (CUSA06638 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73753) [[2]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-75659) [[3]](https://github.com/JDsnyke/PS4-Cheat-List/issues/3#issuecomment-372824847) [[4]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-4#post-76381) [[5]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-6#post-80998) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Persona_5_(CUSA06638-Ver_1.0.0).cht)

    ```
    Money

    0 195E674

    Medicine (Max 999)

    0 195DBB0

    Main Character Level [4]

    0 B38F738

    Main Character EXP (Set your EXP, after one Battle you get the lvl ups)

    0 195B73C

    Main Character HP (Max 999)

    1 195B72C

    Main Character Skill Points (Max 999)

    1 195B730

    Main Character Bullets [3]

    1 7B1D39B4

    Ryuji HP [3]

    1 7B1D39CC

    Ryuji EXP [3]

    0 7B1D3A0C

    Ryuji Gun Bullets [3]

    1 7B1D3C54

    Ryuji Skill Points [3]

    1 7B1D39D0

    Morgana Cat HP [3]

    1 7B1D3C6C

    Morgana Cat Skill Points [3]

    1 7B1D3C70

    Morgana Cat EXP [3]

    0 7B1D3CAC

    Morgana Cat Gun Bullets [3]

    1 7B1D3EF4

    Ann HP [3]

    1 7B1D3F0C

    Ann Skill Points [3]

    1 7B1D3F10

    Ann EXP [3]

    0 7B1D3F4C

    Ann Gun Bullets [3]

    1 7B1D4194

    Days until Expulsion [4]

    0 B392AF0

    Kamoshida Security Level [4]

    0 B392CE4

    Casino Points [2]

    0 23596D60

    Fishing Points [5]

    0 7690AC40
    ```

* Resident Evil 4 (CUSA04885 - Ver 1.1.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-54#post-85014) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Resident_Evil_4_(CUSA04885-Ver_1.1.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/resident-evil-4)

    ```
    Currency

    0 7E485C7C  
    ```

* Resident Evil Origins : RE 0 (CUSA02461 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/re-origins-collection-re-0-ps4-cheater-4-55-codes.46606/) [[2]](https://playstationhax.xyz/forums/topic/4413-re-origins-collection-re-0-ps4-cheater-455-codes/)

    ```
    Handgun Ammo and Equipped Ammo (Slot 01)

    0 20D0EFCDC

    Ink Ribbon (Slot 04)

    0 20D14D554
    ```

* Tales of Zestiria (CUSA02461 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/ps4-cheater.4529/page-2#post-64700)

    ```
    Sorey Exp

    0 103DE7D5BC

    Edna Exp

    0 103DE8E2FC

    Rose Exp

    0 103DE8193C

    Zaveid Exp

    0 103DE9697C

    Lailah Exp

    0 103DE89FBC

    Mikleo Exp

    0 103DE85C7C

    Money

    0 103F605F60

    All Consumables

    0 103DE01024
    0 103DE01028
    0 103DE0102C
    0 103DE01030
    0 103DE01034
    0 103DE01038
    0 103DE0103C
    0 103DE01040
    0 103DE01044
    0 103DE01048
    0 103DE0104C
    0 103DE01050
    0 103DE01054
    0 103DE01058
    0 103DE0105C
    0 103DE01060
    0 103DE01064
    0 103DE01068
    0 103DE0106C
    0 103DE01070
    0 103DE01074
    0 103DE01078
    0 103DE0107C
    0 103DE01080
    0 103DE01084
    0 103DE01088
    ```

* Tekken 7 (CUSA06014 - Ver 1.1.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-17#post-84529) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Tekken_7_(CUSA06014-Ver_1.1.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/tekken-7)

    ```
    Address's are not available (currently), please use cht file instead.

    Health

    0 XXXXXX
    ```

* The Last of Us (CUSAXXXXX - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/the-last-of-us-ps4-cheater-4-55-cheat-codes.46608/) [[2]](https://playstationhax.xyz/forums/topic/4418-the-last-of-us-ps4-cheater-455-cheat-codes/)

    ```
    Ammo (currently has issues, view source for more details)

    0 11748B719C
    ```

* Uncharted Trilogy (CUSA02343 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-2#post-58321)

    ```
    Uncharted 1 - 1st Weapon Bullets

    0 00EA5444

    Uncharted 1 - 2nd Weapon Bullets

    0 00EA54F8
    ```

* Watch Dogs 2 (CUSA04294 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-7#post-82771) [[2]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-7#post-82785) [[3]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-21#post-85750) [[4]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-21#post-85757) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Watch_Dogs_2_(CUSA04294-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/watch-dogs-2)

    ```
    Money [1]

    1 204A81158

    Money [3] [4]

    0 200863CA8
    1 2005B3CA8

    Follower XP [3]

    0 12684EA8

    Life [4]

    1 51E5E660

    Inf Hack [4]

    1 51E273A0

    Inf Hack [2]

    1 207A7CD74
    ```

* Witcher 3 GOTY Edition (CUSA05572 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-19#post-85569) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-58#post-85772) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Witcher_3_GOTY_Edition_(CUSA05572-Ver_1.0.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/the-witcher-3-wild-hunt)

    ```
    Note : According to the author, could be game version 1.3.0 or 1.3.1 compatible.

    Note : When setting XP LV, set value to 600000 than go get a kill. If u mess up and then it says wrong section, simply reboot and set again.
    ```

    ```
    Health

    0 XXXXXX
    0 XXXXXX

    Level XP

    0 XXXXXX
    0 XXXXXX

    Skill Points

    0 XXXXXX
    0 XXXXXX
    0 XXXXXX
    0 XXXXXX
    0 XXXXXX
    0 XXXXXX
    ```

* Witcher 3 GOTY Edition (CUSA05574 - Ver 1.3.0 - Firm 4.55 - PS4Cheater 1.4) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-18#post-85337) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-18#post-85475) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Witcher_3_GOTY_Edition_(CUSA05574-Ver_1.3.0).cht) [[Wiki Guide]](https://www.ign.com/wikis/the-witcher-3-wild-hunt)

    ```
    Money

    1 12333A9A14

    Skill Points

    0 1007C03710
    ```

* Yakuza 0 (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-6#post-64825) [[Wiki Guide]](https://www.ign.com/wikis/yakuza-0/)

    ```
    Money (Dynamic Address - always 2nd value in memory map of size 372,800 KB)

    0 209E8F2B0
    ```

* Yakuza 6 (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-9#post-63548)

    ```
    Money

    0 2023B1D38
    ```

* Yakuza Ishin (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4)  [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-11#post-63905)

    ```
    Money

    0 2003E6BC8 3B9AC9FF
    ```

## Community

Join this [Discord](https://discord.gg/FpRwaZE) channel to chat with like minded people or join the [psxhax](https://www.psxhax.com) forum today!

[![Discord Banner](/assets/discord_join_blurple_square.png "Join the Discord Channel Today!")](https://discord.gg/FpRwaZE)

## Contact Me

Join our [Slack](https://psxcheatlist-slack.herokuapp.com) channel to be notified of the latest commits, open a [Github](https://github.com/JDsnyke/PS4-Cheat-List/issues) issue or mention me using ```@Shurikan117``` on [psxhax](https://www.psxhax.com)

## Donate

[![Donate with Bitcoin](https://en.cryptobadges.io/badge/small/1AQrV5YKDv3WnwEYddHr5UFtiTLUvQ5pQr)](https://en.cryptobadges.io/donate/1AQrV5YKDv3WnwEYddHr5UFtiTLUvQ5pQr)

[![Donate with Ethereum](https://en.cryptobadges.io/badge/small/0x2729F47611dC42758A2f918668E32f464e5d231B)](https://en.cryptobadges.io/donate/0x2729F47611dC42758A2f918668E32f464e5d231B)

[![Donate with Ripple](https://en.cryptobadges.io/badge/small/rJJsXCkzYwMKcnCZN3fVgrxeitYKpEcRZX)](https://en.cryptobadges.io/donate/rJJsXCkzYwMKcnCZN3fVgrxeitYKpEcRZX)

## License

Uses the [MIT](https://github.com/JDsnyke/PS4-Cheat-List/blob/master/LICENSE) license.
