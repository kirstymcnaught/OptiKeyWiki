OptiKey can be controlled with a mouse, or an eye tracker (the preferred method), but it is also possible to use a standard webcam. There are a number of free applications which can use your webcam to track your head movements and translate those into movements of your mouse cursor on screen. As OptiKey can be controlled using the cursor position this means you can control OptiKey using head movements captured via your webcam. This method is a very different experience from using an eye tracking device, but can be very effective.

These applications should all work with OptiKey:
* [Enable Viacam](http://eviacam.sourceforge.net/index.php) - free and open source
* [Camera Mouse](http://www.cameramouse.org/) - free. [(click here for a demo video)](https://www.youtube.com/watch?v=BqHeZAkjTJs)
* [Open Gazer](http://www.inference.phy.cam.ac.uk/opengazer/) - free and open source

*You could also try any other solution (hardware or software) which can control the mouse position effectively, e.g. the [Quha Zono](http://www.quha.com/products-2/zono/), although hardware solution like these can be expensive.*

1. Start whichever application you have chosen to control your cursor position via your webcam, e.g. 'Enable Viacam'. Configure it and make sure it is moving the mouse comfortably and reliably.

2. If you have changed which device OptiKey is using for input (e.g. to an eye tracker) then you will need to tell OptiKey to listen to your mouse cursor position again...

3. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.

4. Change the "Source" (under "Pointing") to "Mouse Position". 

5. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now. 

6. You may want to [slow OptiKey down a little.](https://github.com/JuliusSweetland/OptiKey/wiki/Speed-up-&-slow-down)

7. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.

8. When OptiKey starts up again it will be listening to your mouse cursor's position so try moving your head (or whatever your webcam application is tracking). Position the cursor over a key and complete a fixation ("dwell") to make a selection.

**N.B.** OptiKey will attempt to use your mouse cursor position every time you run it from now on until you change the Pointing source to something else.