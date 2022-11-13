# How to setup MS-DOS in virtualbox
1) Download virtual box from https://www.virtualbox.org/
2) Create a new virtual machine
3) Name it MS-DOS
4) Accept all default settings and hit next button until machine is created
5) Clone this repository
6) Extract the zip file named Setup Disks.zip
7) Go to the MS-DOS machine settings and go to the storage section
8) Click on the floppy icon and load the first floppy from the extracted folder
9) Boot the machine
10) Follow the installation instruction and load the next floppy when the system asks for it.
11) At this point you should have installed all the floppy disks.
12) You have successfully installed MS-DOS on your hard disk / optical 
- By default MS-DOS will try to boot using the floppy.
  In order to boot MS-DOS from disk / optical you have to edit your boot order settings.
  In order to edit your boot order settings you have to:
1) Open virtual box
2) Go to the settings panel of MS-DOS machine
3) Go to system section
4) Now you can edit your boot order by dragging up and down the floppy, hard disk and optical.
- By default the keyboard language is set to US. If you want to change it you can use the 'keyb \<language\>' command.
  I added this line in my autoexec.bat file: keyb it. This way MS-DOS will boot with the Italian keyboard language.  
