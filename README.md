# 🛠️ Linux User Administration Script (TUI)

A Bash-based user and group administration tool with a terminal-based graphical interface using `whiptail`. This menu-driven application allows you to manage users and groups easily via a simple TUI.

---

## 📋 Features

### 👤 User Management
- Add user with password setting
- Modify user (username, UID, home directory)
- Change user password
- Enable/Disable user account
- Delete user (with or without home directory)
- List all users with a selection interface

### 👥 Group Management
- Add group
- Modify group (name, GID)
- Add user to group
- Delete group
- List all groups with a selection interface

### 🛡️ Security Features
- Input validation for usernames and groups
- Password handling with secure prompts
- Root privilege verification

### 📦 Technical
- Uses native Linux commands: `useradd`, `usermod`, `passwd`, `groupadd`, `groupmod`
- Built with Bash and Whiptail
- Lightweight and fast execution

---

## 🖥️ Prerequisites

- Linux environment (tested on Ubuntu/Debian and RHEL/CentOS)
- Bash v4.0+
- `whiptail` (usually pre-installed)

Install `whiptail` if needed:
```bash
# Debian/Ubuntu
sudo apt-get install whiptail

# RHEL/CentOS
sudo yum install newt

# Fedora
sudo dnf install newt
```

---

## 🚀 Installation

1- Clone the repository:
```bash
git clone https://github.com/Salieri20/user-administration.git
cd user-administration
```
2- Make the script executable:
```bash
chmod +x user-admin-menu
```
3- Run with root privileges:
```bash
sudo ./user-admin-menu
```

---
## 🎮 Usage
Navigate the interface using:

* ↑↓ Arrow keys: Move between options

* Enter: Confirm selection

* Tab: Switch between buttons/fields

* Esc: Cancel/Go back

---
## 🛠️ Development
### Testing
Tested on:
* CentOS 9

### Known Issues
* Limited to ASCII characters in usernames
* Performance degrades with 1000+ users/groups

### Future Plans
* Add bulk operations
* Implement user/group search
* Add logging feature

--- 
## 🤝 Contributing
1- Fork the project

2- Create your feature branch (git checkout -b feature/AmazingFeature)

3- Commit your changes (git commit -m 'Add some feature')

4- Push to the branch (git push origin feature/AmazingFeature)

5- Open a Pull Request
