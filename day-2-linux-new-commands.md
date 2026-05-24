# Day 2: Linux New Commands & First Bash Script

**Date:** May 24, 2026
**Time spent:** 2 hours

---

## New Commands Learned Today

| Command | What it does | Example |
|---------|--------------|---------|
| `head` | View first lines of file | `head -n 5 file.txt` |
| `tail` | View last lines of file | `tail -n 10 log.txt` |
| `wc` | Count lines, words, characters | `wc -l file.txt` |
| `sort` | Sort lines alphabetically | `sort names.txt` |
| `uniq` | Remove duplicate adjacent lines | `sort file.txt \| uniq` |
| `history` | Show command history | `history 20` |

---

## First Bash Script Created

### Script 1: first-script.sh
```bash
#!/bin/bash
echo "====================================="
echo "   My First Bash Script"
echo "   Cloud Engineer Journey - Day 2"
echo "====================================="
date

Script 2: system-info.sh (Cloud monitoring preview)
Displays system information

Shows disk usage, memory, CPU, network

Similar to cloud server monitoring scripts

# Creating sample file for practice
echo "Line 1" > sample.txt
echo "Line 2" >> sample.txt

# View first/last lines
head -n 2 sample.txt
tail -n 2 sample.txt

# Count lines
wc -l sample.txt

# Sort content
sort fruits.txt
sort -r fruits.txt

# Remove duplicates
sort items.txt | uniq

# Check command history
history 10

# Create and run bash script
mkdir scripts
cd scripts
nano first-script.sh
chmod +x first-script.sh
./first-script.sh



Commands Practiced Today

# Creating sample file for practice
echo "Line 1" > sample.txt
echo "Line 2" >> sample.txt

# View first/last lines
head -n 2 sample.txt
tail -n 2 sample.txt

# Count lines
wc -l sample.txt

# Sort content
sort fruits.txt
sort -r fruits.txt

# Remove duplicates
sort items.txt | uniq

# Check command history
history 10

# Create and run bash script
mkdir scripts
cd scripts
nano first-script.sh
chmod +x first-script.sh
./first-script.sh


What I Understood Today
[Write 2-3 sentences about what you learned]

Example: "I learned that bash scripts are just text files with multiple commands. The shebang #!/bin/bash tells Linux to run it with Bash. Making scripts executable with chmod +x is necessary before running them."

What Was Confusing
[Write 1-2 sentences]

Example: "The difference between head and tail is clear, but I need more practice with sort | uniq combination."

Reflection
On a scale of 1-10, how comfortable am I with the terminal now? [Your number]

What was the hardest part today? [Your answer]

What am I excited to learn next? [Your answer]

Commands Mastered So Far
Day 1 (23 commands): pwd, whoami, ls, ls -la, cd, mkdir, touch, cp, mv, rm, rm -r, echo >, echo >>, cat, grep, find, --help, man, clear, exit, history (basic)

Day 2 (6 new commands + scripting): head, tail, wc, sort, uniq, bash scripting basics

text

### Step 4: Fill in your answers

Replace the bracketed `[Your answer]` sections with your own words.

### Step 5: Commit the file

- Commit message: `Day 2: Learned 6 new Linux commands and created first bash script`
- Click **"Commit new file"**

---

## ✅ Day 2 Completion Checklist

| Task | Status |
|------|--------|
| Reviewed Day 1 commands | ☐ |
| Learned `head`, `tail`, `wc`, `sort`, `uniq`, `history` | ☐ |
| Created first bash script (`first-script.sh`) | ☐ |
| Ran the script successfully | ☐ |
| Created system monitoring script (`system-info.sh`) | ☐ |
| Documented everything on GitHub | ☐ |

---

## 🎯 What's Next (Day 3 Preview)

| Topic | What You'll Learn |
|-------|-------------------|
| File permissions deep dive | `chmod`, `chown`, `umask` |
| Process management | `ps`, `top`, `kill`, `jobs`, `bg`, `fg` |
| Environment variables | `export`, `$PATH`, `~/.bashrc` |
| More bash scripting | Variables, loops, conditions |

---

