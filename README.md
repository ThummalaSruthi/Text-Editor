# Text-Editor



1. Action.java (Action Class)
This class tracks every action you do in the text editor, like adding or deleting text.
It remembers:
What action you took (adding or deleting text).
-> The line where the change happened.
-> The actual text you added or deleted.
-> The time when the action happened.
2. Notepad.java (Notepad Class)
This class acts like the text editor itself.
->It stores text in a list (like a notepad with lines).
->It can do the following:
->Insert text into a specific line.
->Delete text from one or more lines.
->Copy text from certain lines.
-> Paste text that was copied to another line.
->Undo the most recent change.
-> Redo the last undone change.
-> Display all or part of the text.
3. App.java (Main Program)
This is the part where the user interacts with the text editor.
You can choose options to:
Add, delete, copy, or paste text.
Undo or redo your last action.
View the text you’ve written.
Exit the program.
