# Group-Policy Password Policy



![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-03-24_120548.webp)
I’m creating a new GPO and naming it Password Policy. This is what I’ll use to enforce password rules across the domain.


![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-03-25_095921.webp)
I’m inside the Group Policy Management Editor. I can see Computer Configuration and User Configuration — this is where all the policy settings live.


![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-03-25_100337.webp)
I navigated down to Computer Configuration > Windows Settings > Security Settings > Account Policies > Password Policy. Everything is showing Not Defined meaning no rules are set yet.


![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-03-25_100454.webp)
I opened the complexity requirements setting. This enforces that passwords must have uppercase, lowercase, numbers, and special characters. I enabled it.


![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-03-25_100620.webp)
The password policy is now configured. Maximum password age is set to 90 days so users have to change it regularly. Minimum password age is 30 days so they can’t just change it right back. Minimum length is 12 characters. Complexity requirements are enabled.


![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-03-25_100454.webp)


# GPO Control Panel

**On the Server (Group Policy Management):**

1. Opened **Group Policy Management** on Server 2022
2. Right-clicked the **Finance** OU under `HOUTECH.LOCL → Departments` and chose **"Create a GPO in this domain and Link it here"**
3. Named the new GPO **"Restriction Policy"**
4. Navigated inside the GPO to **User Configuration → Policies → Administrative Templates → Control Panel**
5. Found the setting **"Prohibit access to Control Panel and PC settings"** and set it to **Enabled**

![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_052603.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_052913.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_063136.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_055639.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_055618.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_061433.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_061138.webp)
![image alt](https://github.com/Hamedadams01/Group-Policy/blob/e0b68d43bbe9bfd5448f5557861e21d10f5f6e0b/Screenshot_2026-04-11_061214.webp)
