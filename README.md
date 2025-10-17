# Grand Magus Alistair's Blog Backups

Automated daily backups of blog-posts.json from the mageblog project.

## Structure

```
backups/
  YYYY/
    MM/
      YYYY-MM-DD-blog-posts.json
```

## Backup Schedule

Backups are created automatically every day at 12 PM Central Time (18:00 UTC) via GitHub Actions.

## Retention

All backups are retained indefinitely for historical record-keeping.

## Restoration

To restore from a backup:
1. Navigate to the desired date's backup file
2. Copy the contents
3. Replace the current blog-posts.json in the mageblog repository

---

*Automated by [mageblog-automation](https://github.com/masterbainter/mageblog-automation)*
