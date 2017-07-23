# Testing for Sensitive Data in Backups

The following feature automatically creates a backup of the app data and then checks if sensitive information are stored.

The following folders myust be inspected for backup data:

* Documents/
* Library/Caches/
* Library/Application Support/
* tmp/

## Reference

https://github.com/OWASP/owasp-mstg/blob/master/Document/0x06d-Testing-Data-Storage.md#testing-for-sensitive-data-in-backups