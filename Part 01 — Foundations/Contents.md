## Part 01 — Foundations

| # | Term | Meaning | What it does / why it matters | 60-second video suggestion |
| --- | --- | --- | --- | --- |
| T001 | **Git** | The name of a distributed version control system; it is not an official acronym. | Records project snapshots and connects them through history. | Open with the name myth, then show one commit. |
| T002 | **Version control** | A way to record and compare versions of files. | Lets you inspect earlier work and coordinate changes. | Change one line and compare two versions. |
| T003 | **Distributed version control** | A model in which clones keep local history. | Enables local commits and collaboration without a single required server. | Disconnect the network and make a local commit. |
| T004 | **Repository** | The Git history, references, and settings for a project. | Stores commits and makes the project navigable. | Point to files, then reveal the repository metadata. |
| T005 | **Local repository** | A repository on your own machine. | Supports local commits, branches, and inspection. | Commit locally before showing any server. |
| T006 | **Remote repository** | A repository accessed through a named network location. | Exchanges refs and objects with other clones. | Show the same commit locally and on Gitea. |
| T007 | **Bare repository** | A repository with no checked-out working tree. | Commonly serves as a shared Git endpoint. | Compare the files in a bare and normal clone. |
| T008 | **Clone** | A local copy made from another repository. | Copies reachable history and sets up a remote. | Clone a demo project and inspect its remotes. |
| T009 | **Project root** | The top directory of the checked-out project. | Anchors paths and usually contains the .git entry. | Run a command from a subfolder, then locate the root. |
| T010 | **.git directory** | The repository's local metadata directory, or a pointer file in linked worktrees. | Holds objects, refs, configuration, and other Git state. | Show why deleting .git loses local history. |
