# Subtitle-Workshop-Classic-v6.0e

Subtitle Editor derived from version 6.0b, but with UTF-8, audio stream selection, VLC support etc. 

### 2019-08-10 (v6.0e/07)

* Tools -> Information and Errors -> Information and Errors: Only errors visible in the error/warning list are handled by the 'Fix Errors' button now.

* The 'no sound' problem reported by Willem52 has been solved (see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/57dbceecc8/?page=0).

* Solved a problem with change of width between sessions when "Smart resize" was on (see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/8b1a0d20ff/).

* Problem with Cyrillic texts solved (see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/8bb900890e/).

* The test for an "Unnecessary Spaces" error between digits has now been limited to just that. 

### 2019-07-26 (v6.0e/06)

* Removed an error in 'text before colon' detection. Digits before the colon are allowed now.

* Removed a problem of losing text in the shown subtitle when it is in bold.

* Solved several problems in subtitles with more than one line.

* Solved a problem with undo and bold tags.

### 2019-07-21 (v6.0e/05)

* The Outline/Shadow problem has been solved.

* The undo problem for multi line subtitles has been solved.

* Removed an error in the SUBSTATIONALPHA read/convert routine.

### 2019-07-14 (v6.0e/04)

* Also the selected audio stream is remembered now (both in projects and non projects), and restored when opening a subtitle or a project. 

* The selected movie is remembered now and restored when loading a subtitle, provided the "AutoSearchMovie" setting is on. 
 
* A problem with the file "LastChoices.txt" (access not allowed) has been solved.

* The WEBVTT subtitle format is supported now.

### 2019-07-01 (v6.0e/03)

* The .ini files holding the video position and the last selected subtitle are removed. The function is still kept in however.

* If there are no audio tracks the audio track menu is disabled now.

* The Greek translation is present now. Thanks to Xenos Latinos, see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/20b5b37fba/#f20e.

* The "SetDelay" has been made more versatile.

### 2019-04-05 (v6.0e/02)

* The (last positions) .ini file is now also created using 'Save As' (thanks Xenos Latinos, see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/ef6797c88b/).

* A new format has been added : the Avid DS Caption format (thanks Xenos Latinos, see https://sourceforge.net/p/subtitle-workshop-classic/discussion/feat/thread/76520698b0/).

* The problem in Tools --> Informations and errors --> Settings Fix tab line "- " on first line not remembered is solved.

### 2019-03-15 (v6.0e/01)

* Added the Croation translation (thanks Abajo, see https://sourceforge.net/p/subtitle-workshop-classic/discussion/general/thread/d4c9e6787c/#2cff).

* Solved the Chinses character problem (thanks GardField, see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/b471b4bf3c/#f7b3).

* Adapted the helpfile.

* Solved a problem with the "Rewind" and "Forward" buttons (2x the required time was stepped).

* The "project" possibility can also be used in non translator mode now.

* When opening a subtitle file the video position and the subtitle selection in the list are restored now (this was already the case with "projects").

* Solved a problem with the 'Save as' screen and big font sizes.

### 2018-11-06 (v6.0d/37)

* Solved a problem with the "Stop" button when using the VLC video renderer.

### 2018-09-11 (v6.0d/36)

* Removed the "double button" error in the main form toolbar (see https://sourceforge.net/p/subtitle-workshop-classic/discussion/bugs/thread/d8863a53/).

### 2018-09-10 (v6.0d/35)

* Removed a crash of the program when checking "Force using regions (may be slow)" in settings --> video preview --> subtitles.

### 2018-09-01 (v6.0d/34)

* Removed a problem with the display of the volume bar with small sizes of the main screen.

### 2018-08-31 (v6.0d/33)

* Removed a problem with the subtitle size in the video preview after using the settings menu.

* The initial language is "English" now.

### 2018-08-23 (v6.0d/32)

* Added double quotes around the parameters for the external player.

* Added an automatic "VIDEO_FILE" to the parameters for the external player (only if parameters is left empty).

### 2018-08-03 (v6.0d/31)

* Made 'Load project" work (translation mode).

* Removed an error in the main ini file location.

### 2018-07-24 (v6.0d/30)

* Removed a font size error in the 'Insert Symbol' screen.

* Correct a small error in the Dutch language file.

* TimedText save can also handle the Single Tags mode now.

### 2018-07-21 (v6.0d/29)

* Supported a deviating dfxp file format (e.g. "tt:br/" in stead of <br/")

### 2018-07-19 (v6.0d/28)

* Made the "Timed Text" format work again. 3 filetypes are associated with that format now:

	xml (timed text xml format) 
	
	ttml (also timed text xml format)
	
	dfxp (Netflix timed text xml format)
	
* The 3rd party software "xmlparser-1.0.20" is no longer needed.	

### 2018-07-15 (v6.0d/25):

* Added 3 extra shortcuts (section Miscellaneous):

	Applies the "Keep minimum duration" setting to the selected subtitles
	
    Applies the "Default Subtitle Pause" setting to the selected subtitles
	
    Applies both the "Keep minimum duration" and the "Default Subtitle Pause" settings to the selected subtitles

* Added an editing possibility for the shortcuts (added to the Settings menu).

    All items in the new section [Edit Shortcuts] were added to the language file
	
	In section [Main menu/Settings] of the language file item 09 was added to the language file
	
	For every language a translation of the shortcut descriptions (including some other info) was added: e.g. Shortcuts_English.txt where 'English' should be replaced by the actual language name. The shortcut translation files are located in the 'Lang' subdir. English and Dutch files are already filled. If a file for a certain language is not found the English one is used.

* Removed an error when switching video renderers.
   
* Removed some errors in the Dutch translation.
	
* Added 'shortcuts.key' (the shortcuts file) to the setup.exe file (was missing).


### 2018-06-10 (v6.0d):

* The versionnumber has been changed from 6.0c to 6.0d because of the addition of the VLC video renderer.

* Added the VLC player as extra renderer (only visible if VLC - the 32 bits version- is installed on your PC). https://www.videolan.org/vlc/download-windows.html

* The Dutch translation has been completed now.

* Added translations for the 'Insert Symbol' window ([Main menu/Edit], values 12, 13 and 14).

* The 'Insert Symbol' window is resizeable now.

* The window 'tools, information and errors' can be maximized now.

### 2018-04-26 (v6.0c):

* File association (Settings, File Types) also works in Windows 10 now.

### 2018-04-06:	

* The font size of the 'Unnecessary Spaces' form is also adapted now to the one of the main form.
	
* Some textboxes have been adapted to cope with longer (translated) texts.

* The 'Font Size' text in 'Settings List' is now the same as in 'Settings Prog'.

* File types (file association) now works as expected.

* The complete French translation has been added (thanks Daneel53).

### 2018-03-29:

* Made read-only subtitle files readable again.

* Made some adaptions for screens with lower resolutions (down-resizing is possible now).

### 2017-12-31:

* Corrected an error reading a.o. SAMI files.

### 2017-11-28:	

* Make spellcheck work again with Word 2016.

### 2017-11-15:

* UTF8 and UTF16 subtitles supported now:

    Adapted also the "Insert Symbol" screen.
	
    UTF8 format is detected automatically.
	
    The "Save as" screen has been adapted to add the possibility to save a subtitle as UTF8.
	
* Detection and selection of more than one audio stream is implemented. 

* Made a number of screens re-size-able:

	The "Settings" screen
 
	The "Output settings" screen and
 
	The "Error and Info" Settings screen.  
 
	The sizes and positions are saved.
  
* The List fontsize is now separated from the Program FontSize

	The separated List font size has been added to the settings menu 
  
* The main menu is made more readable with bigger Program fontsizes. 

	also most screens have been re-arranged for this purpose 
	in some cases the re-size method has been adapted.  

* All screens are made bigger to better cope with high resolution monitors.  
  
* "Setdelay" now shows the time difference between a (stopped) movie time and a selected subtitle time, which is more convenient.  
  
* The file size reported by "Movie Information" is correct now also for files > 4 Gb.  
  
* Added the "m4v" movie format as a valid one.  
  
* Removed a few situations where errors could occur (e.g. doubleclicking on an empty errors list). 

 






