# Configure enviroment 

## Enable Dualboot via cmdlet - Windows 

1- ``` bcdedit /set {bootmgr} displaybootmenu yes ```

2- ``` bcdedit /set {bootmgr} path \EFI\ubuntu\grubx64.efi ```