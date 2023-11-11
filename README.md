## WBUI2 Changelog

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
