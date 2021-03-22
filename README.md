<h1 align="center">Hypixel Skyblock Slayer Script 👋</h1>
 
 
## Table of Contents
- [Coming Soon](#coming_soon)
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions) 
- [License](#license)

# Coming Soon

- Legit mode
- VIP capatability
- XP/hour calculator
- Sven Slayer mode
- Setting to configure sword and Maddox slot

# Description
This script is made for MacroMod 1.12.2. It uses Entity Iterator paired with baritone to find mobs, pathfind, and kill them. The script requires MVP+ (VIP mode coming soon).
# Installation
💾 
Download and unzip the folder, place the 'macros' folder into an instance.
Download Baritone api forge for 1.12.2: https://github.com/cabaletta/baritone/releases?after=v1.2.13 and put it into your mods folder

I will make these files (requested by Iceshades)
- add to "onBetterChat"

```$${ifcontains(%CHATCLEAN%,"[OPEN MENU]");   strip(&chat_json,"%CHATJSON%");   regexreplace(&chat_json,"\"","'");           match("%&chat_json%","'action':'run_command'\W'value':'(/cb [a-z0-9-]+)'",&match,1);   log("&7The following &emaddox-code &7has been matched out of the &eJSON-string&7: &d%&match%");   echo("%&match%");endif;}$$```

- add to "onChat" 

```$$<onChat.txt>```

# Usage
💻  

- Have Sword in 1st slot, and Madox Box in 3rd slot

Change variables in 'SLAYERSTART.txt' to your desired settings.
## Settings

3 Different slayer modes: 
- 0 = No slayers, just xp (Crypt Ghouls) **WORK IN PROGRESS**
- 1 = Revenent Horrors (best xp) (240k-300k/hour with god pot and Wolf)
- 2 = Svens **WORK IN PROGRESS**

4 Different Slayer Levels
- 1 = Level 1
- 2 = Level 2 
- 3 = Level 3
- 4 = Level 4

Webhook

![image](https://cdn.discordapp.com/attachments/784920430946287627/807032252798074890/webhookimage.PNG)

# Contributing
Iceshades#2451 | Helped with regular expressions as well as webhooks. Also helped with a lot of other problems I was facing.

JTReddin#8648 | Moral Support :)

# Questions

Requirements: MVP+ rank (VIP coming soon)
- Why does the script REQUIRE MVP+ or VIP:

The Script requires MVP+ ATM and VIP in the future due to a key feature only available to ranked members. The script uses priate hub lobbies for the lowest possible ditection rate. The script is not Watch Dog detected, so the only way of gettign banned is either by player or staff ie. Player sees you and reports you. Therefore private lobbies are used to lower the risk. The script also needs MVP+ for fastest transprtation as MVP+ has permission to use scrolls to Castle and Crypt Cave.

# License

Anyone is free to copy, modify, publish, use, compile, or
distribute this software, either in source code form or as a compiled
binary, for any NON-COMMERCIAL purpose, and by any
means.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

STRICTLY PROHIBITED TO USE FOR COMMERCIASL USE
