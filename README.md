# Termux Starter Guide for Android

A simple guide for learning Linux, Android terminal basics, and safe cybersecurity practice with Termux.

This project is for learning on your own device, local lab, or systems you have clear permission to test.

## What you will learn

- Basic Linux commands
- Files and folders
- Package management
- Git, Python, and Bash basics
- Basic network checks
- Safe practice ideas

## Start here

1. Install Termux from an official source: [Termux installation guide](https://github.com/termux/termux-app#installation)
2. Update installed packages:

```bash
pkg update && pkg upgrade
```

3. Allow access to shared storage if you need it:

```bash
termux-setup-storage
```

4. Install useful learning tools:

```bash
pkg install git python nano
```

## Basic commands

| Command | What it does |
| --- | --- |
| `pwd` | Shows your current folder |
| `ls` | Lists files and folders |
| `cd folder-name` | Opens a folder |
| `cd ..` | Goes up one folder |
| `mkdir name` | Creates a folder |
| `touch file.txt` | Creates an empty file |
| `cp old.txt new.txt` | Copies a file |
| `mv old.txt new.txt` | Moves or renames a file |
| `cat file.txt` | Shows file contents |
| `rm file.txt` | Deletes a file |

Be careful with `rm`. Check the file name before you run it.

## Packages

```bash
pkg search keyword
pkg install package-name
pkg uninstall package-name
pkg list-installed
```

## Git basics

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git clone https://github.com/user/repository.git
cd repository
git status
```

## Python and Bash

```bash
nano hello.py
python hello.py

nano script.sh
chmod +x script.sh
./script.sh
```

## Networking basics

Use these only on your own device, your own network, or a lab where you have permission.

```bash
ip a
ping 127.0.0.1
curl ifconfig.me
```

For safe security practice, use legal training platforms, capture-the-flag challenges, or machines you own.

## Learning path

1. Learn files, folders, and package commands.
2. Learn Git and basic scripting.
3. Build small Python or Bash projects.
4. Practice networking only in your own lab.
5. Keep notes on what you learn and what each command does.

## Safety and responsible use

- Get permission before testing a network, website, or device.
- Do not scan, attack, or access systems that are not yours.
- Do not use password attacks or exploitation tools against real targets.
- Use local test machines and legal learning platforms.

## Contributing

Suggestions and beginner-friendly improvements are welcome. Open an issue or pull request with a clear explanation of your change.

## License

This project is available under the [MIT License](LICENSE).
