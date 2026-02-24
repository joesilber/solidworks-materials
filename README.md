# solidworks-materials
This repo is for sharing material definitions among [LBNL engineers](https://engineering.lbl.gov/), for use in SolidWorks.

Initial discussion for the sharing approach was discussed in these [slides of 2026-02-18](2026-02-18_solidworks_materials_sharing_strategy.pdf).

## Change approval rules
As of this writing (2026-02-24) we have two rules applied in GitHub which relate to approval of changes.

1. **Require a pull request before merging**.
    - *All commits must be made to a non-protected branch and submitted via a pull request before they can be merged.*
2. **Require conversation resolution before merging**.
    - *All conversations on code must be resolved before a pull request can be merged.*

## Making changes: The "pull request" sequence

1. **Create a branch** from `main` — give it a short descriptive name (e.g. `update-aluminum-density`).
2. **Make your edits** on that branch and commit them.
3. **Push the branch** to GitHub and open a **Pull Request** targeting `main`.
4. **Discussion happens** in the PR — reviewers can comment on specific changes, and you can push additional commits to address feedback.
5. **Once all conversations are resolved**, the PR can be merged into `main`.

All changes must go through this process. Commits can't be done directly to the `main` branch. 
