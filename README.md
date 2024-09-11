# Laptop Win11 Optimization Guide
A detailed guide which will show you how to perfectly setup your laptop. All the optimizations are used in order to gain the max performance. There will be also a few app suggestion which can help you choose the best softwares for your pc.

## Restore Point 
Before you start the optimization process make sure to create a restore point:
- Open Windows Search Bar
- Search "Create a restore point"
- Click on "Create"
  
_(This process makes you create a restore point which can bring you back in case something goes wrong with the optimizations)_

## CTT Utility
- Open Windows Search Bar
- Search "Windows PowerShell" and open it as Administrator
- Copy and Paste this string ```irm "https://christitus.com/win" | iex ```
- Apply the following optimizations:

![Screenshot 2024-09-11 025843](https://github.com/user-attachments/assets/4a777177-e8b9-44d7-ba82-b72d4f631e2f)

- Windows Power Plan:

![Screenshot 2024-09-11 031738](https://github.com/user-attachments/assets/4a8a735c-f7db-4baf-9481-874c66c46524)

## Disable Rounded Corners
In order to give Win11 the better old Win10 windows, I suggest to install this file. It simply removes Win11 rounded corners. [Download](https://github.com/valinet/Win11DisableRoundedCorners/releases/download/1.0.0.3/Win11DisableOrRestoreRoundedCorners.exe)

## Windows Personalization (Optional)
- Open Windows Search Bar
- Search "Settings"
- Go to "Personalization"
- Click on "Show accent color on title bars and window borders
After you enabled this settings
- Open Windows Search Bar
- Search "Registry Editor" and run it as Administrator
- Go to ```HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Accent ```
- Click on StartColorMenu and set the value to 0
- Click on AccentColorMenu and set the value to 0
- Click on AccentPalette, delete everything and set 4 lines of 0s. Make sure to have the cursor on the empty line

![Screenshot 2024-09-11 034344](https://github.com/user-attachments/assets/1f28bcaf-d405-4e57-8fb7-77bedbf38b72)

## App Suggestion
- [7-Zip ](https://www.7-zip.org/a/7z2408-x64.exe)
- [KeePassXC ](https://github.com/keepassxreboot/keepassxc/releases/download/2.7.9/KeePassXC-2.7.9-Win64.msi)
- [Waterfox](https://cdn1.waterfox.net/waterfox/releases/G6.0.19/WINNT_x86_64/Waterfox%20Setup%20G6.0.19.exe)
- [Revo Unistaller](https://www.revouninstaller.com/start-freeware-download/)
