##<a name="visuals">Visual settings</a>

![Management Console Visual tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Visual_Numbered.png)

<a name="visuals-look">**Look**</a>

1. Theme: The look and feel of OptiKey.

2. Scratchpad # of lines: How many lines of text to display in the scratchpad at the top of OptiKey (where your typed words appear). Fewer lines = large text.

3. Cursor width (px): The width of the displayed cursor (mouse pointer) when simulating mouse input. Specified in device independent pixels (px).

4. Cursor height (px): The height of the displayed cursor (mouse pointer) when simulating mouse input. Specified in device independent pixels (px).

5. Magnify source (percentage of screen): Size of the area which will be captured around the selected point for magnification.

6. Magnify destination (percentage of screen): Size of the area in the middle of the screen which will display the magnified area. The ratio of the Magnify Source to Magnify Destination will determine the magnification level, e.g. 10% source and 60% destination = x6 magnification.

7. Keyboard set: The set of keyboards to use.

    'Standard' is the default set and includes the most features.

    'Speech Only' is a simplified keyboard set, designed when you only want to use OptiKey to type and speak words and sentences.

<a name="visuals-font">**Font**</a>

8. Font family: The font to use throught OptiKey. This does not affect the Management Console.

9. Font stretch: The font stretch to use throughout OptiKey, e.g. Normal, Condensed, etc. The available values depends on the selected Font Family. This does not affect the Management Console.

10. Font weight: The font weight to use throughout OptiKey, e.g. Light, Normal, Bold, etc. The available values depends on the selected Font Family. This does not affect the Management Console.

<a name="visuals-notifications">**Notifications**</a>

11. Horizontal fill (percentage of OptiKey): The horizontal size of any popup notification messages that are displayed within OptiKey (e.g. welcome messages, or error messages), as a percentage of OptiKey's size. 100% to completely cover OptiKey horizontally, or less for the notifcation to appear within the bounds of OptiKey.

12. Vertical fill (percentage of OptiKey): The vertical size of any popup notification messages that are displayed within OptiKey (e.g. welcome messages, or error messages), as a percentage of OptiKey's size. 100% to completely cover OptiKey vertically, or less for the notifcation to appear within the bounds of OptiKey.

---

##<a name="sounds">Sound settings</a>

![Management Console Sounds tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Sounds_Numbered.png)

<a name="sounds-speech">**Speech**</a>

1. Voice: The voice to use when OptiKey speaks the contents of the scratchpad. The available set of voices depends on which TTS (Text To Speech) voices you have installed in Windows. Additional voices can be installed from the Microsoft website, or purchased through 3rd party companies. Please email me at optikeyfeedback@gmail.com if you are unsure how to do this, or would like to share a good source of voices.

2. Volume: The volume of speech within OptiKey.

3. Rate: The rate (speed) at which the scratchpad text is spoken. From -10 to +10 (slower to faster).

<a name="sounds-sounds-effects">**Sound effects**</a>

4. Info: The sound to play when an information notification window is displayed.

5. Error: The sound to play when an error notification window is displayed.

6. Key Selection: The sound to play when a key is selected (this is not played for a selection which starts/ends a multi-key selection).

7. Multi-key selection starting: The sound to play when a multi-key selection is starting.

8. Multi-key selection ending: The sound to play when a multi-key selection is ending.

9. Mouse click: The sound to play when a mouse single click is simulated.

10. Mouse double click: The sound to play when a mouse double click is simulated.

11. Mouse scroll: The sound to play when a mouse scroll is simulated.

---

##<a name="words">Word settings</a>

![Management Console Words tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Words_Numbered.png)

1. Language: The dictionary used when auto-completing words and generating multi-key selection matches.

2. Auto space between words: Whether a space will be automatically injected between words.

3. Auto capitalise words: Whether the Shift key will be automatically pressed to capitalise the first letter of the next word when a new sentence is detected.

4. Auto complete words: Whether suggestions will be generated to complete an in-progress word.

5. Maximum number of dictionary matches: How many word matches will be generated for a multi-key selection.

---

##<a name="pointing-and-selecting">Pointing & selecting settings</a>

![Management Console Pointing and Selecting tab with TheEyeTribe position and selecting source](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_EyeTribe_Numbered.png)

<a name="pointing-and-selecting-with-an-eye-tracker">**Pointing & selecting with an eye tracker**</a>

1. Source: Which device is providing location data, e.g. the mouse, an eye tracker, etc.

2. Time until point becomess irrelevent (ms): If the source device (e.g. an eye tracker) timestamps the location data, then this setting controls how old a received point can be before it is considered too old to be useful. These "stale" points will be logged for debugging purposes and then discarded.

3. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons.

4. Key fixation time to lock-on (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates how long you must direct your attention to a key (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation begins. The lock-on period is designed so that a deliberate pause is required on a key before a fixation begins. Without a 'lock-on' period every key will immediately begin a fixation as you direct your attention around the keyboard, which makes the interface busy and less clear.

5. Key fixation time to complete (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates how long you must direct your attention to a key (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation completes. A lower number means fixations complete faster and you can type at a more rapid pace, but your likelihood of making unintended selections also increases. A higher number means fixations complete more slowly, restricting your typing pace, but reducing the chance of unintended selections.

6. Incomplete key fixation time to live (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates the period of time to keep an in-progress fixation when that key loses attention, e.g. you direct your attention at the letter "A" until the fixation is 50% complete, at which point you look away to the letter "L" - the fixation on the letter "A" will remain and can be continued for the period of time defined by this setting. If the fixation is not resumed by returning your attention to the "A" key then it will be discarded.

    N.B. When your attention returns to an incomplete fixation there will be an initial "lock-on" period again (the length of which is dictated by the 'Key fixation time to lock-on (ms)' setting). The fixation can time out and be discarded during this lock-on period.

7. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons.

8. Point fixation time to lock-on (ms): Specific to 'Point selection source' of 'Fixations', this setting dictates how long you must direct your attention to a point (using whatever 'Source' you have selected, e.g. by looking at a point on the screen when using an eye tracking source) before a fixation begins. The lock-on period is designed so that a deliberate pause is required on an area of the screen before a fixation begins. Without a 'lock-on' period point selections will begin as soon as you direct your attention to any point on the screen, which makes point selection difficult.

9. Point fixation time to complete (ms): Specific to 'Point selection source' of 'Fixations', this setting dictates how long you must direct your attention to a point (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation completes. A lower number means fixations complete faster and you can make selections at a more rapid pace, but your likelihood of making unintended selections also increases. A higher number means fixations complete more slowly, restricting your selection pace, but reducing the chance of unintended selections.

10. Point lock-on radius (pixels): Specific to 'Point selection source' of 'Fixations', this setting dictates the size of the initial 'lock-on' area. Your attention must remain completely inside this area for the lock-on time before a fixation begins. A larger radius results in a larger lock-on area (the area is a circle) making it easier to keep your attention within the bounds and begin a fixation, but reduces the accuracy of your selection. A smaller radius results in a smaller lock-on area making it more challenging to keep your attention within the bounds and begin a fixation, but increasing the accuracy of your selection.

11. Point fixation radius (pixels): Specific to 'Point selection source' of 'Fixations', this setting dictates the size of the fixation area (after the initial lock-on). Your attention must remain completely inside this area for the fixation to complete. A larger radius results in a larger fixation area (the area is a circle) making it easier to keep your attention within the bounds and complete the fixation, but more difficult to deliberately break the fixation by directing your attention elsewhere. A smaller radius results in a smaller fixation area making it more challenging to keep your attention within the bounds and complete the fixation, but easer to deliberately break the fixation by directing your attention elsewhere. 

12. Minimum dwell time on a key to include in capture (ms):

13. Capture timeout (ms):

<a name="pointing-with-a-mouse">**Pointing with a mouse**</a>

![Management Console Pointing and Selecting tab with mouse position source](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Mouse_Pointing_Section_Numbered.png)

1. Source:

2. Mouse position sample interval (ms):

3. Time until point becomes irrelevent (ms):

<a name="selecting-with-a-mouse">**Selecting with a mouse**</a>

![Management Console Pointing and Selecting tab with mouse selection trigger](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Mouse_Button_Trigger_Section_Numbered.png)

1. Key selection source:

2. Selection mouse button:

3. Point selection source:

4. Selection mouse button:

<a name="selecting-with-a-keyboard">**Selecting with a keyboard**</a>

![Management Console Pointing and Selecting tab with keyboard selection trigger](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Keyboard_Key_Trigger_Section_Numbered.png)

1. Key selection source:

2. Selection keyboard key:

3. Point selection source:

4. Selection keyboard key:

---

##<a name="dictionary">Dictionary management</a>

![Management Console Dictionary tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Dictionary_Numbered.png)

1. Add new entry:

2. Delete existing entry:

---

##<a name="other">Other settings</a>

![Management Console Other tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Other_Numbered.png)

1. Show splash screen on startup:

2. Check for updates on startup:

3. Debugging mode: