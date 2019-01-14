---
title: "Using git in VSCode"
---

This is a short guide on how to use **git** in **Visual Studio Code** (VSCode). The purpose of git is to allow you to easily share your code with collaborators and track the changes each of you make.

1. **Clone repository**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: clone` + write link to repository
2. **Download existing changes**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`
3. **Upload new changes**: 
  
    1. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: commit all`
    2. Write commit message
    3. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`
    
**New repository?:** Create it online at https://github.com/

<p style="font-size: 20px;"><strong>IMPORTANT NOTE</strong>: To avoid merge conflicts always download existing changes, before you make new ones.</p>

### Merge conflicts

*Skip this if you are a first time user of Git*

If you get a **merge conflict**:

1. Resolve conflicts by point-and-click (don't save the file)
2. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: stage all changes`
3. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: commit all`
4. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`
5. Save the file
6. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: commit all`
7. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `git: sync`

**Problems?** You can undo last commit with `git: undo last commit`

**Worst case:** Make a new clone of the repository and redo the changes.