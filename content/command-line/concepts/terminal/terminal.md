---
Title: 'Terminal'
Description: 'A terminal emulator is a program that allows users to run commands that are processed by the computer.'
Subjects:
  - 'Developer Tools'
  - 'Computer Science'
Tags:
  - 'Command Line'
  - 'Bash/Shell'
CatalogContent:
  - 'learn-the-command-line'
  - 'paths/computer-science'
---

A **terminal** is a tool for interacting with a computer using text-based commands. Historically, terminals were hardware devices that output typed commands to a dedicated piece of hardware, such as a screen or paper spool. Modern usage has evolved to **Terminal Emulators**, which are graphical applications offering features like tabbed interfaces and split views. The terms "terminal" and "terminal emulator" are used interchangeably in current development environments. Terminals enable a variety of functions, from running scripts to automating tasks with shell scripts.

The terminal provides an interface to the _shell_, the command-line interface that conveys human input to the operating system. The shell processes commands and returns output, acting as the intermediary between the user and the system's services and files. While some command processors, like PowerShell and Command Prompt, incorporate their own user interface, others, such as the Unix BASH (Bourne Again SHell), are accessed through a terminal emulator.


## Examples of terminals

Terminals come with different features and interfaces based on the system:

- **macOS** has a native app called "Terminal" and also supports iTerm2, a popular alternative.
- **Windows** users typically work with:
  - Command Prompt (CMD), a legacy terminal based on MS-DOS that is available as a shell.
  - PowerShell, which is available as a standalone terminal or as a shell that offers advanced scripting capabilities.
  - Windows Terminal, the modern, multi-tabbed application supporting Command Prompt, PowerShell, and WSL (Windows Subsystem for Linux) shells.
    - WSL, also called Windows Subsystem for Linux, is an emulation layer that allows the use of Unix-based shells such as BASH or ZSH. It can be run within other terminal emulators or as a standalone program. Read more about WSL [here](https://learn.microsoft.com/en-us/windows/wsl/about).
- **Linux** distributions usually provide multiple options which include:
  - GNOME Terminal, default on GNOME desktops.
  - Konsole, default on KDE/Plasma desktops.
  - xterm, is a lightweight terminal for X11 that comes with nearly all Linux distros.
