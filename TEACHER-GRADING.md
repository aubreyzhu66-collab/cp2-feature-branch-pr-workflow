# CP2 Teacher Grading Guide

Checkpoint 2 uses a **60 automatic + 40 teacher = 100 total** model.

The automatic grader checks the branch/PR lifecycle, including a human approval **before** merge. The teacher grades the reasoning in `submission.md` and the quality of the completed Pull Request workflow.

## Teacher rubric — 40 points

| Category | Points | What to look for |
|---|---:|---|
| Branch safety | 10 | Student understands why feature work belongs on a feature branch rather than directly on `main`. |
| Git workflow explanation | 10 | Student accurately explains staging, committing, and pushing. |
| Pull Request understanding | 10 | Student distinguishes push, Pull Request, review, approval, and merge. |
| Reflection & work quality | 10 | Reflection is specific; commit/PR work is intentional and clear. |

## Fixed grading comment

Grade in the **mother-repository CP2 submission Issue** with:

```text
/manual-grade
Branch safety: 0/10
Git workflow explanation: 0/10
Pull Request understanding: 0/10
Reflection & work quality: 0/10

Feedback:
Write concise feedback here.
```

The newest valid grading comment by `hbycwyh2008` is used. A short-form override remains supported:

```text
/manual-grade 36
```

## Recommended teacher check

Open the merged Pull Request and confirm that the student can explain why pushing a branch is not the same as merging it, why review happens before merge, and why deleting the feature branch after merge does not erase the Pull Request history.
