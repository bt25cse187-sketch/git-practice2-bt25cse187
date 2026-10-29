# Exercise 02: Branching and Merging

## Objective
Learn how to create a Git branch, make changes, commit them, and merge the branch into the main branch.

## Steps Performed
1. Created a sample text file.
2. Created a feature branch.
3. Modified the sample file in the feature branch.
4. Committed the changes.
5. Merged the feature branch into the main branch.
6. Checked the Git status and commit history.

## Commands
```bash
git switch main
git switch -c feature/exercise-02
git add exercise-02/sample.txt
git commit -m "Update exercise 02 sample file"
git switch main
git merge feature/exercise-02
git log --oneline
git status
```

## Result
The feature branch was merged into the main branch successfully.
