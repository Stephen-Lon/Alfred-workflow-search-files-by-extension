# Alfred-workflow-search-files-by-extension
Search for files with a given extension in a given folder (and, optionally, its subfolders). (This ReadMe is for version 2.0)

# Introduction

This workflow enables you to search for files with a given extension in a given folder (and, optionally, its subfolders) and returns them in Alfred. You can choose whether or not to include subfolders in the search. It can also be used as a Universal Action on a selected folder in Finder.

# Important notes

1. The folders from which you initially select to search (unless you use the Universal Action on a selected folder in Finder) are limited to specified folders (and any of their subfolders) in your home folder, specifically ~/Desktop, ~/Documents, ~/Downloads, ~/Movies, ~/Music, ~/Pictures and ~/Public.

  You could add other folders by extending the `Scope` of the initial file filter but I would strongly recommend *not* adding folders outside your home folders. If you were to do so search times would probably be very long and you would fail to find system file extensions without significant alterations to the workflow.

2. If the relevant extension is not found you will see something like this:

<img width="764" alt="Not found" src="https://github.com/user-attachments/assets/245a9019-bd54-4c68-b374-fbf3e6e1de87">


You can simply backspace and try another extension (or press `esc` to end the workflow).

# Usage

To run the workflow do either of the following:

- Type `fxt` (or the other keyword you have set in the user configuration) and you will see this:

<img width="764" alt="Initial dialog" src="https://github.com/user-attachments/assets/13393fc0-208a-430e-8274-6a85fb2ad194">


Press `space` and start typing the name of the folder in which you wish to search. When the name appears in the list you can select it and press ⏎.

![Set folder](https://github.com/user-attachments/assets/19317236-ae66-440e-aeae-0aed4fcd4cd1)


- Alternatively, select a folder in Finder, press your Universal Actions hotkey and look for `Search files by extension` in the list of action. Press ⏎ when it is selected.


You then have the option to search the selected folder and its subfolders (the default) or to search only in the selected folder so in either case you will then see this:.

![Choose](https://github.com/user-attachments/assets/dac0c3c4-1cf8-4390-ba1c-420249753331)



When you have made your choice you will see the search dialog (shown here after selecting the default option to search including subfolders):

![Search](https://github.com/user-attachments/assets/9109f7ef-a0eb-43a9-8a3e-000024e80902)



Type the extension for which you wish to search (*without* the preceding full stop or period) and the result will display:

![Result](https://github.com/user-attachments/assets/59b47c56-3721-4044-a0c0-ce30e44fb28e)


There are three things to note:

- The results are searchable, as shown in the screenshot.
- If you choose to search *excluding* sub-folders no path is shown for the file. If you *include* sub-folders in your search the path from the principal search folder to the sub-folder is shown.
- Remember that you may need to scroll down to see all of the results. In that context you may find it helpful in `System Settings → Appearance` to show scroll bars `Always`—which will help make clear where you are in the list of results when moving through it.)

You can select any file found and press:

- ⏎ to open the file;
- ⌥⏎ to reveal the file in Finder; or
- ⇧⏎ to action the file in Alfred.
