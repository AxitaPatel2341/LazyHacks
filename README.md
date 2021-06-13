# LazyHacks
Make hacking easy with automation to do various type of attacks on your target.

                                                      
     /$$                                     /$$   /$$                     /$$    
    | $$                                    | $$  | $$                    | $$                           
    | $$        /$$$$$$  /$$$$$$$$ /$$   /$$| $$  | $$  /$$$$$$   /$$$$$$$| $$   /$$  /$$$$$$$             
    | $$       |____  $$|____ /$$/| $$  | $$| $$$$$$$$ |____  $$ /$$_____/| $$  /$$/ /$$_____/        
    | $$        /$$$$$$$   /$$$$/ | $$  | $$| $$__  $$  /$$$$$$$| $$      | $$$$$$/ |  $$$$$$          
    | $$       /$$__  $$  /$$__/  | $$  | $$| $$  | $$ /$$__  $$| $$      | $$_  $$  \____  $$          
    | $$$$$$$$|  $$$$$$$ /$$$$$$$$|  $$$$$$$| $$  | $$|  $$$$$$$|  $$$$$$$| $$ \  $$ /$$$$$$$/        
    |________/ \_______/|________/ \____  $$|__/  |__/ \_______/ \_______/|__/  \__/|_______/          
                                   /$$  | $$                                                    
                                  |  $$$$$$/                
                                   \______/                                                      
                                                                                                

  LazyHacks | Make Hacking Easy with Automation | Python 3.9.2                                                                      
                                                                                                                                    
  [!] STRICKLY WARNING : Use it for only Educational purpose                                                                        
      We are not responsible for any criminal activity                                                                              
                                                                                                                                    
      
 Index            Tool Name         
[  01  ]     |    Port Scanner    
[  02  ]     |    ARP Scanner   
[  03  ]     |    Man In The Middle Automation    
[  04  ]     |    DDoS Automations    
[  05  ]     |    Start Advance Backdoor Server   
[  06  ]     |    sshBrute - Linux Only   
[  07  ]     |    FtpBrute    
[  08  ]     |    HashFactory   
[  09  ]     |    Zip File Cracker    
[  10  ]     |    Crypto For Files    
[  00  ]     |    Exit    

LazyHacks@chooseOption~#$                                      

#Installing:		
git clone https://github.com/AxitaPatel2341/LazyHacks.git		
		
#Option 1: (clone using above command)			
$cd LazyHacks			
$python3 LazyHacks.py (root user)        or		
$sudo python3 LazyHacks.py (normal user needs super user permissions)			
			
most of the dependencies will be installed but to use a tool like Advance Backdoor on your windows Target, you may need to install wine(windows environment for linux) and pyinstaller (convert backdoor.py to exe) manually.			
			
#Option 2: (manually)			
1.Unzip the downloaded zip file			
2.Go to the the directory where you extracted your file			
$cd LazyHacks			
3. Install dependencies manually			
4. Run LazyHacks.py with root privileges		
		
#Dependencies			
python version 3.9.2 or above, Python libraries -> mss, thread, urllib, socket, hashlib, fernet, zipfile, pexpect, ftplib,requests,subprocess,shutil,pynput (install using pip3 command), scapy, wine (windows environment for linux), pyinstaller(optional).			
		
		
#How to use			
	After running LazyHacks.py choose option wisely according to which attack you want to perform on your target.			
			
  1)scan_target using Port scan					 
	1. Provide the IP address or Hostname of your target			
	2. Specify ports or scan default 0-1024 ports			
			
  2)scan_target using ARP scan			 
        (To run this attack, you may need super user permissions otherwise run as root)			
	1. Provide interface using option(1,2,3)			
	2. Specify IP range of your network			
				
  3)Man In The Middle attack			
	1. Specify the IP of your Target			
	2. Specify IP address of your Router/Gateway			
		
  4)Slowloris Attack (DoS)			
	1. Specify number of threads (You can skip this, default threads are 200)		
	2. Specify target's IP or Hostname		
	3. Target-port : 80 - default (You can skip this)			
  			
  5)Synflood Attack (DDoS) && Requests Attack (DoS)			
	1. Specify the target IP or Hostname		
	2. Number of threads: 1000 - default (You can skip this)		
  			
  6)Advance Backdoor			
	1. Specify Y (yes) or N (no) according to download backdoor.py or not			
	2. Open another terminal in same directory & open /LazyHacks/Backdoor.py		
	3. Change host_ip="192.168.2.6" to attacker IP, uncomment it and save Backdoor.py			
	4. If target OS is windows , then use below command in your terminal			
	        wine /root/.wine/drive_c/Python/Scripts/pyinstaller.exe --onefile --noconsole Backdoor.py		
	5. If terget OS is linux, then convert backdoor.py to .exe using below command			
	       pyinstaller --onefile --noconsole Backdoor.py			
	6. Send Backdoor.exe to your target			
	7. Specify timeout (default 300 sec) into LazyHacks Backdoor server and wait target to connect			
	8. After connection you get the shell of connected target			
	9. Execute "help" command and follow commands according to which activity you want to			
	     perform on your target.			
				
  7)SSH Password Cracker (Linux only)			
	1. Specify IP of your target			
	2. Specify valid username		
	3. Specify password/list/file/path/passfile.txt			
			
  8)FTP Password Cracker		
	1. Specify Target Host/IP		
	2. Specify path/to/password/file/passftp.txt		
	    Note: Make sure that passftp.txt contains "username:password" format		
		
  9)Hashfactory			
	1. Choose option accordingly your task			
	2. To convert hash to string: Specify Hash value and wordlist path			
	3. To convert string to hash: Specify string			
			
  10)Zip Cracker		
	1. Provide zip file path		
	2. Specify password file path		
		
  11)Crypto for file (File encryption using symmetric key encryption)			
	1. For encryption: Provide file path accordingly which file you want to encrypt			
	2. For decryption: Provide file path of encrypted file			
		               Provide keyfile/path/filename.key 			
			
