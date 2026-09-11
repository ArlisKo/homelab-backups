---
title: Homelab Backups privacy policy
---

# Privacy policy

Updated 11 September 2026. [Home](index.html)

## Purpose and operator

Homelab Backups is a personal backup utility operated by [ArlisKo](https://github.com/ArlisKo) for the operator’s own applications and Google account.

## Data processed

The utility archives application databases, uploaded files, configuration and custom application files for disaster recovery. Archives may contain personal records and configuration secrets. Google OAuth access and refresh tokens are stored on the backup server for authorization; they are not published on this site or included in the configured recovery archives.

## Google Drive access

The utility requests `drive.file` permission for files created by, or explicitly shared with, the utility. It uploads backup archives and reads file information or content to verify backups and perform recovery checks. Google user data is used only for backup and recovery.

## Storage and sharing

Backups are stored on the operator’s server and Google Drive account. They are not intentionally shared publicly. Data is not sold, used for advertising, or used to train AI models. Google processes Drive data under its own policies. GitHub Pages hosts this informational site and may process visitor connection information under [GitHub’s privacy policy](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement). These pages add no analytics, tracking scripts or forms.

## Retention and control

Cloud archives remain until the operator deletes them; there is no automatic cloud-retention deletion. The vehicle-maintenance backup replaces its latest validated local snapshot when a new snapshot is ready. The operator can delete archives from Drive and the server and revoke authorization through Google Account connections. Revoking access stops future authorized operations but does not delete existing archives.

## Contact

Contact the owner through [this project’s issues](https://github.com/ArlisKo/homelab-backups/issues). Do not post private records, credentials or backup contents in public issues.
