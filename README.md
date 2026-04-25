# Conception d’une infrastructure systèmes & réseaux d’entreprise (Projet BTS)
 
# Objectif

Réalisation d’une infrastructure d’entreprise dans le cadre de mon BTS SIO SISR.

# Technologies utilisées

## PfSense

Utilisation d'un logiciel open source de sécurité réseau qui transforme un ordinateur en pare-feu sophistiqué

### Tableau de bord

![TUpfsense1](TUpfsense1.png)

## Windows Server Core (Active Directory, DNS, DHCP)

La version Server Core de Microsoft sans interface graphique, conçue pour les environnements d'entreprise critiques nécessitant des performances et une sécurité renforcée.

## Linux (Debian)

### Configuration routeur

![TUrouteur1](TUrouteur1.png)

# Mise en place 

## Serveurs

### GLPI

![GLPI1](GLPI1.png)

### Zabbix

![TUzabbix1](TUzabbix1.png)

![TUzabbix2](TUzabbix2.png)

### Nextcloud

![TUnextcloud1](TUnextcloud1.png)

![TUnextcloud2](TUnextcloud2.png)

## Sauvegarde 

Veeam Backup & Replication est le moteur de sauvegarde et restauration de Veeam Data Platform

### VEEAM BACKUP

![TUWB1](TUWB1.png)

![TUWB2](TUWB2.png)

![TUWB3](TUWB3.png)

## Réseau

Infrastructure réseau sécurisée avec filtrage et routage fonctionnel.

### Configuration pfSense

- Règles

![TUpfsense4](TUpfsense4.png)

![TUpfsense5](TUpfsense5.png)

- Haute disponibilité (CARP)
  
### Installation relais DHCP

Installation d'un périphérique qui transfère les paquets DHCP entre les clients DHCP et les serveurs DHCP entre différents sous-réseaux

![TUrouteur2](TUrouteur2.png)


### Active Directory

Gestion centralisée des utilisateurs et des ressources avec redondance.

#### Création domaine
  
![AD1](AD1.png)

#### AD primaire + secondaire (redondance)
  
![AD2](AD2.png)

# Services

Déploiement et sécurisation d'une plateforme de supervision et de gestion de parc informatique avec mise en conformité HTTPS

## GLPI
  
![glpi](glpi.png)

## Zabbix (supervision)

![serviceszabbix1](serviceszabbix1.png)

## Nextcloud (avec LDAP)

Mise en place d'un environnement de travail collaboratif 

![servicesnextcloud1](servicesnextcloud1.png)

![servicesnextcloud2](servicesnextcloud2.png)

## VPN IPsec

Mise en place d'une solution permettant la connexion sécurisée entre deux sites distants 

![servicesvpnipsec1](servicesvpnipsec1.png)

![servicesvpnipsec3](servicesvpnipsec3.png)

# Sécurité

## HTTPS

![securiteHTTPS1](securiteHTTPS1.png)

![securiteHTTPS2](securiteHTTPS2.png)

![securiteHTTPS3](securiteHTTPS3.png)

## VPN Nomade

Mise en place d'une solution garantissant des accès sécurisés à un
service, internes au périmètre de sécurité de
l'organisation

![securiteVPN](securiteVPN.png)

![securiteVPN1](securiteVPN1.png)

![securiteVPN2](securiteVPN2.png)

## VPN IPSEC

![securitéVPNipsec1](securitéVPNipsec1.png)


# Outils d'administration Windows

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
