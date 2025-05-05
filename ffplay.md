## FFplay Tanzil from Batch file
* ` a.bat ` file can be
```bat
@echo off 
set v=%1
ffplay http://tanzil.net/res/audio/afasy/%v%.mp3 -loop 0 -nodisp
```
### VLC Equivalent
```bat
@echo off 
set v=%1
vlc http://tanzil.net/res/audio/afasy/%v%.mp3 --loop --intf dummy --no-video --quiet
```
### Add `a.bat` to environment path variable

* Run ` a 002255 `
