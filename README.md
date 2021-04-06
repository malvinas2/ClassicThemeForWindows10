# Classic Theme for Windows 10
Preview on YouTube: (https://www.youtube.com/watch?v=O97VVly4Cdc)  
  
A visual style which brings back the Classic Theme known from Windows 95 or NT to nowadays Version 10. 
<img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/windows_10_with_classic_theme.png">


## Table of Contents

- [Installation](#installation)
- [Miscellaneous](#miscellaneous)
- [Known Bugs](#known-bugs)

## Installation 
`**Remember**: You need administrator privileges for all steps!` 


### 1. ClassicTheme
Download the [Classic Theme](https://github.com/malvinas2/ClassicThemeForWindows10/releases/) and extract its content to an arbitrary directory. 


### 2. OldNewExplorer
Download and install [OldNewExplorer](https://msfn.org/board/topic/170375-oldnewexplorer-119/), use the settings shown below.  
<img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/OldNewExplorer_settings.png" width=30% height=30%>


### 3. Open-Shell
Download and install [Open-Shell](https://github.com/Open-Shell/Open-Shell-Menu/releases/).  
The ClassicTheme directory created in step 1 contains a folder called `_open-shell`.  
Copy the subfolder `Skins` and its contents to the main directory of Open-Shell (usually `%ProgramFiles%/Open-Shell`).  
Run the configuration program `Open-Shell Menu Settings` and afterwards `Classic Explorer Settings`, use the settings shown below.  

| []() | []() | []() | []() | 
| :----: | :----: | :----: | :----: | 
| <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings0.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings1.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings2.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings3.png" height=200px> | 

| []() | []() | []() | 
| :----: | :----: | :----: | 
| <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings5.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings6.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/Open-Shell_settings7.png" height=200px> | 


### 4. StartIsBack
Download and install [StartIsBack](https://www.startisback.com/#download-tab).  
Copy the content of the `_startisback` folder, located in the ClassicTheme directory, to the main directory of StartIsBack (usually `%ProgramFiles%/StartIsBack`).  
Run the configuration program `StartIsBackCfg.exe`, use the settings shown below. 

| []() | []() | []() | 
| :----: | :----: | :----: | 
| <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/startisback_settings1.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/startisback_settings2.png" height=200px> | <img src="https://github.com/malvinas2/ClassicThemeForWindows10/blob/master/_settings/startisback_settings3.png" height=200px> | 


### 5. UltraUXThemePatcher
UltraUXThemePatcher modifies your system files so that 3. party themes can be used.  
Download and install [UltraUXThemePatcher](http://www.syssel.net/hoefs/software_uxtheme.php?lang=en) and restart your computer.  
No further configuration is necessaary. 


### 6. ClassicTheme
Copy the content of the subfolder corresponding to your Windows version to `C:\Windows\Resources\Themes`.  
E.g. save the content of `/ClassicTheme/Theme For Win10 Fall Creators Update 1709/Show Commandbar` into `C:\Windows\Resources\Themes`.


### 7. Windows settings
- Go into `All Settings > Personalization > Colors`. 
- Under `Choose your default Windows mode`, select `Light`.
- <ins>Un</ins>check `Automatically pick an accent color from my background`. 
- Under `Show accent color on the following surfaces`, <ins>un</ins>select the `Start, taskbar, and action center`, and `Title bars and window borders` check boxes.
- Go into `All Settings > Personalization > Themes` and select the classic theme you want. 


### 8. Thin Borders
Run the REG file within the `_Thin Borders` subfolder of your ClassicTheme direcory.  
It'll ask for confirmation, accept it. The folder also contains another registry script to restore default border size.  
Sign out and sign back in to activate your new window border width. 


## Miscellaneous
In case you miss the classic blue wallpaper try the RGB color code `59-110-165 (3B6EA5)` or `0-128-128 (008080)`.  
If you need for some reason the classic grey tone try RGB color codes `200-205-212 (C8CDD4)` resp. `212-208-200 (D4D0C8)`. 


## Known Bugs
See the [issues section](https://github.com/malvinas2/ClassicThemeForWindows10/issues) for known bugs. 
