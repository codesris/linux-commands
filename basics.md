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
# Focus: file viewing, copying, moving, deleting, and comparison

# go to home directory
cd ~

# copy .zshrc from home to Desktop
cp ~/.zshrc ~/Desktop/zshrc-copy

# rename the copied file
mv zshrc-copy zshrc-move

# rename a directory
mv Code-dir Code-move-dir

# remove a file
rm zshrc-move

# remove a directory recursively
rm -r Code-move-dir

# display file contents
cat /tmp/hello

# display file contents with line numbers
cat -n /tmp/hello

# show first line of file
head -n 1 /tmp/hello

# show first character of file
head -c 1 /tmp/hello

# show last line of file
tail -n 1 /tmp/hello

# show last character of file
tail -c 1 /tmp/hello

# show last two characters of file
tail -c 2 /tmp/hello

# move into project directory
cd ~/project

# compare two files line by line
diff file1 file2

# compare two directories recursively
diff -r ~/Desktop ~/Code
