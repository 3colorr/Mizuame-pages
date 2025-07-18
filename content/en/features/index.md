---
title: "Features"
description: ""
featured_image: "/images/MizuameLogo.png"
menu:
  main:
    weight: 2
---
# Outlines
- Basic
  - [The Note](#thenote)
  - [Pin](#pin)
  - [Making Text Black](#makingtextblack)
  - [Keyboard Shortcuts](#keyboardshortcuts)
- Design
  - [Themes](#themes)
  - [Light/Dark mode](#light/darkmode)
- Note Actions
  - [Calculation](#calculation)
  - [Markdown](#markdown)
- [Others](#others)

# Basic

# theNote
The notes that you type will be saved on your PC. Therefore, you cannot share the notes on your the other PC. Because this app is not a high performance note app.

# Pin
You can fix the note with the pin.  
With this setting, The notes will always be displayed on top of the other windows.

# MakingTextBlack
Depending on the app's theme, the color of the text in the note may be yellow or green, which can be hard to see for some people.  
There are themes where the text color is black, but it's slightly gray. Also, some people may prefer the note's text color to be absolutely gray.  
With this setting, you can ignore the app's theme and change the color of the text in the note to black, dark gray, or normal gray.  

# KeyboardShortcuts
You can open the Mizuame by keyboard shortcuts.  

Initially, keyboard shortcuts are `disabled`. You can select a keyboard shortcut you want to use in the general tab of the settings.  
Next, please add Mizuame to `[Settings] > [Privacy & Security] > [Accessibility]` and grant it accessibility permissions.  
Then, please `restart Mizuame`.  

If you grant Mizuame accessibility permissions, it can detect whether keys are pressed. However, Mizuame never stores history of key inputs, nor does it transmit them over the network.

# Design

# Themes
You can choose a theme.  
For example, "White and Blue", "White and Pink", "Light(Gray) and Mint" and more.
{{< figure src="/Mizuame-pages/images/sample-theme-image-blue.png" title="White and Blue" >}}
{{< figure src="/Mizuame-pages/images/sample-theme-image-pink.png" title="White and Pink" >}}
{{< figure src="/Mizuame-pages/images/sample-theme-image-gray.png" title="Light(Gray) and Mint" >}}

# Light/Dark mode
{{< figure src="/Mizuame-pages/images/sample-light.png" title="Light Mode" >}}
{{< figure src="/Mizuame-pages/images/sample-dark.png" title="Dark Mode" >}}

# Note Actions
Initially, all the Note Actions are disabled.  
You can enable the Note Actions you want to use in the general tab of the settings. Conversely, if you no longer want to use the Note Actions, you can disable them in the general tab.  

# Calculation
The app automatically calculates the formulas you enter in the note.  
However, the formula must be enclosed in `(` and `=)`.  
For example, if you enter `(1+2+3-6=)`, it will automatically calculate as `(1+2+3-6= 0 )`.  
In addition to addition, you can calculate the following formulas:
- 2+3-4+5
- 5*5-25
- 1+2*(3+4)/0.1
- (2+2)^2

By default, numbers are rounded to 3 decimal places. You can specify the number of decimal places to round to within a range of 0 to 9 digits, or all (38 digits). You can change this in the General tab of the settings.

{{< figure src="/Mizuame-pages/images/demo-calculation.gif" title="Automatically calculate the formula enclosed in '(' and '=)'" >}}

If you want to recalculate a formula, you have to delete the calculation result between `=` and `)`. 
For example, If you change the formula from `(1+2+3-6= 0 )` to `(1+2+3-7= 0 )`, it will not be recalculated automatically. In this case, you have to delete `0` and the spaces before and after it like `(1+2+3-7=)`.  
Because, the app consider the string between `=` and `)` as the formula and performs the calculation automatically.  
Also, please note that When automatically calculation is performed, the cursor position move to the end of the note. This is one of the issues with this app. It cannot be resolved immediately, please be patient.

Lastly, not all formulas can be calculated. For example, even if you are working on your math homework and need to calculate the 0.5 power of 0.3, this app cannot calculate it.  
Please use a math textbook, the internet, or a scientific calculator.  

# Markdown
Mizuame supports some Markdown syntax.  
This means that there are supported syntax elements as well as unsupported ones.  

{{< figure src="/Mizuame-pages/images/demo-markdown.gif" title="" >}}

When the "Markdown view feature" is enabled, notes opened from the menu bar are displayed in Markdown view. The Markdown view is for preview purposes only, and you cannot edit the notes in this view.  

To edit a note, either click `"Edit" (the icon with a square and pen) in the menu bar`, or double-click on the margin of the Markdown view.   

{{< figure src="/Mizuame-pages/images/sample-markdown-menu-2.png" title="Edit icon" >}}
{{< figure src="/Mizuame-pages/images/sample-markdown-double-click.png" title="double-click on the margin of the Markdown view" >}}

Once you are finished editing and want to return to Markdown view, click `"Markdown View" (the icon with the letter M) `in the menu bar.  

{{< figure src="/Mizuame-pages/images/sample-markdown-menu-1.png" title="Markdown View icon" >}}

**Supported Markdown syntax**  
You can find the following Markdown syntax in the Help tab under Settings in the Mizuame app.

{{< figure src="/Mizuame-pages/images/header.png" title="Header" >}}
{{< figure src="/Mizuame-pages/images/bold-itaric-codeblock.png" title="Bold, Itaric, Code Block" >}}
{{< figure src="/Mizuame-pages/images/formula.png" title="Formula" >}}
{{< figure src="/Mizuame-pages/images/list.png" title="List" >}}
{{< figure src="/Mizuame-pages/images/ordered-list.png" title="Ordered List" >}}

**Unsupported Markdown syntax**  
- Any syntax not listed under Supported Markdown Syntax.

**Sample**
{{< figure src="/Mizuame-pages/images/sample-markdown-note.png" title="Write with Markdown syntax" >}}

{{< figure src="/Mizuame-pages/images/sample-markdown-view.png" title="Markdown view" >}}

# Others
You can change the font size and size of stiky note from "Settings".
{{< figure src="/Mizuame-pages/images/sample-bar-image.png" title="Pin, Eraser, Printing and Settings" >}}

From the “Hidden menu” (the ellipsis circle icon), you’ll see options for printing, exporting a note, and importing a note.
{{< figure src="/Mizuame-pages/images/hidden-menu.png" title="Hidden menu" >}}

**Export Note**  
This option lets you save the contents of the current note to a file on your Mac.  
When you select Export Note, a save dialog appears—choose any location you like and save the file.  

**Import Note**  
This option lets you load a file that was previously exported with Mizuame’s Export Note feature.  
When you select Import Note, an open-file dialog appears—choose the file you want to import.  

:bulb::bulb::bulb:  
When you import a note, its contents are appended to the end of your current note.  
