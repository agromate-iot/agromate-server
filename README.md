# agromate-server
Server component for agromate-iot

# To Install agromatic-server
1. Install Oracle Virtual Box. I used 6.1.16, but you can probably get away with the latest: https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html
1. Create a new local directory.  E.g., C:\agromate-server
1. Download an ISO image of a LTS version of Ubuntu Server.  I used Ubuntu Server 20.04.1 LTS, but you can probably get away with the latest: https://ubuntu.com/download/server
1. Open Virtual Box > New
   1. Name: agromate-server
   1. Location: The directory you created above
   1. Type: Ubuntu
   1. Next
   1. RAM: 1024mb should be plenty, Next
   1. Create a virtual hard disk now, Next
   1. VDI, Next
   1. Fixed Size, Next
   1. 20GB should be plenty, Next
   1. Virtual Machine should now be creating, give it a couple minutes
1. Edit agromate-server configuration by pressing 'Settings' button
   1. Storage tab on left, click on the CD controller, click on the Blue CD on far right, click on 'Choose a disk file...'
      1. Select the ISO file you download above, select OK
1. Start agromate-server by pressing 'Start' button
1. Install Ubuntu on the VM
   1. If you don't understand all the options, just go with the defaults
   1. Your server's name: agromate-server
   1. Pick a username: agromate-server
   1. Choose a password: agromate-server - we take a low security over high convenience stance on this project...feel free to create your own password
   1. Enable Install OpenSSH Server
   1. Install nothing else and just select 'Done' until it starts installing
   1. Reboot when done
