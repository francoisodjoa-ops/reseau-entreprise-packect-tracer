# reseau-entreprise-packect-tracer
premier projet de simulation reseau dans le cadre de mon apprentissage en reseau et cybersecurite
Réseau d'entreprise — Cisco Packet Tracer
Simulation d’un réseau local avec Cisco Packet Tracer
# 1. Présentation du projet
Ce projet consiste à concevoir et tester un premier réseau local (LAN) avec Cisco Packet Tracer. Il s’inscrit dans mon apprentissage des réseaux informatiques et de la cybersécurité.
# 2. Objectifs
- Comprendre le fonctionnement d’un réseau local.
- Relier plusieurs ordinateurs à l’aide d’un switch.
- Configurer des adresses IPv4 statiques.
- Comprendre le rôle du masque de sous-réseau.
- Vérifier la connectivité entre les appareils avec la commande ping.
# 3. Matériel utilisé
- Cisco Packet Tracer
- 2 ordinateurs (PC0 et PC1)
- 1 switch Cisco 2960
- Câbles Ethernet cuivre droits (Copper Straight-Through)
# 4. Plan d’adressage IPv4
- Appareil Adresse IPv4 Masque de sous-réseau
- PC0 192.168.1.10 255.255.255.0
- PC1 192.168.1.11 255.255.255.0
Les deux ordinateurs appartiennent au réseau 192.168.1.0/24. Aucune passerelle par défaut n’est nécessaire pour tester la communication entre ces deux appareils du même sous-réseau.
# 5. Tests réalisés
Depuis PC0, la commande suivante a été exécutée :
ping 192.168.1.11
Résultat observé : PC1 a répondu à la requête, ce qui confirme que la communication entre les deux ordinateurs fonctionne.
# 6. Compétences mises en pratique
- Création d’une topologie réseau simple.
- Connexion d’équipements réseau.
- Configuration IPv4 statique.
- Notions de réseau local et de sous-réseau.
- Vérification de la connectivité avec ICMP et ping.
- Sauvegarde et publication d’un projet avec GitHub.
# 7. Fichier du projet
Le fichier Packet Tracer est disponible dans ce dépôt :
reseau-lan-01.pkt
# 8. Améliorations prévues
- Ajouter un troisième ordinateur.
- Étudier les tables d’adresses MAC du switch.
- Créer plusieurs sous-réseaux.
- Découvrir les VLAN et le routage.
- Introduire des notions de sécurité réseau.
