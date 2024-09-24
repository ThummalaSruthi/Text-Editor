# Text-Editor



1. Action.java (Action Class)
This class tracks every action you do in the text editor, like adding or deleting text.
It remembers:
What action you took (adding or deleting text).<br>
-> The line where the change happened.<br>
-> The actual text you added or deleted.<br>
-> The time when the action happened.<br>
2. Notepad.java (Notepad Class)<br>
This class acts like the text editor itself.<br>
->It stores text in a list (like a notepad with lines).<br>
->It can do the following:<br>
->Insert text into a specific line.<br>
->Delete text from one or more lines.<br>
->Copy text from certain lines.<br>
-> Paste text that was copied to another line.<br>
->Undo the most recent change.<br>
-> Redo the last undone change.<br>
-> Display all or part of the text.<br>
3. App.java (Main Program)<br>
This is the part where the user interacts with the text editor.<br>
You can choose options to:<br>
Add, delete, copy, or paste text.<br>
Undo or redo your last action.<br>
View the text you’ve written.<br>
Exit the program.<br>
