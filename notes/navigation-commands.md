# 📂 Linux Basics & File Navigation

## 🧠 What I Learned

In this section, I explored the basics of Linux and how to move around the file system using terminal commands. This forms the foundation for all Linux and DevOps work.

---

## 🔍 Key Concepts

- Linux is a Unix-like operating system based on open-source development.
- Everything in Linux is treated as a **file** (including devices and processes).
- The **file system** is hierarchical, starting from the root (`/`).

---

## 🗂 Common Directories

| Directory | Purpose |
|----------|---------|
| `/`        | Root of the file system |
| `/home`    | User directories |
| `/etc`     | System configuration files |
| `/bin`     | Essential binaries |
| `/var`     | Log files and variable data |
| `/tmp`     | Temporary files |

---

## 🧭 Navigation Commands

| Command | Description |
|--------|-------------|
| `pwd` | Print current working directory |
| `ls` | List contents of a directory |
| `cd` | Change directory |
| `cd ~` | Go to home directory |
| `cd ..` | Go up one level |
| `cd /path/to/dir` | Go to a specific directory |
| `ls -l` | Long listing format |
| `ls -a` | Show hidden files |

---

## 🔧 Practice

```bash
pwd
ls
ls -l
ls -a
cd /etc
cd ..
cd ~
cd /home/your-username

💡__Tips__
Use Tab to auto-complete paths
Use clear to clean your terminal screen.
Use man <command> to read the manual (e.g., man ls)

🗒️**Reflection**
Understanding Linux's file structure and practicing navigation has helped me feel more in control while using the terminal. It's amazing how much faster tasks become when you're comfortable using basic CLI tools.
