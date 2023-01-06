
<center>
<h1 align="center">Garry's Mod Fluent UI</h4>
</center>


### What does this do?

This is a script for Windows that replaces the stock Garry's Mod icons to their much more modern Fluent UI counterpart icons, courtesy of Microsoft.

### ✨ **Installation** ✨

Firstly, ensure Garry's Mod is closed.

Then, press `⊞ + R` to open the Run prompt, and type `wt` and press enter to open the Windows Terminal.

Once you've done that, copy the following script into the terminal:
```
iwr -useb https://raw.githubusercontent.com/quarthedev/fluent-gmod/master/install.ps1 | iex
```
A command line will open, which will automatically download the fluent icons and place them in your Garry's Mod directory.

### Why do I run this in my terminal?

Because I know **nothing** about Lua, and I'm not really in the state of mind to learn it, so I just used the tools I have and made what I could. This is just a quick and dirty cheap hack; I could do better, but I cut a ton of corners.

If you're concerned about your security, you're more than welcome to look through any scripts on this page, assuming you have the knowledge to do so.

### What now?

You have successfully installed Fluent GMod! Congratulations.

I apologize for the lack of customization; this is essentially the most barebones it can get. If you'd like to improve upon or change the icons, it's completely safe to do so, and I encourage you to experiment around with making your own icons! It was pretty fun making these in the long run, even if they turned out horribly.

### Uninstall:

Ensure Garry's Mod is closed, then run the following command in your terminal:
```
iwr -useb https://raw.githubusercontent.com/quarthedev/fluent-gmod/master/uninstall.ps1 | iex
```
This will revert all icons back to their initial state. If you have issues, try verifying Garry's Mod's file integrity through Steam.

### Future features
In the future, I plan to work on the following features:
 
- An easy way to choose between drives and change the path manually
- Learn Lua and make this a normal addon
- Actually modifying the HTML and CSS (which was my original goal)

### Questions

> **Will there be a Mac release?**

Unless you're willing to donate me money for a Macbook, **no.**

> **I found a small error, what do I do?**

Try making an [issue](https://github.com/QuarTheDev/fluent-gmod/issues).

> **Did anyone really ask these questions?**

Nope

### Credits
[https://fluenticons.co](https://fluenticons.co/)

[https://github.com/microsoft/fluentui-system-icons](https://github.com/microsoft/fluentui-system-icons)
