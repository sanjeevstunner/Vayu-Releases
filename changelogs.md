# Device Changelogs

**`07-19-2022`**
 - [Unsure] Build some RIL libs to overcome call failing issues
 - Disable some GMS components | Results in better wifi speeds and battery backup 
 - Tune zRAM for better performance
 - Add fastboot[in recovery] mode to advanced reboot menu 
 - Upstreamed Pixel Launcher MOD to 9.8 | Full changelogs [HERE](https://www.pling.com/p/1720688/)

**`07-07-2022`**
 - Removed Pixel Launcher MODs app, as it requires root
 - Fixed greyed out USB actions in notifications when connected to PC
 - Revert "Set Recommended Night Display Color Temperature as default" 

**`06-10-2022`**
 - Upstreamed Pixel Launcher MOD to v9.3 | [Changelogs](https://telegra.ph/Changelog-Of-Pixel-Launcher-MOD-05-28)
 - Upstream GCam to MGC_8.1.101_A9_GV2b | [Source](https://www.celsoazevedo.com/files/android/google-camera/dev-bsg/f/dl88/3/)

**`06-04-2022`**
 - Upstreamed Pixel Launcher MOD to v8.4 
   - Added more grids
   - Added more themed icons
   - Full changelogs [HERE](https://telegra.ph/Changelog-Of-Pixel-Launcher-MOD-05-28)
 
**`05-25-2022`**
 - Added Moto Dolby by ReiRyuki - [Source Code](https://github.com/reiryuki/Moto-Dolby-G-Pro-Magisk-Module) 

**`05-24-2022`**
 - Add per-app refresh rate settings

**`05-20-2022`**
 - Updated GCam to latest version (MGC_8.1.101_A9_GV1zfix) Source [HERE](https://www.celsoazevedo.com/files/android/google-camera/dev-bsg/f/dl75/1/)
 - Add QS tile to launch Thermal Profiles
 - Add Ambient Display settings 
   - Pick-up to wake device
   - Hand Wave to wake device
   - Wake device when out of pocket 
 - Add FPS info QS tile 

**`05-14-2022`**
 - Upstreamed Pixel Launcher MOD to v8.4 
   - Added themed icons from the module [In Pure PE AKA Regular PE too] 
   - [More Changelogs](https://telegra.ph/Changelog-Of-Pixel-Launcher-MOD-03-31-2) 

**`05-03-2022`**
 - Increase SWAP (zRAM) memory to improve system smoothness 

**`04-22-2022`**
 - Add Haptics level customisations 
 - Add G Cam by BSG as default [Bug: Camera crashing when system's camera API is requested] [Recommend Config](https://t.me/chandeler_s_chat/13930)

**`04-16-2022`**
 - Enable haptics when swiping text cursor 
 - Remove mobile plan from Settings -> Network & Internet 
 - Set Recommended Night Display Color Temperature as default - [Reference ](https://www.google.com/search?q=recommended+display+temperature+for+night+mode&rlz=1C1ONGR_enIN974IN974&oq=recommended+display+temperature+for+night+mode+&aqs=chrome..69i57j33i160l2.15403j0j7&sourceid=chrome&ie=UTF-8#:~:text=During%20the%20daylight%20hours%2C%20it%27s%20best%20to%20keep%20your%20monitor%20relatively%20cool%20with%20a%20default%20color%20temperature%20of%206%2C500K.%20At%20night%2C%20the%20color%20temperature%20should%20be%20warmer%2C%20and%20around%203%2C400K.)

**`04-15-2022`**
 - Make the UI smoother on top of smoothness provided by Android 12.1
 - Added modded Pixel Launcher as prebuilt home app
   - Double Tap to Sleep
   - More Grids Options [Available 6x9, 6x8, 6x7, 6x6, 5x8, 5x7, 5x6, 5x5, 4x7,
4x6, 4x5, 4x4, 3x3, 2x2]
   - The appearance of app-drawer in-device search bar colour in light/dark theme is correct(which is buggy in original pixel launcher on all aosp based roms, only works fine in pixel devices)
   - Search Results Highlight Colour shows in material you colour. When you press enter while highlighting search results, that app/settings opens. Subtle Changes in Group Highlights & Search Box Highlight
   - Smoothness better than original launcher. Added Tweaks which makes the launcher more smoother. 
   - [Bug] Weather widget in 'At a Glance' widget (below calendar/date) not launching google weather app (Weather data is working fine tho)

**`04-14-2022`**
 - Reduce time taken to boot into system (Faster boot times, usually took 10 seconds to move from splash screen to boot animation, reduced that delay to half)

**`04-07-2022`**
 - Add back Camera2 
 - Dirac Sound Enhancer (AKA) Mi Sound Enhancer 
   - New Presets Added: Live, Balanced, Bass Reduction, Treble Reduction, Soft Bass, Soft Treble 
   - Ported MiSound scenes 
 - Revert "combined signal icons in status bar" 

**`03-29-2022`**
 - Reintroduce `Device parts` with
   - Dirac Sound Enhancer
   - Clear Speaker
   - Thermal Settings
   - Refresh Rate toggle quick tile

**`03-22-2022`**
 - Add call recording to Google Phone app
 - Show **Turbo Charging** when using the proprietary charger, like MIUI
 - Video captured in ScrenRecorder is capped to 120 FPS
 - Some network and GPS improvemnts 

**`03-13-2022`**
 - Nuke Adaptive charging 
 
**`02-21-2022`**
 - Add support for AUX camers in Open Camera App  

**`02-17-2022`**
 - [BUG FIX] Fix IR blaster 

**`02-04-2022`**
 - Switch to Vulkan UI renderer 

**`01-31-2022`**
 - Nuke default camera app 
 - Fix VILTE calls 

**`01-22-2022`**
 - Enable combined signal icons in status bar
 - Increase handset speaker and mic volume
 - Enable vibration multiple intensities options (should help customise vibration intensity between low-high in supported ROMs)
 - Dropped Xiaomi Parts

**`01-18-2022`**
 - Enable quick tap
 - Enable adaptive charging 
 - Add 'Saturated' color mode

--- 

_*note: The list contains future changes, that are tested and will be added in next builds. Thats why the dates are given, the ones added after the builds got published are made for next release cycle. Plox, use your brains and dont bug me with mentioned features not available in your builds._
