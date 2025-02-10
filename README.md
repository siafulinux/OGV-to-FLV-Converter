Nautilus Ogv to Flv Converter script v.1.4 (ffmpeg edition)
-----------------------------------------------------------

A frontend for converting ogg, ogv, asf, mp4 and even other flv files to flv format made 	
initially for gtk-recordmydesktop. Should work just fine for all .ogg/.ogv formats.		
												
Code "compiled" by Jean-Claude, Oct 2008 - https://wiki.ubuntu.com/JeanClaude 		
This code is licensed under the General Public License as released by the 			
Free Software	Foundation. You may use, modify and distribute as long as you use		
the GPL2 or later version. 			

<img src='https://github.com/siafulinux/OGV-to-FLV-Converter/blob/main/OGV%20to%20FLV%20Converter.png'></img>
											
This program is distributed in the hope that it will be useful,				
but WITHOUT ANY WARRANTY; without even the implied warranty of				
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the					
GNU General Public License for more details.							
											
About
-----

I had originally put this together to convert recordmydesktop's ogv files into flash for easy web upload / conversion. I have seen this be very useful to a lot of people and am pleased to release the ffmpeg edition, version 1.4. I have also added some high def resolutions and placed a section in the script to easily update user settings which is useful for converting multiple files without having to change the settings on each conversion.

See http://recordmydesktop.sourceforge.net for more on recordmydesktop.

Demonstration at http://www.youtube.com/watch?v=ChgTqsZM6UM - Outdated!



License
-------

Code put together by Jean-Claude, Oct 2008 - https://wiki.ubuntu.com/JeanClaude
This code is licensed under the General Public License as released by the Free Software Foundation. You may use, modify and distribute as long as you use the GPL2 or later version.

This script is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.


Installation
------------

I've attempted to make the installation really simple for new users. Double click on the "install" file. Select "Run" if prompted. This should copy the script over to the appropriate directory and make it executable. If this fails...

Copy the 'Ogv to Flv Converter' file to your "/home/username/.gnome2/nautilus-scripts" folder and make sure it is executable. Right click over the file and select "Properties" -> "Permissions" and select the checkbox "Allow executing file as program" or "chmod +x filename" from a terminal.


Known Issues
------------

- Cancel buttons do work, but when selecting settings, one must click cancel on each window before the script stops.

- The resulting file has two extensions; filename.ogv.flv for example.


Contact
-------

Please let me know if you've used this script and how it's working out for you and if you experince any problems on gnome-look.org at the project page, http://gnome-look.org/content/show.php/Ogv+to+Flv+Converter?content=90837. No promises that I'll be able to get back to you, but at least I can try to look at the issue.

https://wiki.ubuntu.com/JeanClaude



Changelog:
----------

10/19/2010:

- Changed from mencoder to ffmpeg for conversions.
- Added two high def options including HD720 and HD1080.
- Changed the default resolution from 320x240 to 800x600.
- Changed the default video bitrate from 300 to 1024.

05/11/2010:

Added direct conversion to flash without the need of a temporary AVI file. Thanks to n3mo for the original code that I made minor modifications to.



04/21/2009:

I had begun work on this on 12/07/2008. I dropped it for a number of months until I got some feedback indicating this may be useful to some.

- Added support for .asf and .mp4 files. Formats my digital camera uses.
- Attempted to improve video quality of converted files.
- Added a default conversion option for quick conversion and a "select your own options" option to better customize your video. Options include video resolution / aspect ratio and video as well as audio bitrates.



10/07/2008:

- When installing mencoder for you, the script should detect if it did not succeed. After installing, script will continue without further prompts, unless the above error is detected or entire script completes.
- If one selects the wrong file format, you should now get an error.
- Added a simple install script.
- Changed version number from 0.1 to 1.0.
- Added readme.txt :-)



10/30/2008:

- Fixed problem with Ubuntu 8.10 (Intrepid) where it would incorrectly determine file type and prevent conversion. Thanks to Edwin for feedback on this issue.



11/16/2008:

- Added size selection box with the following options: 320x240, 640x480, 800x600, 1027x768. Thanks to Robin for the original code. Moved to provide for "file format error" prompt before asking for size though.
- Added flash conversion support due to some apparent differences in flash formats or methods of encoding. Also if one wishes to resize a flash file.



04/21/2009:

I had begun work on this on 12/07/2008. I dropped it for a number of months until I got some feedback indicating this may be useful to some.

- Added support for .asf and .mp4 files. Formats my digital camera uses.
- Attempted to improve video quality of converted files.
- Added a default conversion option for quick conversion and a "select your own options" option to better customize your video. Options include video resolution / aspect ratio and video as well as audio bitrates.



10/07/2008:

- When installing mencoder for you, the script should detect if it did not succeed. After installing, script will continue without further prompts, unless the above error is detected or entire script completes.
- If one selects the wrong file format, you should now get an error.
- Added a simple install script.
- Changed version number from 0.1 to 1.0.
- Added readme.txt :-)



10/30/2008:

- Fixed problem with Ubuntu 8.10 (Intrepid) where it would incorrectly determine file type and prevent conversion. Thanks to Edwin for feedback on this issue.



11/16/2008:

- Added size selection box with the following options: 320x240, 640x480, 800x600, 1027x768. Thanks to Robin for the original code. Moved to provide for "file format error" prompt before asking for size though.
- Added flash conversion support due to some apparent differences in flash formats or methods of encoding. Also if one wishes to resize a flash file.


## EOF
