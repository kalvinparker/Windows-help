https://support.microsoft.com/en-gb/topic/-we-couldn-t-update-system-reserved-partition-error-installing-windows-10-46865f3f-37bb-4c51-c69f-07271b6672ac



Works with Windows 10 & 11 with GPT partitition:

1.  Search for cmd. Press-and-hold or right-click on Command Prompt in the results, and select Run as administrator.

2.  At the command prompt, type mountvol y: /s and then hit Enter. This will add the Y: drive letter to access the System Partition.
```
mountvol y: /s
```
4.  Switch to the Y drive by typing Y: and press Enter. Then, navigate to the Fonts folder by typing cd EFI\Microsoft\Boot\Fonts. Once there, type del *.* to delete font files. 
```
Y:
```
```
cd EFI\Microsoft\Boot\Fonts
```
```
del *.*
```
5.  The system may ask you if you are sure to continue, press Y and then Enter to continue. Retry Windows Update :)
