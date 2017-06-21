# 3DiScord
## A Discord client for the 3DS

3DiScord is a heavily WIP Discord client for the 3DS based on [VitaCord](https://github.com/devingDev/VitaCord) by [devingDev / coderx3](https://github.com/devingDev/).  
Note: this is based on an old version of VitaCord so no DMs and it may crash.  
If something is wrong, contact the creator on Discord: cheuble#4952  
**Disclaimer**: The creator is not responsible for anything that happens to you if you're using this app. Use this at your own risk.

### Features

* Send and receive messages in servers only 
* 2FA supported
* You can send DMs now
### Credits

* UI and port by [cheuble](https://github.com/cheuble)
* Network features by [Rinnegatamante](https://github.com/Rinnegatamante/) (from lpp3ds) 
* White theme by NicoAICP (or Hotbrawl20)
**All the original VitaCord staff:**
* coderx3 (devingDev)
* Arkanite
* XandridFire
* SKGleba
* Rinnegatamante
* xyz
* noname120
* davee
* T3CHNOLOG1C  

### Building

In order to build this homebrew, you'll need the following requirements:
* devkitARM (included in devkitPro)
* ctrulib (included in devkitARM)
* [3ds portlibs](https://github.com/Cruel/3ds_portlibs)
* [sf2dlib](https://github.com/xerpi/sf2dlib)
* [sfillib](https://github.com/xerpi/sfillib)
* [sftdlib](https://github.com/xerpi/sftdlib)  
Once you have installed these, a simple `make` should compile it. If you have FBI installed on your 3ds, and python installed on your computer, open FBI and go to `Remote install` -> `Recieve URLs over the network`.
 On your computer, type `make spunch`. This should install the CIA directly on your 3DS!
 
### Changelog 

**1.1** 
* Added DMs support
* Fixed some crashes
* Touch screen sensitivity increased (there shouldn't be any issues now)
* Avatars should now work every time
* Can now scroll with the D-Pad/Control stick
* Now licensed under GPLv3  

**1.0**
* Initial Release