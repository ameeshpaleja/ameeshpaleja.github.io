# ai-lab-backup

ai-lab-backup is a personal backup tool used only by its owner for a private home lab. It uses rclone to copy backup files from the owner's own machines to the owner's own Google Drive, and to read them back for restores.

It requests a single Google Drive permission, drive.file, which lets it see and manage only the files it creates. It cannot see anything else in the Drive. It is not offered to anyone else.

[Privacy policy](https://ameeshpaleja.github.io/privacy.html)
