# Différente Commandes pour paramétrer le réseau sous diférents systèmes d'exploitations. 

Bonjour, bienvenue sur cette page de différentes commande utile sous différents systèmes d'exploitations.<br>
c'est une genre de mini synthèse pour des commandes utilses en ligne de commande pour diverse paramétrage réseau.
*******
Table des matières  
 1. [Différente commande sous windows](#Commande-sous-windows)
 2. [Différente commande réseau sous windows](#Commande-reseau-sous-windows)
 3. [Différente commande réseau sous linux](#Commande-reseau-sous-linux)


*******


<div id='Commande-sous-windows'/> 
## Commande sous windows 

| Commande        | Description      |
| ------|-----|
| firewall.cpl | On peut acceder au paramètre du firewall, Par la suite on doit cliquer sur parametre avance ou on pourrait trouver les regles qui interdisent ou pas qu une connexion reseau se fasse.|

<div id='Commande-reseau-sous-windows'/> 
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
  
<div id='Commande-reseau-sous-linux'/> 
## Commande réseau sous Linux
 
| Commande        | Description      |
| ------|-----|
| apt-get update | mettre à jour les paquets |
|apt-get install resolvconf | permet d’installer le paquet resolvconf (qui nousservira pour les commandes réseaux) |
| apt-get install network-manager | permet d’installer Network Manager qui gèrera alors les interfaces et leurs configurations |
| systemctl enable NetworkManager | permet de laisser Network Manager tout le temps actif, même au redémarrage) |
| dpkg-reconfigure keyboard-configuration | mettre leclavier en clavier Belge. |
| - su - | se mettre en mode super utilisateur (mode root) |
|  ip addr show | cette commande nous permet de voir les cartes de notre serveur et également les adresses IP ( ip -6 addr show pour l’IPv6) |
| ip link show | vous montre votre adresse MAC et tout le niveau deux de votre carte |
| ip route show | vous montre les routes configurées sur le serveur et donc aussi celui du default gateway |
| hostnamectl | nous montre d’autres informations dont le nom d’utilisateur actuelle |
|ip addr flush dev enp0s3 | permet de supprimer toutes les configurations d’adresse IPv4 sur l’interface|
|  ip -6 addr flushdev enp0s | permet de supprimer toutes les configurations d’adresse IPv6 sur l’interface |
| pkill dhclient | permet de (tuer) d’arrêter tous les processus en cours d’exécution associés au programme dhclient |
|  ip route del default |upprime le default gateway (si on ajoute un -6 après ip ça sera pour l’IPv6) 
| nslookup | permet de voir les adresses DNS et les domaines qui y sont liés (il faut installer dnsutils  |

