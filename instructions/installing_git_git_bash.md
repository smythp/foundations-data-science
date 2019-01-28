*Adapted from the [DHRI Curriculum install instructions](https://github.com/DHRI-Curriculum/install/blob/master/sections/git.md).*

# Install Git

Git is a distributed version control system used to manage changes to files and folders. It keeps track of a root folder, called a "repository," and allows a user to revert to earlier versions of a project, pull in changes made by others, and compare versions of a project.

## Mac OS

On Mac OS, git is part of the xcode command line tools. To install them:

1\. Open the Mac OS terminal by clicking the spotlight search button (the magnifying glass) on the top right of your screen, then entering the search term `terminal` on the text box that pops up.  
2\. Type the following in the terminal:

```bash
xcode-select --install
```

3. Close the terminal by typing `exit`, then click the red close button. Reopen the terminal using the instructions above. Test that Git is now available by typing this command:

```bash
git --version
```

If you see a version number, Git has been successfully installed and you're prepared for the lesson.

## Windows

As part of installing git, install the gitbash command line environment so that the command line is consistent across Windows, OSX and Linux.

1. Download git for windows:
https://git-scm.com/download/win

2. *Click* on the git installer:

![git installation icon, looks like a tree branch inside 4 colored squares](../images/windows/git/git00.png)

3. Accept the license and *click* `Next`:

 ![license acceptance window](../images/windows/git/git01.png)

4. Select the installation folder, default is fine. *Click* `Next`:

![installation folder browser with text window showing folder path](../images/windows/git/git02.png)

5. Select the components to be installed, the default is fine: 

![list of check boxes showing install options: additional icons, on the desktop, Windows Explorer integration, Git Bash, Git GUI, Git LFS, Associate *.git configuration files with the default text editor, associate .sh files to be run with bash,  use a true type font in all console windows, check daily for git for windows, check daily for git console updates](../images/windows/git/git03.png)

Select start menu folder (default is fine):

![textbox with browse button listing start menu folder options](../images/windows/git/git04.png)

6. Choose the default editor used by Git. Select `Visual Studio Code` as the default editor. *Click* `Next`:

![installation menu containing drop down of editor options: nano, vim, notepad++, visual studio code, visual studio code insiders](../images/windows/git/git06.png)

7. Choose the "Use Git from the Windows Command Prompt" radio button and then *click* `Next`:

![three radio buttons: use git from git bash, use git from windows command prompt, use git and optional unix tools from the windows command prompt](../images/windows/git/git07.png) 

9. Choose the HTTPS transport backend (the default is fine). *Click* `Next`: 

![list of radio button optionsL 1) use the OpenSSL library, 2) use the native windows secure channel library](../images/windows/git/git08.png)

10. Configure the line ending conversions (the default is fine). *Click* `Next`:

![list of radio button options: 1) checkout Windows-style, commit unix-style , 2) checkout is as is, commit is unix style, 3)checkout as is, commit is as is](../images/windows/git/git09.png)

11. On the 'configuring the terminal emulator to use with Git Bash' window, choose the "Use Windows default console window" option. *Note: Do not choose "Use MinTTY (the default terminal of MSYS2)" as that MinTTY wil break Python.*

![two radio buttons: 1) Use MinTTY, 2) use Windows default console window](../images/windows/git/git10.png)



12. Configure the extra options (the defaults are fine). *Click* `Next`:

![check boxes: 1) enable file system caching, 2) enable git credential manager, 3) enable symbolic links](../images/windows/git/git11.png)

13. VSCode should now be installing:
 
 ![image of progress bar](../images/windows/git/git12.png)

14. *Click* through the rest of the install, leaving the defaults, and then *click* `Finish` on the last window: 

![final installation window that says "completing the git setup wizard"](../images/windows/git/git13.png)

15\. Test the installation. First, open the Windows command line by opening the Start menu (bottom left on desktop by default) and typing:

    cmd
	
Once you're in the command line, type the following:

    git --version
	
If you see a version number, Git is installed in the Windows command line.

To check that Git Bash is installed, open the Start menu again and type:

    git bash
	
Select Git Bash from the menu. If a command line environment opens and you see a prompt with a `$`, Git Bash has been installed successfully.
