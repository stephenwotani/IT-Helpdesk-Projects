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
   
4) **Domains in Active Directory** :A domain is a logical grouping of of objects within active directory  
     Domains Contain :
   🔹Users  
   🔹Computers  
   🔹Groups  
   🔹Organisational Units   
   🔹policies
   
