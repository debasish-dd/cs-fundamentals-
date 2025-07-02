## What happens when we turn on computer?
A computer without a program running is just an inert hunk of electronics. At first when a computer starts a special program runs it's OS, it's then manages pretty much everything for the user.

- The power supply sends electricity to the components of the computer, such as the motherboard, hard drive etc.
- The BIOS perform a power on self tested (POST) to check if every electric component working properly.
- The OS then runs and loaded from the computer's storage into the RAM.
- The OS then initializes its own components and drivers and presents the login screen or desktop environment to the user.

![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20201016104502/12331.png)

---
## Functions of BIOS

- **POST :**  The Power On Self Test happens each time when we on a computer. It initialise every components to ensure that they're working properly. If some errors are found then an error message is displayed on the screen or a number of beeps are heard, These beeps are known as POST beep codes.
---
- **Master Boot Record :** The master boot record is a special boot sector at the begining of the disk, The MBR contains the code that loads the rest of OS, known as bootloader. It contains the code file of the os. It starts when the POST and end when the BIOS searches for the MBR on the Hard Drive, which is generally located in the first sector, first head, first cylinder.

![](https://media.geeksforgeeks.org/wp-content/uploads/mbr-2.png)

---

- **init :** init is the last step of the kernel boot sequence. It looks for the file /etc/inittab to see if there is an entry for initdefault. It is used to determine the initial run level of the system. A run-level is used to decide the initial state of the operating system. 
Some of the run levels are:
  - Level 0: System Halt.
  - Level 1: Single user mode.
  - Level 2: Full multiuser mode without network.
  - Level 3: Full multiuser mode with network.
  - Level 4: user definable.
  - Level 5: Full multiuser mode with network and X display manager.
  - Level 6: Reboot.

- **System Configuration :** The BIOS allows the user to configure various system settings, such as:

 1. Boot order: This determines the order in which the computer checks for bootable devices. For example, if the boot order is set to "hard drive" first, the computer will try to boot from the hard drive before checking other devices such as a CD/DVD drive or a USB drive.
 2. Time and date: The BIOS stores the time and date information, which can be set and adjusted by the user. This information is used by the operating system and various applications.
3. Hardware settings: The BIOS provides options to configure various hardware settings such as CPU voltage, clock speed, and memory timings. These settings can be used to optimize system performance, but should only be changed by advanced users with the proper knowledge.
- **Security :** The BIOS can also provide security features such as:

1. Password protection: The BIOS can be set to require a password to access certain features or to prevent unauthorized booting of the computer. This can be useful in preventing unauthorized access to sensitive data.
2. Secure boot: Secure boot is a feature that ensures that only trusted operating system boot loaders, drivers, and firmware are loaded during the boot process. This helps to prevent malware and other unauthorized software from running on the system.
3. TPM (Trusted Platform Module): Some modern motherboards have a built-in TPM that provides hardware-based security features such as encryption, digital certificates, and secure key storage. This can help to protect sensitive data and prevent unauthorized access to the system.