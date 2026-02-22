# kali-linux-setup
My Kali Linux dual-boot installation and basic Linux command practice.


## Basic Commands in Linux Environment
| Command  | Description                     |
| -------- | ------------------------------- |
| `pwd`    | Shows current working directory |
| `ls`     | Lists files and directories     |
| `cd`     | Changes directory               |
| `mkdir`  | Creates a new directory         |
| `touch`  | Creates a new file              |
| `rm`     | Removes files                   |
| `clear`  | Clears terminal                 |
| `whoami` | Displays current user           |



# Steps I followed to install Kalin on my Windows device
## Downloaded Kali Linux ISO:
  I went to the official Kali Linux website and grabbed the correct ISO file.
  
## Prepared the USB Drive:
  I plugged in my USB drive.

## Partitioned the Drive:
  I chose "Manual" partitioning for the installation, making sure not to overwrite my Windows partitions.
  I allocated space for the root (/) and swap partitions.

## Used Rufus to Create a Bootable USB:
  I opened Rufus, selected my USB drive, and chose the Kali Linux ISO.
  After that, I clicked "Start" to flash it onto the USB.

## Booted from the USB:
  I restarted my laptop and entered the BIOS/UEFI settings by pressing the required key (ESC).
  Then, I adjusted the boot order to make sure the USB drive was first.

## Installed Kali Linux:
  I booted from the USB and selected the graphical installation option.
  I followed the on-screen prompts to install Kali, carefully handling the disk partitioning.

## Installed the Bootloader:
  During the installation, I made sure to install the GRUB bootloader, selecting the same drive as my Windows installation.

## Completed the Installation:
  After finishing the installation, I removed the USB drive when prompted.

##Dealt with Boot Options:
  Now, whenever I restart my laptop, it boots straight into Kali unless Windows is mentioned.
