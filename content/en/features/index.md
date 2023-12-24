---
title: "Features"
description: ""
featured_image: "/images/demo-gif.gif"
menu:
  main:
    weight: 2
---
# Outlines
- Basic
  - [A Note](#thenote)
  - [Pin](#pin)
  - [Making Text Black](#makingtextblack)
- Design
  - [Themes](#themes)
  - [Light/Dark mode](#light/darkmode)
- Note Actions
  - [Calculation](#calculation)
- [Othres](#othres)

# Basic

# theNote
The notes that you type will be saved on your PC. Therefore, you cannot share the notes on your the other PC. Because this app is not a high performance note app.
{{< figure src="/Mizuame-pages/images/demo-gif.gif" title="Auto-save every time you type." >}}

# Pin
You can fix the note with the pin.
{{< figure src="/Mizuame-pages/images/demo-un-pin.gif" title="By default, the note closes." >}}
{{< figure src="/Mizuame-pages/images/demo-pin.gif" title="If the pin is enabled, the note not close." >}}

# MakingTextBlack
Depending on the app's theme, the color of the text in the note may be yellow or green, which can be hard to see for some people.  
There are themes where the text color is black, but it's slightly gray. Also, some people may prefer the note's text color to be absolutely gray.  
With this setting, you can ignore the app's theme and change the color of the text in the note to black, dark gray, or normal gray.  

# Design

# Themes
You can choose a theme.  
For example, "White and Blue", "White and Yellow", "White and Pink" and more.
{{< figure src="/Mizuame-pages/images/sample-theme-image-blue.png" title="White and Blue" >}}
{{< figure src="/Mizuame-pages/images/sample-theme-image-yellow.png" title="White and Yellow" >}}
{{< figure src="/Mizuame-pages/images/sample-theme-image-pink.png" title="White and Pink" >}}

# Light/Dark mode
{{< figure src="/Mizuame-pages/images/sample-light.png" title="Light Mode" >}}
{{< figure src="/Mizuame-pages/images/sample-dark.png" title="Dark Mode" >}}

# Note Actions
Initially, all the Note Actions are disabled.  
You can enable the Note Actions you want to use in the general tab of the settings. Conversely, if you no longer want to use the Note Actions, you can disable them in the general tab.  

# Calculation
The app automatically calculates the formulas you enter in the note.  
However, the formula must be enclosed in `(` and `=)`.  
For example, if you enter `very difficult (1+2+3=)`, it will automatically calculate as `very difficult (1+2+3= 6 )`.  
In addition to addition, you can calculate the following formulas:
- 2+3-4+5
- 5*5-25
- 1+2*(3+4)/0.1
- (2+2)^2

If you want to recalculate a formula, you have to delete the calculation result between `=` and `)`. 
For example, If you change the formula from `very difficult (1+2+3= 6 )` to `very difficult (1+2*10= 6 )`, it will not be recalculated automatically. In this case, you have to delete `6` and the spaces before and after it like `very difficult (1+2*10=)`.  
Because, the app consider the string between `=` and `)` as the formula and performs the calculation automatically.  

However, not all formulas can be calculated. For example, even if you are working on your math homework and need to calculate the 0.5 power of 0.3, this app cannot calculate it.  
Please use a math textbook, the internet, or a scientific calculator.  

# Others
You can change the font size and size of stiky note from "Settings". I don't know if it's a feature you need, but you can also "Printing".  
{{< figure src="/Mizuame-pages/images/sample-bar-image.png" title="Pin, Eraser, Printing and Settings" >}}
