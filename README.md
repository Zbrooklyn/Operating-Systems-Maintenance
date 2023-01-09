# Operating-Systems-Maintenance
![30684](https://user-images.githubusercontent.com/73963020/211402306-95fb4e51-4777-49d4-9620-ec734a02df30.jpg)

This Utility is desined to help with exsisting and new comuter installs providing recomended tools and maitnance options in a effort to steemline the process and make sure your comuter is running at its best proformance.


### Windows 10 

Windows PC Update [Youtube](https://youtu.be/M2mMQfPGZsE), [Learn More](https://christitus.com/install-windows-update-powershell/)

To install Windows updates via PowerShell, you need to install the module first:
```
Install-Module PSWindowsUpdate
Add-WUServiceManager -MicrosoftUpdate
```

Install all available updates
```
Install-WindowsUpdate -MicrosoftUpdate -AcceptAll -AutoReboot | Out-File "C:\($env.computername-Get-Date -f yyyy-MM-dd)-MSUpdates.log" -Force
```




pakages to install
```
choco install vivaldi -y
choco install powertoys -y
choco install arduino -y
choco install easyeda -y
choco install figma -y
choco install odrive -y
choco install obsidian -y
choco install treesizefree -y
choco install unity -y
choco install whatsapp -y
choco install zoom -y
choco install postman -y
choco install chirp -y
```
download from web
 - Beeper [Download](https://www.beeper.com/download)
 - Canva [Download](https://www.canva.com/download/)
 - EasyEDA [Download](https://easyeda.com/page/download)
 - ODrive [Download](https://docs.odrive.com/docs/odrive-usage-guide#install-desktop-sync)
 - Watch Face Studio [Download](https://developer.samsung.com/watch-face-studio/download.html)
 
### Update apps
 using winget

To list all apps avalable (if first time use -y)
 ```
 winget upgrade
```
To update all
```
winget upgrade -h --all
```

### Chris Titus All in one Tool [Learn More](https://christitus.com/one-tool-for-everything/)
 
<details><summary>download from web</summary><p>

</p></details>




<details><summary>pc maintenance</summary>
<p>
   
#### We can hide anything, even code!
   
To perform a clean boot, type "system configuration" in Search and click the "System Configuration" result.

1. Right-click the Windows button > Select Run
2. Type in "msconfig" without the quotes, then click OK.
3. On the General tab, select Selective Startup. Then untick "Load startup items".
4. On the Services tab, click "Hide all Microsoft services".
5. Click "Disable all".
6. On the Startup tab, click "Open Task Manager". A Task Manager window should open.
7. Disable all startup items. You can also choose which startup items to disable, as certain devices might now work properly if the startup item related to it is disabled.
8. Go back to your System Configuration window.
9. Click Apply > OK
10. Click "Restart" when prompted.

Perform repair system files :	
Type cmd in the Windows search bar, right-click on the Command Prompt, and run it as an administrator.
	You must type the commands in their respective order:
	- DISM.exe /Online /Cleanup-image /Restorehealth
	- sfc /scannow
   
Please do not include the (.) at the beginning of the command
Set CPU priority https://www.prnwatch.com/prio/ 
   
   --------
</p>
</details>






### Windows 11

### Ubuntu 


[kde-neon-logo](https://user-images.githubusercontent.com/73963020/211235720-af170b25-625f-4792-9e65-fd4edf76c874.png)

### KDE on Raspberry pi [Youtube](https://youtu.be/dh9KfT-IfFg)
- install raspien liite onto a micro sd card
- Install KDE with apt: sudo apt install kde-plasma-desktop
- Fix Wifi: sudo apt purge openresolv dhcpcd5


<details><summary>open</summary><p>
#### We can hide anything, even code!
```ruby
   puts "Hello World"
```
</p></details>


https://trello.com/c/u5Jyfu1p
