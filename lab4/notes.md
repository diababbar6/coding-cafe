A1) The --global flag tells Git to apply this name and email configuration across the entire user account on the computer. This means every Git repository created or work on in the future will automatically use these credentials
 by default.

A2) The hidden folder named .git appears when running ls -a, but stays hidden when running a regular ls. In Unix-like operating systems, any file or folder whose name begins with a dot (.) is hidden by default. 

A3) Git is offering to track thousands of files and folders. The .venv/ folder contains a massive amount of code that I did not write; it belongs to the Python virtual environment, which stores external libraries and dependencies.

A4) The .venv/ folder (along with any other items matching the rules in the .gitignore file, like __pycache__/ or .DS_Store) has disappeared from the list of untracked files.

A5) It should be committed. The .gitignore file needs to be tracked by Git so that the ignore rules are shared with everyone else working on the project, ensuring that every team member automatically ignores the same temporary or junk files.

A6)• The two headings: It moved from "Untracked files:" to "Changes to be committed:".
   • Three-places model: The file moved from the Working Directory into the Staging Area (also known as the Index).

A7)• What Git printed: Git printed a summary containing the branch name, the abbreviated commit hash,  commit message (Lab work so far), and a line showing the number of files changed alongside insertions and deletions.
   • Files changed: It typically reports 2 files changed (the README.md and the .gitignore file created in the previous section).

A8) They are called the short SHA-1 hash (or short commit hash).They are used as they act as a unique ID for that specific commit.
    One can use them to easily reference, inspect, or checkout that exact point in a project's history without needing to type the full 40-character hash.

A9) 1. git status – Check the state of the working directory and staging area.
    2. git add – Stage the modified or new files.
    3. git commit – Save the staged changes permanently into the repository history.
    4. git log (or git log --oneline) – Verify the commit was successfully recorded in the project history.

A10) It is placed in the root folder because platforms like GitHub automatically display it on the repository's front page, acting as the main introduction and guide for the project.

A11) It safely authenticates the  machine via a browser login flow and automatically sets up a secure git credential helper. This caches the authentication token locally so Git can reuse it for future pushes without asking for a password.

A12) The contents of README.md are showing. GitHub is built to automatically detect this file in the root directory and render its formatted text as the homepage introduction for the repository.

A13) No, pushing does not changes the  local history. It only updates the remote repository on GitHub by uploading the commits that are  already created locally.

A14) Making it private doesn't mean that the git hub repository doesn't exit, it just changes to whom it's visible, in this case, only the author and the collaborators can view it.
     This would prevent the public from being able to see it as a  result.
