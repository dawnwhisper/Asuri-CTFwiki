# Asuri's CTF-wiki

This project is specially built for the Asuri offline competition. It is mainly used to display all documents saved offline, so that players can quickly retrieve and read the information they want to find.

Usage:
```bash
rm _sidebar.md
docsify g .
docsify s
```

bugs:
> 1. When there are too many files, the front-end global search is too slow.
> 2. If the file name starts with `.` or contains special characters such as `#`, the path will die and become 404