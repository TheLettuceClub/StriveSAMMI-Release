# StriveSAMMI-Release
Releases of the Strive x SAMMI live content mod
#### Abstract:
SAMMI support in Guilty Gear Strive. Essentially allows exporting the game state at any instant to drive the SAMMI streaming automation software. This in turn can drive dynamic OBS overlays with data directly from the game as it happens!

See [Strive SAMMI documentation.docx](https://github.com/TheLettuceClub/StriveSAMMI-Release/blob/main/Strive%20SAMMI%20documentation.docx) for setup and general SAMMI documentation.

Questions? Hopefully they're answered [here!](https://thelettuceclub.github.io/mods/)

#### Disclaimer:
**This mod is not intended to support cheating of any kind, or in any way, shape or form.** Use of the mod for it's intended purpose (SAMMI/OBS stuff) is safe and will not get you banned. **Any form of cheating using the data from this mod is entirely the responsiblity of the cheater, not me. Arcsys can ban you.** As a result of this, there is a universal (non-negotiable) 20 frame delay for all message sent from the mod, you should compensate for this in OBS or whatever your endpoint app is.

No leaked content was consulted, viewed or present in the creation of this mod. The offsets, hooks and signatures are entirely my own; reverse engineered thru Ghidra.

#### How to install:
1. Download the release ZIP from the releases tab.
2. extract the entire contents to the Strive installation folder. This is the same folder that has "GGST-Win64-Shipping.exe" in it. (Generally, "SteamApps\Common\GUILTY GEAR STRIVE\RED\Binaries\Win64\")
    * If you have other UE4SS mods installed, don't overwrite the mods.txt file, instead append "GGSTSammi : 1" to it.

#### Acknowledgements:
Based on code given to me by [Wistful-Hopes](https://github.com/WistfulHopes/), based spiritually on super-continent's [ggxrd-mod](https://github.com/super-continent/ggxrd-mod), using offsets from Artemis' [Strive Cheat Table](https://github.com/Tarquinous/GGST_CT). Finally, I'm also using [IXWebSocket](https://machinezone.github.io/IXWebSocket/) to host the WS server.

#### Contact:
Please only contact me if you have issues or major feature requests. Do not ask me how to set up stuff in SAMMI, other documentation covers that.
To reach me:
* quattrodan3 on Discord or in this server: https://discord.gg/Qw8N7QcVRw
* nleff72 on Twitter/BlueSky
* email: dan (at) lakeviewcomputerspecialists (dot) com
