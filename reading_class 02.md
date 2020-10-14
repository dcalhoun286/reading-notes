# **Notes From Read 02**



## Choosing a Text Editor
https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf

* **Important Features:**
    * code completion
    * syntax highlighting
    * variety of themes (easier to read)
    * large selection of extensions
* Other helpful features:
    * syntax highlighting 
        * makes text more noticeable by colorizing it
        * makes it easier to find errors when trying to fix code
    * themes
        * usually, developers choose dark background with text in bright colors
    * extensions
        * helps to accomplish more with minimal effort

* **Using The Software That Already Comes with Your Computer**
    * there are text editors (like VS Code) that help you write code more efficiently
    * more difficult to find errors

### Difference Between TExt Editors and IDEs

* text editors edit and manage texts and also manages files

* IDEs have different software joined together:
    * can edit text, manage files, compile, and debug


## The Command Line
https://ryanstutorials.net/linuxtutorial/commandline.php

* The command line typically presents you with a prompt; what you type is displayed after the prompt
* Prompt will be presented again on a new line after the output of command

* **The Shell, Bash**
    * to know what shell you're using:
    ```
    echo $SHELL
    ```
* Shortcuts
    * Commands are stored in a history. Instead of retyping commands over and over, use up and down arrow keys

## Basic Navigation
https://ryanstutorials.net/linuxtutorial/commandline.php#google_vignette

* pwd -- print working directory
* ls -- list contents of current directory
* cd -- change directory
* Paths
    * ~ -- shortcut for home directory
    * . -- reference to current directory
    * .. reference to parent directory, which is the directory above the current directory

## About Files

* *Everything* is a file! text files, directories, keyboard
* File Extensions:
    * denotes the type of file
    * Examples:
        * .exe, .txt, .png, .jpg
* Case matters
    * will see ERROR message saying file or directory doesn't exist
* Quotes
    * Anything inside quotes is considered a single item
* Escape Characters
    * use backslash to escape the meaning of the next character (such as, if there is a space in the file name)
* Access Hidden Files/Directories
    *ls -a
        * shows all files/directories, including hidden ones