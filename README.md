# Bash Scripting Coursework

A collection of 16 Bash scripting exercises completed as part of the **Cloud and Infrastructure Specialist program (EC Utbildning)**. Each script builds progressively — from simple output and user input to functions, error handling, and system administration tasks.

---

## 📖 About

These scripts were written to practice:

- Variables and user input
- Conditional logic (`if`, `elif`, `else`)
- Comparison operators (`-eq`, `-ne`, `-lt`, `-gt`, `-z`, `-e`, `-r`, `-w`)
- Arithmetic operations
- Loops and functions
- Command-line arguments
- Error handling and input validation
- File and directory operations
- Running scripts with elevated privileges

---

## 📜 Scripts Overview

| # | Script | Purpose | Concepts |
|---|--------|---------|----------|
| 1 | `bash1.sh` | Greet the user with their username | `$USER`, `echo` |
| 2 | `bash2.sh` | Ask for name, age, and city | `read`, variables |
| 3 | `bash3.sh` | Append a name to a file | `>>`, `cat` |
| 4 | `bash4.sh` | Favorite color with a 5-second timeout | `read -t`, `-z` |
| 5 | `bash5.sh` | Compare two numbers | `-eq`, `-ne`, `-lt`, `-gt` |
| 6 | `bash6.sh` | Check if a file exists / is readable / writable | `-e`, `-r`, `-w` |
| 7 | `bash7.sh` | Validate a number between 1 and 10 | `\|\|`, range check |
| 8 | `bash8.sh` | Grade calculator (G / VG / MVG) | arithmetic, `elif` |
| 9 | `bash9.sh` | Arithmetic on two numbers | `+`, `-`, `*`, `/`, `%` |
| 10 | `bash10.sh` | Temperature converter (interactive) | `if/elif/else`, math |
| 11 | `bash11.sh` | Temperature converter (arguments) | `$1`, `$2`, `$#` |
| 12 | `bash12.sh` | Validate argument count | `$#`, `-lt` |
| 13 | `bash13.sh` | Root-only script (clears `/tmp`) | `$SUDO_COMMAND`, `rm -rf` |
| 14 | `bash14.sh` | Backup home directory with `tar` | `tar`, `date`, `$HOME` |
| 15 | `bash15.sh` | Star line function | `for`, functions |
| 16 | `bash16.sh` | Arithmetic with functions & error handling | functions, validation |

---

## 📂 Repository Structure

```
bash-scripting-coursework/
├── README.md
├── bash1.sh
├── bash2.sh
├── bash3.sh
├── bash4.sh
├── bash5.sh
├── bash6.sh
├── bash7.sh
├── bash8.sh
├── bash9.sh
├── bash10.sh
├── bash11.sh
├── bash12.sh
├── bash13.sh
├── bash14.sh
├── bash15.sh
└── bash16.sh
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/bash-scripting-coursework.git
   cd bash-scripting-coursework
   ```

2. **Make the scripts executable**
   ```bash
   chmod +x *.sh
   ```

3. **Run a script**
   ```bash
   ./bash1.sh
   ```

4. **For scripts that take arguments** (e.g. bash11, bash12):
   ```bash
   ./bash11.sh 20 C
   ./bash12.sh arg1 arg2
   ```

5. **For the root-only script** (bash13):
   ```bash
   sudo ./bash13.sh
   ```

---

## 🧰 Concepts Practiced

- `echo`, `read`, variables (`$VAR`)
- Conditionals: `if`, `elif`, `else`, `fi`
- Numeric comparisons: `-eq`, `-ne`, `-lt`, `-gt`, `-ge`, `-le`
- File tests: `-e`, `-r`, `-w`, `-d`
- String tests: `-z`, `!=`, `==`
- Arithmetic: `$(( ))`
- Loops: `for`
- Functions and arguments: `$1`, `$2`, `$#`
- Logical operators: `&&`, `||`
- File redirection: `>>`, `>`
- Command substitution: `$( )`
- System administration: `sudo`, `tar`, `rm -rf`

---

## 💡 What I Learned

- Writing structured Bash scripts with clear input validation
- Handling edge cases (division by zero, out-of-range input, missing arguments)
- Using functions to organize reusable logic
- Understanding the difference between interactive input and command-line arguments
- Applying permissions and running scripts with elevated privileges safely
- Reinforcing Linux fundamentals through hands-on scripting

---

## 🔒 Notes on Anonymization

All usernames, hostnames, and file paths in these scripts have been **anonymized** for privacy. Generic placeholders (`user`, `student`, `server`) are used instead of real identifiers.

---

## 📄 License

This is coursework material. Feel free to use it for learning purposes.

---

*Coursework — Cloud and Infrastructure Specialist program, EC Utbildning.*
