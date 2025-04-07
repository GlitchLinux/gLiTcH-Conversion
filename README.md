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

- Converts Debian to gLiTcH Linux KDE v9.0 with a single command
- Comprehensive system backup before making changes
- Handles package database migration
- Preserves important system configurations
- Special handling for:
  - Encrypted systems
  - NVIDIA drivers
  - Secure Boot systems
- Creates a recovery script for rollback
- Beautiful ASCII art progress display

## Requirements

- A Debian-based system (Debian 10/11 recommended)
- Root access
- Minimum 8GB free disk space
- Stable internet connection

## Installation

1. Download the script:
```bash
wget https://raw.githubusercontent.com/yourusername/glitch-conversion/main/gLiTcH-Conversion.sh
```

2. Make it executable:
```bash
chmod +x gLiTcH-Conversion.sh
```

3. Run as root:
```bash
sudo ./gLiTcH-Conversion.sh
```

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

## Post-Installation

After successful conversion:
- A new user `x` with password `9880` will be created
- Hostname will be changed to `gLiTcH`
- The system will automatically run post-install fixes on first reboot

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, visit [gLiTcH Linux Website](https://www.glitchlinux.wtf)

```
