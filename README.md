# <center> Extract system folder from system.new.dat.br or system.new.dat </center>

Copy all the files (sda2img) in this branch to where system.new.dat.br or system.new.dat are extracted. Then follow the guide at each step. If you wanna extract system.new.dat then start from Extract system.new.dat unless start from beginning.

<b> Supports: </b>
1. system.new.dat.br
2. system.new.dat
3. all android version ROM :-)


# Extract system.new.dat.br

1. `sudo apt install brotli` 

2. `brotli --decompress system.new.dat.br -o system.new.dat`



# Extract system.new.dat

1. `./sdat2img.py system.transfer.list system.new.dat system.img`



# Extract system.img

1. `mkdir output`

2. `sudo mount -t ext4 -o loop system.img output/`



# Gaining Permission Of Extracted system folder

1.  sudo chown -R USERNAME:USERNAME ~/path/of/mounted/image

{Eg:} `sudo chown -R hardik:hardik ~/Documents/ROM/final/Extracted/output`


-_- Booyah! You got the system folder.Now Copy all the files from output folder to any other place.



# Deleting Output Folder

Run these commands where the output folder exists.


1. `sudo umount output`

2. `sudo rm -rf output`


<b><center> Done! Thank Me Later </center></b>


# Credits

1. <a href="https://stackoverflow.com/questions/47893437/how-to-unpack-system-new-dat-br-file-which-i-found-in-android-8-1-romaosp-based">StackOverFlow</a>

2. <a href="https://forum.xda-developers.com/android/software-hacking/how-to-conver-lollipop-dat-files-to-t2978952">XDA</a>

3. G O D 




