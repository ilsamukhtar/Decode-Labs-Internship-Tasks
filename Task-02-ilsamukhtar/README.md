# Task 02 — Version Control with Git

## Overview

This project demonstrates the fundamentals of version control using Git and GitHub.

The objective of this task was to understand how Git can be used to track changes, manage branches, create commits, and collaborate through a remote GitHub repository.

## Objectives

- Understand the basic Git workflow
- Initialize and manage a Git repository
- Track project changes
- Create and manage branches
- Stage and commit changes
- Merge changes into the main branch
- Push project changes to GitHub

## Git Workflow

The following workflow was practiced during this task:

```text
Working Directory
       ↓
    git status
       ↓
    git add
       ↓
   git commit
       ↓
    git push
       ↓
     GitHub

Branch-based development was also practiced:

main
  │
  └── feature/task-02
          │
          ├── Make Changes
          │
          ├── Stage Changes
          │
          └── Commit
                 │
                 ↓
              Merge
                 │
                 ↓
               main

Commands Practiced
Command	Purpose
git status	Check the current repository status
git checkout -b feature/task-02	Create and switch to a new feature branch
git add .	Stage changes for commit
git commit -m "message"	Save changes to Git history
git checkout main	Switch to the main branch
git merge feature/task-02	Merge the feature branch into main
git log --oneline	View the commit history
git push origin main	Push commits to GitHub
git remote -v	View the configured remote repository
Practical Workflow

The following Git workflow was performed during this task:

Checked the repository status.
Created a dedicated feature branch for Task 2.
Added the Task 2 project files.
Staged the changes using Git.
Created a commit with a descriptive message.
Switched back to the main branch.
Merged the feature branch into main.
Verified the commit history.
Pushed the updated repository to GitHub.
Project Structure
Task-02-ilsamukhtar/
├── README.md
└── git-workflow.txt
README.md

Contains an overview of the task, objectives, Git workflow, commands, and outcomes.

git-workflow.txt

Contains the Git commands used to demonstrate the version control workflow.

Outcome

Successfully practiced the fundamental Git workflow, including:

Repository management
Change tracking
Branch creation
Staging
Commits
Branch merging
Remote repository management
Pushing changes to GitHub

This task strengthened my practical understanding of Git, GitHub, branching, and version control workflows used in software development and DevOps environments.

Skills Demonstrated

Git | GitHub | Version Control | Branching | Commits | Merging | Repository Management | Collaboration Basics
