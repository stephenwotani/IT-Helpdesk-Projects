**A Group Policy Object (GPO)** :Is a virtual collection of configuration settings that administrators use to control the working environment of users and computers in an Active Directory network. GPOs allow you to centrally manage security policies, software installation, system settings, and registry tweaks across thousands of machines simultaneously  

Every GPO is divided into two main configuration sections, each targeting a different aspect of your environment:

**Computer Configuration:** Settings applied during system startup, before any user logs in. Examples include network settings, system services, and local security policies.

**User Configuration:** Settings applied when a specific user logs into a computer. Examples include desktop wallpaper restrictions, mapped network drives, and application shortcuts  


## How GPOs are Applied (LSDOU):
GPOs do not automatically take effect just by being created. They must be linked to specific containers within Active Directory. Active Directory processes and applies GPOs in a strict hierarchical order known by the acronym **LSDOU**:

-**L**ocal: The local policy configured on the individual machine itself.  
-**S**ite: Policies linked to the physical Active Directory site (location-based).  
-**D**omain: Policies linked to the entire domain, affecting all objects within it.  
-**O**rganizational Unit (OU): Policies linked to specific OUs. If OUs are nested, policies apply from the highest parent OU down to the deepest child OU




Groups Policies are managed using the Active Directory Tool **Group Policy Management**

**Creating a GPO**
<img width="1592" height="857" alt="creating a Computer Settings GPO" src="https://github.com/user-attachments/assets/8173c9e2-75c4-4927-b8db-2f071abdd8a6" />

**Linking an existing  GPO**
<img width="1595" height="892" alt="linking an existing GPO to the domain " src="https://github.com/user-attachments/assets/0263cf1d-faa7-44ad-89ec-7b265d179553" />

**Linked Domain GPO-Legal Notice In Effect**
<img width="1910" height="1077" alt="group policy legal warning linked to all domain devices" src="https://github.com/user-attachments/assets/db9ba48b-5257-409b-be50-015b3eb2a6a9" />

<img width="1917" height="1010" alt="applying group policy to domains" src="https://github.com/user-attachments/assets/6ebd60b5-6629-43b4-a9aa-13b95deb1783" />

**GPO to Dissable Control Pannel Access To normal users**
<img width="1267" height="562" alt="controll pannel disabled" src="https://github.com/user-attachments/assets/927e5e8c-d98d-4744-9ecf-c6660aef19da" />

