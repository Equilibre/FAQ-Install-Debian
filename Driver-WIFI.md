Il est nécessaire d'installer le paquet firmware-iwlwifi depuis votre package manager.
Si vous n'avez aucun accès réseau, vous pouvez aussi le trouver directement ici :

    wget http://ftp.fr.debian.org/debian/pool/non-free/f/firmware-nonfree/firmware-iwlwifi_0.43_all.deb

Une fois téléchargé, installer le avec la commande :

    sudo su
    dpkg -i firmware-iwlwifi_0.43_all.deb

Un redémarrage sera peut être nécessaire pour activer la carte wifi.
