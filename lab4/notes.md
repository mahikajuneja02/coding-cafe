\# Lab 4 Notes



\## Question 1

`--global` sets the user name and email globally for all Git repositories under the current user account. If left out, the settings would apply only to the current local repository.



\## Question 2

The hidden `.git` directory appeared in `ls -a`. It contains Git's internal tracking configuration, commit history, branch references, and repository objects.



\## Question 3

Git offered to track hundreds or thousands of files. Directories like `.venv/` contain virtual environment files and temporary python dependencies that I did not write.



\## Question 4

The `.venv/` directory and compiled temporary files (`\_\_pycache\_\_/`, `.DS\_Store`) disappeared from the list of untracked files in `git status`.



\## Question 5

Yes, `.gitignore` should be committed. Committing it ensures that all collaborators cloning the repository share the same file exclusion rules.



\## Question 6

`README.md` moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the Working Directory into the Staging Area (Index).



\## Question 7

Git printed the commit summary, including the current branch name, short commit hash (`2ef56d4`), and file change metrics showing 2 files changed with 6 insertions.



\## Question 8

The first seven characters (`2ef56d4`) are the short commit hash (SHA-1 checksum). They serve as a unique identifier for that specific commit in the repository history.



\## Question 9

The four steps of the cycle are:

1\. Modify files in the working directory

2\. Inspect changes using `git status`

3\. Stage files using `git add`

4\. Save snapshot using `git commit`



\## Question 10

`README.md` is automatically recognized by GitHub as the default front page and landing documentation for the repository.



\## Question 11

`gh auth login` authenticates via OAuth and saves a secure personal access token locally, eliminating the need to re-enter credentials on subsequent pushes.



\## Question 12

The contents of `README.md` are rendered as rich HTML on the repository home page because GitHub treats `README.md` as standard project documentation.



\## Question 13

No, running `git push` uploads local commits to the remote server, leaving local history completely unchanged.



\## Question 14

A private repository exists securely on GitHub servers accessible only to authorized collaborators, whereas a non-existent repository has no online storage or cloud backing.

