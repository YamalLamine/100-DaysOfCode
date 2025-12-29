# 🚀 Mac Terminal Quick Start

## 1. Navigation Basics
* `pwd` — **Print Working Directory:** Shows exactly where you are.
* `ls -G` — **List Files:** Shows files in your current folder (the `-G` adds color).
* `cd <folder name>` — **Change Directory:** Moves you into a folder.
* `cd ..` — **Go Back:** Moves you up one folder level.

## 2. File Management
* `mkdir <name>` — Create a new folder.
* `touch <filename>` — Create a new blank file.
* `open .` — Open your current terminal folder in the macOS Finder (very useful!).

## 3. The macOS Power Moves
* `pbcopy < filename.txt` — Copy the text inside a file to your Mac's clipboard.
* `pbpaste > filename.txt` — Paste your clipboard content into a new file.
* `caffeinate` — Prevents your Mac from sleeping (useful for long downloads). Press `Ctrl + C` to stop.
* `say "Hello world"` — Makes your Mac speak the text you type.

> **Tip:** Use the `Tab` key to autocomplete folder and file names while typing!

## 🧹 macOS .DS_Store Cleanup & Prevention

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