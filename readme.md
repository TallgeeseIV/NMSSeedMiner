--------------------------------------- NMSSeedMiner ---------------------------------------  
--------------------------------------- by TallgeeseIV ---------------------------------------


---------------------------------------- Instructions ----------------------------------------

1.)		Backup ALL files from your No Man's Sky save game directory, located at 
		"C:\Users\%UserName%\AppData\Roaming\HelloGames\NMS\%Your_Unique_ID_Folder%"
		by default, to a safe location.

2.)		Double check that they are backed up. I'm not going to be responsible for the
		loss of your original save files.

3.)		Now delete all save game files in your No Man's Sky save game directory.

4.)		Preperation is complete. Now it's time to create the save for seed mining as
		detailed in the next section.


------------------------------------------- Saving -------------------------------------------

	Starship Seeds 	- Please read all instructions For creating your own save. If you'd prefer
			  not to create your own, an optimal save is included. Skip to Note 3.
	
	MultiTool Seeds - Please ensure that the MultiTool menu was the last menu
			  visited before saving, then skip to: 9.)
	
	Freighter Seeds - Not yet fully implemented.


1.) 	Framing your save properly is the last step before generating seed screenshots:

   1a.) Recommended -> Start a NEW SAVE in Creative Mode. Do NOT use your main save!

   1b.) Recommended -> Find a Moon with NO atmosphere. This prevents cloud shadows
		       from affecting shots.

   1c.) Recommended -> Build a Base Computer and set up a "Photography Studio".

2.) 	Build a Portable "Save Point" on the spot you intend to take screenshots from.

3.) 	Stand on it and look down at it.

4.) 	As you look back up, you should notice that the activate prompt stays visible for
	a time.

5.) 	Look back down, and press your activate button as you quickly look up, trying to
	frame your ship as well as possible. The goal is to have the save point not
	"activate" until you are looking at your ship.

6.) 	Continue doing this until you get a properly framed shot. You can reload your save
	to test this and then resave as many times as you need to.

7.) 	Make sure that the Time of Day, Weather, and Lighting are optimal before you save!

8.) 	Keep in mind that generated ships may be slightly larger than your current ship and
	try to allow space for wider wings, longer cockpits, etc.

9.) 	This application is designed to load only the most recent save in slot 1. Make sure
	that your intended seed mining save file is the most recent and occupies slot 1.

	NOTE 1: This process will need to be performed again after every manual save, before
		seed mining.

	NOTE 2: The ship TYPE (Fighter, Hauler, etc.) will not be changed by this application,
		and can also be set by the Save Editor.

10.)	When you are done. Simply backup your seed mining saves and restore your original
	saves. Launch Goatfungus' Save Editor, and change your ship seed to the generated
	seed of your choosing. Save, and reload your game.
		
	NOTE 3: Included in this download is a zip folder labled "save.zip" containing the
		required files to load my save file for taking ship seed screenshots. To use it,
		extract it to your save file directory after backing up your original save files.


------------------------------------ Configuration Options -----------------------------------

	NOTE 4: On launch the application will warn you if you have not downloaded the nmssavetool
		by Matthew Humphrey, and will prompt you to automatically download and install it.
		This application is required for new seed generation. Visit the following url for
		manual downloading and installation:

		https://github.com/matthew-humphrey/nmssavetool/releases/download/v2.0.1.6-beta-4/

		Simply extract the archive to the same directory as NMSSeedMiner_vX.X.exe. Leave
		the nmssavetool .exe and components in their original folder,
		"nmssavetool-2.0.1.6-beta-4".


NMS Game Path:			The full path to your No Man's Sky installation directory.
				Pressing default will auto-fill this with the Steam or GoG path
				if detected on your system.

NMS Save Path:			The full path to your No Man's Sky save file directory.
				By default this is located in:

				"C:\Users\%UserName%\AppData\Roaming\HelloGames\NMS\%Your_Unique_ID_Folder%"

Screenshot Path:		The full path to the intended destination of your generated seed shots.

FileType:				Screenshot filetype. Options are Jpg, Bmp, Png and Gif. Bmp not
						recommended due to much larger file size. Png or Jpg Recommended.

Mouse Distance Mult:	Multiplier in pixels for mouse travel while navigating menus.
						Several factors affect mouse travel distance on each PC and it
						may ber necessary to adjust this value. Higher values are faster,
						but increasingly less accurate.

Enable Mods:			Automatically adjusts "DISABLEMODS.TXT" accordingly.

ClearShot:				The "ClearShot" mod forces the game to run in 720p windowed mode,
						disables the hud and crosshairs, several screen and weather affects,
						makes mouse clicks instant, and enables certain options to speed up
						loading and the process in general. It is NOT recommended to run
						other mods with ClearShot due to the HIGH probability of conflicts
						with other mods. The application will prompt you on how to handle
						this.

	NOTE 5: ClearShot is NOT OPTIONAL, as the script will not perform correctly without it.

	NOTE 6: Do NOT install Clear Shot until AFTER you have framed your save, as the lack of
		    hud elements and instant click make that process more difficult.

Mode:					Seed Generation Mode:

						- Ship will generate new ship needs.
						- MultiTool will generate new multitool seeds and automatically
						  open the menu before capturing an image.
						- Freighters are not yet fully implimented and currently behave
						  similarly to ship seeds.


--------------------------------------- External Tools ---------------------------------------

NMS Save Editor by Goatfungus: https://github.com/goatfungus/NMSSaveEditor


----------------------------- Additional Information and Caveats -----------------------------

1.)		The NEXT update added a new paint setting for ships. I do not know all the details,
		but I do know that Goatfungus' Save Editor was updated with a checkbox to toggle
		between old and new paint styles. This application only generates seeds in old mode,
		however switching to new mode on any seed will yield the same ship model with alternate
		paint. This means that for every ship you find with the appropriate model, you have two
		chances at finding appropriate paint.

2.)		This application was designed to run under default settings. While I have tested many
		different configurations, there are bound to be some that I did not account for.

3.) 	Time between screenshots is almost entirely based on your load times. As such, it is
		recommended to have the game installed to your fastest hard drive.

4.) 	This application uses timeout paramaters in case something goes wrong, such as the game
		freezing. By default these times are 3 minutes for launching the game, and 1 minute for
		loading	a save file while already in game. In the event that either task takes longer
		than the timeout parameters, the process will be ended and the game will be relaunched
		automatically.

	NOTE 7: If the need arises to adjust these parameters, they can be changed by opening
			config.ini with a text editor. Times are set in seconds.


--------------------------------------- Special Thanks ---------------------------------------

tic & Rseding91   - GDI+ Standard Library
Learning one 	  - GDI+ Cropping and Resizing Functions
MasterFocus 	  - GDI+ Image Search Function
Jess Harpur 	  - Zip Extraction Function
Matthew Humphrey  - nmssavetool
Goatfungus		  - NMS Save Editor

	and of course,

Hello Games		  - NO MAN'S SKY
