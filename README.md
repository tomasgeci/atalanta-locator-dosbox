[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://supportukrainenow.org/)

# atalanta-locator-dosbox
OK1DUO Atalanta Locator Dosbox config for Windows 10

### download atalanta locator
[http://ok1duo.nagano.cz/](http://ok1duo.nagano.cz/)

### download and install DosBox
[DosBox](http://www.dosbox.com/download.php?main=1)

### How-To
- create folder on your local hard drive
- copy locator install file **"loc1229.exe"** to this folder
- run dosbox
- run these commands (based on your folder path)
```diff
+ mount c: your_local_drive\your_local_folder_path
```
- go to C:\ drive ```c:```
- check if locator installer exist in mounted folder
```
dir
```
- run locator installer
```
loc1229.exe
```
- replace DosBox config with included **"dosbox-0.74.conf"**
- edit config according to your locator local path (section [autoexec])
