### Description

This file contains a list of mods for the xnyu-debug-studio. The application checks this file to receive information about download location and version to determine if something changed.

### Add a new mod

If you want to add your mod to the list, feel free to make a pull request. After a code review, your mod may be added to the list.

### Syntax

- mods: The parent tag which contains all mods
- mod: The specific mod in the list
- name: Name of the mod. This name should be static, even if the version has changed. Otherwise the client cant detect if there is an update available.
- version: The latest version of the mod. This can be an arbitrary value in the format 1.0.0 and should increase in some way after an update
- link: A link to the .ZIP file of the build
