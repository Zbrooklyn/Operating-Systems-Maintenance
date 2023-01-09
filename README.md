# Operating-Systems-Maintenance-

### Windows 10 

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






Windows 11

Ubuntu 


[kde-neon-logo](https://user-images.githubusercontent.com/73963020/211235720-af170b25-625f-4792-9e65-fd4edf76c874.png)

KDE on Raspberry pi [Youtube](https://youtu.be/dh9KfT-IfFg)
- install raspien liite onto a micro sd card
- Install KDE with apt: sudo apt install kde-plasma-desktop
- Fix Wifi: sudo apt purge openresolv dhcpcd5


<details><summary>open</summary>
<p>

#### We can hide anything, even code!
```ruby
   puts "Hello World"
```
</p>
</details>


https://trello.com/c/u5Jyfu1p
