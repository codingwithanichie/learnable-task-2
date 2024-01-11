# learnable-task-2

# Explain version control.
A system for tracking and managing changes to files over time, typically used for software code but applicable to other file types as well

# Explain difference between git and github
Git tracks changes in files, creates snapshots of those changes (called commits), and allows you to revert to previous versions, manage branches, and collaborate with others.
WHILE 
Github provides a platform to store and manage Git repositories, offering additional features.

# List 3 other github alternatives
- GitLab
- Bitbucket
- Gitea

# Explain the difference between git fetch and git pull
git fetch is generally considered safer as it doesn't modify your local working directory, leaving you with the option to decide how to handle the changes later.
WHILE
git pull is faster and more convenient as it performs both download and merge in one step. However, it can cause merge conflicts if there are incompatible changes in your local branch and the remote repository.

# Explain in simple terms git rebase and the command for it
Rebasing is like picking up your branch (C) and neatly placing it on top of the latest commit in the main branch (E), creating a linear history.
git fetch origin
git rebase origin/main

# Explain in simple terms git cherry-pick and the command for it 
Imagine you're working on a project with your friend, and you both have your own branches. Let's call yours "feature_cool_button" and theirs "bug_fix_menu." You accidentally made a cool button animation that your friend needs for their bug fix, but integrating the whole "feature_cool_button" branch would mess up their changes.
git cherry-pick <commit-ID>
git cherry-pick --no-commit <commit-ID>
