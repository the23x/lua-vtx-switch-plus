## Lua VTX Switch (the23 edition)

Minimalistic OpenTX Lua script for switching VTX RaceBand channels.

_Current version is for colored and black and white screens._

1. Install [betaflight-tx-lua-scripts](https://github.com/betaflight/betaflight-tx-lua-scripts).
2. Make sure you have Fatshark band and Raceband configured as Band 4 and Band 5 in your VTX table (usually they are).


3. If you have a large color screen (Jumper T16, Jumper T18, RadioMaster TX16S and Frsky Horus X10S)<br/>
 ![Screenshot](https://github.com/the23x/lua-vtx-switch-plus/blob/master/screenshotbs.png?raw=true)
	- Put `vtx_bs.lua` to `SCRIPTS/TOOLS` directory of your SD card if your screen like this.
	- Select `vtx_bs` in `[SYS]->[TOOLS]` page of your transmitter setup.

4. If you have a black and white screen (by [AlexeyStn](https://github.com/alexeystn/lua-vtx-switch))<br/>
 ![Screenshot](https://github.com/the23x/lua-vtx-switch-plus/blob/master/screenshotss.png?raw=true)
	- Put `vtx_ss.lua` to `SCRIPTS/TELEMETRY` directory of your SD card if your screen like this.
	- Select `vtx_ss` in `[DISPLAY]` page of your model setup.


Inspired by [ghostface](https://gist.github.com/ghostface/b7de909b24fc7ce4b4c75de515c0ae46#file-vtx-lua-L1).
