<h1>Building Cyber security Lab From Scratch</h1>


<h2>Description</h2>
🔬 Ultimate Cybersecurity Home Lab – Hands-On Threat Detection & Ethical Hacking Playground
This project is a step-by-step walkthrough of building a powerful, real-world cybersecurity home lab from scratch. It features a virtualized environment that includes:

🎯 Kali Linux – Penetration testing & ethical hacking toolkit

💥 Metasploitable – Intentionally vulnerable VM for exploit practice

🛡️ Ubuntu Server + Wazuh – Security monitoring, threat detection, and log analysis

🧩 Ubuntu Desktop – General user workstation for simulation

🧠 Flare VM – Malware analysis and reverse engineering suite

This is a  hands-on practice with real attack and defense scenarios.
<br />


<h2>System Requirements</h2>

- <b>RAM: 16 GB (🔁 32 GB or more highly recommended for running multiple VMs)</b> 
- <b>CPU: 2.0 GHz or faster, multi-core processor</b>
- <b>Storage: 500 GB SSD (or higher, depending on snapshots and logging needs)</b> 
- <b>Virtualization Support: Enabled in BIOS/UEFI (VT-x/AMD-V)</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

- <b>## 🔧 Step-by-Step Setup

### 1. Install Virtualization Software
- [VirtualBox](https://www.virtualbox.org/)
- Enable virtualization in BIOS

### 2. Download VM Images
- Kali Linux: https://www.kali.org/get-kali
- Metasploitable2: https://sourceforge.net/projects/metasploitable/
- Ubuntu Server: https://ubuntu.com/download/server
- Ubuntu Desktop: https://ubuntu.com/download/desktop
- FLARE VM: https://github.com/mandiant/flare-vm

### 3. Configure Network
- Create a Host-Only or Internal Network
- Assign static IPs to all VMs
- Keep lab isolated from the internet

### 4. Configure Each VM
- **Kali Linux**: Update tools and test exploits
- **Metasploitable2**: Use default credentials (msfadmin:msfadmin)
- **Ubuntu Server + Wazuh**: Follow official Wazuh docs
- **Ubuntu Desktop**: Simulate employee or victim behavior
- **FLARE VM**: Use PowerShell to install the toolkit

### 5. Run Practice Scenarios
- Kali targets Metasploitable
- Wazuh monitors attacks
- FLARE VM analyzes malware
- Ubuntu Desktop used for phishing tests

### 6. Automate & Maintain
- Use install scripts
- Create snapshots before major actions
- Keep tools and OS updated


Once everything is installed and configured, you’ll have a safe, isolated, and powerful lab for hands-on cybersecurity training.</b> 


<img src="(https://imgur.com/a/nZPIZl5)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
