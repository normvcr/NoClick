# NoClick
Drag, Left, Right and Double Click the mouse using only mouse movement -- no physical clicking.

## Introduction
NoClick allows the user to Drag, Left, Right and Double Click the mouse using only mouse movement -- no physical clicking is necessary.  When the mouse stops moving, four *click panes* appear, corresponding to *Drag*, *Left*, *Right* and *DoubleClick*.  When the mouse is placed into one of the click panes, the corresponding mouse action occurs where the mouse originally stopped.

NoClick has been used on Linux and Windows.  


## Source code
The source code for NoClick resides on the umbrella repository [Projects](https://github.com/normvcr/Projects), where the entire Proejects source may be obtained.

Alternatively, the NoClick-specific source code may be obtained, as follows:

1. Do this only the first time cloning into the
[Projects](https://github.com/normvcr/Projects)
repository.

Add **--sparse** to the Projects clone command
>   git clone --sparse https://github.com/normvcr/Projects.git

2. Change to the Projects folder
>   cd Projects

3. Restrict sparse checkout to folders (not to cherry-pick files)
>   git sparse-checkout init --cone

4. Get the NoClick source code with the supplied Bourne script
>   checkoutNoClick

The advantage of this approach, is that projcts may be separately downloaded as convenient, but still reside within a common repository, thus avoiding redundant copies of common source code.

## Installation
NoClick is built on top of the [BLDEV](https://github.com/normvcr/BLDEV) project, whose source code was also obtained in the previous section.  If BLDEV is not already installed on your machine, please follow the BLDEV installation instructions[BLDEV](https://github.com/normvcr/BLDEV)/BUILDINIG.md .  The Clang/LLVM libraries are *required* to build NoClick -- this is an option in the BLDEV installation.


The **Building.md** file describes how to install NoClick.

The document, **NoClickUserManual.pdf** reviews the usage of NoClcik.

## License
NoClick is distributed under the MIT license.  The folder *Attributions* contains licenses and acknwledgements for 3rd party code, which, themselves, may have conditions distinct from the NoClick distribution license.  Notably, the QT license is LGPL.
