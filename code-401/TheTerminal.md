# Practice in the Terminal

## Resource: <https://ryanstutorials.net/linuxtutorial/commandline.php>

I have been waiting for this tutorial!

1. The Command Line: here we learned the basic set up of a command line in a terminal. You will begin with a prompt, expecting to be given a command, then you can provide options/arguments.

- Options modify command behavior and typically start with a (-).

- When a command is entered you will either get an output/nothing/ or an error. You will be prompted to enter another command and that is how you know the previous command is done executing.

2. Basic Navigation: pwd is print working directory which will always be the current location you are in. ls is short for list and alone will list all the items in current directory.

- Understand that the file system is a hierachical structure.

- There are 2 types of PATHS: Absolute uses (/) and will specify location based off root. Relative does not use (/) and will specify location based off current file.

- Helpful tips, (~  tilde) shortcut for home directory. (.  dot) reference to current directory. (..  dotdot) reference to parent of current directory. (cd  change directory) this is used to move, if no argument(location) is provided will be shortcut to home directory.

- You can use Tab for autocompletion.

3. More About Files: everything is a file. Sometimes you may not know what kind of file so you can use **file [path]**.

- Remember case sensitivity, you can use the same letter in options but depending on case sensitivity you will get different results.

- Spaces in the command line seperate items! You cannot put spaces in the name of a file. If you had to you must wrap the name in quotes or use `(\)` to escape the space.

- Hidden files, can be hidden if the name starts with a dot (.) but will not be shown with ls, must use ls -a to show all files including the hidden ones. Remove the dot to make it unhidden.

4. Manual Pages: use man `<command to look up>` to access the manual pages for your system. Will specify commands available.

- man -k `<search term>` allows you to search for a key word in the manual page.

- *"If you want to search within a manual page this is also possible. To do this, whilst you are in the particular manual page you would like to search press forward slash '/' followed by the term you would like to search for and hit 'enter' If the term appears multiple times you may cycle through them by pressing the 'n' button for next."*

5. File Manipulation: to make a directory use mkdir followed by the name. mkdir [options] `<Directory>`

- To remove a directory use rmdir. rmdir [options] `<Directory>`

- To create a blank file use touch. touch [options] `<filename>`

- Copying a file use cp (copy). cp [options] `<source> <destination>` to copy a directory use cp -r

- Moving a file or directory use mv (move). mv [options] `<source> <destination>` can take advantage of this to rename.

- Remove a file/directory with rm (remove). rm [options] `<file>` you cannot undo this, but can use -ri to cancel or have more options.

***Reference the manuals and cheatsheet!***

Cheatsheet <https://ryanstutorials.net/linuxtutorial/cheatsheet.php>
