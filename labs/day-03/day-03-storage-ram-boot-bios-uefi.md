# Day 3 - Storage, RAM, Boot, BIOS/UEFI

## Topic
Today I learned the basics of storage, RAM, boot process, BIOS, and UEFI. These are important for understanding common Help Desk issues like slow computers, full storage, boot errors, and systems that fail to load Windows.

## Concepts Learned

### Storage
Storage is where data is saved permanently. It keeps files, apps, documents, photos, videos, and the operating system even after the computer shuts down.

### RAM
RAM means Random Access Memory. It is temporary working memory used by active apps and tasks. RAM clears when the computer shuts down.

### RAM vs Storage

| RAM | Storage |
|---|---|
| Temporary memory | Permanent saving space |
| Used by active apps | Saves files and apps |
| Clears after shutdown | Stays after shutdown |
| Fast working space | Long-term saving space |

Simple meaning:

```text
RAM = temporary working space
Storage = permanent saving space
```

### HDD
HDD means Hard Disk Drive. It is older and slower storage with moving spinning disks inside.

### SSD
SSD means Solid State Drive. It is faster storage with no moving spinning disk.

### NVMe SSD
NVMe SSD is a very fast type of SSD used in many modern laptops.

### C Drive
In Windows, the main storage drive is usually called C:. It contains Windows, programs, user files, downloads, desktop files, temporary files, and app data.

A good rule is to keep at least 15% to 20% free space.

## Boot Process

Boot means starting the computer and loading the operating system.

Basic boot process:

1. Power button is pressed.
2. Computer receives power.
3. Firmware starts.
4. Hardware is checked.
5. Computer finds the boot device.
6. Windows starts loading.
7. Login screen appears.

## Boot Device

A boot device is the device the computer uses to start the operating system.

Examples:

- Internal SSD
- Internal HDD
- USB drive
- External drive
- Network boot

Normally, a laptop should boot from the internal SSD.

## BIOS and UEFI

BIOS and UEFI are firmware. Firmware is low-level software built into the motherboard that starts before Windows.

- BIOS means Basic Input/Output System.
- UEFI means Unified Extensible Firmware Interface.

Simple meaning:

```text
BIOS/UEFI wakes the computer up before Windows starts.
```

BIOS/UEFI is not a port. It is firmware built into the motherboard.

## Boot Order

Boot order tells the computer where to look first for the operating system.

Example:

```text
1. Internal SSD
2. USB drive
3. Network boot
```

If boot order is wrong, the computer may fail to start Windows.

## Secure Boot

Secure Boot is a UEFI security feature. It helps make sure trusted boot software starts the computer.

## TPM

TPM means Trusted Platform Module. It is used for security, encryption, and Windows 11 requirements.

## BitLocker

BitLocker is Windows drive encryption. It protects drive data. If boot settings change, a computer may ask for a BitLocker recovery key.

Important rule:

```text
Do not randomly change BIOS/UEFI settings on a company laptop.
```

## Hands-On Check

### Storage
- Total storage: 952 GB
- Used storage: 465 GB
- Free storage: 487 GB

### Largest Storage Categories
- GTA 5
- Microsoft Teams
- Slack

### RAM
- Total RAM: 15.8 GB usable
- RAM in use: 12 GB
- Available RAM: 3.8 GB
- RAM speed: 4267 MT/s
- Slots used: Not upgradeable / soldered RAM on Surface Pro 8

### Laptop
- Laptop brand/model: Microsoft Surface Pro 8

### BIOS/UEFI Access
- BIOS/UEFI key: Hold Volume Up + press Power
- Boot menu key: Hold Volume Down + press Power

## Technician Notes

Storage is healthy because about half of the drive is still free. RAM usage was high because 12 GB out of 15.8 GB was in use. If the laptop feels slow, I should check browser tabs, Teams, Slack, VS Code, Codex, startup apps, and background processes.

## Troubleshooting Scenario

### Problem
User says: "My laptop says No bootable device found."

### Meaning
The laptop turned on, but it could not find a storage drive with Windows.

### Possible Causes

1. SSD or HDD failed.
2. Storage drive is loose.
3. Boot order is wrong.
4. Windows boot files are damaged.
5. BIOS/UEFI cannot detect the drive.
6. External USB device is confusing the boot process.
7. BIOS settings were changed recently.

### Questions I Should Ask

1. When did this start?
2. Did the laptop fall recently?
3. Was there a Windows update?
4. Is any USB drive plugged in?
5. Did anyone change BIOS settings?
6. Do you hear unusual clicking sounds?

### First Things I Would Check

1. Remove USB drives.
2. Restart the laptop.
3. Check if BIOS/UEFI detects the internal drive.
4. Check boot order.
5. Escalate if the internal drive is not detected.

## Mini Quiz Answers

1. Storage is used to permanently save user data, files, apps, and the operating system.
2. RAM helps the CPU run active tasks efficiently.
3. RAM is fast temporary working memory used while the computer is running. Storage is permanent memory where user data and system files are saved.
4. HDD is an older storage device with spinning disks. It is slower than SSD.
5. SSD means Solid State Drive. It is faster storage with no spinning disk.
6. Boot means starting the computer. Firmware starts first, checks hardware, finds the boot device, and loads Windows.
7. A boot device is the device that contains the operating system files needed to start the computer.
8. BIOS/UEFI is firmware built into the motherboard. It starts before Windows, checks basic hardware, finds the boot device, and helps start the operating system.
9. Boot order is the sequence the computer follows when looking for a device to start from.
10. "No bootable device found" usually means the computer cannot find a valid device with an operating system. Possible causes include wrong boot order, loose or failed SSD/HDD, damaged Windows boot files, or BIOS/UEFI not detecting the drive.

## Reflection
Today I learned how storage, RAM, boot devices, BIOS, and UEFI connect to real Help Desk problems. I corrected my understanding of BIOS/UEFI and learned that it is firmware, not a port. I also checked my laptop storage, RAM usage, and Surface Pro 8 BIOS/boot keys.

## Status
Day 3 completed.
