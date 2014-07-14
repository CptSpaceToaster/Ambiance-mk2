##Ambiance-mk2##
###A Theme for Ubuntu/Gnome/Unity/Metacity/and Whatever?###
Author: CptSpaceToaster

Notes: Made for Ubuntu 12.04LTS, but it will probably work in other places.
- Assumes user is running Nautilus
- Assumes you like dark-grey and dark-dark-grey

####Step One: Place the folder in one of these two places####
`cd ~/.themes`  
`git clone https://github.com/CptSpaceToaster/Ambiance-mk2`
- Installs for local user only
- You'll need to use MyUnity or the UbuntuTweakTool to select it afterwards

`cd /usr/share/themes/`  
`sudo git clone https://github.com/CptSpaceToaster/Ambiance-mk2`  
`sudo mv Ambiance Ambiance.bak`  
`sudo mv Ambiance-mk2 Ambiance`
- Installs for all users
- Replace the old Ambiance Directory with this one
- Open up Settings->Appearences, enable another theme, then enable Ambiance

####Step Two: Restart Nautilus####
I don't know why this is necessary, but maybe I was just doing something wrong.  
`$ nautilus -q`  
`$ nautilus`

####Step Three: Reboot and Login####
