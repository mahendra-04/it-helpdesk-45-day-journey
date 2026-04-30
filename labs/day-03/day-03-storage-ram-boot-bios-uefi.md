# Day 3 - Storage, RAM, Boot, BIOS/UEFI

## Topic
Today I learned the basics of storage, RAM, boot process, BIOS, and UEFI. These are important for understanding common Help Desk issues like slow computers, full storage, boot errors, and systems that fail to load Windows.

## Concepts Learned

### Storage
Storage is where data is saved permanently. It keeps files, apps, documents, photos, videos, and the operating system even after the computer shuts down.

Examples of stored data:

- Windows files
- Installed apps
- Documents
- Downloads
- Photos
- Videos
- Desktop files
- Temporary files

### RAM
RAM means Random Access Memory. It is temporary working memory used by active apps and tasks.

Examples of apps using RAM:

- Chrome
- VS Code
- Outlook
- Teams
- Word

When the computer shuts down, RAM clears.

### RAM vs Storage

| RAM | Storage |
|---|---|
| Temporary memory | Permanent saving space |
| Used by active apps | Saves files and apps |
| Clears after shutdown | Stays after shutdown |
| Affects multitasking speed | Affects saved data and available space |

Simple meaning:

```text
RAM = temporary working space
Storage = permanent saving space
```

### HDD
HDD means Hard Disk Drive. It is older and slower storage with moving parts.

Common HDD symptoms:

- Slow startup
- Apps open slowly
- Disk usage stays high
- Freezing
- Clicking sound from drive

### SSD
SSD means Solid State Drive. It is faster than HDD and has no moving spinning disk.

Benefits:

- Faster startup
- Faster app loading
- Better performance
- Less freezing than old HDDs

### NVMe SSD
NVMe SSD is a very fast type of SSD used in many modern laptops.

### C Drive
In Windows, the main storage drive is usually called C:.

The C drive usually contains:

- Windows
- Program Files
- Users folder
- Desktop
- Documents
- Downloads
- App data
- Temporary files

A full C drive can make a computer slow. A good rule is to keep at least 15% to 20% free space.

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

### BIOS
BIOS means Basic Input/Output System. It is the older firmware system.

### UEFI
UEFI means Unified Extensible Firmware Interface. It is the newer firmware system used in modern computers.

Simple meaning:

```text
BIOS/UEFI wakes the computer up before Windows starts.
```

## BIOS/UEFI Settings

A technician may check:

- Boot order
- Storage detection
- Secure Boot
- TPM
- Virtualization
- System time
- Hardware information

Important rule:

```text
Do not randomly change BIOS/UEFI settings on a company laptop.
```

Wrong changes can cause boot problems or BitLocker recovery prompts.

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

## Common Help Desk Issues

- C drive is full
- Computer is slow
- Disk usage is 100%
- No bootable device found
- Windows stuck on repair screen
- Laptop asks for BitLocker recovery key
- Computer does not detect SSD
- RAM usage is high
- Computer freezes when opening apps

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

## Mini Quiz Review

1. Storage saves files, apps, and the operating system permanently.
2. RAM is temporary working memory used by active apps.
3. RAM clears after shutdown, while storage keeps data.
4. HDD is older and slower storage with moving parts.
5. SSD is faster storage with no moving parts.
6. Boot means starting the computer and loading the operating system.
7. A boot device is the device used to start Windows or another OS.
8. BIOS/UEFI is firmware that starts before Windows.
9. Boot order decides which device the computer checks first when starting.
10. No bootable device found usually means the computer cannot find a drive with Windows.

## Reflection
Today I learned how storage, RAM, boot devices, BIOS, and UEFI connect to real Help Desk problems. I learned that storage and RAM are different, boot errors are often related to storage or boot order, and BIOS/UEFI settings should not be changed randomly.

## Status
Day 3 completed. Extra hands-on practice is still useful for BIOS/UEFI key identification and RAM/storage review.
