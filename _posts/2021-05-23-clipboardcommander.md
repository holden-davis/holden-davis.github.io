---
title: ClipboardCommander
author: Holden Davis
date: 2021-05-23
categories: [Project, Program]
tags: [Python, Git, Github, Windows, Application, Desktop]
---

## [ClipboardCommander](https://holden-davis.github.io/ClipboardCommander) is a simple program written in Python that extends the capabilities of the operating system's clipboard.

Clipboard Commander can:
* Display the current contents of the system clipboard
* Copy the current contents of the system clipboard for later use
* Swap previously copied contents into the system clipboard
* Hold multiple entries for later clipboard use

Clipboard Commander is written in Python and uses:
* [tkinter](https://docs.python.org/3/library/tkinter.html) as the basis of the gui
* [ttk](https://docs.python.org/3/library/tkinter.ttk.html#module-tkinter.ttk) as the basis for the gui's widget system
* [pyperclip](https://pypi.org/project/pyperclip/) for the clipboard functionality

This is my first foray into Python, creating useable files, and seeing a project of my own through to completion, so it's undoubtedly _very_ rough around the edges. In addition, there's plenty of further functionality to implement, such as a better gui and Linux compatibility. However, it still functions as is, and that's better than it could be!

|On Startup|With Content|
|:-|:-|
|![Blank](../../assets/img/clipboardcommander/ClipboardCommanderBlank.png)|![WithContent](../../assets/img/clipboardcommander/ClipboardCommanderSwap.png)|
