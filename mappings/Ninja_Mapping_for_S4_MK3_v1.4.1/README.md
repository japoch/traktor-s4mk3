# Description and Instructions
**Latest version:** 1.4.0
**Updated:** April 21, 2020

**NOTE: This mapping does not fully support Traktor Pro 3.6 due to issue which breaks Pad FX Please use 3.5 or 3.7 version instead.**


This mapping will activate 4 additional pad modes in each Deck. See provided JPG file for the list of all new features.

Since ver. 0.4.1 you can choose to install special tsi "Kontrol S4 MK3 Ninja (Freeze + Remix)" which is offering 64 Sample Cell triggers in Decks C and D. This tsi deactivates Pad Modes on Deck C and Deck D and activates all 64 triggers instead. Do not expect full LED feedback here - the feedback is limited to "loaded" and "playing" states. 

Since ver. 1.0.2 you can choose to install special tsi "Kontrol S4 MK3 Ninja (Freeze + Vinyl Brake)" which takes the advantage of Turntable effect in order to produce that turntable stop sound each time you press a PLAY button to stop a Deck. Anybody who attempted to map this on their own knows how difficult this can be because TTFX doesn't work if assigned Deck is stopped... To use this feature you will have to enable Virtual Midi Ports on your computer. The process if fairly easy and instructions are included in download.

**1. Tone Play:** Hold SHIFT and press PLAY to toggle the Tone Play Mode 'ON' and 'OFF'. Works with any cue =)
Ensure to enable the following setting: Preferences\Transport\Cue Play (CUP) Mode\ set to "**Instant**" (not "On Release" which is default setting)
-Since the 0.3.0 version you can press CUE button to toggle between two sets of Key (tone) values:

  * 0, +1, +2, +3, +4, +5, +6, +7
  * -7, -6, -5, -4, -3, -2, -1, 0

**2. Freeze Mode:** Hold SHIFT and press HOTCUES to toggle the Freeze Mode 'ON' and 'OFF'. The Flux Mode function will be activated automatically.

-Since the 0.3.0 version you can choose to install one of three different types of controls for this Pad Mode:
  *Freeze Mode
  *Loop/Roll Mode
  *Beatjump Mode


**3. PAD FX 1:** Hold SHIFT and press SAMPLES to toggle the PAD FX 1 Mode 'ON' and 'OFF'.

-Reverb
-Filter 92-O
-Delay T3
-Echo Freeze
-Beatmasher x3
-Turntable FX
-Transpose Stretch (Activated by supercombo)
-LaserSlicer (Activated by supercombo)
-Ramp Delay

**4. PAD FX 2:** Hold SHIFT and press STEMS to toggle the PAD FX 2 Mode 'ON' and 'OFF'. 

-Iceverb
-Filter LFO
-Delay T3
-Echo Freeze
-Gater x3
-Turntable FX
-WormHole (Activated by supercombo)
-Flanger Pulse (Activated by supercombo)
-Macro 1: Beatmasher + Reverb + Filter 92
-Macro 2: Beatmasher + LoFi + Peak Filter
-Macro 3: LaserSlicer + Phaser + Peak Filter
-Macro 4: Gater + Zzzurp + WormHole


**Note on PAD FX:**
-Each deck uses 2 FX Units which means that you can control effects on Decks A and C independently of Decks B and D.
-The Echo Freeze button have built in fail/safe setting - once it is activated, the mapping will prevent you from selecting an other Deck or a Pad Mode until you deactivate the Echo Freeze button first. In this way you won't have to think about whether you left it activated or not. You can use the Echo Freeze to freeze a track and then push the Load Encoder switch to stop Echo and load the selected track simultaneously.

(A/C + B/D + HOTCUES + SAMPLES + STEMS + VIEW are disabled whilst Echo Freeze is activated)

-Top four fx buttons are extension of a PAD FX. Use them in combination with pads for more instant grat effect controls. Press a button to activate effects and keep it held down to modulate fx parameters automatically.

**Installation:**

Download and unzip the file. Inside you should see one folder with mapping content. It is strongly recommended to back up all your current mappings and effect settings in the Controller Manager before importing this one because those will be overwritten in the step 2! And be aware that there is no undo.  

1). Start Traktor and click the gear symbol to open the preferences window. Click the BIG IMPORT button which is located at the bottom of the preferences window and then navigate to the folder where the .tsi file is saved. Once you select the .tsi and click on OK the next window will pop-up asking you which settings do you wish to import - ONLY the "**controller mappings**" and the "**effect settings**' categories should be selected - then click on OK. Please note that you need to repeat this step one more time to successfully import the FX settings. (this only matters if you're installing this mapping for the first time)

2). Go into the Controller Manager's upper-right corner and make sure that the In-Port is set to your Kontrol S4 MK3 hardware.
If you want to add more controller mappings next to this one be sure to use smaller Import button which is located under Device Setup: Add > Import TSI > Import Other.
Click on [https://traktormaps.com/](https://traktormaps.com/) if you need help with custom mappings for Traktor.
Mix on and I hope this mapping serves you well.