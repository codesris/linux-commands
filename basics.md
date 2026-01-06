# Linux CLI Notes Day 1

### File Navigation
```bash
cd / ls / pwd examples
```
---

### File Manipulation
```bash
touch, mkdir, cp, mv, rm
```
---

### Package Management
```bash
apt update/install
```
---

### Notes:
```bash
- rm -rf is dangerous
- cd ~ always goes home
```
---

# Linux CLI Notes – Day 2

### go to home directory
```bash
cd ~
```
---

### copy .zshrc from home to Desktop
```bash
cp ~/.zshrc ~/Desktop/zshrc-copy
```
---

### rename the copied file
```bash
mv zshrc-copy zshrc-move
```
---

### rename a directory
```bash
mv Code-dir Code-move-dir
```
---

### remove a file
```bash
rm zshrc-move
```
---

### remove a directory recursively
```bash
rm -r Code-move-dir
```
---

### display file contents
```bash
cat /tmp/hello
```
---

### display file contents with line numbers
```bash
cat -n /tmp/hello
```
---

### show first line of file
```bash
head -n 1 /tmp/hello
```
---

### show first character of file
```bash
head -c 1 /tmp/hello
```
---

### show last line of file
```bash
tail -n 1 /tmp/hello
```
---

### show last character of file
```bash
tail -c 1 /tmp/hello
```
---

### show last two characters of file
```bash
tail -c 2 /tmp/hello
```
---

### move into project directory
```bash
cd ~/project
```
---

### compare two files line by line
```bash
diff file1 file2
```
---

### compare two directories recursively
```bash
diff -r ~/Desktop ~/Code
```
---
