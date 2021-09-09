My learnings from Ubuntu.

Ubuntu is forked from debian...

packet manager:
apt-get --> Debian, Ubuntu

----------------
Comandos Ubuntu:
----------------
--update and refresh repository lists<br>
sudo apt update

--atualiza somente os pacotes já instalados da versão atual<br>
sudo apt upgrade

--atualiza a versão da distro ex: 20.04 para 21.04<br>
sudo apt-get dist-upgrade

--to clean up outdated package deb files<br>
sudo apt-get autoclean

--to remove any unused dependencies<br>
sudo apt-get autoremove

--to clean up apt cache<br>
sudo apt-get clean

--instala o gcc para funcionar o guest additions no VirtualBox<br>
sudo apt install build essential<br>
sudo apt install gcc<br>
sudo apt install make perl<br>
sudo apt install dkms<br>

--The software-properties-common package gives you better control over your package manager by letting you add PPA (Personal Package Archive) repositories<br>
sudo apt install software-properties-common 

--Deadsnakes is a PPA with newer releases than the default Ubuntu repositories<br>
sudo add-apt-repository ppa:deadsnakes/ppa

