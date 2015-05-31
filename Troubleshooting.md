##<a name="smart-screen-warning">Smart Screen warning</a>

*When I try to install or run OptiKey on Windows 8 I see a Smart Screen warning saying that OptiKey is an unrecognised and potentially dangerous application.*

Due to the fact that OptiKey is a new application Windows will consider it un unknown entity for a little while and warn people installing it that it may not be trustworthy. Don't worry - it doesn't mean that the installer you are using has been compromised. Click "MORE INFO" and then "RUN ANYWAY" and the installation/run will continue normally. I expect this warning to go away as OptiKey matures and Windows starts recognising it as a "safe" application.

---

##<a name="cannot-open-management-console">Cannot open Management Console</a>

*I can't open the Management Console.*

Two things need to happen for the Management Console to open;

1. OptiKey must have focus - it will be highlighted on the taskbar when it has focus, but if you are unsure just click on OptiKey to focus it.

2. Press the 'ALT' key and the 'P' key at the same time - to do this hold down 'ALT' and then press 'P' once.
If the console is still not opening then check that OptiKey is not currently simulating key strokes by checking whether the Simulate Key Strokes key is locked down (see ('Simulate a physical keyboard'[https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-keyboard] for more). If it is locked down, then you may have a modifier key pressed which is interfering with you pressing ALT + M. Either release any down modifier keys (Shift, Ctrl, Win, or Alt), or release the Simulate Key Strokes key and try again. 

---

##<a name="eye-tracker-issues">Eye tracker issues</a>

*Eye tracker not working or stops working.*

1. Check that your eye tracking applications are running as expected and that you've completed any required setup, such as calibrating your eye tracker using its supplied software.

2. Check that the eye tracking device is connected securely to the computer/laptop/tablet.

3. Check the eye tracking software's logs, for example if you are using TheEyeTribe tracker then both the server and client applications produce logs. Are there any messages explaining that something has gone wrong (these are usually marked with WARNING or ERROR). Not sure how to find the logs or how to read them then please email me at [optikeyfeedback@gmail.com](mailto:optikeyfeedback@gmail.com).

* Poor eye tracking performance/accuracy.*

1. Check that the eye tracking device is connected securely to the computer/laptop/tablet.

2. Check the eye tracker setup. The correct positioning is specific to each tracker, so check the tracker's documentation, but commonly the tracker should be in the middle of the screen and directly below it.

3. Is there too much light coming in through a window or a direct light source? Eye trackers typically use infra-red light, so can be confused if there is a strong source of IR light near you, such as the sun.

4. Don't look down - keep the keyboard level with your eyeline. Looking down closes your eyelid over your eye, reducing tracking accuracy.

5. Calibrate the eye tracker to an area less than the total screen size.

6. Only screen sizes up to 24 inches are supported by trackers like GazeTracker and TheEyeTribe. Check the limitations.

7. If available, calibrate for more points (12 rather than 9, for example).

8. If available, when calibrating try to match the background/foreground colours to the product you will end up using, e.g. this on-screen keyboard.

9. An effective head rest can prevent head movement.

10. Sit so that your head is within the effective range of your eye tracker. For GazeTracker and TheEyeTribe this is between 45 and 75cm from the tracker/screen.

11. Try your eye tracker at different refresh rates, for example TheEyeTribe tracker can be set to 30fps or 60fps, which is achieved by starting the EyeTribe server with the "-f=30" or "-f=60" switch, e.g. "C:\Program Files (x86)\EyeTribe\Server\EyeTribe.exe" -f=60

---

##<a name="factory-reset">Factory reset settings</a>

*Factory resetting / defaulting all settings.*

If you would like to return OptiKey to the state it is in when you first install it (all settings back to their original factory values), delete all of the directories that start with **"OptiKey.exe_"** in your roaming app data directory (C:\Users\*YOUR_USER_NAME*\AppData\Roaming\JuliusSweetland). For me (with a username of Julius) the steps would be;

1. Close OptiKey if it is running.

2. Navigate to C:\Users\*Julius*\AppData\Roaming\JuliusSweetland (don't worry if you don't see the "AppData" directory, it is hidden by default. Just type the path into the navigation bar at the top of File Explorer).

3. You will see one directory in there called "OptiKey" - leave that. It contains your log files and customised dictionary(ies).

4. Delete the other directories. For me that means deleting "OptiKey.exe_Url_2dm1ifc0wqzcnmfgnsyhbssrcdx5zgbz", but your folder names will vary.

5. Start OptiKey again.

*Resetting the dictionary.*

I wouldn't recommend this - perhaps just edit your dictionary in the Management Console (with OptiKey focussed press ALT + M) and then select the "Dictionary" tab. If you want to completely discard your current dictionary (including all data about which words you use commonly), then delete one or all of the dictionary files from your roaming app data directory (C:\Users\*YOUR_USER_NAME*\AppData\Roaming\JuliusSweetland\JuliusSweetland\OptiKey\Dictionaries). For me (with a username of Julius) the steps would be;

1. Close OptiKey if it is running.

2. Navigate to C:\Users\Julius\AppData\Roaming\JuliusSweetland\OptiKey\Dictionaries (don't worry if you don't see the "AppData" directory, it is hidden by default. Just type the path into the navigation bar at the top of File Explorer).

3. Delete the dictionary files you no longer want (or delete the whole "Dictionaries" folder.

4. Start OptiKey again. A new dictionary will be created for you automatically.

---

##<a name="multiple-monitors">Multiple monitors</a>

*Can I use OptiKey across multiple monitors?*

OptiKey is designed to work on 1 monitor only. Attempting to move it between monitors, or across multiple monitors will almost certainly result in incorrect behaviour. If this is a requirement for you then I can attempt to support it. Please email me at [optikeyfeedback@gmail.com](mailto:optikeyfeedback@gmail.com).

---

##<a name="no-menu-key">No Menu key</a>

*I am unable to see the Menu key.*

If you are unable to see the Menu key you may be running in 'Speech Only' mode (see ['Speech only mode'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#speech-only-mode) for more). To change from 'Speech Only' to 'Standard' mode;

1. With OptiKey focussed press ALT + M to open the Management Console.

2. Select the 'Visuals' tab at the top.

3. Change the 'Keyboard Set' from 'Speech Only' to 'Standard'.

4. Click the OK button at the bottom. 

---

##<a name="mouse-simulation-issues">Mouse simulation issues</a>

*Mouse actions are not working as expected.*

Mouse actions (clicking, scrolling, etc) can be impacted by certain keys, called modifier keys (Shift, Ctrl, Win, or Alt). If you are attempting to click/scroll/other mouse action and nothing/something unexpected is happening, then it may be because one of these keys is pressed and you have the Simulate Key Strokes key locked down (see ('Simulate a physical keyboard'[https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-keyboard] for more). The mouse keyboard contains a section to show you the state of the modifier keys - you can release the modifier keys individually from the mouse keyboard, or return to the main keyboard and release the Simulate Key Strokes key.

---


Bad or failed multikey selection matches - too sensitive, word/phrase not in dictionary.
If you are finding that multikey selections are producing bad or unexpected results then it may be that OptiKey is being too sensitive or not sensitive enough when registering your interest in the letters which make up your intended word. In other words OptiKey may be including letters you did not mean to glance at, or missing letters you intentionally glance at. First decided which you think is most likely; if you are given matches which include letters that you only glanced at accidentally then OptiKey is probably being too sensitive. If, however, it is missing letters that you looked at intentionally then it is probably not being sensitive enough.

To decrease OptiKey's sensitivity:
1.With OptiKey focussed press ALT + M to open the Management Console.
2.Select the 'Pointing & Selecting' tab and scroll down to the "Multi-Key Selection" section.
3.Change the setting 'Minimum dwell time on a key to include in capture (ms)' to a larger value. If the current value is 50ms, for example, then try 100ms (a 10th of a second), or even larger. This setting controls how long you need to direct your attention to each key (letter) in a multi-key selection before OptiKey registers your interest in that letter. If you set the value to 500(ms) then you would need to hold your attention on each key (letter) in the multi-key selection for half a second before OptiKey would consider you "interested" in that letter. 

To increase OptiKey's sensitivity:
1.With OptiKey focussed press ALT + M to open the Management Console.
2.Select the 'Pointing & Selecting' tab and scroll down to the "Multi-Key Selection" section.
3.Change the setting 'Minimum dwell time on a key to include in capture (ms)' to a smaller value. If the current value is 250ms, for example, then try 100ms (a 10th of a second), or even smaller. This setting controls how long you need to direct your attention to each key (letter) in a multi-key selection before OptiKey registers your interest in that letter. If you set the value to 100(ms) then you would need to hold your attention on each key (letter) in the multi-key selection for a tenth of a second before OptiKey would consider you "interested" in that letter.

Not sure whether the sensitivity should be decreased or increased? Send me an email with as much detail as possible about what you attempted to capture and what OptiKey suggested. I'll work with you to figure out the problem and suggest how to tweak your settings to improve your experience.


Crash? Unexpected behaviour? Something else wrong?  
If something isn't working as you'd expect, you encounter a crash, a freeze, or something else horrible, then let me know and I'll get it fixed for you. I need something from you though; as much information about the problem as you can supply. Here's the ideal list of things your email will contain;
1. Logs. Developers love logs. You'll need to turn on 'Debugging mode' first (in the Management Console which is accessed by pressing ALT+M, in the 'Other' section). Turn that on then do whatever you did before to cause the unexpected problem, crash, or whatever it was, then close OptiKey. The logs are stored in a special directory which is personal to you. On Windows this will be (open File Explorer and find this directory);
C:\Users\YOUR_USER_NAME\AppData\Roaming\JuliusSweetland\Logs
Grab the latest log file (the modified date on the file will be the most recent) and attach it to an email to optikeyfeedback@gmail.com, but don't send it just yet! I also need...
2. A short description of what you were doing when the problem occurred.
3. What is the problem? A crash? OptiKey did one thing and you were expecting something else? 
4. Anything else that you think is useful. Screenshots are amazing.
I know it's demanding, but if you give me great info then I'll fix it and no-one else will have to send be that lot again.