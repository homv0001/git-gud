# Git Gud Template Repository 
A beginner-friendly Git &amp; GitHub **template repository** to help you learn and practice Git and GitHub basics. Accompanies our Git Gud: A Guide to Git &amp; GitHub workshop.

Click the green **"Use this template"** button above to create your own copy of this repo.

## Task 1: Getting Started
- Go to https://github.com/compsci-adl/git-gud
- Use this template
- Clone your repo
- Open repo in VS Code

## Task 2: Make a Change
Edit INTRO.md by adding your name to the description, stage your changes, make a commit and push it. 

## Task 3: Create a Branch
Create and switch to a new branch called feature/more-info and update INTRO.md to include your city and country and whether you are a uni student. Then commit changes and push. Repeat for feature/duck-info with below info:

- **First Name:** Donald
- **Last Name:** Duck
- **City:** Duckburg
- **Country:** United States

- **Are you a university student?**  
    - [ ] At The University of Adelaide  
    - [ ] At another university  
    - [x] No

## Task 4: Merge Branch
Merge your new branch into the main branch by making a PR and clicking squash and merge. Delete the branch when done.

## Task 5: Resolving Merge Conflicts
Switch to the feature/duck-info branch and try to make a PR for it. Fix the merge conflicts.

## Task 6: Stashing
Modify INTRO.md, stash the changes, and then apply them.

## Task 7: Rewind
- For INTRO.md, make and commit two changes (no need to push them)
- Use `git log` to find the commit hashes
- Reset: Run `git reset --soft <first-commit-hash>` to move HEAD back but keep changes staged
- Check the status with `git status`
- Revert: Run `git revert <second-commit-hash>` to create a new commit that undoes that change
- Check the commit history with `git log`

## Task 8: Stars
- Go to the CS Club GitHub Organisation https://github.com/compsci-adl
- Find some projects you like
- Click the ⭐ button at the top-right of the repository page


