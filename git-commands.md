Git Practice Record

Exercise 01: Basic Git Operations

Command

Purpose

git status

Checks the current repository status.

git add sample.txt

Stages the sample file for committing.

git commit -m "Add first practice file"

Saves the staged changes in Git history.

git log --oneline

Displays a short commit history.

Exercise 02: Branching and Merging

Command

Purpose

mkdir -p exercise-02

Creates the Exercise 02 directory.

cd exercise-02

Opens the Exercise 02 directory.

touch README.md sample.txt output.txt

Creates the three exercise files.

echo "Changes made in feature/exercise-02 branch." >> exercise-02/sample.txt

Appends a line to the sample file when run from the repository root.

git branch

Lists the local branches.

git switch -c feature/exercise-02

Creates and switches to the feature branch.

git add exercise-02/sample.txt

Stages the modified sample file.

git commit -m "Update exercise 02 sample file"

Commits the file changes.

git switch main

Switches back to the main branch.

git merge feature/exercise-02

Merges the feature branch into the current branch.

git status

Checks whether changes remain uncommitted.

git push origin main

Pushes the main branch to GitHub.

git push -u origin feature/exercise-02

Pushes the feature branch to GitHub and sets its upstream.

Other Useful Commands

Command

Purpose

git --version

Checks the installed Git version.

git config --global user.name "Bhargav Ram"

Sets the Git commit author name.

git config --global user.email "YOUR_GITHUB_EMAIL"

Sets the Git commit author email.

git clone REPOSITORY_URL

Downloads a repository from GitHub.

git remote -v

Displays the configured remote repositories.

git pull origin main

Fetches and integrates changes from the remote main branch.

Merge Conflict Record

Conflict encountered: No merge conflict has been encountered during this practice so far.

Explanation: A merge conflict occurs when Git cannot automatically combine changes, such as when two branches modify the same lines of a file differently.

Resolution: If a conflict occurs, inspect the conflicting file, choose the intended content, remove the conflict markers, save the file, and stage the resolved changes.

Example commands after resolving a conflict:

git status
git add README.md
git commit -m "Resolve README merge conflict"

Update this section if a real merge conflict is encountered and resolved.
