# 🛠️ Linux User Administration Script (TUI)

A Bash-based user and group administration tool with a terminal-based graphical interface using `whiptail`. This menu-driven application allows you to manage users and groups easily via a simple TUI.

---

## 📋 Features

- 👤 **User Management**
  - Add user
  - Modify user (username, UID, home directory)
  - Change user password
  - Enable/Disable user account
  - Delete user
  - List all users

- 👥 **Group Management**
  - Add group
  - Modify group (name, GID)
  - Add user to group
  - Delete group
  - List all groups

- 📦 Uses native Linux commands like `useradd`, `usermod`, `passwd`, `groupadd`, `groupmod`, `getent`, and `id`

---

## 🖥️ Prerequisites

- Linux environment
- `whiptail` installed
- Root or sudo privileges

To install `whiptail` (if not already installed):

```bash
sudo apt-get install whiptail   # Debian/Ubuntu
# or
sudo yum install newt           # RHEL/CentOS

