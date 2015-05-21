# Server Cheat Sheet

##System


- /usr – installed binary 
- /etc – configuration files- /var – log, variable data- /root – root user directory- /home – user home directory- /proc – system process directory- /dev – devices - /tmp – temporary
##Folder Navigation
`ls` (list) - lists files in the current working directory  `ls –la` - list everything about files  `cd` (change directory) – ` cd /etc/network`  `.`  - current working directory  `..` - one directory back  `~` - my own home directory `/home/username`  `cd ..` – move one directory back  `pwd` – show my where I'm in the directories
##Directory
`mkdir` (make directory)  `rm` (remove directory)  
` rm –r` (remove directory recursively)  ` cp` (copy)  
`cp /etc/passwd ~`  (copy passwd to my home directory)  ` cp /etc/passwd .` (copy file to current directory)   ` cp ~/passwd ~/passwd.bak`  (make a copy of passwd)  
##Directory Operations
`mv` (move)  
`mv source dest` (works like rename if in the same directory)`mv /tmp/somefile newfile` (move file to current directory)`mv file newname` (rename)  `touch filename` (makes empty file named filename)  `ln –s linkname path/to/file `makes simbolic link, aka „shortcut”


