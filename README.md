
# How to find windows 10 product key

[![how to find windows 10 product key](redd.png)](https://icncomputer.com/how-to-find-windows-10-product-key/)


**3 simple ways to find your Windows 10 product key**


1. Command prompt
2. PowerShell
3. Registry File


## 1. Command prompt
The most direct method for finding your Windows 10 product key is from the command line. Type “cmd” into the Windows 10 desktop search box and then right-click the command line result and select “run as administrator” from the context menu. Type this command at the prompt:

(wmic path softwareLicensingService get OA3xOriginalProductKey)

**As you can see in Figure A, the command will display your current Windows 10 product key.**


## 2. PowerShell

If you are using Windows 10 PowerShell, the process is similar. Right-click the Start Menu button and then select Windows PowerShell (Admin) from the context menu. Type this command at the prompt to reveal the product key as shown in Figure B.

( powershell "(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey" )


## 3. Registry File

As you might imagine, the product key is stored in the Windows 10 Registry File, so it is possible to find the code there if you know the right key. Type “regedit” into the Windows 10 desktop search and select the appropriate item in the results. Navigate to this key:

(ComputerHKEY_LOCAL_MACHINESOFTWAREMicrosoftWindows NTCurrentVersionSoftwareProtectionPlatform)
**As you can see in Figure C, the BackupProductKeyDefault key will reveal a valid Windows 10 product key.**
