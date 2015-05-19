<a name="type-your-first-word">**Type your first word**</a>

Run OptiKey and it will be displayed with a dark theme, position itself somewhere in the top left corner of your screen, and hover above all other applications. By default it uses your mouse cursor position for input and and selecting a key is performed by hovering over a key for about 1.5 seconds. 

![Alpha keyboard typing welcome sentence](http://juliussweetland.github.io/OptiKey/images/Keyboard_Alpha_Typing_Welcome_Sentence.png)

Try it out - move your mouse cursor over OptiKey and notice how the current key under your cursor is highlighted with a red outline. Keep the mouse cursor over a single key and you'll see an indication of your selection progress on the current key. This is a method of selection called "fixation" or "dwell" and requires you to keep your attention (the cursor) on each key for an amount of time in order to select the key. 

Complete a selection over a letter and it will be pressed and appear in the "scratchpad" at the top. You will also notice that some auto complete suggestions will appear above the scratchpad. Keep selecting letters to type a whole word, or select one of the auto complete suggestions to complete your word. 

If you make a mistake you can use the backspace key to delete your last selection:

![BackOne key](http://juliussweetland.github.io/OptiKey/images/Key_BackOne_Up.png)

or the BackMany key to delete the last whole word:

![BackMany key](http://juliussweetland.github.io/OptiKey/images/Key_BackMany_Up.png) 

That's all there is to start selecting keys and typing words.

---

<a name="numbers-symbols-&-diacritics">**Numbers, symbols and diacritics**</a>

At some point you'll probably want to type a number, symbol, or diactrical letter (e.g. an accented e). For the numbers and symbols keyboard select the Symbols key:

![Symbols key](http://juliussweetland.github.io/OptiKey/images/Key_Symbols_Up.png)

There are too many symbols to fit on one screen (in fact there are 3 screens of symbols). You can toggle between the screens by selecing the keyboard number key, which progresses to the next keyboard and then loops back to the first again:

![1 of 3 key](http://juliussweetland.github.io/OptiKey/images/Key_Symbol_1of3_Up.png)
![2 of 3 key](http://juliussweetland.github.io/OptiKey/images/Key_Symbol_2of3_Up.png)
![3 of 3 key](http://juliussweetland.github.io/OptiKey/images/Key_Symbol_3of3_Up.png)

At any time you can select the Alpha key to go back to the main (A-Z letters) keyboard:

![Alpha key](http://juliussweetland.github.io/OptiKey/images/Key_Alpha_Up.png)

If you want diacritical letters or currency symbols select the Menu key and then the diacritic key (#1 on the menu keyboard) or currency key (#2 on the menu keyboard):

![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

Again, there are more diacritical characters or currency symbols than it is possible to fit on one screen, so use the "1 of X", "2 of X" keys to move between the screens. As before, the Alpha key on each of those keyboards takes you back to the letters keyboard.

---

<a name="using-eye-trackers">**Using eye trackers**</a>

As an alternative to selecting keys with your mouse cursor, OptiKey also supports selection using your eyes ([currently supported eye trackers](https://github.com/JuliusSweetland/OptiKey/wiki/Requirements#supported-eye-trackers)). 

1. Connect your tracker and start the tracker's application(s) (e.g. for TheEyeTribe you would start the client and server applications). 

2. Complete any initial setup to get the tracker up and running. Usually this involves getting yourself/your tracker/your screen in the correct position and competing a calibration. 

3. Once it's tracking your eyes reliably start OptiKey.

4. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.

5. Change the "Source" (under "Pointing") to your tracking device. 

6. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now). 

7. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.

8. When OptiKey starts up again it will be listening to your eye tracker so try looking around rather than using the mouse cursor to make key selections.

---

<a name="change-selection-method">**Change selection method**</a>

OptiKey supports a number of selection methods to select a key (or a point on the screen when controlling the mouse). We've seen the fixation method in the ['Type your first word'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#type-your-first-word) section, where you dwell over a key for a period of time until the selection is made, but you can also press a keyboard key or click a mouse button to indicate that you want to make a selection. 

1. To change the selection method open the Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab. 

2. Under "Selection" you'll see "Key selection source" and "Point selection source". The former is the setting to change the way keys are selected, whilst the latter is the setting to change the way points are selected when controlling the mouse.

3. When you change either method you will be shown other associated settings, for example if you select that you would like the "Key selection source" to be "Keyboard Key" then there will be a setting to change which key is used (and likewise for "Mouse button").

Try it out - change the "Key selection source" to "Keyboard key". By default it will expect the "Ins"/"Insert" key, so click "OK" to save your changes (and restart OptiKey), direct your attention to a key, and press the "Ins" key once to select that key.

---

<a name="make-optikey-speak">**Make OptiKey speak**</a>

1. Make key selections to type some text into the "scratchpad" (the area at the top of the OptiKey keyboard).

2. Select the Speak key:

![Speak key](http://juliussweetland.github.io/OptiKey/images/Key_Speak_Up.png)

3. The voice, rate of speech and volume are all changeable from the Management Console (with OptiKey focussed press ALT + M). 

*Which voices you can choose depends on which voices are installed in your copy of Windows. Please google for instructions on how to add new voices as the method varies for each version of Windows.*

---

<a name="simulate-a-physical-keyboard">**Simulate a physical keyboard**</a>

Typing words into the "scratchpad" is great if you only want OptiKey to speak, but you can also use OptiKey to simulate keystrokes on a physical keyboard and type into other applications.

1. To get started clear the scratchpad by selecting the Clear key:

![Clear key](http://juliussweetland.github.io/OptiKey/images/Key_Clear_Up.png)

2. Select the Simulate Key Strokes key to turn keystroke simulation on (the key will stay locked down until you decide you want to release it by selecting it again):

![Simulate Key Strokes key](http://juliussweetland.github.io/OptiKey/images/Key_SimulateKeyStrokes_Up.png)

3. Focus another application where you would like to begin typing, e.g. type a letter into Microsoft Word, or an email into Gmail. You can focus the other application by using a physical mouse to select it and bring it to the foreground, or use OptiKey to simulate the mouse selection (see ['Simulating a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulating-a-physical-mouse)).

4. Select keys to type as usual. As you make each selection it will appear in both the scratchpad and your selected application. The BackOne and BackMany keys can be used to correct any mistakes (introduced in the ['Type your first word'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#type-your-first-word) section).

![Simulating a physical keyboard to type into Microsoft Word](http://juliussweetland.github.io/OptiKey/images/Typing_Into_Word.png)

You may have also noticed that some new keys are available now that the Simulate Key Strokes key is pressed, for example the Shift, Ctrl, Win and Alt keys:

![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Up.png)
![Ctrl key](http://juliussweetland.github.io/OptiKey/images/Key_Ctrl_Up.png)
![Win key](http://juliussweetland.github.io/OptiKey/images/Key_Win_Up.png)
![Alt key](http://juliussweetland.github.io/OptiKey/images/Key_Alt_Up.png)

These work in exactly the same way as they do on a physical keyboard, and can be combined with other keys by holding them down. Try selecting one of them and you'll notice that it cycles through 3 states; UP, DOWN, and LOCKED DOWN, before returning to UP. For example, the Shift key progresses like this:

![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Up.png)
![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Down.png)
![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Locked_Down.png)
![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Up.png)
etc...

This makes it easy to press or lock down a number of keys together. For example, select Ctrl to press it down, and then press the "P" key to send the "Print" command to the active application. The Ctrl key will be automatically released after you select the "P" key, unless it is in the LOCKED DOWN state.

It is a good idea to check if any of these "modifier" keys (Shift, Ctrl, Win, Alt) are pressed if you experience unexpected behaviour while typing into another application as they can impact your key selections.

With the Simulate Key Strokes key pressed there is also a new keyboard available to you; the 'Physical' keyboard (#3 on the menu keyboard), which you'll find by selecting the Menu key. This keyboard contains all the keyboard keys we've not covered yet, such as ESCAPE, INSERT, ARROW KEYS, FUNCTION KEYS, etc.

![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

---

