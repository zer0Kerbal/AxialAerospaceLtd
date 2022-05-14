---
permalink: /ManualInstallation.html
title: ManualInstallation
---

<!-- ManualInstallation.md v1.1.0.0
AxialAerospaceLtd (AA/L)
created: 01 Oct 2019
updated: 02 Mar 2022 -->

<!-- based upon work by Lisias -->

# AxialAerospaceLtd (AA/L)

 Simple plugin to take notes in game for Kerbal Space Program.

A roughly 2/3 scale model of Sierra Nevada Corp's Dream Chaser vertical launch spaceplane with cargo bay and docking nosecone!

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AxialAeroSpace/AxialAerospaceLtd`
* Extract the package's `AxialAerospace/` folder into your KSP's as follows:
  * `<PACKAGE>/AxialAerospace` --> `<KSP_ROOT>/GameData/AxialAeroSpace`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AxialAeroSpace/AxialAerospaceLtd`
* Extract the package's `GameData/` folder into your KSP's as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  [GameData]
    [AxialAerospace]
      [AxialAerospaceLtd]
        [Agencies]
          ...
        [Compatibility]
          ...
        [Localization]
          ...
        #.#.#.#.htm
        changelog.md
        GPLv3.txt
        AxialAerospaceLtd.version
        readme.htm
      ...
  KSP.log
  ...
```

### Dependencies

* none
