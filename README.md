# Alfred-workflow-search-files-by-extension
Search for files with a given extension in a given folder (and, optionally, its first level subfolders).

# Introduction

This workflow enables you to search for files with a given extension in a given folder (and, optionally, its first level subfolders) and returns them in Alfred. You can choose whether or not to include subfolders in the search. It can also be used as a Universal Action on a selected folder in Finder.

# Important notes

1. The folders from which you initially select to search (unless you use the Universal Action on a selected folder in Finder) are limited to specified folders (and any of their subfolders) in your home folder, specifically:

	~/Desktop, ~/Documents, ~/Downloads, ~/Movies, ~/Music, ~/Pictures and ~/Public  

	You could add other folders by extending the `Scope` of the initial file filter but I would strongly recommend *not* adding folders outside your home folders. If you were to do so search times would probably be very long and you would fail to find system file extensions without significant alterations to the workflow.

2. The extension search is case insensitive (i.e. it will find both upper and lower case versions of the given extension). 

3. If the relevant extension is not found you will see something like this:

![Error](https://github.com/user-attachments/assets/56ade17f-6668-488e-811f-2de5237eef02)


As indicated simply press `esc` to end the workflow.

# Usage

To run the workflow do either of the following:

1. Type `fxt` (or the other keyword you have set in the user configuration) and you will see this:

![Search files by extension](Images/Initial dialog.png)

Press `space` and start typing the name of the folder in which you wish to search. When the name appears in the list you can select it and press <kbd>⏎</kbd>.

![Set folder](https://github.com/user-attachments/assets/bfca5a1e-e01f-4d4d-a8c3-d9cc8c659b0c)


2. Alternatively, select a folder in Finder, press your Universal Actions hotkey and look for `Search files by extension` in the list of action. Press <kbd>⏎</kbd> when it is selected.


In either case you then have the option to search the selected folder and its first level subfolders (the default) or to search only in the selected folder and you will see this:.

![Choose](https://github.com/user-attachments/assets/09dd5798-d70a-4c58-b459-108c2d76f5c8)


When you have made your choice you will see the search dialog:

![Search](https://github.com/user-attachments/assets/6801751f-7956-4712-a991-fede1fe0c543)


Type the extension for which you wish to search (*without* the preceding full stop or period) and the result will display:

<img width="764" alt="Result" src="https://github.com/user-attachments/assets/7d4ddda6-5a28-43cb-8fd0-38ebc026586b">


There are three things to note:

- The results are searchable, as shown in the screenshot.
- If you choose to search *excluding* sub-folders no path is shown for the file. If you *include* sub-folders in your search the path from the principal search folder to the sub-folder is shown.
- Remember that you may need to scroll down to see all of the results. In that context you may find it helpful in `System Settings → Appearance` to show scroll bars `Always`—which will help make clear where you are in the list of results when moving through it.)

You can select any file found and press:

- <kbd>⏎</kbd> to open the file;
- <kbd>⌥</kbd><kbd>⏎</kbd> to reveal the file in Finder; or
- <kbd>⇧</kbd><kbd>⏎</kbd> to action the file in Alfred.
