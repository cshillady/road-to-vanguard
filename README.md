## Road to Vanguard Repository

This will keep track of some of my projects during my Xpanxion Java Development Training program.

# Videos Watched
- [Git Tutorial](https://youtu.be/8JJ101D3knE)
- [Command Prompt Basics: How to use CMD (18m)](https://youtu.be/A3nwRCV-bTU)
- [Learn Git In 15 Minutes (15m)](https://youtu.be/USjZcfj8yxE)
- [Git Tutorial for Beginners: Command-Line Fundamentals (30m)](https://youtu.be/HVsySz-h9r4)

# Helpful Links

# Primary Workflow
- Identify the branch you are on:  git branch
- Create a branch from the branch you are currently on: git checkout -b dev-{your initials}-{context}
- Code Monkey
  - Write code
  - Run code
  - Test code
- See what has changed: git status
  - ProTip: Always run git status before you make a commit (to make sure you are not adding "junk" to your commit)
- Stage all files: git add --all
- Create a commit: git commit -m "YOUR_MESSAGE_HERE"
- Push to GitHub: git push origin YOUR_BRANCH_NAME
- Create Pull Request (PR)
- Merge PR
- Update your local dev branch: git checkout dev && git pull origin dev
- Delete your branch that was just submitted: git branch -D YOUR_BRANCH_NAME