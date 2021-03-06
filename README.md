﻿Card Idle Remastered
===========

Card Idle Remastered is a WPF remake of Idle Master, developed by jshackles (https://github.com/jshackles/idle_master). 

It offers rich UI and flexible idle management.

Card Idle Remastered was designed to browse all games with card drops and to idle one selected game as simple as possible (in a single click).

It helps to get remaining card drops in games you own without wasting disk space and CPU and RAM resources.

I publish notifications about new Card Idle releases in Twitter [#CardIdleRemastered](https://twitter.com/hashtag/CardIdleRemastered?src=hash). Additionally Card Idle Remastered performs auto-check for new releases at startup.

![](https://github.com/AlexanderSharykin/CardIdleRemastered/blob/master/Install/Card_Idle_Main_Page.png)

Requirements
-------
Steam account with non-F2P games with cards

Minimal understanding of Steam cards, game badges and card drops [Steam FAQ](https://steamcommunity.com/tradingcards/faq)

OS Windows 7 and higher

.Net Framework 4.5

Internet Explorer 10 or 11

Stable Internet connection

You should be logged into your Steam account via Steam client to start idling.

---

Card Idle has an official Steam account: [CardIdleRemastered](https://steamcommunity.com/profiles/76561198801350858/). Invite to friends!

![](https://github.com/AlexanderSharykin/CardIdleRemastered/blob/master/Install/Card_Idle_Profile.png)

---

Card Idle has badges preview feature. Badges art is collected by community and available on SteamCardExchange site.

![](https://github.com/AlexanderSharykin/CardIdleRemastered/blob/master/Install/Card_Idle_Showcases.png)

---

Card Idle works in a Single, Multi (Automatic) or Time Idle mode.

Time Idle Mode
-------

Open **Time Idle** tab

Click on Plus to add a new game to list

In the selection dialog enter game ID or store page url 

Confirm selection

Click Start button under game image

**Time Idle mode doesn't require login**

Card Idle saves games list before quit

Single Game Idle Mode
-------

Open **Badges** tab

Decide which game to idle and find it in the list using a grid scroll or a quick-search field

Click Start button

Wait until all cards drop and idle process stops

Automatic Game Idle Mode
-------

Open **Badges** Tab

Decide which games to idle and add them to the idle queue by clicking Enqueue button

Enqueue Selected button under the grid will add all games to the queue

Open **Queue** Tab

Change idle priority if necessary

Click Dequeue button to remove a game from the queue if necessary

Select Idle mode. Default mode is "One by One" which means that Card Idle runs one game idle process at a time and starts the next game only when all cards received. 

Two "Trial" modes ("Trial First" and "Trial Last") were introduces for games which have 2 hour delay before cards begin to drop. Card Idle will run such "trial" games together, stop those what reached 2 hour and pick next from the queue. Default number of processes is 16, max number is 255. When there is no more trial games Card Idle switches to "One by One" mode.

Due to changes in Steam card drop system it became possible to get 1 card drop with a simple method: 1. launch a game from library 2. wait some time 3. quit the game. "Periodic Switch" mode automates the process. Card Idle starts the 1st game from the queue, waits for a short interval, stops the game, waits a bit for Steam to react (and possibly drop a card), starts the 2nd game from the queue, waits, stops it, etc, repeat for all games in the queue.

If "All" mode is selected, Card Idle will start all games from the idle queue.

Launch automatic idle: click **[Start]** button

Click **[Stop]** button to interrupt automatic idle if necessary

**Card Idle stops all idle processes on quit or logout.**

**Card Idle saves idle queue before quit and clears it on logout**

License
-------

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation.  A copy of the GNU General Public License can be found at http://www.gnu.org/licenses/. For your convenience, a copy of this license is included.