# Anydesk How to install on ubuntu 22.04
Installation de anydesk sous ubuntu 22.04

Installer AnyDesk sous Ubuntu 22.04

I- Via le terminal

1- Mettre à jour le système Ubuntu

$- sudo apt update


2- Ajouter le référentiel AnyDesk

$- curl -fsSL https://keys.anydesk.com/repos/DEB-GPG-KEY|sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/anydesk.gpg

$- echo "deb http://deb.anydesk.com/ all main" | sudo tee /etc/apt/sources.list.d/anydesk-stable.list

3- Installez AnyDesk sur Ubuntu
$- sudo apt update

$- sudo apt install anydesk

4- Lancez AnyDesk sur Ubuntu
$- anydesk


II- Via le fichier .deb

1- Télécharger le fichier.deb ci dessus et se déplacer dans le repertoire ou le fichier a été téléchargé
par exemple : 
$- cd Téléchargement

2- exécuter la commande suivante pour installer anydesk à l'aide du .deb téléchargé
$- sudo dpkg -i anydesk_6.3.0-1_amd64.deb

3- lancer anydesk
$- anydesk
