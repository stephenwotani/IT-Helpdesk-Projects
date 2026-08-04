## Groups in Active Directory
Groups are collections of user accounts, computer accounts, and other groups that administrators manage as a single unit to simplify network maintenance and access control
There are two types of groups
-**Security Groups**: These are used to assign permissions to shared resources (such as files, folders, and printers) or to assign AD user rights. They can also double as email distribution lists    

-**Distribution Groups:** These are used strictly for communication purposes, such as sending emails to a pool of users through Microsoft Exchange. They cannot be assigned access control permissions  

**Group Scopes**
The scope of a group determines its visibility across the network forest and the types of objects it can contain

A) **Domain Local**: can include users, computers, and groups from any domain in the forest used to grant permissions to certain files

B) **Global** can only include Users, computers, and groups only from the same domain.    

To manage permissions cleanly across multi-domain environments, Microsoft recommends the **AGDLP** nesting methodology:
Add **Accounts** (users/computers) into...)**Groups with Global scope** (based on business roles), and nest those into...**Groups with Domain Local scope** (based on resource access requirements), which are granted...**Permissions** to the target resource

