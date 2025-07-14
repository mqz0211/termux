# ⚡ Ethical Hacking Starter Guide with Termux (Android Only)

Welcome to your mobile hacking lab!
This guide is your all-in-one starter pack to learn ethical hacking using only **Termux on Android** — no PC needed.

> 📌 **For education only. Don't hack systems you don't own or have permission to test.**

---

## 🤔 Before We Begin: What Are Termux, Repos, and Packages?

### 📱 What is Termux?

**Termux** is a free terminal emulator app for Android. It gives you a Linux command-line environment where you can run hacking tools, write code, and learn cybersecurity — all from your phone.

### 📦 What is a Package?

A **package** is a bundle of code that adds a new feature or tool. For example:

* `nmap` — a package that scans networks for open ports
* `git` — a package used to download or clone code from GitHub

You install packages in Termux to add functionality.

### 🧃 What is a Repository (Repo)?

A **repository** is a collection of packages stored online. When you install a tool, Termux checks its repositories for the latest version of that tool.

* **Updating the repo** means downloading the latest list of available packages.
* Example: `pkg update` refreshes the repo list.

---

## 📲 Installing Termux

1. 📥 Download **Termux** from the **Google Play Store**:
   [https://play.google.com/store/apps/details?id=com.termux](https://play.google.com/store/apps/details?id=com.termux)
2. Open it and run:

   ```bash
   pkg update && pkg upgrade
   ```

   This command updates your list of packages and upgrades any old ones.

---

## 🧠 What You'll Learn

* Linux command basics
* File management in Termux
* Networking, scanning, reconnaissance
* Installing & using hacking tools
* Useful shell tips and productivity

---

## 💻 100+ Basic Termux Commands (Cheat Sheet)

### 📁 File & Directory Commands

```bash
pwd                # Show current directory
```

```bash
ls                 # List files
```

```bash
ls -a              # Show hidden files
```

```bash
cd [dir]           # Change into directory
```

```bash
cd ..              # Move up one directory
```

```bash
mkdir [foldername] # Create a folder
```

```bash
rmdir [foldername] # Remove empty folder
```

```bash
touch file.txt     # Create new file
```

```bash
rm file.txt        # Delete a file
```

```bash
rm -rf foldername  # Force delete folder & contents
```

```bash
cp a.txt b.txt     # Copy file
```

```bash
mv b.txt c.txt     # Rename or move file
```

```bash
cat c.txt          # Show file content
```

```bash
clear              # Clear terminal
```

### ⚙️ System & Package Management

```bash
pkg update              # Refresh list of available packages
```

```bash
pkg upgrade             # Upgrade installed packages
```

```bash
pkg install [package]   # Install a new package
```

```bash
pkg uninstall [package] # Remove an installed package
```

```bash
pkg list-all            # List all available packages
```

```bash
pkg search [package]    # Search for a package by name
```

```bash
apt install [package]   # Alternate package installer
```

```bash
termux-info             # Show Termux system/device info
```

### 🌐 Network & Internet Tools

```bash
ifconfig                 # Show network interfaces and IPs
```

```bash
ip a                     # Alternate way to view network info
```

```bash
ping google.com          # Check internet connectivity
```

```bash
traceroute google.com    # Show path to host
```

```bash
nslookup google.com      # DNS resolution info
```

```bash
whois hackthebox.com     # Domain registration info
```

```bash
curl ifconfig.me         # Show external IP address
```

```bash
wget https://example.com # Download file from URL
```

```bash
nmap 127.0.0.1           # Scan local system for open ports
```

### 🔐 Ethical Hacking Tools (Install These)

```bash
pkg install git         # Download & manage code from GitHub
```

```bash
pkg install python      # Run Python scripts & tools
```

```bash
pkg install nmap        # Scan networks and ports
```

```bash
pkg install sqlmap      # Test SQL injection vulnerabilities
```

```bash
pkg install hydra       # Brute-force login credentials
```

```bash
pkg install metasploit  # Full exploitation framework
```

```bash
pkg install openssh     # Secure shell access
```

```bash
pkg install netcat      # TCP/IP networking tool
```

### 🐍 Python & Bash Basics

```bash
python3                 # Start Python interpreter
```

```bash
python3 file.py         # Run a Python script
```

```bash
chmod +x script.sh      # Make shell script executable
```

```bash
./script.sh             # Run shell script directly
```

```bash
nano script.sh          # Edit script in terminal editor
```

```bash
bash script.sh          # Execute script using bash
```

### 📂 Useful Termux Directories

```bash
cd ~                            # Go to Termux home directory
```

```bash
cd /sdcard                      # Access Android internal storage
```

```bash
cd ~/downloads                  # Termux downloads directory
```

```bash
ls /data/data/com.termux/       # View Termux internal data files
```

### 🛠 System Utilities

```bash
top                      # View real-time running processes
```

```bash
ps                       # List active processes
```

```bash
kill [pid]               # Kill process by ID
```

```bash
df -h                    # Show disk space usage
```

```bash
du -sh folder            # Show size of folder
```

```bash
history                  # List previous commands
```

```bash
uptime                  # Show system uptime
```

```bash
uname -a                # Show system kernel and OS info
```

### 💡 Tips & Tricks

```bash
!!                          # Repeat last command
```

```bash
history | grep [term]       # Search command history
```

```bash
cd folder && ls             # Chain commands
```

```bash
alias ll='ls -la'           # Create shortcut command
```

```bash
CTRL + C                    # Stop a running command
```

```bash
CTRL + D                    # Exit terminal or interpreter
```

## 📘 Recommended Reading & Channels

* **Linux Basics for Hackers**
* **The Hacker Playbook**
* YouTube: **NetworkChuck**, **IppSec**, **STÖK**, **Hackersploit**, **David Bombal**

---

## 🛡️ Stay Legal

* Only hack with permission.
* Practice on test machines or online labs.
* Document everything. Skills matter more than shortcuts.

**👨‍💻 Happy Hacking — From Your Pocket Terminal.**
