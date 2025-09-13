# ---------- LINUX (10 essential commands) ----------
pwd                     # Print current working directory
ls -l                   # List files in long format
cd /path/to/dir         # Change directory
cp file1 file2          # Copy file1 to file2
mv file1 file2          # Move or rename file
rm file                 # Remove file
cat file.txt            # Display file contents
grep "text" file.txt    # Search text inside a file
chmod +x script.sh      # Make file executable
top                     # Show running processes

# ---------- GIT (10 essential commands) ----------
git init                # Initialize a new git repo
git clone URL           # Clone repo from remote
git status              # Show status of repo
git add file.txt        # Stage file for commit
git commit -m "msg"     # Commit staged changes
git log --oneline       # Show commit history
git branch              # List branches
git checkout branch     # Switch to branch
git merge branch        # Merge branch into current
git push origin main    # Push changes to remote

### Linux: ls
*Usage:* ls -la  
Lists files in a directory.  
- -l = long format  
- -a = show hidden files  

*Example:*
```bash
ls -la /etc


### Linux: pwd — Print working directory
*Usage:* pwd  
*What it does:* Prints the absolute path of the current directory.  
*Example:*
```bash
pwd

### Linux: cd — Change directory
*Usage:* cd <path> • cd .. (up) • cd ~ (home)  
*Example:*
```bash
cd ~/projects
cd ..

### RM - Remove
*Usage:* rm -rf <path>  
*Warning:* Permanently deletes without prompt; double-check the path.  
*Example:*
```bash
rm -rf old_folder/



### Linux: cp — Copy files/directories
*Usage:* cp <src> <dst> • cp -r <dir> <dst>  
*Example:*
```bash
cp notes.txt backup_notes.txt
cp -r src/ backup/

*Usage:* mv <src> <dst>  
*Example:*
```bash
mv draft.txt final.txt
mv file.txt docs/file.txt
