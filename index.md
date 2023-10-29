# Operating systems
**What is Unix?**
It is a multi-user, multi-tasking operating system. A common operating system used in server and PCs

**What is the difference between Unix and Linux?**
Traditional environment: CLI (command line interface), this is powerful and faster but requires finding out what the commands are
Now, there can are graphical user interfaces

| | **Unix** | **Linux** |
| -------- | ------- | ------- |
| **Operating System** | Both are operating system |
| **Development** | Unix is developed by different commercial vendors and non-profit organisation | Linux is open source |
| **Licensing** | Require license to use | Can be used freely without licensing fees |
| **Availability** | Common on enterprise level, less on personal PCs | Common on enterprise and personal PPCs |

# Introduction to CLI
We type command into the _**shell**_, the command interpreter. There are various types of shells – bash, dash, ash, chsh, ksh, zsh

## General Commands
| **Commands** | **Description** | **Sample codes (if any)** |
| -------- | ------- | ------- |
| $ in the command prompt | $ means the command prompt, shell’s way of indicating it is ready for the next command. This can be customized to include things like current directory, time and even customized prompts eg ‘what’s next master?’ |  |
| date | gives date and time | |
| cal | gives calendar | |
| ls | list contents of current directory | |
| ls -l | gives long listing of current directory, including owner, size, date and permissions for files | |
| pwd | print current working directory | |
| cd | change directory | cd ~ (goes to home) <br> cd .. (goes back one folder) |
| mkdir | create a new directory | |
| rmdir | remove empty directory. If there’s file inside directory, it will throw an error| |

## File related Commands
| **Commands** | **Description** | **Sample codes (if any)** |
| -------- | ------- | ------- |
| cat | shows content of a file, means 'concatenate content and print' |  |
| cp | copy file |  |
| mv | move file |  |
| diff | shows differences between 2 files |  |
| rm | delete file (caution: forever deleted) |  |
| grep | find occurrences of a string in one or more files|  |
| find . -name xx | find files with filenames starting ‘xx’ in the current directory| find . -name test.txt (conduct search in current directory) <br> find / -name test.txt (conduct search from root directory) |


## References
Introduction info: https://man7.org/linux/man-pages/man1/intro.1.html 
How to create this github page: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
Markdown guide: https://www.markdownguide.org/cheat-sheet/
