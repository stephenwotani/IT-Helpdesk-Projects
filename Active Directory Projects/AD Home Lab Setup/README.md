# Active Directory Home Lab Setup
***
**setup**  
1)**A Hypervisor** : **Oracle Virtual Box**  This is a software that helps us to run multiple virtual machines on our single device a

2)**Server OS**:  Windows Server 2022    

3)**Client OS**: Windows 10/11 Enterprise 
**

**steps taken to setup my Active Directory Home Lab**   
1)Installing Oracle Virtual Virtual Box (The Hypervisor)    
2) Downloading the Microsoft Server 2022 OS ISO file from the official microsoft website  
3)Downloading the Microsoft windows 11  OS ISO file from the official microsoft website 
4)Mounting Both the Server and Client ISO files on the Oracle Virtual Box  
**configuring the server Machine** 

-setting up an administrator account and and loging cridentials for the admin account  
-configuring the network settings by issigning  a static IPV4 ip to the server,a subnetmask and a DNS IP  
-Launching Active Directory in tools   
-Creating our first Forest and Tree  
-creating a Domain Name Called WOTANILABS.LAN  

**configuring the client Machine**  
-In the network settings of the client machine an IPV4 is assigned to the machine with thesame Network IP as the server machine  
-A default subnet mask is assigned to the client machine and the default Dns setting IP is same as the Server IP.  
-Adding the client machine from a workgroup to a Domain  


**Activities in Pictures** 
<img width="1917" height="987" alt="running server enviroment" src="https://github.com/user-attachments/assets/641fd6a6-0b4d-47d0-b299-7ebdddc188dd" />
<img width="1904" height="987" alt="mounting the server" src="https://github.com/user-attachments/assets/65f2b874-1e55-4f42-aa47-51ff71665f51" />
<img width="1912" height="1037" alt="Screenshot 2026-07-20 045121" src="https://github.com/user-attachments/assets/8bfe9c16-82b8-4175-bdae-82d27d7cb00d" />
<img width="1910" height="930" alt="Screenshot 2026-07-20 045349" src="https://github.com/user-attachments/assets/94c8b643-8ce4-4252-847a-bb2eb1057f46" />
<img width="1917" height="1078" alt="Screenshot 2026-07-20 045900" src="https://github.com/user-attachments/assets/409635a9-ad38-4027-8355-86e573e58ea0" />
<img width="1916" height="962" alt="successdull connection to local DNS server" src="https://github.com/user-attachments/assets/d3d855de-10f6-4ea3-af03-686e35fa5676" />
![Uploading running server enviroment.png…]()





