# Checkpoint 2 — Feature Branch, Pull Request, Review & Merge

## Goal

Show that you can complete the core Git collaboration workflow without developing directly on `main`.

```text
clone
→ create feature branch
→ edit
→ git status
→ git add
→ git commit
→ git push
→ open Pull Request
→ review
→ merge
```

CP2 focuses on the branch/PR lifecycle. CP3 adds Issues and Project/Kanban tracking to that lifecycle.

## Start the exercise

[![Copy Exercise](https://img.shields.io/badge/COPY%20EXERCISE-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=GitHub-Feature-Branch-Pull-Request-Workflow&owner=%40me&name=cp2-feature-branch-pr-workflow&description=Checkpoint+2:+Feature+Branch+%26+Pull+Request+Workflow&visibility=public)

Keep the copied repository **Public** so the mother repository can inspect the evidence.

After the copy is created:

1. Wait for the **Exercise Issue** to appear automatically.
2. Open that Issue and note your exact required branch.
3. Clone the repository locally.
4. Complete the work on the required CP2 branch.
5. Open a Pull Request, get it reviewed, then merge it.

You do **not** need to open **Actions** or manually run a workflow.

## Required branch

```text
cp2-YOUR-GITHUB-USERNAME
```

Example: `cp2-octocat`.

The Pull Request must use this branch as the **head/source branch** and `main` as the **base/target branch**.

## Challenge

On your required CP2 branch:

1. Replace the starter line in `feature.txt` with a short feature description.
2. Complete `submission.md`.
3. Use `git status` before and after staging.
4. Stage the intended files with `git add`.
5. Commit with a meaningful message.
6. Push the CP2 branch to `origin`.
7. Open a Pull Request from `cp2-YOUR-GITHUB-USERNAME` → `main`.
8. Request review from another GitHub user.
9. Receive at least one submitted **APPROVED** review.
10. Merge only **after** the approval.

The Pull Request should change only:

```text
feature.txt
submission.md
```

GitHub detects the Pull Request automatically. Do **not** enter a PR number in `submission.md`.

After merge, deleting the feature branch is allowed. The grader uses the Pull Request's stored head ref/SHA, review history, and merge timestamp as durable evidence.

## Automatic grading — 60 points

| Evidence | Points |
|---|---:|
| Correct CP2 branch identity | 5 |
| `feature.txt` changed on the PR head | 10 |
| At least one commit belongs to the PR | 5 |
| PR changes only `feature.txt` and `submission.md` | 5 |
| `submission.md` is complete on the PR head | 10 |
| Pull Request targets `main` | 5 |
| Human **APPROVED** review submitted before merge | 10 |
| Pull Request merged after approval | 10 |
| **Automatic total** | **60** |

The original **Exercise Issue** is the student-facing status page. Its score comment updates in place.

## Submit for teacher grading

Submit only after the PR has been approved and merged:

[![Submit CP2](https://img.shields.io/badge/SUBMIT%20CP2-%E2%86%92-0969da?style=for-the-badge&logo=github)](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow/issues/new?template=cp2-submission.yml)

Repository URL and GitHub username are detected automatically.

Teacher rubric:

- Branch safety — 10
- Git workflow explanation — 10
- Pull Request / review understanding — 10
- Reflection & work quality — 10

```text
Student repository
→ automatic /60
→ approved review
→ merge
→ Submit CP2
→ mother repository /manual-grade /40
→ teacher grade syncs to the original Exercise Issue
→ Final score /100
```

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| **CP2 — You are here** | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| CP4 | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
