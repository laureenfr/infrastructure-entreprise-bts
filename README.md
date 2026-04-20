# infrastructure-entreprise-bts

## Objectif
Réalisation d’une infrastructure d’entreprise dans le cadre de mon BTS SIO SISR.

## Technologies utilisées
- pfSense (firewall, NAT, VPN)

![TUpfsense1](TUpfsense1.png)

- Windows Server (Active Directory, DNS, DHCP)

![TUwindowsserver1](TUwindowsserver1.png)

- Linux (Debian)


- GLPI

![GLPI1](GLPI1.png)

- Zabbix

![TUzabbix1](TUzabbix1.png)

![TUzabbix2](TUzabbix2.png)

- Nextcloud

![TUnextcloud1](TUnextcloud1.png)

![TUnextcloud2](TUnextcloud2.png)

- Sauvegarde avec VEEAM BACKUP

## Mise en place

### Réseau
- Configuration pfSense
- Routage et relais DHCP

![TUrouteur1](TUrouteur1.png)

![TUrouteur2](TUrouteur2.png)

### Active Directory
- Création domaine
  
![AD1](AD1.png)
- AD primaire + secondaire (redondance)
  
![AD2](AD2.png)

### Services
- GLPI
  
![glpi](glpi.png)

- Zabbix (supervision)

![serviceszabbix1](serviceszabbix1.png)

- Nextcloud (avec LDAP)

![servicesnextcloud1](servicesnextcloud1.png)

![servicesnextcloud2](servicesnextcloud2.png)

- VPN IPsec

![servicesvpnipsec1](servicesvpnipsec1.png)

![servicesvpnipsec3](servicesvpnipsec3.png)

### Sécurité
- HTTPS

![securiteHTTPS1](securiteHTTPS1.png)

![securiteHTTPS2](securiteHTTPS2.png)

![securiteHTTPS3](securiteHTTPS3.png)

- VPN Nomade

![securiteVPN](securiteVPN.png)

![securiteVPN1](securiteVPN1.png)

![securiteVPN2](securiteVPN2.png)

- VPN IPSEC

![securiteVPNipsec1](securiteVPNipsec1.png)


## Outils d'administration Windows
- Console mmc.exe

## Outils de connexion à distance
- MRemoteNG

![mremoteng](mremoteng.png)

- WinSCP

## Résultat
Infrastructure complète fonctionnelle avec supervision et sécurisation.

## Compétences
- Administration systèmes Windows/Linux
- Réseaux
- Cybersécurité
- Supervision
