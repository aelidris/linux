# Linux Project – Introduction to Debian & Virtualization  

**Author:** Abdelfattah Elidrissi  
**Repository:** [linux](https://learn.zone01oujda.ma/git/aelidris/linux)  

---

## 📌 Introduction  

Linux is the most widely used **kernel**, the core of an operating system.  
It can be found everywhere: in **data centers, phones, gaming consoles, cars, planes, submarines, and even space stations**.  

Operating systems built on the Linux kernel are called **Linux distributions**.  
One of the most popular distributions is **Debian**, which is the focus of this project.  

Through this project, you will:  
- Discover **Debian Linux** and its role in servers.  
- Understand **what lies beneath your programs** and the Cloud services you use every day.  
- Learn practical tricks to control both your personal machine and remote servers.  

---

## 💻 Virtualization  

To practice in a standardized and risk-free environment, we use **VirtualBox** as a hypervisor.  

VirtualBox allows us to run multiple **virtual machines (VMs)**, each behaving like a separate computer, inside a window on our host system.  

For example, you can run **Linux, Windows, and macOS** simultaneously on the same machine.  

This ensures:  
- No risk of breaking your host OS.  
- A consistent environment for everyone.  
- Easier experimentation and learning.  

---

## ⚙️ Installation  

We install **Debian** using the official ISO image (recommended: `netinst` installer).  

Steps:  
1. **Create** a new VM in VirtualBox.  
2. **Attach** the Debian ISO file as an optical drive (CD/DVD).  
3. **Start** the VM and follow the installation steps.  
4. Once installed, **reboot** to start Debian.  

You will now have a fully functional Debian system ready to use in your VM.  

---

## 📴 Shutting Down the VM  

To power off the virtual machine safely, always perform a **graceful shutdown**:  

- Use **ACPI Shutdown** in VirtualBox.  
  - This is equivalent to pressing the **power button** on a physical computer.  
  - It ensures all processes are stopped cleanly and no data is lost.  

Alternatively, inside Debian you can run:  

```bash
shutdown -h now
