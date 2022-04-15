# Device Changelogs

**`04-14-2022`**
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
