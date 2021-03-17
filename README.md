# BashFile
Bash File Commands

## Execute a BashFile (.bin)
Execute a file from current folder  
`./filename`  

## Navigation
Change directory  
`cd <folder>`  
  
Change directory (return 1 level)  
`cd ..`  
  
Present working directory  
`pwd`  

Open the Present working directory in the Explorer  
`open .`  

Open the Present working directory in the Visual Studio  
`code .`  


## Listing Files
List files in the current directory  
`ls`  

List files including hidden files  
`ls -a`  

List files including hidden files and details  
`ls -all`  


## Copy all file/directories names to clipboard  
`dir /b /s |clip`  
  
  





## Check my IP Address
Display your PC Hostname  
`hostname`  

Display your PC IP (Windows)  
`ipconfig`  

Display your PC IP (Linux)  
`ip`  

Display your PC IP (Linux)  
`hostname -I`  

Display your PC IP (Linux)  
`ip addr show`  

Display your PC IP (Linux)  
`curl ifconfig.me`  

Display your PC IP (Linux)  
`curl ifconfig.me`  

Display your PC IP (Linux)  
`curl ipecho.net/plain`  

Display your PC IP (Linux)  
`curl ident.me`  

`curl bot.whatismyipaddress.com`  

Display your PC IP (Linux)  
`curl https://diagnostic.opendns.com/myip`  

Display your PC IP (Linux)  
`curl http://checkip.amazonaws.com`  

Display your PC IP (Linux)  
`curl http://whatismyip.akamai.com`  

Display your PC IP (Linux)  
`wget -qO- ifconfig.me`  



## Remote Connection by Ethernet  
`ssh <b>username</b>@<b>ipaddress</b>`  


## Remote Connection File Copy  
`scp <b>filename</b> <b>username</b>@<b>ipaddress</b>:/<b>directory</b>`  

Recurrent copies  
`scp -r <b>localDirectory</b> <b>username</b>@<b>ipaddress</b>:/<b>directory</b>`



## Create New Text File  
### Linux  
`cat filename.txt`  
  
### Windows  
`echo some-text  > filename.txt`  




## VIM Editor
Edit a file  
`vi <b>filename</b>`  

Change to edition mode  
`i`  

Delete a line  (press d twice)  
`dd`  

Save  
`Press twice the keys <SHIFT> + <Z>`  

Save (Write)  
`:w`  

Close the file (Quit)  
`:q`  

Save and Close the file (Write & Quit)  
`:wq`  

Close without Save the file (Quit & Not)  
`:q!`  
