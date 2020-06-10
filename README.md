# <center> Extracting system folder from system.new.dat.br </center>

Copy all the files in this branch to where system.new.dat.br or system.new.dat and follow the guide.

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



# Gaining Permission Of Extracted `system` folder

1.  sudo chown -R USERNAME:USERNAME ~/path/of/mounted/image

{Example:} `sudo chown -R hardik:hardik ~/Documents/ROM/final/Extracted/output`


-_- Booyah! You got the system folder 



# Credits

1. <a href="https://stackoverflow.com/questions/47893437/how-to-unpack-system-new-dat-br-file-which-i-found-in-android-8-1-romaosp-based">StackOverFlow</a>

2. <a href="https://forum.xda-developers.com/android/software-hacking/how-to-conver-lollipop-dat-files-to-t2978952">XDA</a>

3. G O D 




