# Active-Directory-From-Scratch

## 🧠 Objective
Deploy and configure an Active Directory Domain Controller in a virtual lab environment using VirtualBox and Windows Server. This forms the foundation for future Blue Team and SOC-focused labs by simulating a realistic enterprise setup.

## 🖥️ Environment
- **Virtualization**: VirtualBox
- **Operating System**: Windows Server 2022 (GUI install)
- **Host OS**: macOS / Windows
- **Network Configuration**: Internal Network + Host-Only Adapter

## 📚 Tutorial Reference
EastCharmer YouTube Series:
> "How to Build an Active Directory Lab (2024)"  
> [YouTube Playlist](https://www.youtube.com/@EastCharmer)

## 🛠 Tools & Features Installed
- Active Directory Domain Services (AD DS)
- DNS Server
- Group Policy Management Console (GPMC)
- Static IP Configuration
- Admin Account & OU Structure

## 📝 Key Steps Performed
1. ✅ Installed Windows Server on VirtualBox VM
2. ✅ Renamed host and set static IP
3. ✅ Promoted server to Domain Controller
4. ✅ Installed DNS and verified zone creation
5. ✅ Created a domain: `eastlab.local`
6. ✅ Set up Organizational Units (OU) for structure: `Users`, `Computers`, `IT`, `HR`
7. ✅ Created test user accounts with custom group policies

## 🔍 Key Concepts Practiced
- Domain Controller Promotion & Configuration
- DNS Setup & Name Resolution
- OU and GPO Design for Access Control
- Virtual Network Setup in Internal & Host-Only Modes

## 📎 Screenshots
| Step | Screenshot |
|------|------------|
| Server Manager dashboard | <img width="968" alt="Screenshot 2025-06-02 at 16 11 45" src="https://github.com/user-attachments/assets/a111abae-1651-46b9-86a8-a8c4f7716223" />
 |
| AD DS Promotion Complete | ![](./screenshots/ad-complete.png) |
| OU Structure | ![](./screenshots/ou-structure.png) |

*(Place your actual screenshots in a `/screenshots/` folder)*

## 🚀 Next Steps
- Add a Windows 10/11 client VM and join to domain
- Practice log collection via Event Viewer and forwarding
- Integrate Wazuh or Splunk for SIEM detection in domain

