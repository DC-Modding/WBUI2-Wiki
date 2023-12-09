## WBUI2 Changelog

### v1.15

- Added user editable button to open the UI (PC only)
- Improved Update logic
- Improved Radial logic

### v1.14

- Fixed not beeing able to invite to tribe

### v1.13

- Fixed that the mod wont work in singleplayer (probably)
- Fixed playerview going wild after closing the UI when using controllers
- Fixed that no icon is displayed if multiple mods/buffs add to the radial menue
- Info text now shows a "square" or "cross" button on consoles

### v1.12

- Cross-Platform Release

### v1.11

- Fixed that the UI now scales properly with the screensize
- Adjusted the UI so the background image is now truly a 16:9 ratio
- Added an `Update` button to the Admin menue which triggers an update like `cheat scriptcommand WBUI2 update`
- Fixed `UpdateInterval` only running once

### v1.10

- Improved buff logic
- Added controller support
- UI can now be opened via radial menue
	- This is only enabled if you're playing on a console or you play actively with a gamepad
- Added Admin menue to set a `JsonURL` and enable `Debug-Mode`
	- The URL in the Admin menue overrides the URL in the INI
	- If you want to go back to the URL set in INI, click in the textbox of the Admin menue, delete everything in it and save

### v1.9

- Removed icon background. You can leave the `iconURL` empty now if you wish to only have the text visible
- Changed Buff start logic
- Added Version-Check

### v1.8

- Fixed mouse cursor beeing locked within the window
- Fixed clientside infinite loop if server could not retrieve a valid JSON

### v1.7

- Scrolling through the UI shouldnt affect the player (switching between FPV/TPV) anymore
- Added new Scriptcommand to toggle DebugMode
-- cheat Scriptcommand WBUI2 debug
- Changed the Textstyles to a bigger fontsize
- You can use ARKML now to colorize the text  
	- <RichColor Color=\"1,0,0,1\">Red Text</>  
	- you HAVE to unescape the double quotes with a \  

### v1.6

- Fixed spacing between text
- removed obsolet code
- added "Check your Browser" notification if you clicked on a link button

### v1.5

- Added colored text
	- <TextStyle.Red>Red text</>
	- Available colors: Red, Green, Blue, Yellow, Orange, Violet, Black, White
- Added Json settings
	- IconPosition: 0/1/2/3 (Default:0) - Set the position of the Icon.
		- 0=Top Left, 1=Top Right, 2=Bottom Right, 3=Bottom Left.
	- IconTextColor: 0/1/2/3/4/5/6/7/8 (Default: 0) - Sets the color of the "F1 For Info" text.
		- 0=Light Blue, 1=Red, 2=Green, 3=Blue, 4=Yellow, 5=Orange, 6=Violet, 7=Black, 8=White
- Improved download background image logic
- On update via cheat scriptcommand WBUI2 update the UI shouldnt open the for the players anymore.
- Added a Wiki https://github.com/DC-Modding/WBUI2-Wiki/wiki

### v1.4

- Disabled INI Settings "UseIni=" and "SettingsJson=" because INI parsing a Json was not possible in the first place.
- Fixed stuck UI if you switched a tab and hit "ESC"
- Added more detailed logging to investigate request issues

### v1.3

- Readded custom image functionality
- Changed "lorem ipsum" text with a more informative text
- adjusted background opacity for the other styles so it matches style "1"
- added visualisation for a selected tab
- added new JSON setting:
-- DisableIconText: true/false (Default:false) - If true the text "F1 for Info" will not be displayed.

### v1.2

- Disabled downloading of the images (will hopefully be re-implemented later)


### v1.1

- Added Logging for the INI settings
- Fixed defaults beeing not set
- Fixed OpenOnStartOnlyNewPlayers not working


### v1.0

- Initial Automatic Mod Upload
