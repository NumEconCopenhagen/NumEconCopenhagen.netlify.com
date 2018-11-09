---
title: "VSCode (git)"
---

This is a short guide on how to use **git** in **Visual Studio Code** (VSCode). The purpose of git is to allow you to easily share your code with collaborators and track the changes each of you make.

1. **Clone repository**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: clone` + write link to repository
2. **Download existing changes**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`
3. **Upload new changes**: 
  
    1. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: commit all`
    2. write commit message
    3. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`
    
**New repository?:** Create it online at https://github.com/

**Skip if first time user:** If you get a **merge conflict**:

1. resolve conflicts by point-and-click (don't save the file)
2. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: stage all changes`
3. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: commit all`
4. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`
5. save the file
6. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: commit all`
7. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`

Problems? You can undo last commit with `git: undo last commit`

To avoid merge conflicts also begin by downloading existing changes.
