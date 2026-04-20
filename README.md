# infrastructure-entreprise-bts

## Objectif
Réalisation d’une infrastructure d’entreprise dans le cadre de mon BTS SIO SISR.

## Technologies utilisées
- pfSense (firewall, NAT, VPN)
- Windows Server (Active Directory, DNS, DHCP)
- Linux (Debian)
- GLPI

![GLPI1](GLPI1.png]

- Zabbix

![TUzabbix1](TUzabbix1.png)

![TUzabbix2](TUzabbix2.png]

- Nextcloud
- Sauvegarde avec VEEAM BACKUP

## Mise en place

### Réseau
- Configuration pfSense
- Routage et relais DHCP

### Active Directory
- Création domaine
  
![AD1](AD1.png)
- AD primaire + secondaire (redondance)
  
![AD2](AD2.png)

### Services
- GLPI
- Zabbix (supervision)
- Nextcloud (avec LDAP)

### Sécurité
- HTTPS
- VPN Nomade

## Outils d'administration Windows
- Console mmc.exe

## Outils de connexion à distance
- MRemoteNG
- WinSCP

## Résultat
Infrastructure complète fonctionnelle avec supervision et sécurisation.

## Compétences
- Administration systèmes Windows/Linux
- Réseaux
- Cybersécurité
- Supervision
