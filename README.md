# awesome-chip
List of free resources for @nextthingco's [CHIP](http://getchip.com/pages/chip) computer

1. Operating Systems
   - Debian (default/built-in)
   - [Yocto](https://bbs.nextthing.co/t/yocto-project-an-initial-teaser-release/833)
   - [Removing the GUI](https://bbs.nextthing.co/t/chip-stripped-down-version/2860) (for server use)
1. Remote Access
   - X forwarding with [VcXsrv](https://bbs.nextthing.co/t/need-an-x11-server-for-win7-or-above-vcxsrv-is-based-on-xorg/2882) or Cygwin/X or XMing or etc.
   - x11vnc
   - [XDMCP](http://askubuntu.com/questions/66431/how-do-i-configure-lightdm-to-work-with-xdmcp) with [MobaXterm](http://mobaxterm.mobatek.net/)
2. Projects
   - Chippy Ruxpin - [Make](http://makezine.com/projects/chippy-ruxpin/), [Hackster](https://www.hackster.io/chip/c-h-i-p-py-ruxpin-5f02f1), [NextThingCo/ChippyRuxpin](https://github.com/NextThingCo/ChippyRuxpin)
   - [CHIP partymobil](https://bbs.nextthing.co/t/chip-partymobil-wifi-rider/2384) (remote control car)
   - [DIY Amazon Echo](https://github.com/jitto/AlexaCHIP) ([forum](https://bbs.nextthing.co/t/turning-the-chip-into-an-amazon-echo/1630/36))
   - [Status page](https://github.com/helgasoft/CHIP-Status)
   - [Turn status light on/off from web](https://bbs.nextthing.co/t/turn-status-led-on-and-off-over-the-web/1827/3)
   - [Wireless access point](https://bbs.nextthing.co/t/create-a-very-basic-wifi-access-point/1727)
   - [Mail Server](https://bbs.nextthing.co/t/private-email-sever-using-c-h-i-p/2312/4) (two links to setup)
   - [Blinky status light and graceful shutdown](https://bbs.nextthing.co/t/blink-chip-program-to-blink-status-light-and-shut-down-when-xio-p7-is-grounded/2336)
   - [Internet-controlled LED strip](https://bbs.nextthing.co/t/salsa-dip-for-c-h-i-p-i2c-arduino-ws2812-pwm-motor/1597)
   - [3d printer controller (octoprint)](https://bbs.nextthing.co/t/octoprint-runs-on-chip/2435)
   - UPnP Media Boxes
     - [GMediaRender](https://github.com/hzeller/gmrender-resurrect) + [BubbleUPnP Server](bubblesoftapps.com/bubbleupnpserver) - low ram, high cpu. BubbleUPnP is optional, requires java. Stream cloud music via android BubbleUPnP or other DLNA server.
     - [Mopidy](https://www.mopidy.com/) - used by [PiMusicBox](http://www.pimusicbox.com/), rather slow at UPnP on CHIP (dleyna plugin required), high ram, low cpu. Written in python. Difficult to set up (add apt repo, configure plugins via conf file, some pluigns need to be installed from pip). Connects directly to cloud media, no support for DLNA server.
     - [MediaPlayer](https://github.com/PeteManchester/MediaPlayer) - features???
     - ~~[Max2Play](http://www.max2play.com/en/)~~ - Not available, but I'm hoping it will be.
     - [minidlna](http://sf.net/p/minidlna) (dlna server only)
     - [Kodi](https://kodi.tv/) - AKA XBMC. Compatible??
     - [Volumio](https://github.com/volumio/Volumio2) - features???
     - squeezelite - needs link
  - [Custom Weather Station with Adafruit.IO](https://bbs.nextthing.co/t/custom-weather-station-with-adafruit-io/2599) (ongoing project)
3. Interesting forum posts:
  - [Printing](https://bbs.nextthing.co/t/printing-with-the-chip-how-too/2517)
  - headless server setup - `sudo apt-get install openssh-server && sudo service openssh start`. See [here](https://bbs.nextthing.co/t/setting-up-chip-as-a-headless-server-with-minimal-tools/1505) for more info.
  - [battery life detection](https://bbs.nextthing.co/t/chip-specs-battery-battery-life-detection/307) - or pull an 18560 battery from a powerbank like [this](https://bbs.nextthing.co/t/cheap-battery-solution-light-modding-required/2704/13)
  - [Solar-powered chip](https://bbs.nextthing.co/t/chip-on-solar-power/1324)
  - [Reading temperature and humidity from i2c](https://bbs.nextthing.co/t/reading-temperature-and-humidity-from-si7013-si7020-si7021/2833)
 - [Using the mic](https://bbs.nextthing.co/t/modifying-the-onboard-trrs-jack-for-microphone-audio-input/2148/7) via header pins or with [Mic instead of video on TRRS](http://docs.getchip.com/#microphone-and-audio-input)
4. Cases
 - [3d-printable CHIPbag case](https://bbs.nextthing.co/t/chipbag-customizable-chip-case/523)
 - [Thinking inside the box](https://bbs.nextthing.co/t/thinking-inside-the-box/1748) (using the cardbox box as a case)
 - [More discussion](https://bbs.nextthing.co/t/time-to-discuss-a-chip-case/1343)
4. Other information:
 - [Chip BBS](https://bbs.nextthing.co/c/CHIP)
 - [Unofficial IRC Channel](https://bbs.nextthing.co/t/c-h-i-p-nextthingco-irc-channel/794)
