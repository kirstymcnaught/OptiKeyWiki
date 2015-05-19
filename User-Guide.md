<a name="type-your-first-word">**Type your first word**</a>

Run OptiKey and it will be displayed with a dark theme, position itself somewhere in the top left corner of your screen, and hover above all other applications. By default it uses your mouse cursor position for input and and selecting a key is performed by hovering over a key for about 1.5 seconds. 

![Alpha keyboard typing welcome sentence](http://juliussweetland.github.io/OptiKey/images/Keyboard_Alpha_Typing_Welcome_Sentence.png)

Try it out - move your mouse cursor over OptiKey and notice how the current key under your cursor is highlighted with a red outline. Keep the mouse cursor over a single key and you'll see an indication of your selection progress on the current key. This is a method of selection called "fixation" or "dwell" and requires you to keep your attention (the cursor) on each key for an amount of time in order to select the key. 

Complete a selection over a letter and it will be pressed and appear in the "scratchpad" at the top. You will also notice that some auto complete suggestions will appear above the scratchpad. Keep selecting letters to type a whole word, or select one of the auto complete suggestions to complete your word. 

If you make a mistake you can use the backspace key to delete your last selection;

![BackOne key](http://juliussweetland.github.io/OptiKey/images/Key_BackOne_Up.png)

or the BackMany key to delete the last whole word;

![BackMany key](http://juliussweetland.github.io/OptiKey/images/Key_BackMany_Up.png) 

That's all there is to start selecting keys and typing words.

---

<a name="numbers-symbols-&-diacritics">**Numbers, symbols and diacritics**</a>

At some point you'll probably want to type a number, symbol, or diactrical letter (e.g. an accented e). For the numbers and symbols keyboard select the Symbols key;

![Symbols key](http://juliussweetland.github.io/OptiKey/images/Key_Symbols_Up.png)

There are too many symbols to fit on one screen (in fact there are 3 screens of symbols). You can toggle between the screens by selecing the keyboard number key, which progresses to the next keyboard and then loops back to the first again;

![1 of 3 key](http://juliussweetland.github.io/OptiKey/images/Key_Symbol_1of3_Up.png)
![2 of 3 key](http://juliussweetland.github.io/OptiKey/images/Key_Symbol_2of3_Up.png)
![3 of 3 key](http://juliussweetland.github.io/OptiKey/images/Key_Symbol_3of3_Up.png)

At any time you can select the Alpha key to go back to the main (A-Z letters) keyboard;

![Alpha key](http://juliussweetland.github.io/OptiKey/images/Key_Alpha_Up.png)

If you want diacritical letters or currency symbols select the Menu key and then the diacritic key (#1 on the menu keyboard) or currency key (#2 on the menu keyboard);

![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

Again, there are more diacritical characters or currency symbols than it is possible to fit on one screen, so use the "1 of X", "2 of X" keys to move between the screens. As before, the Alpha key on each of those keyboards takes you back to the letters keyboard.

---

<a name="using-eye-trackers">**Using eye trackers**</a>

As an alternative to selecting keys with your mouse cursor, OptiKey also supports selection using your eyes ([currently supported eye trackers](https://github.com/JuliusSweetland/OptiKey/wiki/Requirements#supported-eye-trackers)). 

1. Connect your tracker and start the tracker's application(s) (e.g. for TheEyeTribe you would start the client and server applications). 

2. Complete any initial setup to get the tracker up and running; usually this involves getting yourself/your tracker/your screen in the correct position and competing a calibration. 

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

2. Under "Selection" you'll see "Key selection source" and "Point selection source"; the former is the setting to change the way keys are selected, whilst the latter is the setting to change the way points are selected when controlling the mouse.

3. When you change either method you will be shown other associated settings, for example if you select that you would like the "Key selection source" to be "Keyboard Key" then there will be a setting to change which key is used (and likewise for "Mouse button").

Try it out - change the "Key selection source" to "Keyboard key". By default it will expect the "Ins"/"Insert" key, so click "OK" to save your changes (and restart OptiKey), direct your attention to a key, and press the "Ins" key once to select that key.

---

<a name="making-optikey-speak">**Making OptiKey speak**</a>

1. Make key selections to type some text into the "scratchpad" (the area at the top of the OptiKey keyboard).

2. Select the Speak key:

![Speak key](http://juliussweetland.github.io/OptiKey/images/Key_Speak_Up.png)

3. The voice, rate of speech and volume are all changeable from the Management Console (with OptiKey focussed press ALT + M). 

*Which voices you can choose depends on which voices are installed in your copy of Windows. Please google for instructions on how to add new voices as the method varies for each version of Windows.*

---

