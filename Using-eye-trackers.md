OptiKey can be controlled with a mouse, but really comes into its own when controlled with an eye tracker. [The list of supported eye tracking devices is available here](https://github.com/JuliusSweetland/OptiKey/wiki/Supported-eye-trackers).

![TheEyeTribe device setup](http://juliussweetland.github.io/OptiKey/images/theeyetribe-physical-setup.png)

1. Connect your tracker and start the tracker's application(s) as required (e.g. for TheEyeTribe you would start the client and server applications). 

2. Complete any initial setup to get the tracker up and running. Usually this involves getting yourself/your tracker/your screen in the correct position and competing a calibration. Some trackers (such as the Tobii EyeX) store user profiles so you do not need to complete a calibration every time.

3. Once it's tracking your eyes reliably start OptiKey.

4. As this is the first time you have used your eye tracker with OptiKey you will need to tell OptiKey which device you want to use. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.

5. Change the "Source" (under "Pointing") to your tracking device. 

6. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now). 

7. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.

8. When OptiKey starts up again it will be listening to your eye tracker so try looking around rather than using the mouse cursor to make key selections.

**N.B.** OptiKey will attempt to use your eye tracking device every time you run it from now on (unless you change the Pointing source back to the mouse). The eye tracking device must be connected, the engine (software) must be running and it must be calibrated and ready to be used **before** OptiKey is started each time.