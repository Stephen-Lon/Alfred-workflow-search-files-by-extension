# Alfred-workflow-search-files-by-extension
Search for files with a given extension in a given folder (and, optionally, its subfolders)

# Introduction

This workflow enables you to search for files with a given extension in a given folder (and, optionally, its subfolders) and returns them in Alfred. You can choose whether or not to include subfolders in the search.

# Important notes

- The folders from which you initially select to search are limited to specified folders (and any of their subfolders) in your home folder, specifically:

~/Desktop
~/Documents
~/Downloads
~/Movies
~/Music
~/Pictures
~/Public

You could add other folders by extending the `Scope` of the initial file filter but I would strongly recommend *not* adding folders outside your home folders. If you were to do so search times would probably be very long and you would fail to find system file extensions without significant alterations to the workflow.

- If the relevant extension is not found you will see the extension name you typed with no results. You can simply backspace and try another extension (or press `esc` to end the workflow).

# Usage

To run the workflow type `fxt` (or the other keyword you have set in the user configuration). Press `space` and start typing the name of the folder in which you wish to search. When the name appears in the list you can select it and press ⏎. You then have the option to search the selected folder and its subfolders (the default) or to search only in the selected folder. When you have made your choice you will see the search dialog. Type the extension for which you wish to search (*without* the preceding full stop or period) and the result will display.

(*Remember that you may need to scroll down to see all of the results.* In that context you may find it helpful in `System Settings → Appearance` to show scroll bars `Always`—which will help make clear where you are in the list of results when moving through it.)

You can select any file found and press:

- ⏎ to open the file;
- ⌥ + ⏎ to reveal the file in Finder; or
- ⇧ + ⏎ to action the file in Alfred.
