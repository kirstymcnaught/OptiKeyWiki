OptiKey is always simulating keystrokes (i.e. outputting what you type as if you are using a keyboard) , unless you are in the "Conversation" keyboard. Here is how keystroke simulation works:

1. Focus another application where you would like to begin typing, e.g. you want to type a letter into Microsoft Word, or an email into Gmail. You can focus the other application by using a physical mouse to select it and bring it to the foreground, or use OptiKey to simulate the mouse selection (see ['Simulating a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse)).

2. Select keys in OptiKey to type letters and words as usual. As you make each key selection it will appear in both the scratchpad and your selected application. The BackOne and BackMany keys can be used to correct any mistakes (introduced in the ['Type your first word'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#type-your-first-word) section).

![Simulating a physical keyboard to type into Microsoft Word](http://juliussweetland.github.io/OptiKey/images/Typing_Into_Word.png)

You may have also noticed that some new keys are available now that the Simulate Key Strokes key is pressed, for example the Shift, Ctrl, Win and Alt keys:

![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Up.png)
![Ctrl key](http://juliussweetland.github.io/OptiKey/images/Key_Ctrl_Up.png)
![Win key](http://juliussweetland.github.io/OptiKey/images/Key_Win_Up.png)
![Alt key](http://juliussweetland.github.io/OptiKey/images/Key_Alt_Up.png)

These work in exactly the same way as they do on a physical keyboard, and can be combined with other keys by holding them down. Try selecting one of them and you'll notice that it cycles through 3 states; UP, DOWN, and LOCKED DOWN, before returning to UP. For example, the Shift key progresses like this:

![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Up.png)
 ⇨ 
![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Down.png)
 ⇨ 
![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Locked_Down.png)
 ⇨ 
![Shift key](http://juliussweetland.github.io/OptiKey/images/Key_Shift_Up.png)
etc...

This makes it easy to press or lock down a number of keys together. For example, select Ctrl to press it down, and then press the "P" key to send the "Print" command to the active application. The Ctrl key will be automatically released after you select the "P" key, unless it is in the LOCKED DOWN state.

It is a good idea to check if any of these "modifier" keys (Shift, Ctrl, Win, Alt) are pressed if you experience unexpected behaviour while typing into another application as they can impact your key selections.

N.B. It is useful to clear the scratchpad (by selecting the Clear key) when changing where you are typing (e.g. when starting a new email, or moving to another application):

![Clear key](http://juliussweetland.github.io/OptiKey/images/Key_Clear_Up.png)

---

**The physical keyboard**

The 'Physical' keyboard contains the "other" keys from a standard keyboard, e.g. the function keys (F1-F12, PG UP, PG DN, INSERT, etc). To access it:

1. Select the 'Menu' key:

    ![Menu key](http://juliussweetland.github.io/OptiKey/images/Key_Menu_Up.png)

2. Select the 'Physical' key:

    ![Menu keyboard with numbers](http://juliussweetland.github.io/OptiKey/images/Keyboard_Menu_Numbered.png)

The 'Physical' keyboards look like this:

![Symbols keyboard 1 of 3](http://juliussweetland.github.io/OptiKey/images/Keyboard_Physical.png)