# Leveling Guide - Patch Notes

### Heist League

* Current state of level and zone are saved based on build
  * Restarting the tool will not reset state
  * Changing builds will go to the state for that build
* Added On-Death key
  * Useful for taking a screen shot or saving a video steam after dying
  * Could also be used to rage quite

#### Minor improvements

* Gem setups now appear one level before becoming available to make planning easier
* [Discord](https://discord.gg/fzHj3BT) Channel was created to answer questions and share builds
* Vulkan now works better
* Added community builds

### Harvest League

* Added settings menu
  * All settings can now be modified graphically or with INI file
* Added a build planner
  * All of your gems can be set up for each major level milestone
  * Builds are stored in different folders so you can switch between different builds
* Colors are now configurable
* All hotkeys are now configurable
* Syndicate and Incursion cheatsheets are available

#### Minor improvements

* Images were moved to one place to take up less space
* Script was split into multiple files to make it easier to update
* Script now checks Autohotkey version
* Script now correctly accounts for DPI differences in large res screens

### Delirium League

* Added the ability to color notes and guides
  * Only supports Red / Green / Blue for now
* Added user contributed "ShortNotes" folder
  * Contains step by step instructions to make it to maps
* Added the ability to show experience penalty instead of gain

#### Minor improvements

* Improved auto hiding feature
* Cleaned up unused code and fixed some bugs
* Added a warning before deleting large Client.txt files

### Metamorph League

* Added the ability to track your desired gem links while leveling (Alt+g)
  * Automatically updates with your level
* Added the ability to set the folder you want to read your notes from
  * This allows you to have multiple different builds in different folders and just select the folder in the config file
* Removed Map names since they can be different teirs in Metamorph, now you just select a tier for level information
  * Still no support for Map notes, but I'm not sure if I will leave maps in next league, it depends on how Conquerer's feels

### Blight League

* Added Passive Tree overlay
* Allowed per Zone notes
* Added Crafting Recipes to notes
* Now auto hides the overlay after a configurable time (can be disabled)
* Now tracks level and experience automatically
* Calculates how many levels over the optimal level you are for a given zone
* Added 3.8 Maps and tiers for calculating experience during mapping (notes disabled for now)

#### Minor improvements

* Added non-mandatory zones
* Improved word wrapping
* Exp starts hidden with everything else
* The skill tree can now be a png file
* Moved skill tree hotkey to Alt+f so it is closer to the left hand
* Improved tree sizing

### Legion League

* Takes zone layout images and displays them on top of the screen
* Shows leveling notes on GEMs to take and Passives to pick up
* Allows manual notes per Act
* Automatically switches zones

#### Bugs

* Fixed a bug where the application was stealling focus making it hard to Cyclone
* Fixed a bug where the overlay would show up for any dialogue and not just zone changes
* Fixed a bug where the Note width was being used for the Guide width