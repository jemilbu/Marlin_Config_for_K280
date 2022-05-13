# Marlin_Config_for_K280
## Created by: Jacob Milburn (Fall 2021/Spring 2022)

Configuration files for Sunderland Innovation Lab's HE3D printer

### Install the software to work with the firmware
To modify the firmware of the Delta style printer for the first time, follow the steps below to get started (modified from [the official Marlin documentation](https://github.com/MarlinFirmware/MarlinDocumentation/blob/master/_basics/auto_build_marlin.md)).
1. [Install Python](https://www.python.org/getit/)
    - Make sure to include Python on the path
2. [Install Git](https://git-scm.com/downloads)
    - Leave everything at the default options
4. [Install VS Code](https://code.visualstudio.com/Download)
5. Open the Extensions tab on the left side of the VScode UI
6. Search for PlatformIO and download
7. Let PlatformIO finish installing completely and fix any errors it issues
8. Search the Extensions for Marlin
9. Install AutoBuildMarlin
10. Open the Version Control tab on the left side of the VSCode UI
    - [See this link for images of this process](https://code.visualstudio.com/Docs/editor/versioncontrol#_cloning-a-repository)
12. Click Clone Repo
13. Use the HTTPs link in the upper right-hand corner of this page to connect to this repo
14. Open a new Git terminal by:
    1. Clicking on the terminal window at the bottom of the VS code UI
    2. Clicking the large plus button on the right side of the terminal window
    3. Selecting the Git bash option
15. Configure your name and email by entering the following lines where John Doe is your name and johndoe@example.com is your email address associated with your Github account
    - ```$ git config --global user.name "John Doe"```
    - ```$ git config --global user.email johndoe@example.com```

**You have now configured your computer to work with the firmware!**

Before you [push any changes to the remote repo](https://zeroesandones.medium.com/how-to-commit-and-push-your-changes-to-your-github-repository-in-vscode-77a7a3d7dd02), make sure that the current configuration you are working on is not broken.

If you want to push your changes to the remote repo when the configuration is broken, look up how to make a branch in Git to keep your changes separate from the reliable version. 

### How to Edit the Configuration
To edit the configuration of the printer, browse to ```Marlin_Config_for_K280\Marlin-2.0.9.2\Marlin``` and modify the Configuration.h and the Configuation_adv.h files. 
Make sure to research what changes to make as these parameters can have a damaging impact on the printer if not set up properly. 

### How to upload changes to the printer
Once you have made changes to the configuration and would like to push the changes to the printer, follow the steps below:
1. Open the AutoBuild Marlin extension tab
2. Verify that you are in the Marlin 2.0.9.2 Folder (or whatever version is currently applicable)
3. Click the "Build" button for the mega2560
4. Verify that the build is successful; solve issues if not (this can take up to a minute)
5. Plug in the printer
6. Connect to the printer via the blue USB cord
7. Click the "Upload" button for the mega2560
8. Verify that the firmware has been uploaded and then reset the machine using the reset button on the bottom of the display board


### Contact Information
If you have any questions about this process, please contact me at (620) 899-8028 or thisoldemail.9605@yahoo.com (current as of 5/13/2022).
