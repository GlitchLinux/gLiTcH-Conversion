# gLiTcH Linux Conversion Script

A powerful bash script to convert a running Debian system to gLiTcH Linux KDE v9.0.

```plaintext
      _____     ____         ____  _________________       _____    ____   ____
  ___|\    \   |    |       |    |/                 \  ___|\    \  |    | |    |
 /    /\    \  |    |       |    |\______     ______/ /    /\    \ |    | |    |
|    |  |____| |    |       |    |   \( /    /  )/   |    |  |    ||    |_|    |
|    |    ____ |    |  ____ |    |    ' |   |   '    |    |  |____||    .-.    |
|    |   |    ||    | |    ||    |      |   |        |    |   ____ |    | |    |
|    |   |_,  ||    | |    ||    |     /   //        |    |  |    ||    | |    |
|\ ___\___/  /||____|/____/||____|    /___//         |\ ___\/    /||____| |____|
| |   /____ / ||    |     |||    |   |`   |          | |   /____/ ||    | |    |
 \|___|    | / |____|_____|/|____|   |____|           \|___|    | /|____| |____|
   \( |____|/    \(    )/     \(       \(               \( |____|/   \(     )/
    '   )/        '    '       '        '                '   )/       '     '
       ____         ____  _____   ______    ____   ____
      |    |       |    ||\    \ |\     \  |    | |    |_____      _____
      |    |       |    | \\    \| \     \ |    | |    |\    \    /    /
      |    |       |    |  \|    \  \     ||    | |    | \    \  /    /
      |    |  ____ |    |   |     \  |    ||    | |    |  \____\/____/
      |    | |    ||    |   |      \ |    ||    | |    |  /    /\    \
      |    | |    ||    |   |    |\ \|    ||    | |    | /    /  \    \
      |____|/____/||____|   |____||\_____/||\___\_|____|/____/ /\ \____\
      |    |     |||    |   |    |/ \|   ||| |    |    ||    |/  \|    |
      |____|_____|/|____|   |____|   |___|/ \|____|____||____|    |____|
        \(    )/     \(       \(       )/      \(   )/    \(        )/
         '    '       '        '       '        '   '      '        '

## Features

- Converts any Debian to gLiTcH Linux KDE v9.0 with a single command
- Comprehensive system backup before making changes
- Handles package database migration
- Preserves important system configurations
- Special handling for:
  - Encrypted systems
  - NVIDIA drivers
  - Secure Boot systems
- Creates a recovery script for rollback

## Usage

Simply run the script as root and follow the prompts:

```bash
sudo ./gLiTcH-Conversion.sh
```

The script will:
1. Verify system compatibility
2. Create backups of critical files
3. Download the gLiTcH Linux ISO (if needed)
4. Convert your system to gLiTcH Linux
5. Set up the KDE Plasma environment
6. Configure bootloader and system settings

## Safety Features

- Automatic backup of critical system files to `/root/debian-backup-*`
- Recovery script generation
- Comprehensive error checking
- Cleanup on interruption
- Log file at `/var/log/glitch-conversion.log`

## Warning

❗ This script makes deep system modifications that could render your system unbootable if interrupted. Always:
- Back up important data first
- Run on a system you can afford to lose
- Have a recovery USB handy

## Support

For support, visit [gLiTcH Linux Website](https://www.glitchlinux.wtf)
