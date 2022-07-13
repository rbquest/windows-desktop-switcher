# windows-desktop-switcher

## Info 
Small script I always have running to work faster with multiple desktops on Windows 10 x64. It replicates the functionality of an older virtual desktop manager software that I liked a lot but no longer works in windows 10 and newer. It's based on the awesome [pmb6tz/windows-desktop-switcher](https://github.com/pmb6tz/windows-desktop-switcher), the reason for a fork was to make the number of desktops constant each time the script runs. I found that having 4 constant virtual desktops works best for me. I dislike having to create/remove/rename desktops, it gets messy real quick and hard to keep track of and this helps a lot with that.

## Features
- automatically creates 4 desktops on Windows 10 and tries to keep that number always at 4, adds more desktops as necessary to get there each time the script runs
- quickly change between desktops & send windows to specific desktops with shortcuts 

## Hotkeys

| Shortcut      | Description |
| ----------- | ----------- |
| `Ctrl+Shift+1`      | Switch to Desktop #1       |
| `Ctrl+Shift+2`      | Switch to Desktop #2       |
| `Ctrl+Shift+3`      | Switch to Desktop #3       |
| `Ctrl+Shift+4`      | Switch to Desktop #4       |
| `Ctrl+1`      | Move active window to Desktop #1       |
| `Ctrl+2`      | Move active window to Desktop #2       |
| `Ctrl+3`      | Move active window to Desktop #3       |
| `Ctrl+4`      | Move active window to Desktop #4       |

## Instructions 
To run it you can either:
* download the lastest release .exe file
* download the files in the repository and run desktop_switcher.ahk, you'll need [AutoHotKey](https://www.autohotkey.com) installed to run the .ahk script or compile it yourself

To have it automatically run with Windows, you need to add a shortcut to the .exe in
`Users\{user}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`. Guide [here](https://support.microsoft.com/en-us/windows/add-an-app-to-run-automatically-at-startup-in-windows-10-150da165-dcd9-7230-517b-cf3c295d89dd)


## Credits
* This is based on [pmb6tz/windows-desktop-switcher](https://github.com/pmb6tz/windows-desktop-switcher). I recommend using that for more general purposes and more features, more desktops
* VirtualDesktopAccessor.dll by [Ciantic/VirtualDesktopAccessor](https://github.com/Ciantic/VirtualDesktopAccessor)
