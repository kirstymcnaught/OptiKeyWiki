*Eye tracker not working or stops working.*

1. Check that your eye tracking applications are running as expected and that you've completed any required setup, such as calibrating your eye tracker using its supplied software.

2. Check that the eye tracking device is connected securely to the computer/laptop/tablet.

3. Check the eye tracking software's logs, for example if you are using TheEyeTribe tracker then both the server and client applications produce logs. Are there any messages explaining that something has gone wrong (these are usually marked with WARNING or ERROR). Not sure how to find the logs or how to read them then please email me at [optikeyfeedback@gmail.com](mailto:optikeyfeedback@gmail.com).

*Poor eye tracking performance/accuracy.*

1. Check that the eye tracking device is connected securely to the computer/laptop/tablet.

2. Check the eye tracker setup. The correct positioning is specific to each tracker, so check the tracker's documentation, but commonly the tracker should be in the middle of the screen and directly below it.

3. Is there too much light coming in through a window or a direct light source? Eye trackers typically use infra-red light, so can be confused if there is a strong source of IR light near you, such as the sun.

4. Don't look down - keep the screen & tracker level with your eyeline. Looking down closes your eyelid over your eye, reducing tracking accuracy.

5. Calibrate the eye tracker to an area less than the total screen size.

6. Only screen sizes up to 24 inches are supported by trackers like GazeTracker and TheEyeTribe. Check the limitations.

7. If available, calibrate for more points (12 rather than 9, for example).

8. If available, when calibrating try to match the background/foreground colours to the product you will end up using, e.g. this on-screen keyboard.

9. An effective head rest can prevent head movement.

10. Sit so that your head is within the effective range of your eye tracker. For GazeTracker and TheEyeTribe this is between 45 and 75cm from the tracker/screen.

11. Try your eye tracker at different refresh rates, for example TheEyeTribe tracker can be set to 30fps or 60fps, which is achieved by starting the EyeTribe server with the "-f=30" or "-f=60" switch, e.g. "C:\Program Files (x86)\EyeTribe\Server\EyeTribe.exe" -f=60