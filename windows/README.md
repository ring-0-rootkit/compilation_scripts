
Finaly added support for windows

Usage is the same as in linux

But time measuring not as good(-t argument in "run.bat")

# Installation
You should have gcc installed and added to PATH

Installation example using chocolatey:

Installing chocolatey:

Run in PowerShell:

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
Installing MinGW:
```bash
choco install mingw
```

Installation of the script:

This script copy "compilecpp.bat" and "run.bat" into C:\Users\{username}\AppData\Local\Microsoft\WindowsApps folder

Doubleclick "install.bat" in downloaded folder

Or just run this command in cmd(you should be located in downloaded windows folder):
```bash
install.bat
```
