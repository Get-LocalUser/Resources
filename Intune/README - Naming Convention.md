# NAMING CONVENTION
  This naming convention utilized in this dev tenant is taken from [Nicky Westelinck](https://www.nickydewestelinck.be/2024/10/17/how-to-organize-your-microsoft-intune-deployments-like-a-rockstar-part-2/)

**EXAMPLE:**  
GBL – DVC – WIN – Custom -Enable password reset at login – PRD  
BE – DVC – WIN – OneDrive – General Settings – PRD  
IT – DVC -WIN – Security Baseline – Attack Surface Reduction – CAN  
![Real Config Profile w/ naming convention](image.png)

**EXPLANATION:**  
(Ownership) – (Object) – (Platform) -(Type) – (Purpose) – (Ring)  

### DETAILED EXPLANATION:

**Ownership**  
This section is convenient and can be used for several things. For larger organizations that also have branches abroad or organizations that have multiple branches across the country. But also in smaller organizations we can start using this, I am thinking of departments that use different configurations.

GBL = global and is meant for the entire tenant across all branches, departments, etc..  
BE = is meant for deployment to all branches in Belgium  
IT = is meant for deployment to only the IT department  

**Object**  
This is simple and based to what type of Entra ID group the policy is assigned, User (USR) or Device (DVC).

**Platform**  
I also always include the platform to which the policy applies. This gives me a better overview of the total overview of all policies.

WIN = Windows  
AND = Android  
LNX = Linux  
IOS = iOS  
….  

**Type**  
As it says itself, what type of profile is this? This gives you a view of what this policy has effect on, like Browser, OneDrive, OS, etc…

Custom
Browser
OneDrive
Operating System
Account Protection
Security Baseline
…
Here you can use whatever type you like. Important is that you know (by the look of it) to what the configuration of this policy applies.

**Purpose**  
In addition to the type, I will also add some details about what is configured, for example.:

Onedrive – Know Folder Move  
OS – Device Restrictions  
Ring (Optional)  
In addition you can also add a (Ring) to your policies, so you can have the same policies multiple times. The reason here is that if I need to test some changes in certain policies, I never touch the ones in production to avoid a massive impact. Examples are:

PRD = Production  
CAN = Canary or test  
DEV = Development (Optional)  