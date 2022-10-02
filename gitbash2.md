# Git_Bash
### I/O Redirection : Standard OUTPUT
- By default, standard output is screen
- You can redirect output using **">"** after a command to create and save the output in a file.
- Command **"cat"** displays the content of a text file.
- Using **">>"** appends output to an existing file (if it already exitsts), or create and write to a new file if it doesn't exist.

### I/O Redirection : Standard INPUT
- By default, standard input is from keyboard.
- You can redirect input from a file using **"<"**.
- You can mix **"<"** and **">"** toogether in a single line.

### Pipelines ***"|"***
- Pipeline feeds output of previous command to input of next command.
- command1 | command2 | command3 | ...
- Press **"q"** key to exit the screen.

### Expansion
- Special characters expand its meaning when fiven to shell commands 

##### Tip : Backslash **"/"**
- Backslash can be used to ignore line change in command ("enter"), to enter a long command in multiple lines.

### Permissions
- Linux is a multi-user system.
- Files and directories have a permission assigned differently to owner / group/ others.
- $ ***"chmod"*** changes permissions.
Ex) $ chmod 600 some_file.txt
6 = 110 = rw- for owner.
0 = 000 = --- for group.
0 = 000 = --- for others.
- Change the permission of a file "word.txt" that only the owner(you) can read and write, but all the others (including others in the group) can only read it. No execution is needed for all users.

### Superuser
- A superuser has all system administation authority
- Some commands need superuser's privilleges.
- Put **"sudo"** before the command if you are a superuser.
- Type **"exit"** to get out of a superuser session.

### Text Editors
In Linux, You can choose CLI-based of GUI-based text editors.
- ***nano*** : **nano** is a free clone of the text editor supplied with the **pine** email program. **nano** is very easy to use but is very short on features compared to **vim and **emacs**. **nano** is recommended for first-time users who need a command line editor.
- ***gedit*** : **gedit** is the editor supplied with the GNOME desktop environment. **gedit** is easy to use and contains enough features to be a good befinners-level editor.

##### Tip : History
- Type **"history"** to see previous command history.
- Or, save it to a text file.
