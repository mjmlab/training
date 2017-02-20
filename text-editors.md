# Text Editors

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Text Editors](#text-editors)
	- [Atom](#atom)
	- [Other options](#other-options)

<!-- /TOC -->

In general, there are three options for writing code. A bare-bones terminal editor (`nano`), a text editor that helps you a little with formatting and may have plug-ins with various features (`atom`), or a full-featured integrated development environment (IDE) (`pycharm`). Mark uses `atom` right now and is writing this document so he's going to write about that. But feel free to fill in other info below!!

## Atom

1. Download on [atom.io](https://atom.io).
1. Install.
1. Install shell commands
 - In Atom: Atom menu > Install Shell commands. Then open a new terminal window (Mac).
 - This lets you type the command `atom` from the command line to open Atom. You can type `atom .` to open atom in the current directory (note the space dot ` .` after atom).
1. Integrate with `git`.
 - After installing `git`, set up Atom to be used as the commit editor: In the command line, type:
 ```bash
 git config --global core.editor "atom --wait"
 ```
1. To add any desired plugins, go to Atom menu > Preferences:
  - Settings
  - Install
  - Search for packages. Some to consider are:
    - Markdown Preview
    - markdown-toc
    - git-time-machine

## Other options

It's good to know how to use a terminal-based editor (`nano`, `vi`, etc.) so that when working on a remote computer you can edit files. If you have a favorite text editor feel free to submit a pull request (PR) with key features here!
