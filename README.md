# Virtualbox-Raspberry-Pi-Emulator

If you would like to have Raspberry Pi experience before owning the physical board, this is what you need to do:

##Download:
1. Download and install VirtualBox.
2. Download [zip file](http://ediy.com.my/Downloads/Raspberry%20Pi/RaspberryPi.VirtualBox.zip) and extract included file to any folder.
3. Open the torrent file with any torrent client.
4. Start download and you will have over 600 MB ova file upon download completion.

##Instalation:
1. RaspberryPi virtual machine can be created in two steps.
   1. First Step:
      * Nevigate to the downloaded RaspberryPi.ova virtual machine file, double click it and VirtualBox window will open with settings.
      * Click/Enter Import.
      
   2. Second Step:
      * Run VirtualBox.
      * Select File > Import Appliance > choose file path > Continue > Import.
2. A RaspberryPi virtual machine is created.

##Setup:
1. Double click the RaspberryPi icon to start the virtual machine.
2. Enter ***rpi*** for login username and ***password*** for login password.
3. Select Menu > Accesories > LXTerminal.
4. Enter `cd debian` then `./launchDebian` to run Virtual Network Computer server.
5. Enter ***password*** for password.
6. Open another LXTerminal and enter `xtightvncviewer localhost`
7. RaspberryPi login username is ***root*** and password is ***password***.
8. You are now logged into the emulated RaspberryPi, Enjoy!!!.
