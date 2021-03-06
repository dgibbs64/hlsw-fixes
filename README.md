Website: <a href="https://hlswfixes.com/">https://hlswfixes.com</a>

<img src="https://danielgibbs.co.uk/wp-content/uploads/2015/08/hlsw_logo.png" alt="hlsw_logo" width="176" height="41" class="alignnone size-full wp-image-4024" />

<img src="https://danielgibbs.co.uk/wp-content/uploads/2015/08/hlsw-29.jpg" alt="hlsw-29" width="700" height="554" class="alignnone size-full wp-image-4021" />
<br>
An unofficial patch to HLSW that adds a few fixes and more supported servers.

# Adds Support for New Servers

* 7 Days to Die
* ARK: Survival Evolved
* Arma 3
* Blade Symphony
* Black Mesa: Deathmatch
* BrainBread 2
* Chivalry: Medieval Warfare
* Codename Cure
* Contagion
* Counter Strike: Global Offensive
* Day of Infamy
* Dota 2
* Double Action: Boogaloo
* Dystopia
* Empires
* Fistful of Frags
* GoldenEye: Source
* Homefront
* Hurtworld
* Insurgency
* Just Cause 2
* Killing Floor 2
* Medieval Engineers
* Natural Selection 2
* NEOTOKYO
* No More Room in Hell
* Nuclear Dawn
* Pirates, Knights & Knights II
* Rust
* Serious Sam 3
* Serious Sam HD
* Sniper Elite v2
* Sniper Elite 3
* Space Engineers
* Squad
* Sven Co-op
* Starbound
* The Ship
* War of the Roses

note: not all servers may not be fully functioning. Although the HLSW fixes will detect the server, rcon may not work. If the game engine is source it should work but others may not (its worth testing and letting me know).

# Fixes HLSW Bugs
* Fixes Rcon not working for source engine servers.

Without fix

<img src="http://i.imgur.com/4V0KPsv.png" alt="Rcon-no-fix" />

With fix

<img src="http://i.imgur.com/TxMnSUq.png" alt="Rcon-fix" />

* Fixes HL2 Servers being auto-detected as HL servers.

Without fix

 <img src="http://i.imgur.com/dFaZ3MP.png" alt="hl2-nofix" />

With fix

<img src="http://i.imgur.com/IxuHs5q.png" alt="hl2-fix" />

I stumbled across these posted that related to this issue. They resolved the problem and I decided to put these fixes in to an easy to use patch.
* http://www.nomoreroominhell.com/forums/index.php?showtopic=12214
* http://steamcommunity.com/app/222880/discussions/2/35220315821929357

# Install

Make sure you have HLSW v1.4.0.5 installed

1. Download this project <a href="https://github.com/dgibbs64/hlsw-fixes/archive/master.zip">here</a>.

2. Unzip the archive

3. Make sure you have HLSW v1.4.0.5 installed (installer provided).

4. Copy the contents of the hlsw directory to your HLSW directory.

C:\Program Files (x86)\HLSW

## Query Port
Some servers require you to know te query port as well as the game port.

example usage

[IP address]:[game port]:[query port]
127.0.0.0:12871:12881

I am aware that the following require this:
* 7 Days to Die
* Battlefield: Bad Company 2
* Hurtworld
* Natural Selection 2 (QueryPort= GamePort+1)

## Links
<a href="https://github.com/dgibbs64/hlsw-fixes">https://github.com/dgibbs64/hlsw-fixes</a>
<br>
<a href="https://forums.alliedmods.net/showthread.php?t=269963">https://forums.alliedmods.net/showthread.php?t=269963</a>
