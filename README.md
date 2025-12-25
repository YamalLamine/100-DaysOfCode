# 🚀 100 Days of Code – My Journey  

![100 Days of Code](https://img.shields.io/badge/100DaysOfCode-Challenge-blue)  

## 📅 Start Date: 28/12/2025 (Ben's cakeday) | ~~24/02/2025~~   
## 💻 Goal: Become a developer by coding every day for 100 days  

---

## 📜 Rules  
1. Code for at least **34 minutes** every day. It's MY magic number, why do YOU care?
2. Push progress to GitHub daily.  
3. Tweet progress using `#100DaysOfCode` (Optional).  
4. Build projects and improve problem-solving skills.  

---

## 📆 Log  

| Day | Progress | Notes |
|-----|---------|-------|
| 1   | ... | ... | 
| 2   | ... | ... |
| 3   | ... | ... |
| 4   | ... | ... |
| 5   | ... | ... |
| 6   | ... | ... |
| 7   | ... | ... |
| 8   | ... | ... |
| 9   | ... | ... |
| 10  | ... | ... |
| ... | ... | ... |
| 100 | 🎉 Completed the challenge! | Reflection |

| ... | ... | ... |
| DAY BREAK | ... | ... |

Old Log:

| Day | Progress | Notes |
|-----|---------|-------|
| 1   | Miniscule | 11 pm and i just hovered through Java and JavaScript on W3schools | 
| 2   | Nada | I took a break |
| 3 | Nada | Tired as hell |
| 4 | Miniscule, again | Read some appdev ppt |

---

## 💡 Projects & Challenges  
### 📌 Main Projects  
- [Project 1 : Make HTML CSS website] - Description: Learn the basic HTML and CSS structure.
- [Project 2 : Make rock paper scissor game] - Description: Create a rock, paper, scissor game website that counts score and has 3 buttons for rock paper scissor
- [Project 3 : TicTacToe Game] - Description: TicTacToe game.
- [Project 4 : Personal Website] - Description: Start my portfolio website.
- [Project 5 : Blog Website] - Description: (up to me)

### 💻 Coding Challenges  
- [Challenge Source (e.g., LeetCode, CodeWars)] 
- [Challenge no AI! STRICTLY! Only if reasonably needed.] 
- [Anything on the internet or I can think of.]

---

## 📚 Resources Used  
- [Ben's github](https://github.com/Ben-Sicat)  
- [Markdown Guide](https://www.markdownguide.org/)
- [Resource ](Link)  

### 🍎 Official Apple Terminal Resources

* [Terminal User Guide](https://support.apple.com/guide/terminal/welcome/mac) — The official manual for the Terminal app interface and settings.
* [Shell Scripting Primer](https://developer.apple.com/library/archive/documentation/OpenSource/Conceptual/ShellScripting/Introduction/Introduction.html) — Apple's technical guide to the command line environment and automation.
* [Manual (man) Pages Reference](https://developer.apple.com/library/archive/documentation/System/Conceptual/ManPages_iPhoneOS/index.html) — A web-based index of the documentation built into every macOS command.

### 🍎 macOS Git Setup & Resources

#### Initial Configuration
Before using Git on macOS, run these commands to install the necessary tools and link your credentials to the Mac Keychain:

* `xcode-select --install` — Installs Apple's Command Line Tools (required for Git).
* `git config --global credential.helper osxkeychain` — Tells Git to remember your passwords using your Mac's secure Keychain.

#### Official & Mac-Specific Git    Resources
* [Apple Developer: Source Control Management](https://developer.apple.com/documentation/xcode/source-control-management) — Official guide on using Git within the Apple ecosystem and Xcode.
* [GitHub: macOS Keychain Guide](https://docs.github.com/en/get-started/git-basics/updating-credentials-from-the-macos-keychain) — Detailed instructions for managing Git security and tokens on Mac.
* [Git Official Reference Manual](https://git-scm.com/docs) — The complete web-based manual for every Git command.
* [Pro Git Book (macOS Setup Guide)](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) — The "Bible" of Git, featuring a deep dive into macOS configuration.

#### Local Documentation
To view the technical manual for your specific version of Git without leaving the terminal, run:
`man git`

> **Navigation Tip:** In the `man` viewer, use **Spacebar** to scroll and press **q** to quit.

---
## 🚀 Mac Terminal Quick Start

### 1. Navigation Basics
* `pwd` — **Print Working Directory:** Shows exactly where you are.
* `ls -G` — **List Files:** Shows files in your current folder (the `-G` adds color).
* `cd <folder name>` — **Change Directory:** Moves you into a folder.
* `cd ..` — **Go Back:** Moves you up one folder level.

### 2. File Management
* `mkdir <name>` — Create a new folder.
* `touch <filename>` — Create a new blank file.
* `open .` — Open your current terminal folder in the macOS Finder (very useful!).

### 3. The macOS Power Moves
* `pbcopy < filename.txt` — Copy the text inside a file to your Mac's clipboard.
* `pbpaste > filename.txt` — Paste your clipboard content into a new file.
* `caffeinate` — Prevents your Mac from sleeping (useful for long downloads). Press `Ctrl + C` to stop.
* `say "Hello world"` — Makes your Mac speak the text you type.

> **Tip:** Use the `Tab` key to autocomplete folder and file names while typing!

### 🧹 macOS .DS_Store Cleanup & Prevention

Run these commands in your Terminal to remove existing hidden system files from your GitHub repository and prevent them from ever being tracked again.

```bash
# 1. Remove .DS_Store from your current GitHub Repo
# (Removes from Git tracking without deleting the files from your Mac)
find . -name .DS_Store -print0 | xargs -0 git rm --cached -f
git commit -m "Remove .DS_Store files from repository"
git push -u origin main

# 2. Prevent it Permanently (Global Gitignore)
# (Creates a global rule so these files are ignored in all future projects)
echo ".DS_Store" >> ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```
---

## 🎯 Goals & Reflections  
### Short-Term Goals  
- [ ] Improve problem-solving  
- [ ] Learn [Web Dev]  
- [ ] Build a full project  
- [ ] Learn how to code without AI
- [ ] Don't be afraid of work being dirty, BUT;
- [ ] Always do things in <mark>BEST PRACTICES</mark> after learning from mistakes.
- [x] Time will pass, so I might as well do this 🤷;
- [x] plus, I get to learn something.
- [x] Be smart af;
- [x] But more importantly, DON'T give up;
- [x] Keep chipping away at the problem;
- [x] Slowly, and I'll get there;
- [x] And... **Learn by doing!**
- [ ] ...
- [x] ...



### Final Reflections (To be filled at the end)  

---

## 🌟 Connect With Me  
📌 GitHub: [YamalLamine](https://github.com/YamalLamine)  



Git Basics:
- git init
- git add .
- git commit -m "init"
- git remote add origin https://github.com/YamalLamine/100-DaysOfCode.git
- git push -u origin main   


___


## I owe ben coffee after finishing dis...

### bih bih bih
### There's so much to learn and what I'm curious about. I'm happy
