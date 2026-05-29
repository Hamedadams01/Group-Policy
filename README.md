# Group-Policy Password Policy



![image alt]()
I’m creating a new GPO and naming it Password Policy. This is what I’ll use to enforce password rules across the domain.


![image alt]()
I’m inside the Group Policy Management Editor. I can see Computer Configuration and User Configuration — this is where all the policy settings live.


![image alt]()
I navigated down to Computer Configuration > Windows Settings > Security Settings > Account Policies > Password Policy. Everything is showing Not Defined meaning no rules are set yet.


![image alt]()
I opened the complexity requirements setting. This enforces that passwords must have uppercase, lowercase, numbers, and special characters. I enabled it.


![image alt]()
The password policy is now configured. Maximum password age is set to 90 days so users have to change it regularly. Minimum password age is 30 days so they can’t just change it right back. Minimum length is 12 characters. Complexity requirements are enabled.


![image alt]()


# GPO Control Panel

**On the Server (Group Policy Management):**

1. Opened **Group Policy Management** on Server 2022
2. Right-clicked the **Finance** OU under `HOUTECH.LOCL → Departments` and chose **"Create a GPO in this domain and Link it here"**
3. Named the new GPO **"Restriction Policy"**
4. Navigated inside the GPO to **User Configuration → Policies → Administrative Templates → Control Panel**
5. Found the setting **"Prohibit access to Control Panel and PC settings"** and set it to **Enabled**

![image alt]()
![image alt]()
![image alt]()
![image alt]()
![image alt]()
![image alt]()
![image alt]()
![image alt]()
