<h1 align="center">Colemak Mod-DH Wide Ergonomic Mod Implementation for PKL</h1>

## Table of Contents

[**1. Project Introduction**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#1-project-introduction)  
....[1.1. Overview](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#11-overview)  
....[1.2. Added and Changed Dead Keys](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#12-added-and-changed-dead-keys)  
....[1.3. Credits](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#13-credits)  

[**2. Keyboard Layout Variants**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#2-keyboard-layout-variants)  
....[2.1. ANSI Keyboard (101/104-key American) with an ANSI Enter Key](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#21-ansi-keyboard-101-key-american-with-an-ansi-enter-key)  
....[2.2. ANSI Keyboard (101/104-key American) with an ISO Enter Key](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#22-ansi-keyboard-101-key-american-with-an-iso-enter-key)  
....[2.3. ISO Keyboard (102/105-key European)](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#23-iso-keyboard-102-key-european)

[**3. Installation**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#3-installation)

[**4. Configuration**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#4-configuration)  
....[4.1. PKL Configuration](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#41-pkl-configuration)  
....[4.2. Changing the PKL Icon](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#42-changing-the-pkl-icon)  
....[4.3. Add or Remove Keyboard Layouts](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#43-add-or-remove-keyboard-layouts)  
....[4.4. “ANSI with an ANSI Enter Key” vs “ANSI with an ISO Enter Key”](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#44-ansi-with-an-ansi-enter-key-vs-ansi-with-an-iso-enter-key)

[**5. Extend Layer**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#5-extend-layer)  
....[5.1. Key Mapping](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#51-key-mapping)  

[**6. Additional Directories (Not a Part of PKL)**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#6-additional-directories-not-a-part-of-pkl)  
....[6.1. “Icons” Directory](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#61-icons-directory)  
....[6.2. “Images” Directory](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#62-images-directory)  
....[6.3. “Archives” Directory](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#63-archives-directory)

[**7. Contributions**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#7-contributions)

[**8. Licenses**](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#8-licenses)

## 1. Project Introduction

### 1.1. Overview

<p align="justify">Colemak Mod-DH with Wide ergonomic mod keyboard layout for Portable Keyboard Layout (PKL) software: An ergonomic modification of the original Colemak keyboard layout:</p>

* **Mod-DH:** Places the `D` and `H` keys to more comfortable positions; which applies

* ***Angle:*** `\` `Z` `X` `C` `V` `B` *->* `Z` `X` `C` `D` `V` `\` *(ISO) /* `Z` `X` `C` `V` `B` -> `X` `C` `D` `V` `Z` *(ANSI); and*

* **Wide mod:** Moves the right hand position towards the Enter by one key.

<p align="justify">The project's source files are based on the original works of Øystein Bech “DreymaR” Gadmar. It was first created back in 2017 and now published on GitHub; containing my own implementation of the Mod-DH with Wide ergonomic mod for the Colemak keyboard layout for ISO (102/105-key European) and ANSI (101/104-key American) keyboards. The goal is to provide compatibility between Mod-DH with the original Colemak dead keys (with some additional ones—see them in the next seciton) and the PKL software. An improved version of PKL and Mod-DH Wide mod is available on DreymaR's GitHub.</p>
<p align="justify">The project was originally labeled as “Colemak-CAW” (using DreymaR's original naming convention), but it has been changed to “Colemak Mod-DH Wide” due to very little differences between my own implementation of the ergonomic mod and stevep99's original design.</p>

### 1.2. Added and Changed Dead Keys:

List of changed, and additional dead keys not included in the original Colemak dead keys ([website](https://colemak.com/Multilingual)):

* Added lower curved double quotation mark `„` to AltGr+Shift+\\.

* Changed non-breaking space ` ` to Shift+Space (it is originally on Shift+AltGr+Shift).

### 1.3. Credits:

Project source files are based on the works of Øystein Bech “DreymaR” Gadmar: [GitHub](https://github.com/DreymaR).

Colemak keyboard layout by Shai Coleman: [Website](https://colemak.com).

Colemak Mod-DH and Wide mod documentation by stevep99: [Website](https://colemakmods.github.io/mod-dh/).

PKL software by Máté Farkas: [Website](http://pkl.sourceforge.net).

## 2. Keyboard Layout Variants

The different positions of the `Z`, `\`, and `’` keys are highlighted in light red color.

### 2.1. ANSI Keyboard (101/104-key American) with an ANSI Enter Key

![ANSI keyboard with an ANSI Enter key layout image](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/KBlayout_base-ansi-ansi-enter.png)

### 2.2. ANSI Keyboard (101/104-key American) with an ISO Enter Key

![ANSI keyboard with an ISO Enter key layout image](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/KBlayout_base-ansi-iso-enter.png)

### 2.3. ISO Keyboard (102/105-key European)

![ISO (102-key) keyboard layout image](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/KBlayout_base-iso-102-key.png)

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)

## 3. Installation

<p align="justify">Portable Keyboard Layout (PKL) is a portable software by default, meaning that it doesn't need to be installed on your machine and it doesn't require administrator privileges to run.</p>

1. Download the whole repository by clicking on the **Clone or download** button then selecting **Download ZIP**.

2. Save the .zip file (`Colemak_Mod-DH-Wide_PKL-master.zip`) anywhere to your computer then extract it.

3. Double click on **pkl.exe** to run the software.\*

<p align="left"><em>* PKL will automatically activate the pre-defined keyboard layout (from <code>pkl.ini</code>) after launching. Use the</em> <em><strong>left Shift + right CTRL</strong> key combination to suspend it (deactivate the software without closing it). Alternatively, click on the keyboard layout’s icon</em> <img src="https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/pkl-icon_on.png" /> <em>on your taskbar. If you see a red crossed out circle over the icon</em> <img src="https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/pkl-icon_off.png" /> <em>it means that PKL is currently suspended.</em></p>

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)

## 4. Configuration

### 4.1. PKL Configuration

<p align="justify">PKL is configurable by modifying the settings in the <code>pkl.ini</code> file under the <code>[pkl]</code> section. The different options are described below.</p>

| Settings |  |  |  |
| --- | --- | --- | --- |
| ***Option*** | ***Category*** | ***Values*** | ***Description*** |
| `changeLayoutHotkey` | Hotkeys | Multiple* | Switch between keyboard layouts. |
| `changeNonASCIIMode` | Hotkeys | Multiple* | Change input mode for non-ASCII characters. The original input mode may not work with some programs. |
| `displayHelpImageHotkey` | Hotkeys | Multiple* | Toggle the display of help images.** |
| `exitAppHotkey` | Hotkeys | Multiple* | Close PKL in the background. |
| `altGrEqualsAltCtrl` | Keyboard layout | `yes`/`true`/`1`, `no`/`false`/`0` | If enabled, PKL detects AltGr as Ctrl+Alt. It's useful for keyboards that do not come with an AltGr key. The useage of this option is not recommended, because some programs know the difference between AltGr and Ctrl+Alt. |
| `layout` | Keyboard layout | Multiple: See `layouts` directory | Set a keyboard layout or multiple layouts to load upon launching PKL. Use the `changeLayoutHotkey` hotkey to cycle through the keyboard layouts. |
| `compactMode` | Software | `yes`/`true`/`1`, `no`/`false`/`0` | Every external files are placed in the root directory. |
| `displayHelpImage` | Software | `yes`/`true`/`1`, `no`/`false`/`0` | Display help images by default.** |
| `exitTimeOut` | Software | 0..99 | Number of minutes of inactivity after PKL closes in the background. |
| `language` | Software | Multiple: See `languages` directory | Set a display language for PKL. |
| `startsInSuspendMode` | Software | `yes`/`true`/`1`, `no`/`false`/`0` | Start PKL in suspended mode. |
| `suspendTimeOut` | Software | 0..99 | Number of minutes of inactivity after PKL goes into suspended mode. |
| `systemsDeadkeys` | Software | Multiple* | If your original (Windows) keyboard layout has dead keys, then define then here. |

\* *See the AutoHotkey documentation for further information ([link](https://autohotkey.com/docs/KeyList.htm)).*  
\*\* *This feature won't work, because help images are currently unavailable in this project.*

Some settings are also accessible by right clicking on the PKL icon ![PKL on icon](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/pkl-icon_on.png):

* **About:** Displays some information about the current active keyboard layout.

* **Display help image:** Toggles the display of help images.

* **Detect deadkeys:** Assists with detecting dead keys from the Windows keyboard layout. This option is useful if your dead keys do not work as expected.

* **Layouts:** Opens a sub-menu to switch between keyborad layouts. You can alternatively also use hotkeys (it's defined at `changeLayoutHotkey` in the `pkl.ini` file) to cycle through all available keyboard layouts.

* **Change layout:** Does the same as the hotkey to switch to a different keyboard layout.

* **Suspend:** Suspends PKL.

* **Exit:** Quits PKL.

### 4.2. Changing the PKL Icon

<p align="justify">PKL doesn't have any icon file of its own. The icon that is displayed on your taskbar is basically your keyboard's layout icon that is located in its directory. Different icons can be used for different keyboard layouts. To change the taskbar icon of PKL, copy the desired .ico files from the <code>icons</code> directory and place them into the directory of your keyboard layout (e.g., <code>layouts/Colemak_Mod-DH-Wide_(ISO)</code>). See <a href="https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#1-icons-directory">6.1. “Icons” Directory</a> below for further information on the icon files.</p>

### 4.3. Add or Remove Keyboard Layouts

<p align="justify">PKL is configured to load all 3 types of keyboard layouts upon software launch by default (see <code>layout</code> option in <code>pkl.ini</code>). If you want PKL to only load one keyboard layout or you want to add more layouts, then do the following:</p>

1. Close PKL or make sure it's not running.

2. Open `pkl.ini`.

3. Go to and edit the line with `layout =` under `Keyboard layout`.

4. Delete any keyboard layout names you do not wish to use. If you want to add more layouts, make sure to separate the layouts with a comma without space (e.g.,`KB-layout-1,KB-layout-2`).

5. Launch PKL.

### 4.4. “ANSI with an ANSI Enter Key” vs “ANSI with an ISO Enter Key”

<p align="justify">Refer to <a href="https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#2-ansi-101-key-american-with-an-ansi-enter-key">2.2 ANSI Keyboard (101/104-key American) with an ANSI Enter Key<a/> and <a href="https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#3-ansi-101-key-american-with-an-iso-enter-key">2.3 ANSI Keyboard (101/104-key American) with an ISO Enter Key</a> to see the difference between the 2 keyboard variants.

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)

## 5. Extend Layer

<p align="justify">PKL provides an extend layer that may be used for key binds with additional functionality. Key binds of the extend layer are configured in <code>pkl.ini</code>, while the key that activates the layer is defined in the <code>layout.ini</code> file (e.g., <code>layouts/Colemak_Mod-DH-Wide_(ISO)/layout.ini</code>).</p>

### 5.1. Key Mapping

![Extend layer key map](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/KBlayout_extend-layer.png)

<p align="justify">The <code>Z</code>, <code>\</code>, and <code>’</code> keys do not have any function mapped to them because these keys move around on the keyboard variants. Therefore the functions shown in the image are static across all 3 variants.</p>

| Legends |  |  |
| :---: | :---: | :--- |
| ***Keys*** | ***Category*** | ***Description*** |
| ![Ctrl shortcuts](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_ctrl-shortcuts.png) | Ctrl shortcuts | <p>Select all, Cut, Copy, Paste</p><p>Find, Save, Undo, Redo</p>
| ![F1 key](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_f-function-1.png) .. ![F12 key](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_f-function-12.png) | F* function keys | F1 to F12  |
| ![Miscellaneous keys](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_misc.png) | Miscellaneous | <p>Activate the Extend Layer (Caps Lock)</p><br><p>Escape, Insert, Ctrl+Break</p> <p>Bookmarks (web browser), Print Screen</p> |
| ![Modifier keys](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_modifier.png) | Modifiers | Ctrl, Shift, Alt |
| ![Multimedia keys](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_multimedia.png) | Multimedia | </p>Mute, Volume Down, Volume Up, Open Media Player</p><p>Play, Previous, Next, Pause/Stop</p> |
| ![Navigation keys](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_navigation.png) | Navigation | <p>Scroll Down, Scroll Up, Go Back, Go Forward</p><p>Left, Down, Up, Right</p></p>Page Up, Page Down</p>
| ![Text editing keys](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_text-editing.png) | Text Editing | <p>Caps Lock, Tab, Home, End</p><p>Delete, Backspace, Enter</p>
| ![Unmapped keys](https://raw.githubusercontent.com/szabog/Colemak_Mod-DH-Wide_PKL/master/images/extend-layer_unmapped.png) | Unmapped keys | Keys without any functions mapped to them. |

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)

## 6. Additional Directories (Not a Part of PKL)

<p align="justify">These directories are not part of the original Portable Keyboard Layout project, therefore the PKL software won't scan these directories for configuration files.</p>

### 6.1. “Icons” Directory

<p align="justify">This directory was created to store the keyboard layout's icon files for PKL. The icons currently come in a white and black color schemes located under the <code>icons/white</code> and <code>icons/black</code> directories. The icons were created using Paint.NET, the project files are located in the <code>icons/Paint.NET project files</code> directory.</p>

<p align="justify">PKL is capable of switching its icon on the taskbar depending on whether it's active or suspended. <code>on.ico</code> is displayed when the software is active, while <code>off.ico</code> is displayed when it's suspended. Switching between the taskbar icons is automatically handled by PKL. Different keyboard layouts can have different “active” or “suspended” icons, but they must be placed into the their respective layout's folder where the <code>layout.ini</code> file is located (e.g., <code>layouts/Colemak_Mod-DH-Wide_(ISO)</code>).</p>

### 6.2. “Images” Directory

<p align="justify">This directory houses the images and their source files that are part of <code>ReadMe.md</code>. They were created using Keyboard Layout Editor (<a href="http://keyboard-layout-editor.com">website</a>).</p>

### 6.3. “Archives” Directory

This directory was created to preserve older, now obsolete keyboard layout configurations.

* **15/06/2019:** `pkl_LeftNav_ISO.ini` and `pkl_LeftNav_ANSI.ini` are PKL configuration files (`pkl.ini`). They contain the word “LeftNAV” in them, because the cursor navigation was performed by the left hand instead of the right on the Extend layer. Reason: To promote more keyboard focused and less mouse centric workflow.

* **11/07/2019:** `layouts_Colemak-CAW+extd_ISO.ini` and `layouts_Colemak-CAW+extd_ANSI.ini` are PKL keyboard layout configuration files (`layout.ini`). These layout files contained all of DreymaR's dead key mappings (as of 2017). I reverted the dead keys back to the original ones of Colemak ([website](https://colemak.com/Multilingual)). Reason: Easier maintenance and portability to other platforms.

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)

## 7. Contributions

<p align="justify">Contributions are currently not being accepted, because I'm the sole maintainer of the project and it's supposed to reflect my own ideas on this implementation of the Mod-DH Wide ergonomic mod for the Colemak keyboard layout. This stance of mine may be changed in the future.</p>

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)

## 8. Licenses

<p align="justify">The original Portable Keyboard Layout software <code>pkl.exe</code> is licened under GNU General Public License v3.0 (it says v2.0 in some places), published by Máté Farkas at http://pkl.sourceforge.net/ (see <code>license.txt</code> for license notice and <code>gpl-3.0.txt</code> for a copy of the license text). The software source code is not included in this project, for that contact the publisher or go to https://github.com/Portable-Keyboard-Layout/Portable-Keyboard-Layout.

<p align="justify">The original license (and the source files themselves) are missing of <code>pkl.ini</code> (https://github.com/DreymaR/BigBagKbdTrixPKL/blob/master/pkl_ANSI-CurlAngleWide.ini) and <code>layout.ini</code> (https://github.com/DreymaR/BigBagKbdTrixPKL/blob/master/layouts/colemak-eD_ISO-CurlAWide-Sl/layout.ini.).

Source files of this project are licensed as follows:

* `pkl.ini`: BSD 2-Clause License.

* `archives\layouts_Colemak-CAW+extd_ANSI.ini`: Public Domain.

* `archives\layouts_Colemak-CAW+extd_ISO.ini`: Public Domain.

* `archives\pkl_LeftNav_ANSI.ini`: Unlicensed.

* `archives\pkl_LeftNav_ISO.ini`: Unlicensed.

* All files contained under `icons`: Unlicensed.

* All files contained under `images`: Unlicensed.

* All files contained under `languages`: Unlicensed. They are part of the original PKL project.

* All files contained under `layouts` with the exception of `*.ico`: BSD 2-Clause License.

:arrow_up: [Back to Top](https://github.com/szabog/Colemak_Mod-DH-Wide_PKL#table-of-contents)
