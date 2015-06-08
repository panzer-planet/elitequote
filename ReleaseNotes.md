a strike through denotes that the improvement has been completed

### In ELITE QUOTE 0.2 (Released) ###

  1. ~~Now displays price including VAT~~
  1. ~~Now uses JTextFields for better functionality, look and feel.~~
  1. ~~Other sustainability and usability changes~~


### In ELITE QUOTE 0.3 (Released) ###

  1. ~~Now writes a quote to HTML~~
  1. ~~some logical fixes~~
  1. ~~ROUNDS TOTALS TO 2 DECIMALS!!!~~

### In ELITE QUOTE 0.4 (Released) ###

  1. ~~Further improvment to rounding of numbers~~
  1. ~~Further improvement of look and functionality of quote~~
  1. ~~Ability to enter custom company name and have it saved to file and loaded on program   start - scrapped till 0.5 (heavy mission)~~
  1. Ability to enter custom mark up and VAT - scrapped till saving to file is possible
  1. ~~Make Quote button moved to menubar~~
  1. ~~Clear button added~~
  1. ~~Added an icon for the program to use~~
  1. ~~Added user friendliness including:~~
  * ~~Quote's can't be generated without first calculating~~
  * Successful canceling when generating quotes -scrapped till later version
  * ~~Help and about menu~~

### In ELITE QUOTE 0.5 (Released) ###

There was also a 0.5a which fixed some important problem.

  1. ~~Ability to enter custom company name and have it saved to file and loaded on program   start~~
  1. ~~Some bug fixes I cant remember now~~
  1. ~~Ability to enter custom mark up and VAT (not from file)~~
  1. ~~Ability to read from data files to load saved information - further delayed~~
  1. Ability to e-mail quotes straight from the program - further delayed
  1. Ability to create printer friendly quote and to print - further delayed
  1. ~~The Ability to extensively customize the quote - further delayed~~
  1. ~~Ability to customize company profile - redundant and scrapped~~

### In ELITE QUOTE 0.6 (Released) ###
  1. ~~Ability to read from data files to load saved information~~ (Finally Complete)
  1. ~~Selecting different CSS files for different quote styles~~
  1. ~~Changing heading of quote and other settings through options window~~

### In ELITE QUOTE 0.6.1 (Done) ###

  1. ~~Clean up source code and spot problems and errors~~
  1. ~~Fix problems and make code more readable and practical~~
  1. ~~Options frame needs cosmetic fixes~~
  1. ~~Fixed a problem where clicking cancel on the options frame will not show the text file when re-opening it~~
  1. ~~Fixed a major problem where program would have to be restarted before using new settings~~

### In ELITE QUOTE 0.7 (Released) ###

This version will turn Elite Quote into an apparently OSX Native application since it seems
my small user base are mostly OSX users. I considered re-writing the application in
objective-C and Cocoa but I don't think there's any point as I'm far more comfortable with
and experienced in swing.

  1. ~~Menu Bar moved to apple menu bar~~
  1. ~~Application name appears correctly under OSX as Elite Quote and not PriceCalculator(The name of the main Class)~~
  1. ~~Icon appears on Dock~~
  1. ~~Program released in a .dmg~~
  1. ~~JAR Packaged as .app~~

### In ELITE QUOTE 0.8 ###

  1. Ability to e-mail quotes straight from the program
  1. Ability to create printer friendly quote(CSSless Quote)
  1. When creating the quote a JFrame appears with detailed settings
  1. OptionPanes need icons manually specified
  1. In OSX Keyboard shortcuts don't work when a TextField is selected
  1. In OSX a service error occurs creating performance issues
```

__CFServiceControllerBeginPBSLoadForLocalizations timed out while talking to pbs
```
# Quotes must be able to be saved to any directory. Saving in pwd results in quotes being saved inside .app package