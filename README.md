## rclone-snap
[![rclone](https://snapcraft.io/rclone/badge.svg)](https://snapcraft.io/rclone)

[Rclone Project Link](https://github.com/rclone/rclone) 

Rclone ("rsync for cloud storage") is a command-line program to sync files and directories to and from different cloud storage providers.

Please note that this is a `community-maintained package`. Use at your own risk.
  
Due to the strict permissions control of Snap, some features may `not` work.

Due to my limited time and knowledge, problems might not receive fixes.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/rclone)

## Requirements

[Snap installed](https://snapcraft.io/docs/installing-snapd)

## Install

```bash
$ sudo snap install rclone
```

## Usage

see: [Official Docs](https://rclone.org/docs/)


## Data & Config file location

Due to the packaging with Snap, the default paths are different.

- Default config directory: /home/$Your_User_Name/snap/rclone/current/.config/rclone
- Mountpoint can only exist in snap-specific writable directories:
    - SNAP_USER_{DATA,COMMON}: /home/$USER/snap/rclone/{common,current}
    - SNAP_{DATA,COMMON}: /var/snap/rclone/{common,current}


