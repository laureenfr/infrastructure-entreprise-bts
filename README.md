# Conception d’une infrastructure systèmes & réseaux d’entreprise (Projet BTS)
 
## Objectif

Réalisation d’une infrastructure d’entreprise dans le cadre de mon BTS SIO SISR, visant à reproduire un environnement professionnel réel.

## Architecture réseau


## Technologies utilisées

- PfSense (firewall, NAT, VPN)
- Windows Server (Active Directory, DNS, DHCP)
- Linux (Debian)
- GLPI
- Zabbix
- Nextcloud
- VPN

## Mise en place

### Réseau 

Réseau sécurisé avec filtrage des flux et routage fonctionnel entre sous-réseaux.

- Configuration PfSense

Configuration d’un pare-feu pfSense permettant de filtrer les flux réseau et sécuriser l’infrastructure.

![TUpfsense1](TUpfsense1.png)

Règles

![TUpfsense4](TUpfsense4.png)

![TUpfsense5](TUpfsense5.png)

Haute disponibilité (CARP)

![TUpfsense2](TUpfsense2.png) ![TUpfsense3](TUpfsense3.png)

- Routage
  
![TUrouteur1](TUrouteur1.png)

- Relais DHCP

Installation d'un périphérique qui transfère les paquets DHCP entre les clients DHCP et les serveurs DHCP entre différents sous-réseaux.

![TUrouteur2](TUrouteur2.png)


### Active Directory

Infrastructure AD redondante permettant une gestion centralisée et résiliente des utilisateurs.

- Création domaine
  
![AD1](AD1.png)

- AD primaire + secondaire (redondance)
  
![AD2](AD2.png)

### Services

Plateforme complète de gestion, supervision et collaboration déployée et fonctionnelle.

- GLPI

Mise en place et utilisation d’un outil de gestion de parc informatique.

![glpi](glpi.png)

- Zabbix (supervision)

Mise en place et utilisation d’une solution de supervision avec Zabbix.
  
![TUzabbix1](TUzabbix1.png)

- Nextcloud (avec LDAP)

Mise en place d’un environnement de travail collaboratif avec authentification via LDAP.

![TUnextcloud1](TUnextcloud1.png)

- Sauvegarde (avec VEEAM BACKUP)

Mise en place d’une solution de sauvegarde avec Veeam Backup & Replication pour assurer la protection des données.

![TUWB3](TUWB3.png)

### Sécurité

- HTTPS

![securiteHTTPS1](securiteHTTPS1.png)

![securiteHTTPS3](securiteHTTPS3.png)

- VPN

VPN IPsec

Mise en place d'une solution permettant la connexion sécurisée entre deux sites distants 

![servicesvpnipsec3](servicesvpnipsec3.png)

VPN Nomade

Mise en place d'une solution garantissant des accès sécurisés à un
service, internes au périmètre de sécurité de
l'organisation

![securiteVPN2](securiteVPN2.png)

### Système d'exploitation utilisés 

- Windows : Client et Server Core (Active Directory, DNS, DHCP)

La version Server Core de Microsoft sans interface graphique est conçue pour les environnements d'entreprise critiques nécessitant des performances et une sécurité renforcée.

- Linux (Debian 12)

### Outils d'administration centralisée Windows

- Console mmc.exe

Utilisation d'un gestionnaire de console virtuelle incorporée dans Microsoft Windows 

![consolemmc](consolemmc.png)

### Outils de connexion à distance

- MRemoteNG

Utilisation d'un outil pour administrer et centraliser les serveurs via RDP, SSH, VNC, etc

![mremoteng](mremoteng.png)

- WinSCP

Utilisation d'un outil de transfert de fichiers entre un ordinateur local et un serveur distant 

![winscp1](winscp1.png)

![winscp2](winscp2.png)

## Résultat

Infrastructure complète fonctionnelle avec supervision et sécurisation.

## Compétences

- Administration systèmes Windows/Linux
- Réseaux
- Cybersécurité
- Supervision
