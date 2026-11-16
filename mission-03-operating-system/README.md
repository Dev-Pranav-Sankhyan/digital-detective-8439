# Mission 3 - Understand the operating system

## 1. Task / objective
Explore the operating system, running processes, storage, file paths, permissions, and explain what the OS actually does.

## 2. Work completed
Checked my Mac's system info, looked at running processes, compared absolute vs relative paths, and filled out the OS responsibilities table.

### Task 3.1 Explore your operating system
| Information explored | What it tells you | Your observation (privacy-safe) |
| :--- | :--- | :--- |
| Operating system / system details | The OS running the machine | macOS |
| Current account identity | Who is logged in | [redacted] |
| Available and used storage | Hard drive space left | Roughly 200GB used out of 512GB on SSD |
| System activity snapshot | How hard the CPU/RAM is working | CPU mostly idle, spikes when opening apps |

### Task 3.2 - Understand processes
* **What is a process?** It's basically a program or app that is currently running.
* **What is a PID?** Process Identifier. It's a unique ID number the computer gives to every running app.
* **Examples:** VS Code and WindowServer.

### Task 3.3 - Understand paths and permissions
* **Absolute path:** The full address starting from the very root of the computer (e.g., `/Users/[redacted]/digital-detective/mission-03-operating-system`).
* **Relative path:** The shortcut address starting from where you currently are (e.g., `../mission-02-terminal`).
* **Permissions:** `r` means you can read/open the file, `w` means you can write/edit it, and `x` means you can execute/run it.

### Task 3.4 Explain operating-system responsibilities
| OS responsibility | Your explanation | Example |
| :--- | :--- | :--- |
| Process management | Deciding which open app gets CPU time | Running Spotify and a browser at the same time |
| Memory management | Handing out RAM to apps that need it | Giving a game enough memory so it doesn't lag |
| Device management | Controlling plugged-in hardware | Recognizing my mouse when I plug it in |
| File management | Keeping track of where stuff is saved | Putting files into folders on the SSD |
| User interface / shell | Giving you a visual way to use the computer | The Mac desktop or the Terminal screen |
| Security and permissions | Stopping unauthorized access | Needing a password to log into my account |

## 3. Commands / tools used
*   **Terminal**: Used `pwd` and `cd` to test paths, and `top` to view processes.
*   **Git**: To commit the files.

## 4. My understanding
The OS is the manager for the whole computer. It handles all the boring stuff in the background—like giving memory to apps, managing files, and keeping things secure—so we can just click and run programs without worrying about the hardware.

## 5. Difficulties faced
None. Checked the Mac activity monitor and terminal, pretty easy.

## 6. How I resolved them
N/A.

## 7. Evidence / files
*   `mission-03-operating-system/README.md` (this file)

## 8. Commit details
Commit message: "Document operating system and file management". Pushed to GitHub.