# Metasploitable Lab
The ojective of this task is to launch **Metasploitable** VM on your computer and exploit one of the web vulnerabilites of the DVWA service.
The lab is aimed to falmiliarise students with **Burp suite**.

## Installation and setup
#### 1. Install VMware
Download [VMware](https://www.vmware.com/ru/products/workstation-player/workstation-player-evaluation.html) and install it.

#### 2. Setup Metasploitable VM
Download [Metasploitable 2](https://sourceforge.net/projects/metasploitable/) and import it into VMware.
After this it is crusial to change _Network connection_ type into _Bridged_ in VM settings (otherwise you won't be able to connect to machine).

#### 3. Launch VM
Power on VM and login with username `msfadmin` and password `msfadmin`.
Use the following command to obtain the IP address of the VM. 
```bash
ip a
```
The installation is now complete.

## Vulnerabilies exploitation

TO DO
