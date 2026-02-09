# Windows Troubleshooting Guide

This document contains common Windows troubleshooting steps based on IT support practice.  
The purpose is to document solutions for frequent issues faced by end-users.


## 1. PC Running Slow

### Possible Causes
- Too many startup programs
- Low disk space
- Background applications consuming RAM/CPU
- Malware or unnecessary software

### Troubleshooting Steps
1. Restart the system
2. Open Task Manager (`Ctrl + Shift + Esc`)
3. Check CPU / Memory usage
4. Disable unwanted startup programs:
   - Task Manager → Startup → Disable unnecessary apps
5. Free disk space:
   - Delete temporary files
   - Empty recycle bin
6. Run Disk Cleanup:
   - Search "Disk Cleanup" → Run
7. Update Windows and restart


## 2. Internet Not Working (Wi-Fi / LAN)

### Troubleshooting Steps
1. Check if router is powered on
2. Restart router and PC
3. Check if Wi-Fi is connected properly
4. Run Windows Network Troubleshooter:
   - Settings → Network → Troubleshoot

### Useful Commands (CMD)

```cmd
ipconfig /all
ipconfig /release
ipconfig /renew
ipconfig /flushdns

Ping Test
ping google.com
If no response, check network adapter settings and DNS configuration.

3. Software Installation Error
Troubleshooting Steps

Restart the system
Check if enough storage is available
Run installer as Administrator
Disable antivirus temporarily (if required and safe)
Download correct version (32-bit / 64-bit)
Remove old version:
Control Panel → Programs → Uninstall
Install again and restart

4. Windows Update Not Working
Troubleshooting Steps

Restart system
Check internet connection
Run Windows Update Troubleshooter
Clear Windows Update cache (if required)
Try update again

5. Printer Not Working
Troubleshooting Steps

Check printer power and cable connection
Restart printer and PC
Check printer status:
Control Panel → Devices and Printers
Set printer as default
Remove and re-add printer
Reinstall drivers if needed

6. Common Useful Commands (CMD)

Check IP Address
  ipconfig
Check Connectivity
  ping google.com
Trace Network Route
  tracert google.com
DNS Lookup
  nslookup google.com

