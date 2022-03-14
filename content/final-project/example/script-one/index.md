---
title: "Initialization & First Time Deployment Script"
date: 2022-03-10T15:47:05-06:00
draft: false
weight: 1
originalAuthor: ""
originalAuthorGitHub: ""
reviewer: "" # to be set by the approving reviewer
reviewerGitHub:
lastEditor: ""
lastEditorGitHub: ""
lastMod: "2022-03-10"
---

## Example

Pictures of the output of using the script in all states:

- completely successful
- successful but first time deployment failed
- not successful before deployment

## Validation

After running the script the pictures of proof of validation including:

- tools installed successfully
  - `which package` or `package --version` commandss
- remote repo cloned
  - `ls /path/to/clone/location`
  - `cd /path/to/clone/location` & `git remote --v`
- build artifacts created & moved
  - `ls /path/to/artifact/location`
- unit file exists
  - `ls /path/to/unit-file/location`
- deployment currently running
  - `systemctl status [unit-name]`
  - picture of browser with project accessible on port
- email sent
  - picture of email in personal account from server
- crontab successfully edited
  - `crontab -l`