# Configuring Group Policy Objects in Active Directory
 ## Table of Contents
 1. Group Policy Objects Disabled

 # Group Policy Objects Disabled
 - ![Alt text](<Selecting GPO.png>)
- Entering into our GPO, you can see our current forest domain and the multiple GPO's i created within my network that are for the entire network, and for specific groups.
![Alt text](<assets/current linked GPOs.png>)
- We disabled the recycle bin for the entire domain
- ![Alt text](<assets/GPOs linked for sales.png>)
- The GPO's disabled for Sales were Control panel, Command Prompt , and regedit, the registry.
![Alt text](<assets/GPOs linked for sales.png>)
- And when testing everything within my client, we can see everything on the domain is blocked by the administrator within our group policy, a very great tool to harden our enterprise's security and to weed out any unwanted vulnerabilites/ priviledge rules.
![Alt text](<assets/Control Panel blocked.png>)
![Alt text](<assets/regedit disabled.png>)
- You'll notice there is no recycle bin on our desktop, ( Which was specifically a test run for the lab )
