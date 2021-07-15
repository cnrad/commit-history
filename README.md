# readme.md

This repo is only to set commits that happened before my join date on this account, for whatever reasons

```bash
set GIT_COMMITTER_DATE='YYYY-MM-DD HH:MM:SS'
set GIT_AUTHOR_DATE='YYYY-MM-DD HH:MM:SS'
git commit -m "message" --date="YYYY-MM-DD HH:MM:SS" --amend --no-edit
```

Revert to normal:

```bash
set GIT_COMMITTER_DATE=
set GIT_AUTHOR_DATE=
```
