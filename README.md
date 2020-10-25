
# GITS 
### GIT Simplified

![GitHub](https://img.shields.io/github/license/harshitpatel96/GITS)
[![Build Status](https://travis-ci.com/harshitpatel96/GITS.svg?branch=master)](https://travis-ci.com/harshitpatel96/GITS)
[![codecov](https://codecov.io/gh/harshitpatel96/GITS/branch/master/graph/badge.svg?token=G6RG52G2YO)](https://codecov.io/gh/harshitpatel96/GITS/)
![YouTube Video Views](https://img.shields.io/youtube/views/6Y8_RQecnZ8?style=social)

[![DOI](https://zenodo.org/badge/295480790.svg)](https://zenodo.org/badge/latestdoi/295480790)

![GitHub issues](https://img.shields.io/github/issues/harshitpatel96/GITS)
![GitHub closed issues](https://img.shields.io/github/issues-closed/harshitpatel96/GITS)

[![](https://img.youtube.com/vi/6Y8_RQecnZ8/hqdefault.jpg)](https://youtu.be/6Y8_RQecnZ8 "GITS demo")

# About GITS
GITS streamlines most frequently performed workflows using fewer commands which is so much easier and better than usual.
Git-Simplified AKA GITS can be thought of wrapper around major Git functionalities.

# Installation for Linux
1. Clone GITS Repo
2. From the root directory run the following command
    ```
    pip install -r requirements.txt
    ```
3. Go to configurations directory and run the following command
    ```
    bash project_init.sh
    ```
   
# Installation for Windows
1. Clone GITS Repo
2. From the root directory run the following command
    ```
    pip install -r requirements.txt
    ```
3. Currently, this project cannot be run on Windows. You need to make use of WSL to work on this project in Windows 
although this fix would only work for systems running Windows 10. If you are using another version of Windows, using a 
virtual machine might be preferred.

    Please refer this link to enable WSL : https://docs.microsoft.com/en-us/windows/wsl/install-win10

# How to Contribute?
Please take a look at our CONTRIBUTING.md where we provide instructions on contributing to the repo and help us in enhancing the current video conferencing platforms.

# Documentation
## Functionalities Implemented
1. [gits pr_update](https://github.com/harshitpatel96/GITS/blob/master/docs/pr_update.md)
2. [gits profile](https://github.com/harshitpatel96/GITS/blob/master/docs/profile.md)
3. [gits rebase](https://github.com/harshitpatel96/GITS/blob/master/docs/rebase.md)
4. [gits reset](https://github.com/harshitpatel96/GITS/blob/master/docs/reset.md)
5. [gits upstream](https://github.com/harshitpatel96/GITS/blob/master/docs/upstream.md)
6. [gits super reset](https://github.com/harshitpatel96/GITS/blob/master/docs/super_reset.md)
7. [gits add](https://github.com/harshitpatel96/GITS/blob/master/docs/add.md)
8. [gits commit](https://github.com/harshitpatel96/GITS/blob/master/docs/commit.md)
9. [gits create_branch](https://github.com/harshitpatel96/GITS/blob/master/docs/create_branch.md)
10. [gits logging](https://github.com/harshitpatel96/GITS/blob/master/docs/logging.md)
11. [gits undo](https://github.com/harshitpatel96/GITS/blob/master/docs/undo.md)
12. [gits untrack](https://github.com/harshitpatel96/GITS/blob/master/docs/untrack.md)
13. [gits track](https://github.com/harshitpatel96/GITS/blob/master/docs/track.md)
14. [gits delete](https://github.com/harshitpatel96/GITS/blob/master/docs/delete.md)
15. [gits sync](https://github.com/harshitpatel96/GITS/blob/master/docs/sync.md)
## Pydoc implementation
We have tried to write as much documentation as possible. You can use pydoc to go through the documentation. 
For example if you want to go through all the documentation for all files in code/ directory, do the following: 

`cd code`<br>
`python3 -m pydoc -b `

This will open up a browser and you can see all the files. You can click on a particular file to access the 
documentation associated with that file.

This repository is made for CSC 510 Software Engineering Course at NC State University.


