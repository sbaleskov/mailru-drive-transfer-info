---
layout: default
title: Privacy policy — MailRu Drive Transfer
---
# Privacy policy

Effective date: 15 October 2026.

MailRu Drive Transfer is a personal file migration tool operated on the Google account owner's Mac. These pages document the tool; this website does not receive the owner's cloud files or OAuth tokens.

## Data accessed and purpose

The tool accesses file and folder names, paths, sizes, modification times, and file contents in the source Mail.ru Cloud and destination Google Drive. It uses this information to copy the owner's files to Google Drive, skip matching destination files, and verify file sizes. Google Drive OAuth authorization is requested for this migration. The Google consent screen describes the permissions granted to the application.

## Data flow and sharing

File contents are streamed from Mail.ru Cloud through the owner's Mac to the owner's Google Drive. The workflow does not create a full intermediate file archive on the Mac. It does not send files to a separate service operated by this application's developer. Mail.ru and Google process data under their own terms and privacy policies. This tool does not sell data, use it for advertising, or use it to train AI models.

## Local storage and retention

OAuth client settings, access and refresh tokens, source credentials, and operational logs are stored locally on the owner's Mac. Logs can contain file names, paths, transfer statistics, and error messages. Local configuration files are restricted to the account owner. Transfer logs are bounded and rotated. Copied files remain in the owner's Google Drive until the owner removes them.

## Owner's controls

The owner can stop the local transfer, remove its macOS background service, revoke access through the Google account's third-party access settings, and remove local configuration and logs. Revoking access prevents subsequent authorized requests but does not remove files already copied to Google Drive.

## Support

Questions about this personal tool can be submitted through [the project's issue tracker](https://github.com/sbaleskov/mailru-drive-transfer-info/issues). Do not include credentials, tokens, or private file contents in public issues.

[Home](index.html)
