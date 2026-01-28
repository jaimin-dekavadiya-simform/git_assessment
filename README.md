# Git Assessment Project

## Overview
This repository contains my Git assessment project.  
The goal of this project is to demonstrate my understanding of:
- Git basics (init, clone, status, add, commit)
- Branching and merging
- Working with remote repositories (GitHub)

## Screenshot
Below is a screenshot representing the Flow and Structure of Repository:

![Flow](./docs/Screenshot%20from%202026-01-28%2017-03-38.png)

## Branch Operations

- Created a template repository. Using that created a Assessment Repository.
- commit-msg Hook is modified to only accept commit-message which starts with ZOHO_TASK_ID (i.e. "TE_T102 initial commit")
- TE-T102 is created with multiple commits and rebased on develop.
- TE-T103 is created with multiple commits and Squashed on develop.
- TE-T201 is created with one readme commit.
- TE-T202 is created and I cherry-picked commit of T201 into T202 ( T201 is not visible because I forgot to push T201 to remote and my local was deleted afterwards.)
- TE-T202 is commited with four commits, Last commit is deleted and commit-message is edited then merged with develop.
- Develop is merged with Main.
- HotFix - Update readme is performed on main with branch TE-T301
- TE-T401 is created from develop to make some changes finalising the version and merged with develop.
- Develop is merged with Main with a Released Version Tag v1.0.0
