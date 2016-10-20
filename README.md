

VAGRANT DOC



VAGRANT   https://www.vagrantup.com/

Qu’est ce que Vagrant ?   https://www.synbioz.com/blog/vagrant_et_la_virtualisation_pour_faciliter_le_developpement



_____________________________________________________________________________________________




VAGRAND

Install Vagrant & VirtualBox

VirtualBox

Vagrant
https://www.vagrantup.com/


Vagrant permet d'accélerer la mise en place d'environnements de dev.
Il permet de configurer et d'utiliser des machines virtuelles en quelques lignes de commandes.


2)  Boxes:

VAGRANT  ScotchBox

https://box.scotch.io/
1) Download and Install Vagrant 2) Download and Install VirtualBox 3) git clone https://github.com/scotch-io/scotch-box.git 4) Cd Go -> scotch-box -> vagrant up 5) Success! You can now access your project by visiting http://192.168.33.10/
Mettre les fichiers dans le dossier public


OU


VAGRANT & PUPHPET

TuTO https://www.youtube.com/watch?v=Yb20B0kPrro
https://puphpet.com/
1) Go -> https://puphpet.com/ -> Cobfig VM 2) Download VM 3) dézipper , renommez et mettre dans le dossier 4) Cd Go -> le dossier de VM -> vagrant up 5) ouvrir 192.168.56.101
Mettre les fichiers dans le dossier html
Reg ex dans puphpetFinich
Pour reinicialiser le Puphpet utiliser gliser sur https://puphpet.com/ - config.yaml



_____________________________________________________________________________________________


Command-Line Interface

https://www.vagrantup.com/docs/cli/halt.html

http://severin-bruhat.com/tutoriels/vagrant-premiers-pas/


vagrant up  -  lancer vagrant

vagrant ssh - Pour tester si vagrant est bien lancée

vagrant halt  - vagrant stop

vagrant suspend - vagrant Sauvegarder et Pour mettre la VM en veille prolongée

vagrant resume - Pour relancer la VM 



_____________________________________________________________________________________________



EN +


Vagrant & VirtualBox

https://www.vagrantup.com/
https://www.virtualbox.org/


EN + https://github.com/Simplon-lyon/dev-web/wiki/devops
 
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





_____________________________________________________________________________________________




