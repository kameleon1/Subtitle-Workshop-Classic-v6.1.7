# Subtitle-Workshop-Classic-v6.0d

Subtitle Editor derived from version 6.0b, but with UTF-8, audio stream selection, VLC support etc. 

### 2018-07-24 (v6.0d/30)

* Removed a font size error in the 'Insert Symbol' screen.

* Correct a small error in the Dutch language file.

* TimedText save can also handle the Single Tags mode now.

### 2018-07-21 (v6.0d/29)

* Supported a deviating dfxp file format (e.g. "tt:br/" in stead of "br/")

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

* Added the VLC player as extra renderer (only visible if VLC - the 32 bits version- is installed on your PC).

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

 






