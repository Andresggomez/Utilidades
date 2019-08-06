# Utilidades
Some command lines codes very useful in Linux

Entorno Virtual en Python

Creación de un entorno virtual para poder mantener las versiones de las librerías, frameworks aisladas del entorno de las dependencias de proyectos diferentes y del mismo S.O.

Ubuntu / Debian 

sudo apt install python3-pip
sudo pip install virtualenv

cd ~
mkdir mi_proyecto
virtualenv env

cd ~/mi_proyecto
source env/bin/activate

(env) ~/mi_proyecto$ deactivate
~/mi_proyecto$ 


