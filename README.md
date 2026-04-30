# 🗄️🌐 Build-Virtual-Lab- 🌀📶

Overiew
This project demonstrates the setup and configuration of a virtualized network environment using two virtual machines — one Linux-based and one Windows-based. The goal is to practice fundamental system administration, networking, and basic security hygiene concepts in a controlled lab environment.
<br><br>
<h2>1) Lab Environment 🖥️</h2> 

- **Hypervisor:** VirtualBox
- **Virtual machines:**
    - 🪟 **WIN-CLIENT-01** (Windows)
    - 🐧 **LINUX-SERVER-01** (Linux)
<br><br>
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/c53372e1-6ed7-4afa-9e57-d3f1240abf50" />
<br><br>
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/b5333660-369f-4ff7-a2f6-7c77f79c6830" />

<br><br>
<h2>2) Network Design / Configuration 🔧📡</h2>

- **NAT** for internet access


<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/65180f5a-2195-42df-95e3-7c5586bb3809" />
<br><br>
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/f72b3357-8711-4004-9c99-468056b31375" />
<br><br>
<h2>3) Connectivity Validation ✅ </h2> 

- Confirmed communication between **WIN-CLIENT-01** and **LINUX-SERVER-01** over the internal network.
- **Internal Network** for VM-to-VM communication (sent pings)


<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/ba761203-31cf-45de-80f2-ba811cc29ff0" />
<br><br>
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/13b78471-83a1-470d-81b3-5b947aa4e7cf" />
<br><br>
 <h2>4) Basic System Hardening 🛡️🔒 </h2>

**Windows (WIN-CLIENT-01)** 🧱🧯

- Enabled **Windows Defender**
- Configured **Windows Firewall** rules

**Linux (LINUX-SERVER-01)** 🔥🔐

- Enabled and configured **UFW** firewall
- Hardened **SSH** configuration
- Installed and configured **Fail2Ban**

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/6d609812-17aa-4f75-b2b6-609aabe8a2ab" />
<br><br>
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/65f473e2-bfaf-43dd-861f-a9a158c08e8f" />


### 5) Snapshots and Rollback 📸⏪ 

- Created **snapshots** to support quick rollback after testing or configuration changes.

### 6) Key Takeaways 🧠🏁

- Build a **safe testing environment**
- Apply **security hardening early**
- Keep everything **documented and repeatable**
