**Replication in Active Directory**  

This is making sure all domain controllers have the same and consistent information   
Changes in one domain are accepted by another

  **Benefits of Replication**  
  -High Availability  
  -Redundancy  
  -Better Performance  
  -Disaster Resillence  
  -Operational Flexibility  
  -Business continuity  
-There are two types of Replication  
**Intrasite Replication (Inside the same site)**: Speed: Happens almost instantly (typically within 15 seconds of a change)
  
  **Intersite Replication (Between different sites/cities)**:Speed: Occurs on a controlled, scheduled basis (the default is every 180 minutes, though it can be compressed down to 15 minutes)

  **some commands include**  
**repadmin /replsummary:** Gives a quick, high-level overview of the replication health and identifies any DCs that are failing to sync  
**repadmin /syncall:** Forces an immediate manual replication across all domain controllers, bypassing the scheduled wait times.    
**repadmin /showrepl:** Shows the specific replication partners for a DC and the exact time of the last successful inbound and outbound syncs  


