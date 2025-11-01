### WSASS

This is a tool that uses the old WerfaultSecure.exe program to dump the memory of processes protected by PPL (Protected Process Light), such as LSASS.EXE.
The output is in Windows MINIDUMP format.

*This tool automatically replaces the __"MDMP"__ magic header with a PNG magic header.
After the dump is complete, you need to restore the original 4-byte magic at the beginning of the file with the original 4 bytes: __{0x4D, 0x44, 0x4D, 0x50}__ "MDMP".*

### Command Line Syntax

**WSASS.exe path_to_werfaultsecure.exe target_PID**

*Example: __WSASS.exe C:\TMP\WerfaultSecure.exe 888__*

## Links

[Using WSASS to dump LSASS](https://www.zerosalarium.com/2025/09/Dumping-LSASS-With-WER-On-Modern-Windows-11.html)

[Tool to run process with PPL without driver](https://github.com/TwoSevenOneT/CreateProcessAsPPL)

## Demo Video

Youtube: [https://www.youtube.com/watch?v=FZ20oQ-pVwg](https://www.youtube.com/watch?v=FZ20oQ-pVwg)

## ☕ Like what I do? You can fuel my creativity with a coffee!

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/twosevenonethree)

## Tools For Security Researcher and Hacker

Essential tools that every security researcher and hacker should have in their toolkit:

[Essential Tools For Security Researcher and Hacker](https://www.zerosalarium.com/p/essential-tools-for-security-researcher.html)

## READING

Some books you should read to sharpen your cybersecurity skills, especially in offensive security:

[Books on Programming and Cybersecurity recommended by Zero Salarium Researchers](https://www.zerosalarium.com/2025/10/books-on-programming-and-cybersecurity-recommended.html)


## Author:

[Two Seven One Three](https://x.com/TwoSevenOneT)
