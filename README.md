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
- List all users with selection interface

### 👥 Group Management
- Add group
- Modify group (name, GID)
- Add user to group
- Delete group
- List all groups with selection interface

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
