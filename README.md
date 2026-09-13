# 🌐 Network & Infrastructure Lab

A practical virtual infrastructure and network engineering lab built to develop real-world system administration, networking, and infrastructure skills.

## 🏗️ Lab Environment

The lab is built using VMware Workstation and virtual machines.

### 🌐 Network Architecture

| Network | Purpose | Subnet |
|---|---|---|
| 🌍 WAN | Internet / Home Network | DHCP |
| 🔧 Management | Infrastructure Management | 10.10.10.0/24 |
| 💻 Production | Production Systems | 10.10.20.0/24 |
| 🛡️ DMZ | Public-facing Services | 10.10.30.0/24 |

### 🛡️ Firewall

**OPNsense**

- WAN
- Management
- Production
- DMZ
- Firewall Rules
- NAT
- Network Segmentation

### 🖥️ Virtualisation

**VMware Workstation**

Virtual machines are used to simulate an enterprise-style infrastructure environment.

### 🐧 Servers

- Ubuntu Server
- Windows Server
- Future Linux services
- Future monitoring services

## 🎯 Objectives

- Learn network segmentation
- Configure and manage firewalls
- Deploy Linux and Windows servers
- Practice system administration
- Understand enterprise network architecture
- Develop infrastructure troubleshooting skills
- Build a foundation for DevOps and cloud engineering

## 🗺️ Lab Topology

> Network topology diagram will be added here.

## 📂 Repository Structure

```text
netlab-infrastructure/
│
├── 📁 diagrams/
├── 📁 opnsense/
├── 📁 vmware/
├── 📁 servers/
├── 📁 monitoring/
└── README.md
