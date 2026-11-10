# Version Control Review Questions

## 1. What problem does version control solve?

It records how project files change over time. Developers can compare versions, return to earlier work, and collaborate without passing files back and forth.

## 2. What is the difference between Git and GitHub?

Git is the version control tool that runs locally and records project history. GitHub hosts Git repositories online and adds collaboration features such as pull requests and code reviews.

## 3. What do `git add` and `git commit` do?

`git add` stages selected changes for the next snapshot. `git commit` saves the staged changes in the repository history with a message.

## 4. What is a branch used for?

A branch is a separate line of work. It lets a feature or fix be developed without changing the main branch until the work is ready to merge.

## 5. What causes a merge conflict, and how do you resolve one?

A conflict happens when Git cannot automatically combine changes, often because two branches changed overlapping lines. Read the conflict markers, decide what the final file should contain, remove the markers, stage the resolved file, and commit the result.

## 6. What is a pull request?

A pull request proposes merging one branch into another on GitHub. It gives collaborators a place to inspect changes, discuss them, request updates, and approve the work.

## 7. What should you check before committing?

Use `git status` to see what is staged and unstaged, review the diff, and confirm that only the intended files are included. Then use a short, clear commit message.

## 8. What does `git pull` do?

It fetches new commits from a remote repository and integrates them into the current local branch.

## 9. How is `git reset` different from `git revert`?

`git reset` moves the current branch pointer and can remove commits from the visible history. `git revert` creates a new commit that undoes the changes from an earlier commit, which is usually safer for shared history.

## 10. Why review another developer's pull request?

Review can catch bugs, unclear code, accessibility issues, and missing requirements before a change is merged. It also gives the team a shared understanding of the code.

## Study guide note

These are practice questions about the module topics, not answers to the Canvas KBA. The KBA presents its own assessment questions and must be completed independently.
