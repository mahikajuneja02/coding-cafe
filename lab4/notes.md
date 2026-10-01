# Coding Café
Lab work for Coding Café, FM102.

**Name:** Mahika Juneja  
**Roll number:** U20260133  

## Contents
- `lab1/` — terminal
- `lab2/` — variables, types, operations, I/O
- `lab3/` — conditionals and loops
- `lab4/` — git and GitHub

# Lab 4 Notes

## Question 1
The `--global` flag applies the user configuration across all Git repositories on your system. If you omit it, the configuration is set only for the local repository you are currently in, which fails if you are not inside an initialized Git repo.

## Question 2
Running `ls -a` reveals the hidden `.git` directory, which standard `ls` hides. Inside `.git` are internal subdirectories and files—such as `objects/`, `refs/`, `HEAD`, and `config`—that store the repository's full commit history and configuration.

## Question 3
Git offers to track hundreds or thousands of files when unconfigured, mostly located inside `.venv/`. The files inside `.venv/` represent third-party Python virtual environment packages rather than code written by hand.

## Question 4
After creating `.gitignore`, all files and patterns specified inside it (such as `.venv/` and `__pycache__/`) disappear from the untracked list in `git status`. Only `.gitignore` itself appears as an untracked file ready to be staged.

## Question 5
The `.gitignore` file should be committed because it ensures the rules for ignoring untracked files are shared with collaborators and tracked in project history. If ignored, each team member would have to recreate it manually, risking accidental tracking of clutter files.

## Question 6
`README.md` moved from "Untracked files" to "Changes to be committed". In the three-places model, this action moved the file from the Working Directory into the Staging Area (Index).

## Question 7
Git prints a short summary containing the branch name (`main`), the commit hash, the commit message, and the number of changed files and insertions. For this first commit, Git indicates that all staged files were committed with their respective lines created.

## Question 8
The first seven characters of a commit hash are called the short SHA-1 hash or commit ID. They serve as a unique identifier for that specific snapshot in Git's log and history.

## Question 9
The four steps of the Git loop are edit (modify files in your directory), check status (`git status`), stage (`git add`), and commit (`git commit`). Repeat these steps whenever you reach a logical unit of completed work.

## Question 10
`README.md` has a special name and location because code hosting platforms like GitHub automatically render it as the home/landing page of the repository. It gives visitors and reviewers an immediate overview of the repository's purpose, setup, and author details.

## Question 11
`gh auth login` authenticates your machine using an OAuth token or SSH key stored securely in your system's credential helper. This saved credential allows Git to push and pull securely without prompting for a password on every command.

## Question 12
`README.md` is rendered automatically on the main page of the repository. GitHub is designed by default to look for a `README` file in the root directory and display its formatted content for anyone viewing the repository.

## Question 13
No, running `git push` does not alter or rewrite your local commit history. It simply uploads your existing local commits to the remote repository on GitHub so both stay in sync.

## Question 14
A private repository exists securely on GitHub's servers, accessible only to you and explicit collaborators you invite, such as TAs. A non-existent repository does not exist anywhere online, meaning no one can collaborate on it or review its code.