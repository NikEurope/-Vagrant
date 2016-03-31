

Vagrant & VirtualBox


https://www.vagrantup.com/
https://www.virtualbox.org/


Vagrant

 
Vagrant permet d'accélerer la mise en place d'environnements de dev.

Il permet de configurer et d'utiliser des machines virtuelles en quelques lignes de commandes.


https://github.com/Simplon-lyon/dev-web/wiki/devops
 


Installation

    Installer VirtualBox

sudo apt-get update
sudo apt-get install virtualbox virtualbox-qt virtualbox-dkms

    Télécharger Vagrant


Boxes:

    https://box.scotch.io

    Vagrant push
    
    


Box Puphpet   https://puphpet.com


TUTO : https://www.youtube.com/watch?v=Yb20B0kPrro


    configurer sa vm
    télécharger
    dézipper , renommez vm-php7
    déplacez le dossier vers ~/vagrant/boxes/

cd ~/vagrant/boxes/vm-php7
vagrant up

    ouvrir 192.168.56.101



VAGRANT & PUPHPET

TuTO https://www.youtube.com/watch?v=Yb20B0kPrro

https://puphpet.com/

1) Go -> https://puphpet.com/   ->   Cobfig VM
2) Download VM
3) dézipper , renommez  et mettre dans le dossier
4) Cd  Go -> le dossier de VM ->  vagrant up
5) ouvrir 192.168.56.101

Mettre les fichiers dans le dossier   html

Reg ex dans puphpetFinich


Pour reinicialiser le Puphpet utiliser gliser sur https://puphpet.com/   - config.yaml









