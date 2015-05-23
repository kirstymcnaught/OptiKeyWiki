##<a name="type-your-first-word">Type your first word</a>

Run OptiKey and it will be displayed with a dark theme, position itself somewhere in the top left corner of your screen, and hover above all other applications. By default it uses your mouse cursor position for input and and selecting a key is performed by hovering over a key for about 1.5 seconds. 

![Alpha keyboard typing welcome sentence](http://juliussweetland.github.io/OptiKey/images/Keyboard_Alpha_Typing_Welcome_Sentence.png)

Try it out - move your mouse cursor over OptiKey and notice how the current key under your cursor is highlighted with a red outline. Keep the mouse cursor over a single key and you'll see an indication of your selection progress on the current key. This is a method of selection called "fixation" or "dwell" and requires you to keep your attention (the cursor) on each key for an amount of time in order to select the key. 

Complete a selection over a letter and it will be pressed and appear in the "scratchpad" at the top. You will also notice that some auto complete suggestions will appear above the scratchpad. Keep selecting letters to type a whole word, or select one of the auto complete suggestions to complete your word. 

If you make a mistake you can use the backspace key to delete your last selection:

![BackOne key](http://juliussweetland.github.io/OptiKey/images/Key_BackOne_Up.png)

or the BackMany key to delete the last whole word:

![BackMany key](http://juliussweetland.github.io/OptiKey/images/Key_BackMany_Up.png) 

That's all there is to start selecting keys and typing words!

---

##<a name="numbers-symbols-&-diacritics">Numbers, symbols and diacritics</a>

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

##<a name="using-eye-trackers">Using eye trackers</a>

As an alternative to selecting keys with your mouse cursor, OptiKey also supports selection using your eyes ([details of the currently supported eye trackers](https://github.com/JuliusSweetland/OptiKey/wiki/Requirements#supported-eye-trackers)).

![TheEyeTribe device setup](http://juliussweetland.github.io/OptiKey/images/theeyetribe-physical-setup.png)

1. Connect your tracker and start the tracker's application(s) (e.g. for TheEyeTribe you would start the client and server applications). 

2. Complete any initial setup to get the tracker up and running. Usually this involves getting yourself/your tracker/your screen in the correct position and competing a calibration. 

3. Once it's tracking your eyes reliably start OptiKey.

4. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.

5. Change the "Source" (under "Pointing") to your tracking device. 

6. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now). 

7. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.

8. When OptiKey starts up again it will be listening to your eye tracker so try looking around rather than using the mouse cursor to make key selections.

---

##<a name="change-selection-method">Change selection method</a>

OptiKey supports a number of selection methods to select a key (or a point on the screen when controlling the mouse). We've seen the fixation method in the ['Type your first word'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#type-your-first-word) section, where you dwell over a key for a period of time until the selection is made, but you can also press a keyboard key or click a mouse button to indicate that you want to make a selection. 

1. To change the selection method open the Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab. 

2. Under "Selection" you'll see "Key selection source" and "Point selection source". The former is the setting to change the way keys are selected, whilst the latter is the setting to change the way points are selected when controlling the mouse.

3. When you change either method you will be shown other associated settings, for example if you select that you would like the "Key selection source" to be "Keyboard Key" then there will be a setting to change which key is used (and likewise for "Mouse button").

Try it out - change the "Key selection source" to "Keyboard key". By default it will expect the "Ins"/"Insert" key, so click "OK" to save your changes (and restart OptiKey), direct your attention to a key, and press the "Ins" key once to select that key.

---

##<a name="make-optikey-speak">Make OptiKey speak</a>

1. Make key selections to type some text into the "scratchpad" (the area at the top of the OptiKey keyboard).

2. Select the Speak key:

    ![Speak key](http://juliussweetland.github.io/OptiKey/images/Key_Speak_Up.png)

3. The voice, rate of speech and volume are all changeable from the Management Console (with OptiKey focussed press ALT + M). 

*Which voices you can choose depends on which voices are installed in your copy of Windows. Please google for instructions on how to add new voices as the method varies for each version of Windows.*

---

##<a name="simulate-a-physical-keyboard">Simulate a physical keyboard</a>

Typing words into the "scratchpad" is great if you only want OptiKey to speak, but you can also use OptiKey to simulate keystrokes on a physical keyboard and type into other applications.

1. To get started clear the scratchpad by selecting the Clear key:

    ![Clear key](http://juliussweetland.github.io/OptiKey/images/Key_Clear_Up.png)

2. Select the Simulate Key Strokes key to turn keystroke simulation on (the key will stay locked down until you decide you want to release it by selecting it again):

    ![Simulate Key Strokes key](http://juliussweetland.github.io/OptiKey/images/Key_SimulateKeyStrokes_Up.png)
     → 
    ![Simulate Key Strokes key](http://juliussweetland.github.io/OptiKey/images/Key_SimulateKeyStrokes_Locked_Down.png)

3. Focus another application where you would like to begin typing, e.g. type a letter into Microsoft Word, or an email into Gmail. You can focus the other application by using a physical mouse to select it and bring it to the foreground, or use OptiKey to simulate the mouse selection (see ['Simulating a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse)).

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

There is also a new keyboard available to you if the Simulate Key Strokes key is pressed; the 'Physical' keyboard (#3 on the menu keyboard), which you'll find by selecting the Menu key. This keyboard contains all the other keyboard keys we've not covered yet, such as ESCAPE, INSERT, ARROW KEYS, FUNCTION KEYS, etc.

![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

---

##<a name="simulate-a-physical-mouse">Simulate a physical mouse</a>

OptiKey is able to simulate mouse input, meaning you can click, drag and scroll as if using a physical mouse. To open the mouse keyboard select the Menu key and then the 'Mouse' key (#4 on the menu keyboard).

![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

The basic mouse actions (left, middle and right click, or scrolling - #1 to #4, and #7 to #14 on the mouse keyboard) are performed by:

1. Selecting the desired mouse action key (e.g. left click).

2. A large mouse cursor will be displayed to show where OptiKey is pointing. Direct your attention to the point where you wish to perform the mouse action and hold it there. A progress indicator will indicate that you are performing a selection. When the progress indicator completes your mouse action (a click, or scroll) will be performed at that point.

![Mouse keyboard](http://juliussweetland.github.io/OptiKey/images/Keyboard_Mouse_Numbered.png)

To increase your precision when making mouse selections you can switch on magnification by locking down the Magnifier key:

![Magnifier key locked down](http://juliussweetland.github.io/OptiKey/images/Key_Magnifier_Locked_Down.png)

Selecting a point becomes a two step process when using the magnifier:

1. Direct your attention to roughly where you wish to click/scroll, at which point a magnified image of that area will be displayed.

2. Direct your attention to exactly where you wish to click/scroll in the magnified image to perform the action at that point (or select outside the magnified area to cancel the action).

![Performing a mouse action while using the Magnifier](http://juliussweetland.github.io/OptiKey/images/Clicking_On_Magnified_Folder.png)

Performing a Drag operation (#5 on the mouse keyboard) is slightly different as two selections have to be made after you select the drag key:

1. Select point one (this will be a two step process if the Magnifier key is pressed or locked down). This first selection will be where the mouse button is pressed and held down.

2. Select point two (again, a two step process if using the magnify feature) - this will be the point to which the mouse cursor is dragged and released.

The 'Repeat Last' key (#6 on the mouse keyboard) allows you to repeat the last mouse action taken, which can be useful if you want to scroll down a long web page one scroll at a time, for example.

*N.B. If you have the Simulate Key Strokes key locked down then keys #16 to #19 on the mouse keyboard show you the state of the modifier keys (Shift, Ctrl, Win and Alt) and allows you to release any which are pressed/locked down. If you attempt a mouse action while a modifier key is pressed then you may experience unexpected behaviour. For example clicking on a file in File Explorer while the Ctrl key is pressed adds the file to the current selection, rather than simply selecting the file.*

---

##<a name="multi-key-selection">Multi-key selection</a>

<a name="typing-whole-words">**Typing whole words**</a>

Instead of typing each letter of a word individually, it is possible to capture a whole word (or phrase) in one go. To activate multi-key selection select the Multi-key Selection key to lock it down:

1. ![Multi-key selection key up](http://juliussweetland.github.io/OptiKey/images/Key_MultiKeySelection_Up.png)
2. ![Multi-key selection key locked down](http://juliussweetland.github.io/OptiKey/images/Typing_Hello_MultiKeyCapture_Turning_On_MultiKeyCapture.png)
3. ![Multi-key selection key locked down](http://juliussweetland.github.io/OptiKey/images/Key_MultiKeySelection_Locked_Down.png)

The process of capturing a word using fixation selection then works like this;

1. Select the first letter of the word, e.g. the "h" if you want to type "hello". You have begun capturing the word (or phrase).

    ![Selecting the first letter](http://juliussweetland.github.io/OptiKey/images/Typing_Hello_MultiKeyCapture_Starting.png)

2. Direct your attention to each letter in the word. You don't have to select each one, just briefly register your interest in each letter; "e", "l", then "o". Don't worry about double letters like the "ll" in "hello" - OptiKey will figure that out for you.

    ![Selecting the rest of the letters](http://juliussweetland.github.io/OptiKey/images/Typing_Hello_MultiKeyCapture_The_Whole_Capture.png)

3. When you get to the last letter select it to signal that you are finished capturing the word (or phrase). OptiKey will match what you captured with its dictionary of words and phrases and type the best match to the "scratchpad". Alternative suggestions will be displayed at the top, which you can select if OptiKey matched your capture to the wrong word.

    ![Multi-key selection of hello completed](http://juliussweetland.github.io/OptiKey/images/Typing_Hello_MultiKeyCapture_Complete.png)

Multikey selection learns which words you use frequently and will improve its suggestions over time.

<a name="typing-whole-phrases">**Typing whole phrases**</a>

Whole phrases are types in the same way as whole words, but instead of typing each letter of each word you only type the first letter of each word. For example if the phrase "how are you" was in the dictionary, then you could type this as one multi-key selection like this:

1. Select the first letter of the first word, i.e. the "h" from "how". This begins the capture.

2. Direct your attention to the first letter of each word, so "a", then "y" in our example.

3. Stay on the last letter ("y") to select it and signal that you are finished capturing. The set of matching words and phrases will be calculated and the best choice output to the scratchpad (the rest of the suggestions will appear at the top, above the scratchpad).

*N.B. OptiKey can only find matches for your multi-key selection in its dictionary - see ['Changing and editing the dictionary'] (https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide##changing-and-editing-the-dictionary) for info on how to add and remove words and phrases.*

---

##<a name="auto-capitalisation-and-auto-spacing">Auto-capitalisation & auto-spacing</a>

OptiKey can help to increase your typing rate by working out if your next word is the start of a new sentence and automatically pressing the Shift key for you to capitalise the next letter. This works when typing letter by letter, as well as typing whole words using multikey selection.

OptiKey can further speeds things up by automatically inserting spaces between words and sentences. This works best when using multi-key selection to enter whole words and phrases.

*Both of these features are turned ON by default, but can be toggled on or off from the Management Console (with OptiKey focussed press ALT + M).*

---

##<a name="the-dictionary">The dictionary</a>

<a name="edit-the-dictionary-from-the-management-console">**Edit the dictionary from the Management Console**</a>

The default dictionary contains many common words and phrases, but you will probably want to customise it by adding and removing entries. You can view and customise the dictionary from the Management Console:

1. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Dictionary" tab.

    ![Editing the dictionary from the Management Console](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Dictionary_Numbered.png)

2. To add a new word or phrase type it (as a lower case word unless it is a proper noun, abbreviation, etc) in the box at the top (#1 in the screenshot) and click 'Add' to add it to the dictionary.

3. To remove an entry just click the 'Delete' button next to it (#2 in the screenshot).

4. Click 'OK' to save your changes.

<a name="edit-the-dictionary-from-the-scratchpad">**Edit the dictionary from the scratchpad**</a>

You can also add words and phrases directly from the scratchpad by pressing the Add To Dictionary key. OptiKey will examine the words and sentences that you have already typed into the scratchpad and ask you which you would like to add to the dictionary:

1. Type the word to add on its own, or as part of a sentence.

2. Select the Add To Dictionary key.

    ![Editing the dictionary from the Management Console](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_AddToDictionary_Up.png)

3. OptiKey will find all words in the scratchpad which are not already in the dictionary and ask you, one at a time, if you would like to add the word. Confirm to add to the dictionary.

    ![Confirming a candidate entry to add to dictionary](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Keyboard_YesNoQuestion.png)

To add a phrase it is very similar:

1. Clear the scratchpad using the Clear key:

    ![Clear key](http://juliussweetland.github.io/OptiKey/images/Key_Clear_Up.png)

2. Type the phrase exactly as you would like it to be available in the dictionary. You don't need to capitalise the first letter unless it is a proper noun as OptiKey will auto capitalise the first letter if it is the start of a new sentence (if that setting is turned on - see [Auto-capitalisation](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#auto-capitalisation-and-auto-spacing) for more).

3. Select the Add To Dictionary key.

    ![Editing the dictionary from the Management Console](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_AddToDictionary_Up.png)

4. Confirm to add the phrase when asked. OptiKey will also ask you if you would like to add any new words that appear in your phrase - choose to confirm if the word is useful, or skip if not.


<a name="change-the-dictionary-language">**Change the dictionary language**</a>

To change the dictionary language used by OptiKey:

1. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Words" tab.

    ![Change the dictionary language from the Management Console](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Words_Numbered.png)

2. Select the desired language (#1 in the screenshot).

3. Click 'OK' to save your changes.

---

##<a name="change-size-position-and-opacity">Change size, position and opacity</a>

OptiKey can be resized, moved and made more or less transparent. Select the Menu key and then the Size & Opacity key (#6 on the menu keyboard) or Position & Opacity key (#7 on the menu keyboard):

![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

<a name="size-and-opacity-keyboard">**Size & opacity keyboard**</a>

![Size & Opacity keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Size_And_Opacity_Numbered.png)

    #1-8: Expand OptiKey in selected direction by number of pixels shown on key #9
    #9: Toggle through a sequence which controls how many pixels to resize by when using keys #1-8 and #10-17
    #10-17: Shrink OptiKey in selected direction by number of pixels shown on key #9
    #18: Restore OptiKey to previous size (if maximised)
    #19: Maximise OptiKey
    #20: Decrease opacity, i.e. make OptiKey more see-through
    #21: Increase opacity, i.e. make OptiKey less see-through
    #22: Return to previous (Menu) keyboard

<a name="position-and-opacity-keyboard">**Position & opacity keyboard**</a>

![Position & Opacity keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Position_And_Opacity_Numbered.png)

    #1-8: Move OptiKey in selected direction by number of pixels shown on key #9
    #9: Toggle through a sequence which controls how many pixels to move by when using keys #1-8
    #10-17: Jump (move) OptiKey to selected screen boundary
    #18: Restore OptiKey to previous size (if maximised)
    #19: Maximise OptiKey
    #20: Decrease opacity, i.e. make OptiKey more see-through
    #21: Increase opacity, i.e. make OptiKey less see-through
    #22: Return to previous (Menu) keyboard

---

##<a name="change-the-theme">Change the theme</a>

1. Open the Management Console (with OptiKey focussed press ALT + M).

2. Select the 'Visuals' tab at the top.

3. Change the 'Theme' (#1 in the screenshot).

  ![Change the theme from the Management Console](http://juliussweetland.github.io/OptiKey/images/Management_Console_Visual_Numbered.png)

4. Click the OK button at the bottom.

---