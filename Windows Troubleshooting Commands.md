# 🛠️ Windows Troubleshooting Commands – With Purpose (WHY)

> ✅ Helps you **explain in interviews + understand real usage**

---

# 🔹 1. System Repair Commands

```bash
sfc /scannow
```

### ✅ Why we use:

* To **repair corrupted or missing system files**
* Used when:

  * System crashes
  * Apps not opening
  * Windows behaving abnormally

---

```bash
DISM /Online /Cleanup-Image /RestoreHealth
```

### ✅ Why we use:

* To **fix Windows image corruption**
* Used when:

  * SFC fails
  * Windows update errors occur
  * Deep system issues

---

```bash
DISM /Online /Cleanup-Image /ScanHealth
```

### ✅ Why we use:

* To **check if Windows image is damaged (without fixing)**

---

# 🔹 2. Disk Repair Commands

```bash
chkdsk C: /f /r
```

### ✅ Why we use:

* To **fix disk errors and bad sectors**
* Used when:

  * System is slow
  * Files are corrupted
  * Disk errors appear

---

```bash
fsutil dirty query C:
```

### ✅ Why we use:

* To check if disk is **marked for repair (dirty state)**

---

# 🔹 3. Network Commands

```bash
ipconfig /all
```

### ✅ Why we use:

* To **view full network configuration**
* Helps identify:

  * IP address
  * DNS
  * Gateway

---

```bash
ipconfig /release
ipconfig /renew
```

### ✅ Why we use:

* To **refresh IP address**
* Used when:

  * No internet
  * IP conflict

---

```bash
ipconfig /flushdns
```

### ✅ Why we use:

* To **clear DNS cache**
* Used when:

  * Website not loading
  * DNS mismatch

---

```bash
netsh winsock reset
```

### ✅ Why we use:

* To **fix network socket issues**
* Used when:

  * Internet connected but not working

---

```bash
netsh int ip reset
```

### ✅ Why we use:

* To **reset TCP/IP settings**
* Used when:

  * Network configuration is broken

---

```bash
ping google.com
```

### ✅ Why we use:

* To **test internet connectivity**
* Checks if system can reach external server

---

```bash
tracert google.com
```

### ✅ Why we use:

* To **trace path of network connection**
* Helps find where connection fails

---

```bash
nslookup google.com
```

### ✅ Why we use:

* To **test DNS resolution**
* Confirms domain → IP conversion

---

# 🔹 4. Boot Repair Commands

```bash
bootrec /fixmbr
```

### ✅ Why we use:

* To **repair Master Boot Record**
* Used when system not booting

---

```bash
bootrec /fixboot
```

### ✅ Why we use:

* To **fix boot sector issues**

---

```bash
bootrec /rebuildbcd
```

### ✅ Why we use:

* To **rebuild boot configuration data**

---

# 🔹 5. Process & Performance

```bash
tasklist
```

### ✅ Why we use:

* To **view running processes**
* Helps find heavy apps

---

```bash
taskkill /PID 1234 /F
```

### ✅ Why we use:

* To **force stop a frozen application**

---

```bash
perfmon
```

### ✅ Why we use:

* To **monitor system performance (CPU, RAM, Disk)**

---

# 🔹 6. Logs & System Info

```bash
systeminfo
```

### ✅ Why we use:

* To **view system details**
* Useful in troubleshooting & documentation

---

```bash
msinfo32
```

### ✅ Why we use:

* To get **detailed system configuration (GUI)**

---

```bash
eventvwr
```

### ✅ Why we use:

* To **check system error logs**
* Helps identify root cause

---

# 🔹 7. User & Access Commands

```bash
whoami
```

### ✅ Why we use:

* To check **current logged-in user**

---

```bash
net user
```

### ✅ Why we use:

* To **list all user accounts**

---

```bash
net localgroup administrators
```

### ✅ Why we use:

* To check **admin privileges**

---

# 🔹 8. Windows Update Commands

```bash
wuauclt /detectnow
```

### ✅ Why we use:

* To **force Windows update check**

---

```bash
net stop wuauserv
net start wuauserv
```

### ✅ Why we use:

* To **restart Windows Update service**

---

# 🔹 9. Advanced Tools

```bash
rstrui
```

### ✅ Why we use:

* To **open System Restore**

---

```bash
cleanmgr
```

### ✅ Why we use:

* To **free disk space**

---

```bash
shutdown /r /t 0
```

### ✅ Why we use:

* To **restart system immediately**

---
