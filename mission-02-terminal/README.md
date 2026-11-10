# Explore basic Terminal operations

|Operation/command name|What it does|What I observed|
|--|--|--|
|Current directory display|pwd|/Users/nishu/Desktop/digital-detective-8088|
|Directory listing|ls|List of all the folders and files in the current directory|
|Detailed listing|ls -l|Shows all the permissions of the folders and files|
|Change directory|cd mission-02-terminal|Changes directory|
|Create directory|mkdir terminal-practice|Creates a new folder inside parent folder|
|Create empty file|touch brainstorm.txt|Creates a file|
|Copy file|cp brainstrom.txt notes.txt|copies the brainstorm file and the copied file gets the name notes.txt|
|Move / rename|mv notes.txt terminal-pratice/|moved notes.txt into terminal-practice directory
|Display file contents|cat brainstorm.txt|Shows the contents of brainstorm.txt|

# Task 2.2
- Replacing a file's content removes everything that was previously written, while adding text to the end keep's the previous content and just adds more text at the end of the the text.
- Coying a file keeps the original one and creates a copy of it, while move just moves the files and doesn't create a copy of it.
- The current direcotory display provides the files and folders inside the current direcorty
- It is helpful to check whether the folders are files we created are actually created or not.

# Task 2.3
- `ls` --- lists all the files and directories inside current directory
- `ls -l` --- gives the detailed information of the files and folders 
- `ls -a` --- shows the hidden files too
- `ls -h` --- shows the human readable file sizes

- Flags helps us get to a particular part of the command. As explained above, each flag has it's own ability, one shows the hidden files, other shows human readable file size etc..
- It can also be comined, for example `ls -la` gives the detailed info as well as the hidden files

- fortune | cowsay ---> forune command gives us a random quote and that quote is given as an input to cowsay command, which gives a cow saying the quote as an output

# Task 2.4
- Homebrew version - 7.0.11
- Few packages brew manages:
    - ffmpeg
    - cowsay
    - supabase
    - node

- Package manager like homebrew is a home where all the packages lives, we can install them whenever we want with the help of it.


