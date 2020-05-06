# File Shredder

PowerShell script for shredding files.

If you have more than enough free disk space, your files will most likely still be recoverable - even after shredding.

Have a good read about this topic [here](https://www.streetdirectory.com/travel_guide/124464/hardware/understanding_file_shredding_and_the_wipe_disk_process.html).

Tested with PowerShell v5.1.18362.752 on Windows 10 Enterprise OS (64 bit).

Made for educational purposes. I hope it will help!

Reference point was this [article](https://www.codeproject.com/Articles/22736/Securely-Delete-a-File-using-NET).

## How to Run

Open the PowerShell from [\\src\\](https://github.com/ivan-sincek/file-shredder/tree/master/src) and run the commands shown below.

Set the execution policy:

```pwsh
Set-ExecutionPolicy Unrestricted
```

Run the script:

```pwsh
.\file_shredder.ps1 .\somefile.txt
```

Or run the following command from either PowerShell or Command Prompt:

```pwsh
PowerShell -ExecutionPolicy Unrestricted -File .\file_shredder.ps1 .\somefile.txt
```
 
 ## Images

![Shredding](https://github.com/ivan-sincek/file-shredder/blob/master/img/shredding.jpg)
