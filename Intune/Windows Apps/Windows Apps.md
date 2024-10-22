# WINDOWS APPS
The following Applications are uploaded in the Intune tenant.  

### APP NAME

| App Name                                                  | Type                             | Other          |
| --------------                                            | --------------                   | -------------- |
| AApp Installer - GLB - DEV                                | Microsoft Store app (New)        |                |
| Company Portal - GLB - DEV                                | Microsoft Store app (New)        |                |
| Google Chrome - GLB - DEV                                 | Windows app (Win32)              |                |
| Google Chrome Beta - GLB - DEV - Development              | Windows app (Win32)              |                |
| IntuneDebugTools - GLB - DEV                              | Windows app (Win32)              |                |
| Microsoft 365 Apps for Windows 10 and later - GLB - DEV   | Microsoft Store app (New)        |                |
| Microsoft Edge for Windows 10 and later                   | Microsoft Store app (New)        |                |
| Microsoft PowerToys - GLB - DEV                           | Microsoft Store app (New)        |                |
| WinGet-AutoUpdate-Configurator - GLB - DEV                | Microsoft Store app (New)        |                |
| Zoom Workplace (64-bit) - GLB - DEV                       | Windows app (Win32)              |                |
| Zoom(32bit) - BOT - DEV                                   | Windows app (Win32)              |                |

  
### DETECTION RULES

Detection rules vary based on the application type and other factors but outlined below in the general method.  

**Application Architecture:** MSI  
- MSI Product code  

**Application Architecture:** EXE  
- Genrerally a detection of a registry key that makes sense for the specific application located in  
    - HKLM:\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\  
    -or-  
    - HKLM:\SOFTWARE\WOW6432Node\Microsoft\Windows\CurrentVersion\Uninstall\  

[Basic App Detetcion Script](https://github.com/asjimene/miscellaneous-tools/blob/master/BasicAppDetectionScript/BasicAppDetectionScript.ps1)