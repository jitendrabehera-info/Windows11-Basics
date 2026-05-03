🌐 Windows 11: Network Configuration & Troubleshooting Guide
🔹 1. View Network Configuration (ipconfig)

Steps:
Press Windows + R
Type cmd → Enter
Run:
ipconfig

👉 Shows IP address, gateway, DNS

<img width="1919" height="1069" alt="image" src="https://github.com/user-attachments/assets/ed3995c0-d78a-4b09-8040-702722d6fdea" />


🔹 2. Set Static IP Address

Steps:
Press Windows + I → Settings
Go to Network & Internet → Advanced network settings
Click Network adapter options
          OR
Press Windows + R
Type ncpa.cpl → Enter

Right-click adapter → Properties
Select Internet Protocol Version 4 (IPv4)
Enter:
IP address
Subnet mask
Gateway
DNS

<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/3f9a263f-e90f-4039-9f9e-e5629aa249c0" />



🔹 3. Switch Public ↔ Private Network

Steps:
Settings → Network & Internet
Click your network
Select:
Public
Private

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a3a8986f-0a4b-49c1-b0d8-677af2f40174" />



🔹 4. Troubleshoot Network Issues

Steps:
Right-click network icon
Click Troubleshoot problems

OR

Settings → Network → Troubleshooter

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8703e705-1e19-4ab3-bb56-fc2250eca690" />


🔹 5. Test Connectivity using ping

ping google.com

👉 Checks connectivity

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/b911a1a9-7933-47a8-ab06-e9c9499b557b" />


🔹 6. Use tracert Command

tracert google.com

👉 Shows route path

<img width="1919" height="668" alt="image" src="https://github.com/user-attachments/assets/b5e5c0ee-effc-4b79-b52f-41f93cb9162f" />


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

<img width="1319" height="803" alt="image" src="https://github.com/user-attachments/assets/1f0bc851-2aa6-42fa-8243-da25fe3c5d95" />


🔹 11. Access Shared Folder

Steps:
Press Windows + R
Type:
\\IP-ADDRESS

<img width="1907" height="582" alt="image" src="https://github.com/user-attachments/assets/07447543-7ef3-4edb-aa6c-6561ef56b9b6" />


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

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9835c238-baed-4dff-ba08-f447caa6e4ca" />



