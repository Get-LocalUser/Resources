# NAMING CONVENTION
  This naming convention is utilized in this dev tenant but might be slightly mdofied per section.  
  Taken from [Nicky Westelinck](https://www.nickydewestelinck.be/2024/10/17/how-to-organize-your-microsoft-intune-deployments-like-a-rockstar-part-2/)

**EXAMPLE:**  
GBL – DVC – WIN – Custom -Enable password reset at login – PRD  
BE – DVC – WIN – OneDrive – General Settings – PRD  
IT – DVC -WIN – Security Baseline – Attack Surface Reduction – CAN  

## Explanation

The naming convention follows the structure:  
**(Ownership) – (Object) – (Platform) – (Type) – (Purpose) – (Ring)**

### Detailed Breakdown

### **1. Ownership**

Defines which branch or department the policy is targeted towards. Useful for large organizations with multiple branches or departments. 

- **GBL:** Global, for the entire tenant across all branches, departments, etc.
- **BE:** Deployment to all branches in Belgium.
- **IT:** Deployment only to the IT department.

### **2. Object**

Indicates the type of Entra ID group the policy is assigned to: 

- **USR:** User
- **DVC:** Device

### **3. Platform**

Specifies the platform to which the policy applies:

- **WIN:** Windows  
- **AND:** Android  
- **LNX:** Linux  
- **IOS:** iOS  

### **4. Type**

Describes the type of profile or what aspect the policy targets, allowing for better organization and clarity. Example types include:

- **Custom**  
- **Browser**  
- **OneDrive**  
- **Operating System**  
- **Account Protection**  
- **Security Baseline**  

Feel free to use whatever types suit your organization’s needs, ensuring they clearly indicate the purpose of the configuration.

### **5. Purpose**

Provides additional details about what the policy configures. For instance:

- **OneDrive – Known Folder Move**  
- **OS – Device Restrictions**  

### **6. Ring (Optional)**

Defines the environment or stage of the policy, allowing for multiple versions of the same policy based on the testing or production status. This helps prevent accidental modifications to critical configurations. Examples include:

- **PRD:** Production  
- **CAN:** Canary or test  
- **DEV:** Development (Optional)  