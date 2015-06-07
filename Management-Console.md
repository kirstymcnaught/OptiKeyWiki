##<a name="visuals">Visual settings</a>

![Management Console Visual tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Visual_Numbered.png)

    <a name="visuals-look">**Look**</a>

1. Theme: The look and feel of OptiKey.

2. Scratchpad # of lines: How many lines of text to display in the scratchpad at the top of OptiKey (where your typed words appear). Fewer lines = large text.

3. Cursor width (pixels): The width of the displayed cursor (mouse pointer) when simulating mouse input. Specified in pixels.

4. Cursor height (pixels): The height of the displayed cursor (mouse pointer) when simulating mouse input. Specified in pixels.

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

    <a name="pointing-with-an-eye-tracker">**Pointing with an eye tracker**</a>

1. Source: Which device is providing location data, e.g. the mouse, an eye tracker, etc. In this example the source is TheEyeTribe eye tracker.

2. Time until point becomess irrelevent (ms): If the source device (e.g. an eye tracker) timestamps the location data, then this setting controls how old a received point can be before it is considered too old to be useful. These "stale" points will be logged for debugging purposes and then discarded.

    <a name="selection-with-fixations">**Selection with fixations**</a>

3. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is Fixations.

4. Key fixation time to lock-on (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates how long you must direct your attention to a key (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation begins. The lock-on period is designed so that a deliberate pause is required on a key before a fixation begins. Without a 'lock-on' period every key will immediately begin a fixation as you direct your attention around the keyboard, which makes the interface busy and less clear.

5. Key fixation time to complete (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates how long you must direct your attention to a key (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation completes. A lower number means fixations complete faster and you can type at a more rapid pace, but your likelihood of making unintended selections also increases. A higher number means fixations complete more slowly, restricting your typing pace, but reducing the chance of unintended selections.

6. Incomplete key fixation time to live (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates the period of time to keep an in-progress fixation when that key loses attention, e.g. you direct your attention at the letter "A" until the fixation is 50% complete, at which point you look away to the letter "L" - the fixation on the letter "A" will remain and can be continued for the period of time defined by this setting. If the fixation is not resumed by returning your attention to the "A" key then it will be discarded.

    N.B. When your attention returns to an incomplete fixation there will be an initial "lock-on" period again (the length of which is dictated by the 'Key fixation time to lock-on (ms)' setting). The fixation can time out and be discarded during this lock-on period.

7. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is Fixations.

8. Point fixation time to lock-on (ms): Specific to 'Point selection source' of 'Fixations', this setting dictates how long you must direct your attention to a point (using whatever 'Source' you have selected, e.g. by looking at a point on the screen when using an eye tracking source) before a fixation begins. The lock-on period is designed so that a deliberate pause is required on an area of the screen before a fixation begins. Without a 'lock-on' period point selections will begin as soon as you direct your attention to any point on the screen, which makes point selection difficult.

9. Point fixation time to complete (ms): Specific to 'Point selection source' of 'Fixations', this setting dictates how long you must direct your attention to a point (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation completes. A lower number means fixations complete faster and you can make selections at a more rapid pace, but your likelihood of making unintended selections also increases. A higher number means fixations complete more slowly, restricting your selection pace, but reducing the chance of unintended selections.

10. Point lock-on radius (pixels): Specific to 'Point selection source' of 'Fixations', this setting dictates the size of the initial 'lock-on' area. Your attention must remain completely inside this area for the lock-on time before a fixation begins. A larger radius results in a larger lock-on area (the area is a circle) making it easier to keep your attention within the bounds and begin a fixation, but reduces the accuracy of your selection. A smaller radius results in a smaller lock-on area making it more challenging to keep your attention within the bounds and begin a fixation, but increasing the accuracy of your selection.

11. Point fixation radius (pixels): Specific to 'Point selection source' of 'Fixations', this setting dictates the size of the fixation area (after the initial lock-on). Your attention must remain completely inside this area for the fixation to complete. A larger radius results in a larger fixation area (the area is a circle) making it easier to keep your attention within the bounds and complete the fixation, but more difficult to deliberately break the fixation by directing your attention elsewhere. A smaller radius results in a smaller fixation area making it more challenging to keep your attention within the bounds and complete the fixation, but easer to deliberately break the fixation by directing your attention elsewhere. 

    <a name="multi-key-selection">**Multi-key selection**</a>

12. Minimum dwell time on a key to include in capture (ms): When a multi-key selection (see ['Multi-key selection'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#multi-key-selection) for more) is in progress this setting dictates the minimum amount of time that you must direct your attention to each key in order to register your interest in that key. Lower values allow you to complete the multi-key selection more quickly, but increase the chance that you will accidentally register interest in keys you are not actually interested in, resulting in less accurate matches. Higher values increase the amount of time required to complete each multi-key selection, but decrease the chance of registering keys accidentally.

13. Capture timeout (ms): The maximum duration of a multi-key capture. If a multi-key capture exceeds this amount of time the capture will be discarded.

    <a name="pointing-with-a-mouse">**Pointing with a mouse**</a>

![Management Console Pointing and Selecting tab with mouse position source](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Mouse_Pointing_Section_Numbered.png)

1. Source: Which device is providing location data, e.g. the mouse, an eye tracker, etc. In this example the source is the mouse.

2. Mouse position sample interval (ms): How often the mouse position is sampled. Lower values are more efficient, but result in less accurate location data.

3. Time until point becomes irrelevent (ms): As described above.

    <a name="selection-with-a-mouse">**Selection with a mouse**</a>

![Management Console Pointing and Selecting tab with mouse selection trigger](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Mouse_Button_Trigger_Section_Numbered.png)

1. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Mouse Button.

2. Selection mouse button: The Mouse Button used to trigger a key selection.

3. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Mouse Button.

4. Selection mouse button: The Mouse Button used to trigger a point selection.

    <a name="selection-with-a-keyboard">**Selection with a keyboard**</a>

![Management Console Pointing and Selecting tab with keyboard selection trigger](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Keyboard_Key_Trigger_Section_Numbered.png)

1. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Keyboard Key.

2. Selection keyboard key: The Keyboard Key used to trigger a key selection.

3. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Keyboard Key.

4. Selection keyboard key: The Keyboard Key used to trigger a point selection.

---

##<a name="dictionary">Dictionary management</a>

![Management Console Dictionary tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Dictionary_Numbered.png)

1. Add new entry: Type a new dictionary entry (word or phrase) and click the 'Add' button to include in the dictionary. Click 'OK' to persist your changed.

    N.B. Unless the word is a proper noun, or should always be capitalised, the new entry should be in lower case.

2. Delete existing entry: Click the 'Delete' button next to any entry that you wish to remove from the dictionary. Click 'OK' to persist your changed.

---

##<a name="other">Other settings</a>

![Management Console Other tab](http://juliussweetland.github.io/OptiKey/images/Management_Console_Other_Numbered.png)

1. Show splash screen on startup: Enable/disable the welcome splash screen which shows for a few seconds when OptiKey starts.

2. Check for updates on startup: Enable/disable the automatic check for newer versions of OptiKey. If update checks are enabled, and an update exist, then a splash screen is displayed for a few seconds to prompt you to download the new version.

3. Debugging mode: Enable/disable debugging mode, which displays the current capture rate of the position source, the points detected during a multi-key capture, and turns on verbose logging, which is helpful when debugging problems with OptiKey.