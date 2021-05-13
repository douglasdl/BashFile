# BashFile
Bash File Commands

## Execute a BashFile (.bin)
Execute a file from current folder  
```sh
./filename
```  

## Navigation
Change directory  
```sh
cd <folder>
```  
  
Change directory (return 1 level)  
```sh
cd ..
```  
  
Present working directory  
```sh
pwd
```  

Open the Present working directory in the Explorer  
```sh
open .
```  

Open the Present working directory in the Visual Studio  
```sh
code .
```  


## Listing Files
List files in the current directory  
```sh
ls
```  

List files including hidden files  
```sh
ls -a
```  

List files including hidden files and details  
```sh
ls -all
```  


## Copy all file/directories names to clipboard  
/b = Uses bare format (no heading information or summary).  
/s = Displays files in specified directory and all subdirectories.  
/o = List by files in sorted order.  
```sh
dir /b /s |clip
```  
  
  





## Check my IP Address
Display your PC Hostname  
```sh
hostname
```  

Display your PC IP (Windows)  
```sh
ipconfig
```  

Display your PC IP (Linux)  
```sh
ip
```  

Display your PC IP (Linux)  
```sh
hostname -I
```  

Display your PC IP (Linux)  
```sh
ip addr show
```  

Display your PC IP (Linux)  
```sh
curl ifconfig.me
```  

Display your PC IP (Linux)  
```sh
curl ifconfig.me
```  

Display your PC IP (Linux)  
```sh
curl ipecho.net/plain
```  

Display your PC IP (Linux)  
```sh
curl ident.me
```  

```sh
curl bot.whatismyipaddress.com
```  

Display your PC IP (Linux)  
```sh
curl https://diagnostic.opendns.com/myip
```  

Display your PC IP (Linux)  
```sh
curl http://checkip.amazonaws.com
```  

Display your PC IP (Linux)  
```sh
curl http://whatismyip.akamai.com
```  

Display your PC IP (Linux)  
```sh
wget -qO- ifconfig.me
```  



## Remote Connection by Ethernet  
```sh
ssh <b>username</b>@<b>ipaddress</b>
```  


## Remote Connection File Copy  
```sh
scp <b>filename</b> <b>username</b>@<b>ipaddress</b>:/<b>directory</b>
```  

Recurrent copies  
```sh
scp -r <b>localDirectory</b> <b>username</b>@<b>ipaddress</b>:/<b>directory</b>
```



## Create New Text File  
### Linux  
```sh
cat filename.txt
```  
  
### Windows  
```sh
echo some-text  > filename.txt
```  




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
```sh
:w
```  

Close the file (Quit)  
```sh
:q
```  

Save and Close the file (Write & Quit)  
```sh
:wq
```  

Close without Save the file (Quit & Not)  
```sh
:q!
```  


# Open Windows Startup Folder  
```sh
shell:startup
```
