# Day 1: Linux Command Line Fundamentals

**Date:**   23-05-2026

**Time spent:** 2.5 hours

---

## What I Learned Today

Today I learned 23 essential Linux commands. These are the foundation of cloud engineering because over 90% of cloud servers run on Linux.

---
## What I Understood Today
I understand that Linux is the operating system that runs most cloud servers. The commands I learned today (`pwd`, `ls`, `cd`, `mkdir`, `rm`) are things I will use every single day as a cloud engineer. I also learned that the terminal is not magic - it just follows commands exactly as I type them. The most important thing I understood is to always type `pwd` before doing anything so I know exactly where I am.

## What Was Confusing
"at the statrting it was very confusing that how to remember all command but praticing this ofentlt its made easy to handle all stuffs"

## Reflection

**On a scale of 1-10, how comfortable am I with the terminal?** [8]


**What am I excited to learn next?** [Great learning of command for crationg files and navigating to directory]


## Complete Command List
### Navigation Commands

| Command | What it does | I used it to... |
|---------|--------------|------------------|
| `pwd` | Print working directory | Find where I am in the filesystem |
| `cd /` | Change to root directory | Go to the root of Linux system |
| `cd ~` | Change to home directory | Return to my safe practice area |
| `cd ..` | Move up one directory | Go back to parent folder |

### Information Commands

| Command | What it does | I used it to... |
|---------|--------------|------------------|
| `whoami` | Show current username | Confirm I'm logged in as csimran |
| `ls` | List files | See what's in my current directory |
| `ls -la` | List ALL files with details | See hidden files and permissions |

### File Operations

| Command | What it does | I used it to... |
|---------|--------------|------------------|
| `mkdir` | Make directory | Create a folder called day1 |
| `touch` | Create empty file | Make multiple practice files |
| `cp` | Copy file | Duplicate my-first-file.txt |
| `mv` | Move/rename file | Rename backup.txt to saved.txt |
| `rm` | Remove file | Delete second.txt |
| `rm -r` | Remove directory recursively | Delete the entire day1 folder |

### File Content Commands

| Command | What it does | I used it to... |
|---------|--------------|------------------|
| `echo >` | Write text to file | Create my-first-file.txt |
| `echo >>` | Append text to file | Add a second line to test.txt |
| `cat` | View file contents | Read my-first-file.txt |

### Search Commands

| Command | What it does | I used it to... |
|---------|--------------|------------------|
| `grep` | Search inside files | Find lines containing "Linux" in test.txt |
| `find` | Find files by name | Locate all .txt files |

### Help Commands

| Command | What it does | I used it to... |
|---------|--------------|------------------|
| `--help` | Show command help | Learn more about ls |
| `man` | Open manual page | Read the full ls manual |

---

## Commands I Typed (Practice Log)

```bash
pwd                          # /home/csimran
whoami                       # csimran
ls                           # empty directory
ls -la                       # showed hidden files .bashrc, .profile
cd /                         # went to root
pwd                          # /
ls                           # saw bin, etc, home, usr, var
cd ~                         # back home
mkdir day1                   # created folder
cd day1                      # entered folder
echo "Hello Cloud Engineer" > my-first-file.txt
cat my-first-file.txt        # Hello Cloud Engineer
cp my-first-file.txt backup.txt
ls                           # saw both files
mv backup.txt saved.txt
echo "Another file" > second.txt
rm second.txt
cd ..                        # back to home
rm -r day1                   # deleted everything
echo "Linux is fun" > test.txt
grep "Linux" test.txt        # found the line
find . -name "*.txt"         # found test.txt
rm test.txt
ls --help                    # viewed help
man ls                       # viewed manual (q to quit)
