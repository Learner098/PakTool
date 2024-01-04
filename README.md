## Installing process

1. Install Termux from PlayStore or best from fdroid site

## Enter This Command:
```
termux-setup-storage
```
```
apt update && apt upgrade
```
```
pkg install git
```
## Clone this repository
```
git clone https://github.com/learner098/PakTool
```
then,
```
cd PakTool
```
```
chmod +x setup
```
```
bash setup
```
## Note: ''type paktool every time to start tool''

After installation, dir_pak folder is created inside Download folder of your device storage where you must put your paks files to be moded.

## Unpack
1. After selecting unpack feature,You will see all the paks.
2. select which one you want to unpack 
3. it will start unpacking after few seconds
4. after complete process,output dat folder is stored inside termux storage (PakTool/output_folder)

## Repack 
1. Before using repack feature,you must place edited files inside "copied_dat" folder which is found inside Download folder
2. By typing 2,it starts repacking process

## Search_Text
1. If you want to search specific "text" inside output dats files then select this feature
2. after putting text,it will search for all the dat files that contain specific "text" provide by you
3. Read prompt carefully and give input what it says.
4. you will these dats files are copied inside 'copied_dat' folder inside Download
5. Edit these dats files(these files are considered for repacking)

## Error_Fix
1. There are two more option one is "Reset_Pak" for deleting paks files stucked inside termux storage and another is "Reset_Output" for deleting all the output data from termux storage
