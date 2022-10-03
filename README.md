# AUTODARTS-DESKTOP

Autodarts-desktop manages several extension-tools for Autodarts.io.
It handles download, setup, use and version-check.
 - You can easily start tools like caller or extern to transfer thrown darts to other web-dart-platforms.
 - Desired tools can be downloaded in the download area.
 - The administration of needed parameters is simplified by setup windows - no more console/batch-file handling =)

## Presentation
![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/Main.png?raw=true)


For example autodarts-caller (Setup):
 - autodarts-caller is a tool that can tell your thrown score and also the possible checkout score. 
 ![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/SetupCaller.png?raw=true)
  - for more info about autodarts-caller visit https://github.com/lbormann/autodarts-caller

Autodarts-extern tool (Setup):
 - automates multiple dart-web-platforms accordingly to the state of an https://autodarts.io match.
 ![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/SetupExtern.png?raw=true)
  - for more info about autodarts-extern visit https://github.com/lbormann/autodarts-extern

You can also use other assistant-programs:
 - dartboards-client (for webcam support with dartboards.online)
 - visual-darts-zoom (for an image zoom onto thrown darts)
 ![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/vdz.png?raw=true)
  - for more info about Visual-Darts-Zoom visit https://lehmann-bo.de/
  - for more info about dartboards-client visit https://dartboards.online/


Moreover you can start custom-apps, e.g. OBS (Open Brodcast System) - to create a visual cam with custom theme:

![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/OBS2.png?raw=true)
With OBS it is possible to display the Autodarts.io game in the virtual camera.


![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/OBS1.png?raw=true)
It is also possible, to integrate a player camera with OBS into the virtual camera stream.


![alt text](https://github.com/Semtexmagix/autodarts-desktop/blob/master/OBS3.png?raw=true)
A full screen mode for the board.

All of this can be easily realized via OBS scenes. The scenes can be switched during the game in OBS or e.g. via hotkey.
If you use obs and start it with the custom-app function. Use "--startvirtualcam" as start-agument so obs automatically starts in visual cam mode. 


## BUGS

It may be buggy. You can give me feedback in Discord (Autodarts.io) ---> Reepa86


## TODOs
- refactor setup-areas for using AppManager
- cross-platform
- autostart + (tray?)
- close custom-app on exit
- Add new app: droidcam (android) + epoccam (iOS)


### Done
- alot


## LAST WORDS
Thanks to Timo for awesome https://autodarts.io.
Thanks to Wusaaa for the caller and the extern tools and also for the many help =D 
