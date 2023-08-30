# Anydesk_ubuntu22.04_install
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
