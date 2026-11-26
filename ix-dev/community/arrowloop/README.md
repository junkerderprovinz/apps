# ArrowLoop

[ArrowLoop](https://github.com/junkerderprovinz/arrowloop) keeps two folders in sync in both directions, on local disks or on any rclone backend such as SMB, SFTP, S3 or WebDAV. It remembers what both sides last agreed on, lists every change before a run, moves deleted files to a trash and stops a run that would delete more than half the known files.

<!-- x-readme:warnings:start -->

**!!! WARNING !!!**

This application can be granted additional elevated permissions beyond standard containerization protections, depending on the configuration. Use at your own risk.

The following additional privileges may be enabled from installing this application:

• Host Networking

<!-- x-readme:warnings:end -->
