# FreePIE-VR-Controls for Wii-Motes

# Thanks sstf! (November 2nd 2017)

I have added two files made by sstf (wiimote_leap_vive_2.py, and wiimote_leap_vive_nogyro.py).

wiimote_leap_vive_nogyro.py uses the leap motion gyro instead of the wiimote gyro so we'll help people having issues with the wiimote gyro not working with freepie (Also see https://github.com/ajayyy/Wiimote-FreePIE-VR-Controls/issues/1#issuecomment-330001698 if you are having this issue)

wiimote_leap_vive_2.py is an improved version of wiimote_leap_vive.py, and might be better for people having issues with it.

# EDIT September 16th 2017:

Looks like the wii rotations is only read when you have a wii motion plus. I don't really know of a way to fix that, if anyone finds away, feel free to send it to me. Thanks!

# EDIT August 24th 2017:

Someone by the name of sstf found out a way to make the controllers appear. They now should appear after pressing a button on the wii controller. The rotation still doesn't work though. One guess I have about the rotation is that freepie might only use the rotation of wiimotes with wii motion plus. If anyone has wii motion plus it would be awesome if they could tey it out with that. Refer to the beta testing section.

# EDIT July 5th 2017:

Sorry for abandoning this, but I never got it working perfectly, once I get my computer working with SteamVR again, I'm going to try this again. I might do this with the Kinect too (Kinect + Wiimote). Stay tuned by watching this repo. If you have any questions, you can contact me here: dev   @   ajayinkingston.com (I added spaces to prevent bots from stealing it)

# Beta Testing
If you would like to test it out, here are the instructions:

1. Install FreePIE http://andersmalmgren.github.io/FreePIE/
2. Install the Leap Motion FreePIE plugin located here: ~~http://www.mtbs3d.com/phpBB/viewtopic.php?f=139&t=19753~~ **Edit**: the link seems to be broken on that page now. The file is called [LeapMotionPlugin.zip](https://github.com/ajayyy/Wiimote-FreePIE-VR-Controls/raw/master/LeapMotionPlugin.zip), just unzip it and put the contents in the FreePIE installation folder.

<b>If you find any problems opening FreePIE after downloading the plugin, visit https://github.com/AndersMalmgren/FreePIE/issues/101</b>

3. Install Leap Motion sensor Orion https://api.leapmotion.com/orion
4. Install team VR Razer Hydra Driver http://store.steampowered.com/app/491380/
5. Copy the sixense_fake.dll (located in the root folder of your FreePIE installation) over the sixense.dll in the driver files from steam (usually located in C:\Program Files (x86)\Steam\steamapps\common\SteamVR Driver for Razer Hydra) MAKE SURE YOU RENAME IT
6. Download the files in this repository: https://github.com/ajayyy/Wiimote-FreePIE-VR-Controls/archive/master.zip

# Once installed, do this to run it
1. Run FreePIE, and open up one of the scripts in this repository (try both out)
2. Run the script
3. Run SteamVR
