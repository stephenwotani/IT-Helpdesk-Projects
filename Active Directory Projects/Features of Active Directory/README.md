Activie Directory Stores Objects in a hierachical order. The following are features of Active Directory  
1) **FOREST** : A forest is the top level security boundary in Active Directory
 It has the following characteristics:  
🔹 Contains one or More Trees or domains  
🔹Shares a common Schema    
 🔹Share a common Global Catalog  
 🔹Trust Relationships between Domains  
 e.g STEVEWOTANI.LAN is a forest and can contain the following domains:  
 BH.STEVEWOTANI.LAN  
 USA.STEVEWOTANI.LAN  
 CM.STEVEWOTANI.LAN  
 All the domains belongs to thesame Tree.

 
2) **Tree** : is a collection of domains sharing a contigous namespace
   eg STEVEWOTANI.LAN
   +--SALE.STEVEWOTANI.LAN  
   +--IT.STEVEWOTANI.LAN  
   +--HR.STEVEWOTANI.LAN
   This Domains form a Tree Because they share thesame DNS namespace
   
3) **Domains in Active Directory** :A domain is a logical grouping of of objects within active directory  
     Domains Contain :  
   🔹Users  
   🔹Computers  
   🔹Groups  
   🔹Organisational Units   
   🔹policies  
     Each domain has:  
  ` -It's own database  
    -It's own domain controller(server)  
     -uses DNS for Name Resolution
    - provides Authentication Services
 
   4)**Organisational UNITS (OU)** : Organisational units allow IT admins to logicaly organise objects within a domain    
    
    **uses of OU**:   
   -Departmental Seperations  
   -Delegation of Administration  
   -Applying Group Policies  
   eg.  
   +--Finance  
   +--HR  
   +--Finance  
   +--SALES
5) **SITES in Active Directory** :
   Sites Represent the Physical Network Topology
   **purpose of sites**  
   -Opptimize Replication traffic  
   -Improve Authentication Performance  
   -Control Domain Controller Usage
   e.g
   -Head Office Site  
   -Branch Office Site
   
6)**Active Directory SCHEMA** 
   The Schema describes the Structure of the Active Directory Database    
   It defines:   
   -Object Types(users,computers,group)    
   -Attribute of Objects  
   -Rules of Object Creation  

   6)**Global Catalog** : The global controller is a special role assigned to the domain controller 
   purpose:
   -Stores partial attributes of all objects in the forest  
   -Enables Forest wide searches  
   -supports user login authentication  
   -Resolve Universal group membership.  
  7) **Domaain Controller(domain servers)**: A  domain controlleris a server running active directory domain services  
   Responsibillites:  
   -Authenticate Users  
   -Stores Active Directory Database  
   -Replicates Directory data  
   -Applies Security Policies  
   -Handles Login Requests  
  8) 
   
    
