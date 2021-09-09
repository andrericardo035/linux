My learnings from ubuntu-os.

Ubuntu is forked from debian...

packet manager:
apt-get --> Debian, Ubuntu

----------------
Comandos Ubuntu:
----------------
--update and refresh repository lists
sudo apt update

--atualiza somente os pacotes já instalados da versão atual
sudo apt upgrade

--atualiza a versão da distro ex: 20.04 para 21.04
sudo apt-get dist-upgrade

--to clean up outdated package deb files
sudo apt-get autoclean

--to remove any unused dependencies
sudo apt-get autoremove

--to clean up apt cache
sudo apt-get clean

--instala o gcc para funcionar o guest additions no VirtualBox
sudo apt install build essential
sudo apt install gcc
sudo apt install make perl
sudo apt install dkms

--The software-properties-common package gives you better control over your package manager by letting you add PPA (Personal Package Archive) repositories
sudo apt install software-properties-common 

--Deadsnakes is a PPA with newer releases than the default Ubuntu repositories
sudo add-apt-repository ppa:deadsnakes/ppa

