   WARNING: Those who are bad spelling intolerant please turn back!

                    ###### ###### ###### ##   ##
                       ##  ##     ##  ## ### ###
                    ## ##  ##     ##  ## ## # ##
                    #####  ###### ###### ##   ##
       
                    ######### ######### ########
                    ##_____   ##      # ##
                           ## ######### ##
                    ######### ##        ########
           
                         v1.95 by John Moore
                ©2001-2009 JCOM Computer Productions
              Original Uematsu.DLL  ©2001 Marius Fodor
		   Upgraded Uematsu.DLL - Bootgod
               SNESAPU core ©2001-2007 Anti Resonance

  Web: http://jcom.shorturl.com   email: butter_pat_head@hotmail.com

DISCLAIMER:
Use at your own risk.  JCOM Computer Productions do not take
responsibility if this program causes your CPU to melt, your monitor to 
explode, your bank account to be wiped, your head to fall off, etc etc. 
You have been warned!

For changes see whatsnew.txt

JCOM-SPC is a SPC player, for those who don't know what a SPC file is,
it is a dump of the Super Nintendo's sound RAM that has been dumped 
from a Super Nintendo game using a emulator eg.zSNES.  these dumps 
usually contain code and data that allows the SNES's SPC700 APU to play 
music and SFX.  These files require a special player to play these, 
JCOM-SPC just happens to be one. Acknolagements go to Anti Resonance, 
who created the brilliant SNESAmp SPC core, and then made the 
sourcecode available to anybody who want's to use it.  Here is a list 
of all the current features that JCOM - SPC includes:

Supports sampling rates up to 48Khz, mono/stereo, up to 16bit*
Full channel muting, preamp and stereo seperation control, on the fly
Built in playlist editor
Easy file association
WAV file recording
Fast Forward and Rewind capability. 
Up to 10 favorites can be stored into JCOM - SPC for quick access.
RSN compressed SPC soundtrack support

*Settings above these may crash.

Installation:

If you have not allready done so, download and install the latest 
version of Runtimer from the JCOM website as this will contain all the 
needed files to run JCOM - SPC and any other Visual Basic programme 
downloaded from the site.  To install JCOM - SPC just unzip the archive to a folder and run JCOM - SPC by double clicking its icon.  After the breif intro screen you will be asked to configure JCOM - SPC and if you want to associate SPC files with JCOM - SPC.


Global controls:
	
	Remote control:
		  Play / Pause: Play / Pause
		  Stop: Stop
		  ReWind: ReWind
		  FastForward: FastForward
		  Next chapter: Next SPC
		  Prev chapter: Previous SPC
		  1 - 0: Plays Favorite
		  Up - Down: Moves thrugh the SPC tag info
		  Power: Closes JCOM - SPC
		  Program: Minimises / restores JCOM - SPC

Main window controls:

	Play: Plays / Restarts / unpauses the current SPC
	Stop: Stops the playing / recording of a SPC
	Pause: Pauses / unpauses the current SPC
	Fast Forward: Advances the playing SPC by 5 seconds
	Re Wind: Goes back 5 seconds
	Next: Advances to the next SPC in the current playlist or RSN
	Previous: Goes back to the previous SPC in the playlist or RSN
	Scrollbar: changes what info is displayed about the current
	  SPC.  

File menu:

	Open: Allows you to load a SPC file, playlist or RSN.
	Playlist Editor: Opens the playlist editor.
	Exit: Quits JCOM - SPC

Controls menu:
	
	Brings up the control window

Favorites menu:
	
	0 - 9: Plays favorite SPC / Playlist
	Organise Faforites: Opens the Favorites window

Options menu:

	Settings: Opens the JCOM - SPC configuration window
	Save Window Positions:  Remember the positions of JCOM-SPC's
	  windows when shut down so they are the same the next time you
	  start JCOM-SPC.
	Remote control: Opens the remote control settings window
	Hotkeys: Enables / Disables hotkeys (not working at moment)
	Associate Files: Associates SPC and playlist file types to
          JCOM - SPC so that it will be launched whenever a SPC or
          playlist file is double clicked in the windows explorer.

Help menu:
	
	About: Shows the cool about box! ^_^


Playlist editor controls:

	Add item: Brings up the add item dialouge box, only SPC files
          can be added to a playlist.
	Add Dir:  Bring up the directory selection dialouge box, all
          SPCs in the selected directory will be added to the playlist.
	Remove: Removes the selected item from the playlist.
	Rem. All: Clears the playlist.
	UP: Moves the selected item up by one.
	Down: Moved the selected item down by one.
	Load: Opens the load playlist dialouge.
	Save: Opens the save playlist dialouge.

Control box controls:

	Preamp level: Sets the amount of preamp, the higher the louder
	  but increases distortion.
	Stereo Seperation: Sets the amount of stereo seperation, ranges 
	  include Mono, reduced, SNES, increased and full.
	Channel 1-8: Mutes / unmutes a sound channel.
	Record: Begins WAV recording, opens up the destination dir
	  dialouge if none is selected.  Press again to stop
	  recording.
	Browse: Opens the dir selection dialouge.  This is where WAV
	  file recordings will be written to.

Settings window controls:

	Sample rate: Sets the sample rate for SPC playback, the higher
	  the better sound quality but requires more CPU power.
	Interpolation: Sound interpolation can improve sound quality
	  however requires extra CPU power. Cubic usually requires the
	  most CPU power but produces the best results while Gaussian
	  interpolation is the same as used by the SNES.  Note, before
	  reducing / disabling interpolation try decreasing the sample
	  rate as this will provide a better trade off between sound
	  quality and CPU power.
	BPS: Select how many bits per sample to use, only use 8 if you
	  are using a 8 bit soundcard and ony use 32 if you soundcard
	  supports it.
	Channels: selects Mono or Stereo output.  Select Mono if your
	  soundcard is mono only.
	Mixing routine:  There are various mixing routines that are
	  optimised for the various CPUs.  Pick 386 if you have a 486
	  or a Pentium CPU, pick MMX if you have a Pentium MMX, P2 or 
	  celeron CPU, pick 3DNow! if you have a AMD K6-2 or later and 
	  pick SSE if you have a later P3 or P4.
	Low pass filter: enables the low pass filter similar to the one 
	  used on the SNES.
	Enable SPC song times:  SPC which have play lenghts emmbedded
	  in them will will stop / advance playlist when they have
	  played for the time specified in the SPC.
	"Surround" sound: Creates a surround sound effect
	Record to wave with sound: SPC recording will also be heard, 
	  disable to speed up recording.
	Fast seeking: Enables fast seeking, speeds up fast forward and 
	  re wind operations.
	Old sample decompression: Uses the old sample decompression
	  routime.  Fixes some incorrect sounds in some SPC but
	  reduces the quality of the emulation.
	Mixing priority: Sets how much CPU time will be given to the
	  playback of SPCs
	Sound buffer: The larger the buffer, the less chance of sound
	  interruption when doing other things but actions such as
          muting and changing the preamp / stereo seperation will take
	  longer to take effect.  Set higher for slower machines.
	Advance playlist when recording: If set JCOM - SPC will advance
	  to the next SPC in a playlist when the current one ends when
	  recording to WAV, usefull for converting a entire playlist
	  in one go.

Remote control settings window controls:
	
	Remote enabled: Enabled the remote control.
	Serial port to use: Select the serial port that the remote
	  sensor is connected to.
	
	
If you have any suggestions for JCOM - SPC or want to report any bugs, 
email me at butter_pat_head@hotmail.com or post it on my message board 
on my site.

Thanx go to:
Anti Resonance for SNESAmp and SNESAPU
Marius Fodor for supplying a easily understood version of SNESAmp and 
 SNESAPU with Super Jukebox
Bootgod for upgrading superjukebox (and uematsu.dll) to use latest
 SNESAPU
The makers of zSNES for creating the SPC file format.
Microsoft for Windows and Visual Basic (they are not really that bad)
My Mum for feeding me
BT for supplying my house with a phone line
The seat belt in my car for saving my life when I crashed it in to a ditch
FortuneCity.co.uk for supplying 100 megs of free web space
Shorturl.com for providing a simple, easy to remember url for my site
Commodore for inventing the best sound chip found in a 8 bit!
Nintendo and all its licensees for creating games with top-notch music
TV Tokyo, Yomiko and XEBEC for creating Martian Successor Nadesico
GAINAX for creating Neon Genesis Evangelion
Big West & Co for creating the Macross series
Clamp for Chobits
Koshi Rikudo for Excel Saga
The British government for making it illegal to drive without a seat belt!
/m/, the best imageboard ever!

and anybody else that I can't remember at this current moment in time!

No Thanx go to:
FortuneCicy.co.uk for ditching banner ads in favour of loads of popups!
Sega for dictching the Dreamcast
Sony for being so bloody successfull with the Playstation
Nintendo for not really trying
Microsoft for trying to muscle in on the console industry
The makers of my CD-RW drive for making such a crap one!
Commodore for creating a sound chip which will die at the drop of a hat!
The Hollywood movie industry for inventing the DVD region coding scheme
All those spam emailers!
The universe for making it so bloody cold in my room in winter!
Fate for making me write off my first car within the first 2 months!
DIC for the attrocity that is the english Sailor Moon Dub!
Microsoft for Vista
Sony for the PS3
Nintendo for not putting S/PDIF on the Wii
/g/, because everybody on /g/ are Fags. 