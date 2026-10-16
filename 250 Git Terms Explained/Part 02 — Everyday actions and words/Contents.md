## Part 02 — Everyday actions and words

| # | Term | Meaning | What it does / why it matters | 60-second video suggestion |
| --- | --- | --- | --- | --- |
| T011 | **Snapshot** | A recorded state of a project at a point in history. | Lets a commit refer to complete file content rather than a bare list of edits. | Compare two snapshots and highlight the changed paths. |
| T012 | **Initialize** | Create repository metadata for an existing or new directory. | Turns a folder into a local Git repository. | Run `git init` and reveal the new Git state. |
| T013 | **Status** | Git's report of branch, staged, unstaged, and untracked state. | Answers what would go into the next commit. | Read a short `git status` after three kinds of edits. |
| T014 | **Add** | Put file content or selected changes into the index. | Chooses what the next commit will include. | Add one file while leaving another out. |
| T015 | **Checkout** | Select a branch or commit, or restore paths from a source. | Updates HEAD, index, and/or working files depending on form. | Contrast branch checkout with file checkout. |
| T016 | **Switch** | Change the current branch or detach at a commit. | Moves a worktree to another line of development. | Switch branches and observe changed files. |
| T017 | **Log** | A view of commit history. | Lets you follow changes and branch structure. | Compare a one-line log with a graph log. |
| T018 | **Show** | A command displaying an object or commit's details. | Reveals a commit message, metadata, and patch. | Open one commit by ID. |
| T019 | **Remove (`git rm`)** | A command that removes paths from the index and usually the working tree. | Stages tracked-file removal. | Compare ordinary file deletion with `git rm`. |
| T020 | **Move (`git mv`)** | A convenience command that moves a path and stages the result. | Records the new path; rename display is inferred when comparing snapshots. | Move a file and inspect the staged diff. |