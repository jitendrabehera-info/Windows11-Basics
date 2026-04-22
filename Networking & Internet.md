🌐 Windows 11: Network Configuration & Troubleshooting Guide
🔹 1. View Network Configuration (ipconfig)
Steps:
Press Windows + R
Type cmd → Enter
Run:
ipconfig

👉 Shows IP address, gateway, DNS

🔹 2. Set Static IP Address
Steps:
Press Windows + I → Settings
Go to Network & Internet → Advanced network settings
Click Network adapter options
Right-click adapter → Properties
Select Internet Protocol Version 4 (IPv4)
Enter:
IP address
Subnet mask
Gateway
DNS

🔹 3. Switch Public ↔ Private Network
Steps:
Settings → Network & Internet
Click your network
Select:
Public
Private

🔹 4. Troubleshoot Network Issues
Steps:
Right-click network icon
Click Troubleshoot problems

OR

Settings → Network → Troubleshooter

🔹 5. Test Connectivity using ping
ping google.com

👉 Checks connectivity

🔹 6. Use tracert Command
tracert google.com

👉 Shows route path

🔹 7. Configure DNS Manually
Steps:
Open adapter properties
Select IPv4
Enter DNS:
8.8.8.8
8.8.4.4

🔹 8. Connect to Wi-Fi Securely
Steps:
Click Wi-Fi icon
Select network
Enter password

👉 Use WPA2/WPA3 networks

🔹 9. Configure Ethernet Adapter
Steps:
Open Network adapter settings
Right-click Ethernet → Properties

🔹 10. Share Folder Over Network
Steps:
Right-click folder → Properties
Go to Sharing tab
Click Share

🔹 11. Access Shared Folder
Steps:
Press Windows + R
Type:
\\IP-ADDRESS

🔹 12. Enable Network Discovery
Steps:
Control Panel → Network & Sharing
Enable:
Network discovery

🔹 13. Enable File & Printer Sharing
Steps:
Same location as above
Enable:
File & Printer sharing

🔹 14. Reset Network Settings
Steps:
Settings → Network & Internet
Click Network reset

🔹 15. Test Remote Connectivity (Basic)
Steps:
Use:
ping <IP>
Try:
mstsc

👉 Remote Desktop test

