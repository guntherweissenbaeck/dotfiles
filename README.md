# Managing Dotfiles Using yadm

If you have an existing remote repository
Clone your existing repo using yadm.

```bash
yadm clone <url>
yadm status
```

If you don’t currently have a repository
Start out with an empty local repository

```bash
yadm init
yadm add <important file>
yadm commit
```

Eventually you will want to push the local repo to a remote.

```bash
yadm remote add origin <url>
yadm push -u origin <local branch>:<remote branch>
```
