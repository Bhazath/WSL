# **WSL** 

- To install in windows
```
wsl --install
```
- The wsl -d command is used to start a specific distribution in the Windows Subsystem for Linux (WSL). You need to provide the name of the distribution you want to run after the -d option.
```
wsl -d <distribution_name>
```
#

# View

- The wsl --list (or wsl -l) command is used to list all the installed WSL distributions.
```
  wsl --list --verbose
  wsl -l -v 
```
- To shoutdown all wsl vm
```
  wsl --shutdonw
  # to down one vm
  wsl --terminate <disoro_name>
```
- To set default disto in wsl
```
  wsl -set-default <distro>
```

# Installation 
- To view all distro online
```
wsl --list --online
```
- To install a online distro
```
wsl --install <distribution_name>
```
- to connect to user in distro
```
wsl -d <distro> -u <user-name>
```
#
# To delete
- To remove
  ```
  wsl --unregister <distro>
  ```
#

# CMD command in wsl  
- You can run all command in win command in wsl
  ```
  ping.exe
  notepad.exe
  explorer.exe .
  ```
- You can run wsl command in powershell
  ```
  ipconfig | wsl grep 192.
  ```
#
# 
# BACKUP
```
wsl --list --verbose
```
```
wsl --export <distor> <distor.tar> 
```
# Import
```
wsl --import <anyname> <newpath D:\wsl> <distor.tar>
```
