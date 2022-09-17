# Quest for Glory IV (CD version) - Bugfix patch
This is a small, unofficial bugfix patch for Quest for Glory IV: Shadows of Darkness (CD Version).

It provides some additional fixes to AshLancer's [QFG4-Enhanced](https://github.com/AshLancer/QFG4-Enhanced) patch v1.1a.

## Fixes included
Squidstone Arc:
* Fixed all crashes when walking up, down or sliding on the slippery pathway
* Fixed a crash when throwing stones at the bonzai or trying to pick it up

Jester's Inn room:
* Fixed a bug changing the hero's speed to max after sitting on the chair

## How to install

1. Backup the PATCHES folder in your QFG4 directory. An easy way to do this is to rename the folder to something like PATCHES_BAK.

2. Download the [latest release](https://github.com/h3rmit-git/QFG4-Fixes/releases) of the patch.

3. Extract the contents of the zip to the PATCHES folder in your QFG4 directory. Always overwrite when prompted.

4. Open your RESOURCES.CFG configuration file in your QFG4 folder with Notepad and ensure that the patches folder is included in the ``patchDir`` variable. The patchDir variable is a semicolor-separated list of folders, either absolute or relative.
   
   E.g. 
   
   ``patchDir=.\;.\patches``
   
 ## How to uninstall

To uninstall, restore your old PATCHES folder to your QFG4 directory.
