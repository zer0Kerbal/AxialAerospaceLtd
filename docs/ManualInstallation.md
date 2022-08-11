---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Axial Aerospace Ltd (AAL)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Axial Aerospace Ltd (AAL)

[Home](./index.md)

*It's what we do*

Adds Axial Aerospace Ltd. Agent, Flags, and common config files used in all Axial Aerospace's add-ons for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `AxialAerospace` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/AxialAerospaceLtd`
* Extract the package's `AxialAerospace/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/AxialAerospace` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/AxialAerospaceLtd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/AxialAerospaceLtd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/AxialAerospaceLtd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [AxialAerospace]
        ...
      + [AxialAerospaceLtd]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Localization]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * AxialAerospaceLtd.version
        * changelog.md
        * GPL-2.0.txt
          ManualInstallation.htm
        * readme.htm
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

[AAL]: https://github.com/zer0Kerbal/AxialAerospaceLtd "AxialAerospace Ltd (AA/L)"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
