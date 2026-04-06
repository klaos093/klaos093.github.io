---
title: "From Fundamentals to Real Infrastructure – My Windows Server Journey"
date: 2026-04-06 12:00:00 +0100
categories: [Infrastructure, Windows Server]
tags: [active-directory, powershell, virtualization, sysadmin, noroff]
---

### Stepping Into the Server Room

In my previous post, I shared how I started working with Windows Server and building my first lab environment. Since then, I’ve progressed deeper into the practical side of system administration and infrastructure—and things are starting to feel much more real.

This phase of my studies focused on expanding from basic setup into managing services, securing systems, and understanding how enterprise environments actually function.

---

### 🔧 Building the Core: Active Directory & Identity

After the initial installation, I moved into the "brain" of the network. Learning how to manage **Active Directory (AD)** and the **Active Directory Administrative Center (ADAC)** was a turning point. It’s one thing to create a user; it’s another to understand how **DNS** and **DHCP** keep the entire heartbeat of the network alive.

Key areas I explored included:
- **Identity Management:** Using ADAC to manage complex organizational units.
- **Resource Access:** Setting up file shares with precise NTFS and Share permissions.
- **Group Policy (GPO):** Learning how to enforce security and behavior across hundreds of machines from a single window.
- **Connectivity:** Configuring the "traffic controllers" of the network (DNS and DHCP).

---

### 🔐 Security and the Power of the CLI

As the course progressed, the focus shifted toward security and remote administration. This is where I moved away from the "point-and-click" interface and into the heart of modern administration.

- **Server Core:** Learning to manage Windows Server without a desktop interface (GUI) to reduce the attack surface and save resources.
- **PowerShell:** This was a big step forward. Using commands and scripts to automate tasks is faster, more powerful, and essential for any modern SysAdmin.
- **Remote Access:** Configuring secure ways for users to connect to the network without compromising safety.

---

### 🖥️ The Virtual Lab: My Sandbox for Success

One of the most valuable parts of this experience has been managing my own virtual lab. By using **Hyper-V**, I’ve been able to simulate a real-world enterprise network on a single physical machine.

My current lab includes:
- **A Primary Domain Controller** (The "Boss" of the network).
- **Standalone Servers** (For file storage and specific services).
- **Windows Client Machines** (To test how policies actually affect users).

This environment allows me to "break" things safely, troubleshoot the fallout, and understand the ripple effects of every configuration change.

---

### ⚙️ Advanced Resilience & Storage

More recently, I’ve introduced enterprise-grade reliability concepts into my workflow:
- **DFS (Distributed File System):** Making sure files stay accessible even if one server goes down.
- **Redundancy & Backup:** Planning for the "worst-case scenario" with robust recovery strategies.
- **Storage Quotas:** Managing how much space users can take up to prevent server crashes.
- **Containers:** An introduction to modern, lightweight ways to deploy applications.

---

### 💡 What I’ve Learned So Far

This journey has taught me that IT is not just about "making it work"—it's about:
- **Design:** Creating systems that are secure by default.
- **Interactions:** Understanding how a tiny change in DNS can bring down a whole company.
- **Resilience:** Being able to troubleshoot effectively when things go wrong.
- **Mindset:** Thinking like both an administrator (efficiency) and a defender (security).

---

### 🚀 Looking Ahead

As I continue my studies in **Network and IT Security** at Noroff, I’m becoming more confident with the tools used in the industry today. My goal is to keep building, breaking, fixing, and documenting—one PowerShell script at a time.

---

### In Plain Terms

Building a server network is like building a small digital city. You need to provide the "roads" (Networking), the "laws" (Group Policy), and the "security" (Firewalls and Permissions). My virtual lab is where I practice being the architect, the mayor, and the police force all at once. It’s challenging, but seeing a complex system work perfectly because of your configuration is incredibly rewarding.

---

*Note: This post reflects my personal learning experience as a student at Noroff and does not include or reproduce any proprietary course material.*
