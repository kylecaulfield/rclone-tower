---
title: rclone-tower privacy notice
---

# rclone-tower privacy notice

Last updated: October 30, 2026

rclone-tower is a personal OAuth client. Kyle Caulfield uses it so that rclone, running on his own home server, can mount his own Google Drive. It is not offered to the public and has a single user.

## What it accesses

Files and file metadata in the owner's Google Drive, through the Google Drive API scopes, so rclone can list, read, upload, rename and delete files on the owner's behalf.

## Where the data goes

Data moves directly between Google's servers and the owner's server. Files are cached temporarily on that server. Nothing is shared with any third party, sold, used for advertising, or used to train AI or machine learning models.

## Credentials

The OAuth token is stored only in rclone's configuration file on the owner's server.

## Google API Services User Data Policy

Use of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements.

## Revoking access

Remove "rclone-tower" at https://myaccount.google.com/permissions at any time.

## Contact

Open an issue at https://github.com/kylecaulfield/rclone-tower/issues
