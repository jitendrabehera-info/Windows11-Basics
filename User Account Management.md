
# 👤 Windows 11: User Account Management

---

## 🔹 16. Create Local Standard User

### Steps:

1. Press **Windows + I** → Settings
2. Go to **Accounts → Other users**
3. Click **Add account**
4. Select **I don’t have this person’s sign-in info**
5. Click **Add a user without a Microsoft account**
6. Enter username → Click **Next**

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/f3cdee50-cc8d-4548-8ac5-ea487e15e1d3" />


---

## 🔹 17. Create Local Administrator Account

### Steps:

1. Go to **Accounts → Other users**
2. Select user → Click **Change account type**
3. Choose **Administrator** → OK

![Admin Account](images/admin-account.png)

---

## 🔹 18. Modify User Account Type

### Steps:

1. Settings → Accounts → Other users
2. Select user
3. Click **Change account type**
4. Choose:

   * Standard
   * Administrator

![Modify Account](images/modify-account.png)

---

## 🔹 19. Set Password Policy (Basic)

### Steps:

1. Press **Windows + R**
2. Type:

```cmd id="pwdpolicy"
secpol.msc
```

3. Go to:

* Account Policies → Password Policy

👉 Configure:

* Minimum password length
* Password complexity

![Password Policy](images/password-policy.png)

---

## 🔹 20. Configure Account Lockout Policy

### Steps:

1. Open:

```cmd id="lockout"
secpol.msc
```

2. Go to:

* Account Policies → Account Lockout Policy

👉 Set:

* Lockout threshold
* Lockout duration

![Lockout Policy](images/lockout-policy.png)

---

## 🔹 21. Enable/Disable User Account

### Steps:

1. Press **Windows + R** → `lusrmgr.msc`
2. Click **Users**
3. Right-click user → Properties
4. Check/Uncheck:

* **Account is disabled**

![Enable Disable User](images/enable-disable.png)

---

## 🔹 22. Rename a User Account

### Steps:

1. Open:

```cmd id="rename"
lusrmgr.msc
```

2. Go to **Users**
3. Right-click → **Rename**

![Rename User](images/rename-user.png)

---

## 🔹 23. Delete a User Account Safely

### Steps:

1. Backup user data (important ⚠️)
2. Go to **Settings → Accounts → Other users**
3. Select user → Click **Remove**

![Delete User](images/delete-user.png)

---

## 🔹 24. Configure Parental Controls

### Steps:

1. Open **Settings → Accounts → Family**
2. Add family member
3. Configure:

   * Screen time
   * App restrictions

![Parental Control](images/parental-control.png)

---

## 🔹 25. Manage Sign-in Options (PIN, Password)

### Steps:

1. Go to **Settings → Accounts → Sign-in options**
2. Choose:

   * PIN
   * Password
   * Fingerprint

![Sign-in Options](images/signin-options.png)

---

## 🔹 26. Configure Auto-Login

### Steps:

1. Press **Windows + R**
2. Type:

```cmd id="autologin"
netplwiz
```

3. Uncheck:

* “Users must enter a username and password”

![Auto Login](images/auto-login.png)

---

## 🔹 27. Limit Access to Control Panel

### Steps:

1. Press **Windows + R**
2. Type:

```cmd id="gppanel"
gpedit.msc
```

3. Go to:

* User Configuration → Administrative Templates → Control Panel

4. Enable:

* Prohibit access to Control Panel

![Control Panel Restriction](images/control-panel-limit.png)

---

## 🔹 28. Configure Login Background

### Steps:

1. Go to **Settings → Personalization → Lock screen**
2. Choose background image

![Login Background](images/login-bg.png)

---

## 🔹 29. Test Permissions with Multiple Users

### Steps:

1. Create multiple users
2. Login with each user
3. Try:

* Access files
* Install apps
* Change settings

👉 Observe permission differences

---

## 🔹 30. View User Login History

### Steps:

1. Press **Windows + R**
2. Type:

```cmd id="eventviewer"
eventvwr.msc
```

3. Go to:

* Windows Logs → Security

👉 Check login events

![Login History](images/login-history.png)

---

# ⚡ Useful Shortcut Keys

```md id="user-shortcuts"
Windows + I → Settings
Windows + R → Run
Windows + L → Lock
Ctrl + Alt + Delete → Security options
Windows + X → Power Menu
```

---
