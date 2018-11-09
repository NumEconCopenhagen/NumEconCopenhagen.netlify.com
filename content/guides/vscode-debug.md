---
title: "VSCode (debugging)"
---

This is a short guide on how to use the **debugger** in **Visual Studio Code** (VSCode).

1. **Add breakpoint:** <kbd>F9</kbd> (*not on empty line*)
2. **Start:** <kbd>F5</kbd>
3. **Steps:** 

  1. **Into**: <kbd>F11</kbd> (go into functions)
  2. **Over**: <kbd>F10</kbd> (go over functions)  
  3. **Out**: <kbd>Shift</kbd>+<kbd>F11</kbd> (continue until current function is finished)
  
4. **Continue:** <kbd>F5</kbd>
5. **Stop:** <kbd>Shift+F5</kbd>

**Tutorial:**

1. Write the following code

    {{< highlight python "linenos=table" >}}
    def f(a,b):
        a += 2
        b += 2
        g(a,b)

    def g(a,b):
        a += 1
        b += 1

    a = 0
    b = 0

    f(a,b)
    f(a,b)
    f(a,b)
    f(a,b)
    f(a,b)
    print(a,b)
    {{< / highlight >}}

2. Add breakpoint on line 13
3. Start debugger
4. Experiment with stepping into, over and out

**Open debug infomation**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>D</kbd>

**Open debug console**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Y</kbd> (you can write terminal commands here)

**Conditional breakpoint:** Right click on breakpoint (in list or by line number)

**Bonus info:** It also stops at errors.
