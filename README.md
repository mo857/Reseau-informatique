firewall.cpl ==>On peut acceder au firewall avec la recherche firewall.cpl. Par la suite on doit cliquer
sur parametre avance ou on pourrait trouver les regles qui interdisent ou pas qu une
connexion reseau se fasse.<br><br>
netsh interface show interface = on peut voir le nom et le statut de notre
interface réseau<br><br>
netsh interface ip add address= pour modifier l’adresse IP.<br><br>
apt-get update = mettre à jour les paquets<br><br>
ipconfig /renew = demande une nouvelle adresse IP au serveur DHCP<br><br>
ipconfig /release = libère l’adresse ip actuelle<br><br>
netsh interface ip set dns «Ethernet» dhcp = cette commande permet de configurer en mode DHCP l’adresse IPv4 d’un serveur DNS.<br><br>
netsh interface ip delete address "Ethernet" «IPV4» = cette commande permet de supprimer une IPV4 sur la carte Ethernet
ipconfig /flushdns = Efface le cache DNS local<br><br>
netstat =Affiche les connexions réseau actives, les ports ouverts et d'autres informations réseau<br><br>
tracert = Affiche le chemin pris par les paquets pour atteindre une destination spécifiée.<br><br>
ping = Envoie un paquet de test à une adresse IP spécifiée pour vérifier la connectivité réseau.<br><br>
