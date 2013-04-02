# Evernote Image Extractor.scpt
## by Chris Sauvé of [pxldot](http://pxldot.com)


## Description
This script will run through your Evernote library and save every image and PDF file attached to your notes with a usable name. Extracting these files typically results in unintelligible file names, while this script will save them out using the name of the note to which they were attached (appending numbers to the name in the case of multiple images/ documents attached to the same note). The script will start by asking whether you want to safe images, PDF files, or both, and will them let you select any subset of the notebooks in your Evernote account to run through and, finally, will ask you where you would like to save the extracted files. The script will automatically create a new folder within this directory for every extracted notebook.


## Installation
Download the most recent version of the script. Once you have downloaded the script, navigate to your Application script folder located at `~/Library/Scripts/Applications/Evernote`. Apple hides the Library folder in Mac OS X 10.7 or later by default, so the easiest way to get to this folder is to select the menu item `Go > Go To Folder...` in Finder.app. You may have to manually create an Evernote folder in the `~/Library/Scripts/Applications` directory if you do not have any previous scripts for Evernote (you may have to create more of the folders in the directory; if you don't have an Applications folder or even a Scripts folder, you will have to create those as well).


## Using The Script
Your best bet is simply to open this file in AppleScript Editor, compile it, and run it. Your other option is to run the script from Apple's AppleScript menu. If you don't have a little script icon near the clock in your Mac's menubar, you need to turn this on manually. Open AppleScript Editor.app from your `Applications > Utilities` folder. Go to AppleScript's preferences by selecting `AppleScript Editor > Preferences...` from the menubar. On the "General" pane, you should check the checkbox to "Show Script menu in menu bar". Now, when in Mail.app, select the new script menubar item and you will see the script at the bottom of the list, ready to be clicked and run.


## Version History
- **0.1.0** (April 2, 2013): Initial re-release.


## License
Use it, change it, repackage it, whatever. Try not to take credit for my work.