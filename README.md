# Linux Text Editors
A Linux text editor is a software application speciafically designed for creating, modifying, and managing text files on a Linux-based operating system. In this project, I explore various text editors available in Linux.

## VIM TEXT EDITOR
The Linux Vim text editor, short for Vi improved, is a powerful and versatile text editing tool deeply ingrained in the Unix and Linux ecosystems. Vim has a steeper learning curve compared to simpler editors like Nano.

## working with Vim Editor - Commands Used
- **Open a new file in Vim**: `vim exercise.txt`

(Linux-Text-Editor/img/create file on vim.png)

- **Insert text**: Press `i` to enter insert mode and add text.

(Linux-Text-Editor/img/insert command.png)

- **Edit text**: 
Deleting a character: press esc on your keyboadrd to exit the insert mode. Position the cursor on a character you want to delete and press x.
Deleting a Line: To delete an entire line in the file, ensure that you are not in the insert mode. Then, place the cursor on a line and press d twice on your keyboard to delete the entire line.

(Linux-Text-Editor/img/edit on vim.png)

- **Undo Changes**: ensure you are not in the insert mode, then press u to undo.

(Linux-Text-Editor/img/undo command.png)

- **Save the file and exit**: After you have finished writing into the file, press esc, then type `:wq` and press Enter. 

(Linux-Text-Editor/img/save on vim.png)

- **Exit without Saving the file**: Incase you do not intend to save the file, simply press esc, then type :q! and press enter type `:q!` and press Enter. 

(Linux-Text-Editor/img/quit on vim.png)

## working with Nano Text Editor - Commands Used

Among Linux text editors, Nano stands out as a user-friendly and straightforward tool, making it an excellent choice for users who are new to the command line or those who prefer a more intuitive editing experience.

- **Open a new file in Nano**: Use the command `nano nano_file.txt`

(Linux-Text-Editor/img/open nano file.png)

(<type in nano.png>)

- **Insert and Editing Text**: Type a few lines of text into the file. Nano has a simple interface, and you can start typing immediately.

(<type in nano 2.png>)

- **Saving Changes**: Save your changes by pressing Ctrl + o. Nano will prompt you to confirm the filename; press Enter to confirm.

[save on nano]: <save on nano-1.png>

- **Exiting on Nano**: if you wish to exit nano without saving the file press Ctrl + x. If you have unsaved changes, Nano will prompt you to save before exiting.

- **Opening an existing Nano File**: Open an existing file using the command `nano existing_file.txt`
Navigate through the file using the arrow keys, write in data and save the file 

[def]: <open existing nano file.png>

[def2]: <save existing nano file.png>