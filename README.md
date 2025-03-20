# Exam-practice250318
## Creating a Bootable USB
[Here is the first link to how to create bootable USB](https://www.youtube.com/watch?v=NSRCZEKDMK8)
[Here is the first link how to create bootable USB](https://www.youtube.com/watch?v=abpAPQH1RsI)
##Steps

Method 1: Using Rufus (recommended for most cases)
Download Rufus:

Visit the official Rufus website and download the tool.
Insert the USB Drive:

Plug in the USB drive into your computer.
Open Rufus:

Launch the Rufus program you downloaded.
Configure Rufus:

Device: Select your USB drive from the dropdown menu.
Boot selection: Choose "Disk or ISO image (Please select)" from the dropdown menu.
Select the ISO: Click on the "SELECT" button and browse to the location of the ISO file you want to use (e.g., Windows ISO).
Partition Scheme: Select GPT (for UEFI systems) or MBR (for legacy BIOS systems).
File System: Select NTFS (recommended for Windows OS) or FAT32 (for Linux).
Cluster Size: Leave it at the default setting.
Start the Process:

Once you have configured everything, click the Start button.
If prompted, choose to write in ISO Image mode (recommended).
Rufus will warn you that all data on the USB will be destroyed. Click OK to continue.
Wait for the Process to Finish:

The tool will begin creating the bootable USB. This process may take several minutes, depending on the size of the ISO.
Done:

Once the process is complete, you will see a message saying Ready. Your bootable USB drive is now ready.
