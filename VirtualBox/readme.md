
###Tuto VM physique 
https://forum.ubuntu-fr.org/viewtopic.php?id=365418

###Pour lancer sur Grub2 

http://ubuntuforums.org/showthread.php? … ost9232654

La commande proposée (grub-mkrescue --output=~/.VirtualBox/rescue.iso /boot/grub) fabrique bien une image iso bootable avec la bonne configuration. Cependant, le démarrage n'est pas automatique, il faut taper configfile /grub.cfg pour lancer le système.

