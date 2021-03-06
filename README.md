# Automatic Off-site Backups of Cloud Applications 

This is a set of utilities and scripts to handle automatic 
synchronization of remote servers to your home folder according
to a schedule.

* These Scripts are Designed for use with Mac OS (localhost).
* Includes Per-Run Logging and Auto-Cleanup of Old Log Files.
* Example Backup Script & LaunchAgent Template included in Documentation.
* Uses MacOS Notification Center & Auto-Opens Logfile with Console.app when done.
* Tested with DigitalOcean (Ubuntu) Droplet & DigitalOcean Spaces & MacOS Mojave 10.14.5
* Supports most servers and cloud storage providers (See [Rclone Docs](https://rclone.org/docs/)).

Copy the repo to your local home folder and rename it 
"**BackupTool**".

Required Dependency: [Rclone](https://rclone.org/install/).

1) [Configuration.md](https://github.com/bayareawebpro/offsite-cloud-backups/blob/master/docs/1-Configuration.md)
2) [BackupScript.md](https://github.com/bayareawebpro/offsite-cloud-backups/blob/master/docs/2-BackupScript.md)
3) [LaunchAgent.md](https://github.com/bayareawebpro/offsite-cloud-backups/blob/master/docs/3-LaunchAgent.md)
4) [SSH-Examples.md](https://github.com/bayareawebpro/offsite-cloud-backups/blob/master/docs/4-SSH-Examples.md)

##### Example Log Output:
```
===Cloud Backup 2019-06-04@03:00AM===
Dumping Remote Databases...
Synchronizing Database Snapshots...
Synchronizing CDN Storage...
Backup Completed Successfully.
Old Log Files Trimmed.
```
