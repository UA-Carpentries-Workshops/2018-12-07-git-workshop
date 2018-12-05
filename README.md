# 2018-12-07-git-workshop

# Details

__Date__: Dec. 7, 2018

__Time__: 9am to 12pm

__Location__: Drachman Hall A122

# Git installation

## Windows

Download the Git for Windows installer.

Run the installer and follow the steps bellow:

Click on "Next".

Click on "Next".

Click on "Next".

Click on "Next".

Select "Use the Nano editor by default"

Click on "Next".

Ensure that "Use Git from the Windows Command Prompt" is selected. (If you forget to do this gitbash will not work properly, requiring you to remove the GitBash installation, re-run the installer and to select the "Use Git from the Windows Command Prompt" option.)

Click on "Next".

Ensure that "Use the OpenSSL Library" is selected.

Click on "Next".

Ensure that "Checkout Windows-style, commit Unix-style line endings" is selected.

Click on "Next".

Ensure that "Use Windows' default console window" is selected.

Click on "Next".

Ensure that "Enable file system caching" and "Enable Git Credential Manager" are selected.

Click on "Next".

Click on "Install".

Click on "Finish".

If your "HOME" environment variable is not set (or you don't know what this is):

Open command prompt (Open Start Menu then type cmd and press [Enter])

Type the following line into the command prompt window exactly as shown:

```
setx HOME "%USERPROFILE%"
```

Press [Enter], you should see SUCCESS: Specified value was saved.

Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.

## macOS
The default shell in all versions of macOS is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). 

See the Git installation video tutorial for an example on how to open the Terminal. You may want to keep Terminal in your dock for this workshop.

## Linux
The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.
