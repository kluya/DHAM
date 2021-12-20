# DHAM
Daily Hunt Assistant Manager
=============

What it does
=============
	Set-up mode: It will read your daily mark logs and store the monsters in a database
    Run mode: It will find the monsters in the database and kill them
    Settings: Define the job you want to use, if you want to use your chocobo, your idle location, and grand company

Installation / Re-Installation
=============
    download the attached zip
    extract it
    move/copy/over-write entire folder 'DailyHuntAssistantMode' to the LuaMods folder 'C:\MINIONAPP\Bots\FFXIVMinion64\LuaMods\'
    If currently in-game and bot is attached select 'MMOMinion' -> 'Reload LUA'

Set-Up
=============
    Set bot mode to 'XDaily Hunt Assistant'
    ensure 'Setup' is clicked
    start bot
    Click on the location you'd like to get your marks: ARR / HW / StB / ShB / EW
    Scroll through the mobs, and then accept each hunt log
    Or if already accepted, go into your special inventory and open each hunt mark log and scroll through each mob on each hunt mark log 
    (when you scroll the hunt marks, it will identify the mobs and store it in a database)

Run
=============
    Set bot mode to 'XDaily Hunt Assistant'
    ensure 'Run' is clicked
    start bot
    Bot will now locate and terminate all hunts on your log, or die trying.

Managing Hunts
=============
    Clicking on the buttons of each log 'Mark Bills (ARR)' (for instance) will bring up a window which will show the name of the mob and the status. Either 'done' or 'failed'. You can manually set the status of the hunt as failed (if you want to avoid certain hunts bc of your level) or as 'done' if you have already killed the mob before setting up the bot.
    Clicking on 'Reset' will remove all mobs from the database. You will need to re-open the mark logs while in 'XDaily Hunt Assistant bot' mode and while set up mode is on in order to re-record the hunts.
    This bot won't know what marks you have already killed before setting/resetting up the bot. If you add a hunt that was already killed to the database the bot will kill it endlessly. If you use the reset option, be sure to click the button of the marks and manually set their status as 'done' if they are already killed.
    Bot has settings.
    Settings - General: | Idle Location: Where you go after everything is dead | Grand Company: Your GC for selecting the GC Huntboard | Move Timeout: if you havent moved for whatever reason it will port back to your idle location | Save State: I recommend you set this as on bc its helpful if you get disconnected or log off | Don't Wait for Fate: i recommend this setting as on. This will do all non-fate ARR mobs first, and then go to fate locations for the rest |
    Settings - Job Switch: See explanation in the GUI
    Settings - Companion: Set the Chocobo mode: Free / defender / healer / dps | Set when to summon Chocobo: Never / Always / Fates only

Special Note:
=============
    In order to use the job switch function you must set the Auto-Equip Gearset number in the main bot. To do this click: MMOMinion -> FFXIVMinion -> Settings -> Auto-Equip
    Match the gearset number of your jobs and input it in the appropriate boxes

Credits
=============
    1st off, a big thanks to anahronik for originally creating this mod. Thanks also goes to users lanceangel, itsu, and kali who have helped contribute translations of mob hunts.

Contact
=============
    You may find me on discord: gafgarion#1120


Updates
=============
	12/19/21 - Full Endwalker Release
		Mare Lamotorum hunts re-enabled due to mesh issues being resolved
		Fixed locations for mobs Ufiti - Thavnair - EW, Northern Snapweed - Labrynthos - EW

	12/17/21 - Endwalker Preview Release
		updated max level under Xdaily Hunt Assistant: Settings -> Job Switch -> Low/High
		Added all EndWalker hunts with locations
		Mare Lamotorum hunts disabled due to navigation mesh issues

	7/31/19 - Misc Updates
		updated max level under Xdaily Hunt Assistant: Settings -&gt; Job Switch -&gt; Low/High
		I have removed Chocobo Stance Function, it will rely on FFXIVMinion settings which is under: MMOMinion -&gt; FFXIVMinion -&gt; Settings -&gt; Companion
		I have updated the position for SB Mob Phoebad

	7/14/19 - Localization Updates
		Kali has given me localization for all hunts for French / German / Japanese. This bot will now work for these client languages. Thank you Kali!

		I have added localization support for FR / DE / JP Clients
		I have added SHB hunt Sea Anemone - This should be all SHB hunts please let me know if i missed any
		I have improved the location of SB Hunt Muu Shuwuu - Previously when trying to get this hunt character would be prone to spanning out indefinately while on a mount
		I have improved the hunt location of SB Hunt: Gasame - previously ive seen the character stop in the middle of the air and not go anywhere
		I have improved the hunt locations of SHB Hunts: Sulfur Byrgen, Evil One, and Debitage
