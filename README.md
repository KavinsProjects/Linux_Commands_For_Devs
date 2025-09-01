 # 🐧 Linux Commands for Developers

A handy reference for essential Linux commands every developer should know. From navigating the terminal to editing files and managing packages, this guide has you covered.

---

## 📁 Basic System Commands

| Command              | Description                                                  |
|----------------------|--------------------------------------------------------------|
| `pwd`                | Prints the current working directory                         |
| `uname -a`           | Displays OS version and system details                       |
| `whoami`             | Shows the current username                                   |
| `clear`              | Clears the terminal screen                                   |
| `history`            | Lists all previously entered commands                        |
| `sudo`               | Executes commands with superuser privileges                  |

---

## ✍️ Working with the `vi` Text Editor

| Action                        | Command / Shortcut                                     |
|-------------------------------|--------------------------------------------------------|
| Open a file                   | `vi hello.txt`                                         |
| Enter insert mode             | Press `i`                                              |
| Save and exit                 | Press `Esc`, then type `:wq` and hit `Enter`           |
| Exit without saving           | Press `Esc`, then type `:q!` and hit `Enter`           |
| Delete entire line            | In normal mode, type `dd`                              |

---

## 📂 File & Directory Management

| Command                        | Description                                           |
|--------------------------------|-------------------------------------------------------|
| `mkdir foldername`             | Creates a new directory                              |
| `touch filename`               | Creates an empty file                                |
| `rm filename`                  | Deletes the specified file                           |
| `rm *.txt`                     | Deletes all `.txt` files in the current directory    |
| `cat filename`                 | Displays the contents of a file                      |
| `cp source.txt destination.txt`| Copies file to a new location                        |
| `cat source.txt >> destination.txt` | Appends content to another file               |
| `echo "your text"`             | Prints the text to the terminal                      |
| `history >> commands.txt`      | Saves command history to a file                      |

---

## 📦 Installing Packages

To install a package using APT (Debian-based systems):

```bash
sudo apt-get install package-name

#Some Of commands are updateing in process

