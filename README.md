# ZeldaForPC

# Install


Download and install [Ryjunx](https://github.com/Ryujinx/release-channel-master/releases/download/1.1.1340/ryujinx-1.1.1340-win_x64.zip)

By default Ryujinx will use %appdata%/Ryujinx (or the equivalent application data folder on Linux/macOS) to store all of it's permanent files. This includes firmware, save files, shader caches and other configuration. If you wish Ryujinx to be fully self-contained you may use portable mode!
# PROD.KEYS (in repository) 
    Now that you've downloaded the Ryujinx archive, open it and extract the contents of the publish folder onto your drive in the location of your choice. We recommend against using your desktop or the root of any drive as these can sometimes be protected.

    Navigate to where you extracted the Ryujinx files, and double-click on Ryujinx.exe. This will launch the emulator and you will be met with the following message (don't worry; this is normal!) image

    Click OK on the warning box.
    Now that Ryujinx has been launched, the proper folders have been created for you in your %appdata% folder.

    Click File at the top left of the Ryujinx window, and then click Open Ryujinx Folder.
    image

    Navigate down into the system subfolder and paste your prod.keys file here. The file/folder structure should look like this (JohnDoe substituted for your username):
    image

    Close and reopen Ryujinx so that the prod.keys file is validated.
    You're done installing keys!
# Install Switch Firmware (also in repoitory) 
Initial Setup Continued - Installation of Firmware

Now that your keys are installed, it's time to install a firmware. Make sure you have an untrimmed XCI file of a recent game cartridge you dumped, or have compiled your dumped firmware into a ZIP file.

    Open Ryujinx. There should be no warning about KEYS.md anymore; if you still get the warning, go back through the prod.keys steps and ensure you have placed the file correctly.

    Now that Ryujinx is open, click Tools > Firmware > Install from XCI/ZIP
    image
    This brings up the "Choose the firmware file to open" window.

    image

    Using the Ryujinx window, navigate to the location of your dumped XCI file and click Open. You will be asked to confirm whether you want to install the firmware. Make sure your prod.keys are at least as new as the firmware you are installing!
    (Your firmware version number may vary)

    image

    Click Yes. You will see a message that the firmware is installing and was successfully installed:
    image

    Click OK. If all went well, you will now see your firmware version listed as the "System Version" in the bottom right hand corner of the main Ryujinx window.
    image
# Adding Games (Zelda is in repository)

Make a folder anyware on your PC
paste your NSP or XCI into that file
in Ryjunx, go to settings (under options) and select "add" under "game directorys" you will be promted to pick a folder. Pick the folder with the games in it.
Click OK to save
