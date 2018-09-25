# Visual-Studio-2017-Update-problem
This is a short description on how to handle an update problem on Visual Studio 2017. The problem arises when an update has to execute after the download is complete. An error message occurs: 
Unable to install to target location. Error: The folder c:\program files (x86)\Microsoft Installer or a file within is locked by another program. Close anay program that might be using it and try again.
To fix the problem do this:

1. Rename the folder: C:\Program Files (x86)\Microsoft Visual Studio\Installer like: C:\Program Files (x86)\Microsoft Visual Studio\InstallerX1
2. Run the program: VS_Installer from the renamed folder.

This has been found on Stack Overflow. It is a hotfix and not a permanent solution. The cause of the problem and a permanent fix is not known at this moment.
A screen dump of the error has been added to the project.
