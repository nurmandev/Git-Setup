# Tom & Jerry Git Collaboration Project

## 📌 Project Overview  
This project demonstrates the importance of a **Version Control System (VCS)**, specifically **Git**, in collaborative software development.  

Using **Tom and Jerry** as an example scenario:  
- **Tom** updated the homepage with his own section.  
- **Jerry** added contact information in the footer.  
- Both changes were made on the same file, but thanks to Git, the contributions were tracked, managed, and merged without overwriting each other’s work.  

This project highlights how Git prevents conflicts, preserves history, and allows teams to collaborate efficiently.  

---

## 🛠️ Git Workflow Demonstrated  

Below are the key Git commands used in this project:  

```bash
# Initialize a new Git repository
git init

# Add file(s) to the staging area
git add index.html

# Commit changes with a message
git commit -m "Message"

# Create a new branch (optional step for collaboration)
git branch tom
git branch jerry

# Switch between branches
git checkout tom
git checkout jerry

# Merge contributions
git merge branch-name

# Check the status of the repository
git status

# Push local repository to GitHub
git remote add origin https://github.com/your-username/tom-jerry-vcs.git
git branch -M main
git push -u origin main
