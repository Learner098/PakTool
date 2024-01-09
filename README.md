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
```
cd PakTool
```
```
chmod +x setup
```
```
bash setup
```
## Note: ''type paktool every time to start tool anywhere inside termux and also if you face any problem''

After installation, dir_pak folder is created inside Download folder of your device storage where you must put your paks files to be moded.

## Unpack
1. After selecting unpack feature,You will see all the paks.
2. select which one you want to unpack 
3. it will start unpacking after few seconds
4. after complete process,all the extraccted output data is stored inside termux storage (PakTool/output_folder)

## Repack 
1. Before using repack feature,you must place edited files inside "/Download/copied_folder"

## Find_Text
1. If you want to search specific "text" inside output dats files then select this feature
2. after putting text,it will search for all the dat files that contain specific "text" provide by you
3. Read prompt carefully and give input what it says.
4. you will these dats files are copied inside 'copied_folder' folder inside Download
5. Edit these dats files(these files are considered for repacking)

## Utilities
1. there are four more options: "Erase_pak_folder","Erase_output_folder","Erase_copied_folder","Null/Add_content"
2. Erase_pak_folder : delete the pak file stucking inside termux storage 
3. Erase_output_folder : delete all the extracted output files stucking inside termux storage
4. Erase_copied_folder : delete copied files inside download folder of device storage
5. Null/Add_content : this can emptied your all copied files also you can put desired text which will be replaced

video tutorial: https://youtu.be/mnzBEhFvtoM?si=Hj0vaamFngGwZmn-