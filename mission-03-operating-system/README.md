# Task 3.1

|Information explored|What is tells you|Your observation|
|--|--|--|
|Operating system/ system details|Core software architecture|arm64|
|Current account identity|Who is the owner of the current terminal session|nishu|
|Available and used storage|How many storage hass been used and how much is left|14G used 772G left|
|System activity snapshot|shows the computer resource(CPU, GPU,...) are behaving at this second|Shows the PID, CPU% etc... for different activities|

# Task 3.2
- Process is a program that is currently running or being executed
- PID column shows us the PID of each program/process tunning in our computer. PID is a unique ID given to each process
- Two processes currently running in my computer are - 
    - Google chrome
    - VS Code

# Task 3.3
- Absolute path - Starting from root directory: eg: /Users/nishu/Desktop/digital-detective-8088/mission-03-operating system/README.md
- Relative path - Starting from current directory: eg: /digital-detective-8088/mission-03-operating-system/README.md

# Task 3.4

|OS Responsibilty|Your explaination|Example|
|--|--|--|
|Process management|Manages the process, creates PID, monitors the process and terminates it|PID created from the opened Google chrome|
|Memory management|Controls the memory part|Google chrome gets a certain memory inside RAM|
|Device management|Communicates and controld the hardware part connected|Handling device drivers|
|File management|Organize, store, track and secure our files|VS code asking permission to open a folder or a file|
|User interface/ shell|Interface where user interacts with the computer|Using GUI and creating a folder|
|Security and permissions|secures our files and folders|executing a non-executable file shows error|

- Commands used - 
    ls -l
    pwd
    ps aux - snapshot of system activity
    uname -a - the OS env we are using
    whoami - owner of the current terminal session
    df -H / - storage used and remaining storage

- Difficulties faced - 
    checking the OS env we are using
    overall storage left and used
    
