With OptiKey selected press 'ALT' and 'M' on your keyboard to open the Management Console, then select the 'Pointing & Selecting' tab at the top. The Management Console must be accessed using a physical mouse and keyboard.

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

12. Selection progress indicator behaviour - Only available if the key or point selection source is 'Fixations', this controls the selection progress animation that is displayed on the key or at the point being selected. You can choose to have a pie chart fill up to show your selection progress, or for a solid circle to shrink (to help draw your eye to the centre of the key if using an eye tracker), or grow.

13. Selection progress indicator start size (%) - Only available if the 'Selection progress indicator behaviour' setting is 'Shrink' or 'Grow', this controls the selection progress indicators initial size (when starting a selection). The value is a percentage (0-100) where 100% is the full size of the key or cursor involved in the selection. When the progress indicator behaviour is 'Grow' this value must be less than the end size. When the behaviour is 'Shrink' this value must be greater than the end size.

14. Selection progress indicator end size (%) - Only available if the 'Selection progress indicator behaviour' setting is 'Shrink' or 'Grow', this controls the selection progress indicators final size (when completing a selection). The value is a percentage (0-100) where 100% is the full size of the key or cursor involved in the selection. When the behaviour is 'Grow' this value must be greater than the start size. When the progress indicator behaviour is 'Shrink' this value must be less than the start size.

    <a name="multi-key-selection">**Multi-key selection**</a>

15. Minimum dwell time on a key to include in capture (ms): When a multi-key selection (see ['Multi-key selection'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#multi-key-selection) for more) is in progress this setting dictates the minimum amount of time that you must direct your attention to each key in order to register your interest in that key. Lower values allow you to complete the multi-key selection more quickly, but increase the chance that you will accidentally register interest in keys you are not actually interested in, resulting in less accurate matches. Higher values increase the amount of time required to complete each multi-key selection, but decrease the chance of registering keys accidentally.

16. Capture timeout (ms): The maximum duration of a multi-key capture. If a multi-key capture exceeds this amount of time the capture will be discarded.

---

<a name="pointing-with-a-mouse">**Pointing with a mouse**</a>

![Management Console Pointing and Selecting tab with mouse position source](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Mouse_Pointing_Section_Numbered.png)

1. Source: Which device is providing location data, e.g. the mouse, an eye tracker, etc. In this example the source is the mouse.

2. Mouse position sample interval (ms): How often the mouse position is sampled. Lower values are more efficient, but result in less accurate location data.

3. Time until point becomes irrelevent (ms): As described above.

---

<a name="selection-with-a-mouse">**Selection with a mouse**</a>

![Management Console Pointing and Selecting tab with mouse selection trigger](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Mouse_Button_Trigger_Section_Numbered.png)

1. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Mouse Button.

2. Selection mouse button: The Mouse Button used to trigger a key selection.

3. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Mouse Button.

4. Selection mouse button: The Mouse Button used to trigger a point selection.

    ![Management Console Pointing and Selecting tab with mouse selection trigger - Multi-key selection section](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Button_Trigger_Multi_Key_Selection_Numbered.png)

5. Stop signal: When a multi-key selection capture has begun by pressing the mouse button, this setting dictates how should that session is ended. Available options are to release the button, or to press the same button again to stop the capture.

---

<a name="selection-with-a-keyboard">**Selection with a keyboard**</a>

![Management Console Pointing and Selecting tab with keyboard selection trigger](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Keyboard_Key_Trigger_Section_Numbered.png)

1. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Keyboard Key.

2. Selection keyboard key: The Keyboard Key used to trigger a key selection.

3. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Keyboard Key.

4. Selection keyboard key: The Keyboard Key used to trigger a point selection.

    ![Management Console Pointing and Selecting tab with mouse selection trigger - Multi-key selection section](http://juliussweetland.github.io/OptiKey/images/Management_Console_Pointing_And_Selecting_Button_Trigger_Multi_Key_Selection_Numbered.png)

5. Stop signal: When a multi-key selection capture has begun by pressing the keyboard key, this setting dictates how should that session is ended. Available options are to release the key, or to press the same key again to stop the capture.