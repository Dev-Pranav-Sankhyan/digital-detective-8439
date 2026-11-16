# Mission 2 - Become comfortable with the Terminal

## 1. Task / objective
Practice basic Terminal commands like making folders, moving files, using flags and pipes, and explaining package managers.

## 2. Work completed
Practiced terminal commands in a test folder. Answered questions about file operations, flags, pipes, and package managers like Homebrew.

### Task 2.1 - Explore basic Terminal operations

| Operation / command name | What it does | What I observed |
| :--- | :--- | :--- |
| Current-directory display (`pwd`) | Shows the full path of where I am | Printed the path to my folder |
| Directory listing (`ls`) | Lists files and folders | Showed the files in the folder |
| Detailed listing (`ls -l`) | Lists files with extra info | Showed permissions, size, and date |
| Change directory (`cd ..`) | Moves up one folder | Changed my location to the parent folder |
| Create directory (`mkdir`) | Makes a new folder | Created a new practice folder |
| Create empty file (`touch`) | Makes a blank text file | Created a file without opening an editor |
| Copy file (`cp`) | Duplicates a file | Made an exact copy with a new name |
| Move / rename file (`mv`) | Moves or renames it | Renamed the copied file |
| Display file contents (`cat`) | Prints the text inside | Showed the text in the terminal |

### Task 2.2 - Practise file changes safely
* **Replacing vs adding:** Replacing overwrites everything in the file. Adding (appending) just puts new text at the end and keeps the old stuff.
* **Copy vs move:** Copying makes a second duplicate file. Moving just relocates it or changes its name without making a copy.
* **pwd usefulness:** It tells you exactly where you are so you don't mess with the wrong files.
* **ls usefulness:** It lets you see what files are actually in the folder you're in.

### Task 2.3 - Understand flags and pipes
Flags change how a command works. For example, `ls` just shows names, but `ls -lah` shows hidden files and readable file sizes. 
A pipe `|` takes the output from the first command and feeds it into the second. `ls -l | head` takes the long list of files and only prints the first few lines.

### Task 2.4 - Understand package managers
Package managers like Homebrew on Mac make it super easy to install, update, or remove software from the terminal. It saves you from downloading random installers from websites.

## 3. Commands / tools used
*   **Terminal (zsh)**: Used to run all the commands on my Mac.
*   **Git**: To stage and commit the work.

## 4. My understanding
The terminal is just a text way to use the computer. Commands like `ls`, `cd`, and `mkdir` do the same things as clicking around in Finder, but faster once you know them. Pipes and flags just let you combine commands and change how they behave.

## 5. Difficulties faced
None really.

## 6. How I resolved them
N/A.

## 7. Evidence / files
*   `mission-02-terminal/README.md` (this file)

## 8. Commit details
Commit message: "Complete Terminal and file management mission". Checked GitHub and it pushed successfully.