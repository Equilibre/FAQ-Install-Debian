    su
    mkdir /blinux
    mount /dev/sda7 /blinux

Pour la monter de manière automatique à chaque démarrage du système, vous pouvez ajouter la ligne suivante dans /etc/fstab :

    mount /dev/sda7 /blinux  auto    rw,user,noauto  0       0
