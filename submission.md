# Checkpoint 2 Submission

> Complete this file on your required `cp2-YOUR-GITHUB-USERNAME` branch.
> The grader reads this file from the Pull Request's stored **head commit**, so it still works after merge or branch deletion.
> GitHub detects the Pull Request number automatically.

Name: Aubrey  
GitHub Username: aubreyzhu66-collab  
Required Branch: cp2-aubreyzhu66-collab

## Commands Used

I completed this version through the GitHub web interface:

```text
Created cp2-aubreyzhu66-collab from main
Edited feature.txt and committed "Update feature description"
Edited submission.md and committed "Complete CP2 submission"
```

## Question 1 — Branch Safety

Why should you avoid implementing this checkpoint directly on `main`?

Answer: `main` should remain a stable integration branch. A feature branch isolates incomplete work, makes the exact changes easy to compare in a Pull Request, and allows review before anything is integrated into `main`.

## Question 2 — Stage vs Commit

What is the difference between `git add` and `git commit`?

Answer: `git add` selects the current contents of specific files and places them in the staging area for the next commit. `git commit` records a permanent local snapshot of everything currently staged, together with a meaningful message; it does not push that snapshot to GitHub.

## Question 3 — Push, Pull Request, Review, Merge

Explain what changes when you push a branch, open a Pull Request, receive a review, and merge the Pull Request.

Answer: Pushing publishes the local branch and its commits to `origin`. Opening a Pull Request proposes merging that branch into `main` and provides a place to inspect the diff and discuss it, but it does not change `main`. A submitted review records another user's approval or requested changes. Merging after approval integrates the Pull Request's changes into `main` and preserves the review and merge history as evidence.

## Reflection

Which checkpoint in the branch → PR → review → merge workflow is most useful for preventing mistakes, and why?

Answer: The required APPROVED review before merge is the most useful checkpoint because it adds an independent check before `main` changes. The reviewer can confirm that the branch targets `main`, that only the two permitted files changed, and that the submission is complete. This catches mistakes while they are still easy to fix and leaves a clear audit trail.
