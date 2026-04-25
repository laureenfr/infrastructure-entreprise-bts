# Conception d’une infrastructure systèmes & réseaux d’entreprise (Projet BTS)
 
## Objectif

Réalisation d’une infrastructure d’entreprise dans le cadre de mon BTS SIO SISR.

## Technologies utilisées

- pfSense (firewall, NAT, VPN)
- Windows Server (Active Directory, DNS, DHCP)
- Linux (Debian)
- GLPI
- Zabbix
- Nextcloud
- VPN

## Mise en place

### Réseau 

- PfSense

Utilisation d'un logiciel open source de sécurité réseau qui transforme un ordinateur en pare-feu sophistiqué

![TUpfsense1](TUpfsense1.png)

Règles

![TUpfsense4](TUpfsense4.png)

![TUpfsense5](TUpfsense5.png)

Haute disponibilité (CARP)

![TUpfsense2](TUpfsense2.png) ![TUpfsense3](TUpfsense3.png)

Routage
  
![TUrouteur1](TUrouteur1.png)

Relais DHCP

Installation d'un périphérique qui transfère les paquets DHCP entre les clients DHCP et les serveurs DHCP entre différents sous-réseaux

![TUrouteur2](TUrouteur2.png)


### Active Directory

Gestion centralisée des utilisateurs et des ressources avec redondance.

#### Création domaine
  
![AD1](AD1.png)

#### AD primaire + secondaire (redondance)
  
![AD2](AD2.png)

### Services

- GLPI
- Zabbix (supervision)
  
![TUzabbix1](TUzabbix1.png)

- Nextcloud (avec LDAP)

Mise en place d'un environnement de travail collaboratif 

![TUnextcloud1](TUnextcloud1.png)

- Sauvegarde (avec VEEAM BACKUP)

Veeam Backup & Replication est le moteur de sauvegarde et restauration de Veeam Data Platform

![TUWB3](TUWB3.png)

# Sécurité

## HTTPS

![securiteHTTPS1](securiteHTTPS1.png)

![securiteHTTPS2](securiteHTTPS2.png)

![securiteHTTPS3](securiteHTTPS3.png)

## VPN

- VPN IPsec

Mise en place d'une solution permettant la connexion sécurisée entre deux sites distants 

![servicesvpnipsec1](servicesvpnipsec1.png)

![servicesvpnipsec3](servicesvpnipsec3.png)

- VPN Nomade

Mise en place d'une solution garantissant des accès sécurisés à un
service, internes au périmètre de sécurité de
l'organisation

![securiteVPN](securiteVPN.png)

![securiteVPN1](securiteVPN1.png)

![securiteVPN2](securiteVPN2.png)

## Système d'exploitation utilisés 

- Windows Server Core (Active Directory, DNS, DHCP)

La version Server Core de Microsoft sans interface graphique, conçue pour les environnements d'entreprise critiques nécessitant des performances et une sécurité renforcée.

- Linux (Debian)

- Windows client

## Outils d'administration centralisée Windows

### Console mmc.exe

Utilisation d'un gestionnaire de console virtuelle incorporée dans Microsoft Windows 

![consolemmc](consolemmc.png)

## Outils de connexion à distance

### MRemoteNG

Utilisation d'un outil pour administrer et centraliser les serveurs via RDP, SSH, VNC, etc

![mremoteng](mremoteng.png)

### WinSCP

Utilisation de transfert de fichiers entre un ordinateur local et un serveur distant 

![winscp1](winscp1.png)

![winscp2](winscp2.png)

# Résultat

Infrastructure complète fonctionnelle avec supervision et sécurisation.

# Compétences

- Administration systèmes Windows/Linux
- Réseaux
- Cybersécurité
- Supervision
