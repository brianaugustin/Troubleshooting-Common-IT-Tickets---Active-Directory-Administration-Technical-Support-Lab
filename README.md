# Troubleshooting-Common-IT-Tickets---Active-Directory-Administration-Technical-Support-Lab
I simulated a real-world Help Desk/System Administration environment using Windows Server 2025 to resolve frequent IT support tickets. I focused on identifying and fixing identity management issues, security permission conflicts, and account lifecycle challenges. By utilizing Active Directory Users and Computers (ADUC) and NTFS file system security, I demonstrated the ability to maintain system uptime, enforce security policies, and ensure end-users have the correct access to organizational resources.

---

## Technical Skills Demonstrated
* **Virtualization:** VMware Workstation/ESXi configuration.
* **Directory Services:** Active Directory Domain Services (AD DS) setup and management.
* **Security:** Role-Based Access Control (RBAC), NTFS permissions, and Password Policies.
* **Governance:** Organizational Unit (OU) structuring and account lifecycle management.

---

## Implementation & Screenshots

### 1. Active Directory Hierarchy & Structure
I designed a logical directory tree to reflect an organizational structure, ensuring efficient management of users and assets.
![Navigating the Active Directory Directory Tree](https://github.com/user-attachments/assets/95df1df8-a68f-472b-8aeb-e75ad3807efe)
* **What I did:** Created Organizational Units (OUs) to categorize users and computers, enabling targeted Group Policy application and delegated administration.

### 2. Role-Based Access Control (RBAC)
Implemented the principle of least privilege by using Security Groups to manage resource access.
![Role-Based Access Control (RBAC) via Security Groups](https://github.com/user-attachments/assets/ddbe2fea-34b9-4e76-aab9-4828234f6584)
* **What I did:** Configured Security Groups to streamline permission management, ensuring users only receive access based on their specific job functions.

### 3. Advanced File System Security
Beyond directory-level security, I configured granular access at the file system level.
![Configuring Advanced NTFS File System Permissions](https://github.com/user-attachments/assets/9c44595e-7205-4e14-83e9-3f2536a7b5c2)
* **What I did:** Applied Advanced NTFS permissions to secure sensitive data, managing Inheritance and specific "Read/Write/Modify" attributes for different user groups.

### 4. Account Lifecycle & Security Policies
Managed the "Join-Move-Leave" process by enforcing strict account status and expiration parameters.
![Configuring Account Expiration Policies](https://github.com/user-attachments/assets/0fef7ddf-a7ce-4ce3-874f-62ae40795fd0)
![Enabling and Disabling Domain Accounts](https://github.com/user-attachments/assets/12e3d8a2-1903-41c7-87b7-22443f221499)
* **What I did:** Set automated account expiration dates for temporary staff and manually toggled account states to prevent unauthorized access during employee offboarding.

### 5. Administrative Overrides & Identity Security
Handled critical security interventions and verified the integrity of the identity store.
![Administrative Password Overrides](https://github.com/user-attachments/assets/0a5394e3-99b2-4637-9e17-637dbbc1305c)
![Managing Identity Security and Account Status](https://github.com/user-attachments/assets/38992f17-0cbb-4d4a-ac08-d3ec3cabd725)
* **What I did:** Performed administrative password resets and utilized Active Directory Administrative Center (ADAC) to monitor account security metadata and operational status.
