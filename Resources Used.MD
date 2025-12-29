# 📚 Resources Used  
- [Ben's github](https://github.com/Ben-Sicat)  
- [Markdown Guide](https://www.markdownguide.org/)
- [Resource ](Link)  

## 🍎 Official Apple Terminal Resources

* [Terminal User Guide](https://support.apple.com/guide/terminal/welcome/mac) — The official manual for the Terminal app interface and settings.
* [Shell Scripting Primer](https://developer.apple.com/library/archive/documentation/OpenSource/Conceptual/ShellScripting/Introduction/Introduction.html) — Apple's technical guide to the command line environment and automation.
* [SS64 Mac Command Reference](https://ss64.com/mac/) — The most reliable, searchable online index for macOS Terminal commands and their flags.
* **On-Device Shortcut:** Type `x-man-page://<command>` in Safari (e.g., `x-man-page://git`) to open a clean, readable manual window directly on your Mac.
* **CLI Manual:** Run `man <command>` in your Terminal to view the documentation locally.

## 🍎 macOS Git Setup & Resources

### Initial Configuration
Before using Git on macOS, run these commands to install the necessary tools and link your credentials to the Mac Keychain:

* `xcode-select --install` — Installs Apple's Command Line Tools (required for Git).
* `git config --global credential.helper osxkeychain` — Tells Git to remember your passwords using your Mac's secure Keychain.

### Official & Mac-Specific Git    Resources
* [Apple Developer: Source Control Management](https://developer.apple.com/documentation/xcode/source-control-management) — Official guide on using Git within the Apple ecosystem and Xcode.
* [GitHub: macOS Keychain Guide](https://docs.github.com/en/get-started/git-basics/updating-credentials-from-the-macos-keychain) — Detailed instructions for managing Git security and tokens on Mac.
* [Git Official Reference Manual](https://git-scm.com/docs) — The complete web-based manual for every Git command.
* [Pro Git Book (macOS Setup Guide)](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) — The "Bible" of Git, featuring a deep dive into macOS configuration.

### Local Documentation
To view the technical manual for your specific version of Git without leaving the terminal, run:
`man git`

> **Navigation Tip:** In the `man` viewer, use **Spacebar** to scroll and press **q** to quit.