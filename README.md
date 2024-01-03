## Commande sous windows 
| Commande        | Description      |
| ------|-----|
| firewall.cpl | On peut acceder au paramètre du firewall, Par la suite on doit cliquer sur parametre avance ou on pourrait trouver les regles qui interdisent ou pas qu une connexion reseau se fasse.|

## Commande réseau sous windows
| Commande        | Description      |
| ------|-----|
| netsh interface show interface | On peut voir le nom et le statut de notre interface réseau |
| netsh interface ip add address | modifie l’adresse IP |
| ipconfig /renew | demande une nouvelle adresse IP au serveur DHCP |
| ipconfig /release | libère l’adresse ip actuelle |
| netsh interface ip set dns «Ethernet» dhcp | cette commande permet de configurer en mode DHCP l’adresse IPv4 d’un serveur DNS |
| netsh interface ip delete address "Ethernet" «IPV4» | cette commande permet de supprimer une IPV4 sur la carte Ethernet |
| ipconfig /flushdns | Efface le cache DNS local |
| netstat | Affiche les connexions réseau actives, les ports ouverts et d'autres informations réseau |
| tracert | Affiche le chemin pris par les paquets pour atteindre une destination spécifiée |
| ping | Envoie un paquet de test à une adresse IP spécifiée pour vérifier la connectivité réseau |

## Commande réseau sous Linux
| Commande        | Description      |
| ------|-----|
| apt-get update | mettre à jour les paquets |
|apt-get install resolvconf | permet d’installer le paquet resolvconf (qui nousservira pour les commandes réseaux) |
| apt-get install network-manager | permet d’installer Network Manager qui gèrera alors les interfaces et leurs configurations |
| systemctl enable NetworkManager | permet de laisser Network Manager tout le temps actif, même au redémarrage) |
| dpkg-reconfigure keyboard-configuration | mettre leclavier en clavier Belge. |
| - su - | se mettre en mode super utilisateur (mode root) |
