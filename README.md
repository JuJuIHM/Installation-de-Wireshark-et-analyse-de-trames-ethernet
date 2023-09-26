# Installation-de-Wireshark-et-analyse-de-trames-ethernet

Quels protocoles ont été utilisés dans la trace réseau capturée ? Indique comment tu as eu cette information (quelle fenêtre, éventuellement quelle ligne ou quelle colonne).

Les protocols utilisés sont :
- ARP, protocole de résolution d’adresse (Address Resolution  Protocol)
- Le protocole ICMP (Internet Control Message Protocol) 
![image](https://github.com/JuJuIHM/Installation-de-Wireshark-et-analyse-de-trames-ethernet/assets/137881830/f2f3006c-6e71-44c9-91bc-4abc9db1a112)

Quelles sont les adresses IP et les adresses MAC des interfaces ayant échangé des informations ? Address Resolution Protocol (ARP, protocole de résolution d’adresse)
IP de la machine source : 10.1.1.1 - adresse MAC : 00:50:79:66:68:00
IP de la machine de destination : 10.1.1.2 - adresse MAC : 00:50:79:66:68:01

Quel filtre d'affichage permet de ne plus afficher les paquets ARP ?
Aucune idée...

Quelles informations sont disponibles dans la colonne info de la liste des paquets pour la ligne 3 ?
la machine source a fait un ping, a interrogé une autre machine.

Le paquet N°8 est-il une question ou une réponse ? et quel est le paquet correspondant (la question, si c'est une réponse ou la réponse, si c'est une question ?
Le paquet n°8 est une réponse. La demande (question) correspondante est le paquet n°7.

