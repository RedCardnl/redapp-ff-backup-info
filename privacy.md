# Privacy Policy

redapp ff_backup is a personal backup utility operated by the account owner.

## Google Drive access

The utility uses rclone and the Google Drive API to list existing backup files and upload logs and reports from the owner's redapp servers to Google Drive. The configured backup locations are:

- `funding_rollback/runtime/v1`
- `funding_rollback/raw/v1`

The OAuth permission requested by rclone is `drive`. This permission can technically allow broad access to Google Drive files, although this backup workflow uses the configured backup locations.

## Storage and sharing

The rclone OAuth token is stored in the rclone configuration on the owner's main server. Backup files are stored in the owner's Google Drive. This website does not store backup files.

The utility is for the account owner's personal use. Data is not intentionally shared with other users or used for advertising.

Backup files remain in Google Drive until the account owner deletes them. The account owner can revoke the utility's Google access in [Google Account connections](https://myaccount.google.com/permissions).

## Contact

For questions about this utility or this policy, contact the support email shown on the Google authorization screen.
