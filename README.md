# -Tuto-Installation-d-un-serveur-web-sous-linux-PHP-7.4
Création et installation d'un serveur web sous linux

-----------------------------------------------------------------------------------------

Crée un hébergement web Linux server
Server Linux recommander :

Ubuntu 16.04
Ubuntu 18.04
Ubuntu 20.04
CentOS 7 / 8 / 9
Debian 8 / 9 /10
 Simple et pratique vous avez juste à taper la liste des commandes suivante dans l'ordre indiquer !

On vas commencer par le serveur apache2 / PHP

Les Dépôts

-----
Mise à jour
Ajout des dépôts
et installation :


```apt update && upgrade
apt -y install software-properties-common curl
LC_ALL=C.UTF-8 add-apt-repository -y ppa:ondrej/php
add-apt-repository -y ppa:chris-lea/redis-server
apt update
apt-add-repository universe
apt -y install php7.2 php7.2-cli php7.2-gd php7.2-mysql php7.2-pdo php7.2-mbstring php7.2-tokenizer php7.2-bcmath php7.2-xml php7.2-fpm php7.2-curl php7.2-zip mysql-server apache2 tar unzip git redis-server 
```

Voila vous avez installer les paquets pour le serveur web
Nous allons maintenant modifier le mot de passe root MYSQL Serveur

Arrêtez le serveur de base de données en lançant:

