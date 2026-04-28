# Build-Virtual-Lab-

Overiew
This project demonstrates the setup and configuration of a virtualized network environment using two virtual machines — one Linux-based and one Windows-based. The goal is to practice fundamental system administration, networking, and basic security hygiene concepts in a controlled lab environment.

### 1) Lab Environment

- **Hypervisor:** VirtualBox
- **Virtual machines:**
    - 🪟 **WIN-CLIENT-01** (Windows)
    - 🐧 **LINUX-SERVER-01** (Linux)

### 2) Network Design

- **NAT** for internet access
- **Internal Network** for VM-to-VM communication (sent pings)

### 3) Connectivity Validation

- Confirmed communication between **WIN-CLIENT-01** and **LINUX-SERVER-01** over the internal network.

### 4) Basic System Hardening

**Windows (WIN-CLIENT-01)**

- Enabled **Windows Defender**
- Configured **Windows Firewall** rules

**Linux (LINUX-SERVER-01)**

- Enabled and configured **UFW** firewall
- Hardened **SSH** configuration
- Installed and configured **Fail2Ban**

### 5) Snapshots and Rollback

- Created **snapshots** to support quick rollback after testing or configuration changes.

### 6) Key Takeaways

- Build a **safe testing environment**
- Apply **security hardening early**
- Keep everything **documented and repeatable**
