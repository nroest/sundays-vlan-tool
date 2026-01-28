# Sunday’s VLAN Tool

A small, friendly Windows app that makes working with Hyper-V networking way less painful.

Sunday’s VLAN Tool gives you a simple visual way to manage virtual switches, vEthernet adapters, and VLANs on your host without having to live in PowerShell every time something breaks or needs changing.

Built for those moments when:
- A vSwitch comes back as *Internal* after a reboot  
- Your VLANs stop talking  
- You just want to see what’s actually going on  
- You need to rebind a switch without nuking your setup  

This puts all the important stuff in one place, in a UI that feels like a proper network tool instead of a scripting exercise.

---

## What you can do
- See all Hyper-V switches and vEthernet adapters at a glance  
- Rebind switches to different physical NICs without recreating them  
- Create, rename, and clean up adapters easily  
- Set VLAN modes without hunting PowerShell syntax  
- Assign IP settings to adapters quickly  
- View LLDP info to identify uplinks and switch ports  
- Jump straight to Windows network settings when things get weird  

---

## Who it’s for
Anyone who:
- Uses multiple VLANs  
- Runs trunked adapters  
- Gets tired of broken networking after reboots  
- Wants a “Sunday fix it” tool instead of a 20-line PowerShell command  

---

## Requirements
- Windows with Hyper-V enabled  
- Administrator rights  

Download the latest build from the **Releases** section of this repository, run as admin, and fix your VLAN mess without losing your mind.
