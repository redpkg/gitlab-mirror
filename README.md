# GitLab Mirror
Backup all repos from GitLab.

# Usages
Copy `.env.example` to `.env`, and set up config.

```
// Your personal access tokens, need api scope.
PRIVATE_TOKEN=

// Group name you want backup, you can set subgroup like group/subgroup.
GROUP_NAME=

// Backup directory you want.
BACKUP_PATH=./mirrors
```

Run `pipenv install` install dependencies, and run `pipenv run python main.py` to start backup.
