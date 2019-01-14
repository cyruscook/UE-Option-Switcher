# UE-Option-Switcher
A more user friendly alternative to dropdown menus written entirely in Blueprints. It is inspired by what games like Fortnite use, except has expanded on their functionality.

Named an option switcher because I've never seen any other name for it, and it reminds me of widget switchers.

![Example Gif](https://i.imgur.com/Hh7WgiG.gif)

## How to use
Place both the arrow_icon.uasset and OptionSwitcher.uasset anywhere in your projects content directory. You will then be able to place the option switcher widget into any widget blueprint by navigating to the "User Created" section of the Palette.

![Palette Image](https://i.imgur.com/eiq46p8.png)

You can edit all the default values of the option switcher simply by clicking on it and looking in the "Details" window. The Option Switcher also shares many functions to the Dropdown menu (such as "Set Options", "Get Selected Option" and "Add Option"). This makes it very easy to replace any dropdown menus you are using at the moment with Option Switchers - there's no need to rewrite the logic behind it, only change the functions to the option switchers.

![Function Example](https://i.imgur.com/3IymHRM.png)

The Option Switcher doesn't just inherit many of the Dropdown Menu's functions but expands upon them, offering functions such as "Set Selected Option Num".

Sadly custom widgets don't support the very easy way of creating events from the Details panel through a one click button. However, what you can do is the following:

![Event Dispatcher On Value Changed Example](https://i.imgur.com/AIIZ0Gm.png)

What you want to do is on the parent widget's construct bind an event of your choice to the "OnValueChanged" event dispatcher of the Option Switcher.
