# Projet : Mise en place d'un routeur sur Linux avec VirtualBox (GEAY Raphaël et AGUER Hugo)

## Présentation du projet

Ce projet a pour objectif de mettre en place un **routeur** virtualisé pour une petite entreprise, capable de gérer plusieurs zones réseau et de fournir des services essentiels. En plus du routage, le routeur offre les fonctionnalités suivantes :

- **Firewall** : Mise en place de règles de filtrage pour sécuriser le trafic.
- **DHCP** : Attribution automatique des adresses IP aux clients.
- **DNS** : Résolution de noms pour faciliter l'accès aux ressources.
- **Portail captif** : Contrôle des accès clients via une authentification web, basée sur CoovaChilli et Apache/PHP.

## Configuration des machines virtuelles

### Routeur (Ubuntu)

- **Système et interfaces réseau**  
  - Installation d'Ubuntu sur VirtualBox.
  - Configuration des interfaces réseau pour séparer le trafic LAN et WAN.

- **Services réseau**  
  - Activation et configuration du pare-feu avec des règles personnalisées.
  - Mise en place du service DHCP et DNS.

- **Portail captif**  
  - Utilisation de **CoovaChilli** pour intercepter le trafic et gérer l'authentification.
  - Serveur web **Apache** configuré avec PHP pour servir le portail captif.
  - Le portail présente un formulaire de connexion (login.php) et redirige l'utilisateur vers Internet après authentification.

### Clients (Ubuntu)

- **Configuration réseau**  
  - Paramétrage en DHCP.
- **Tests de connectivité**  
  - Validation de l'accès aux services internes et à Internet.
  - Vérification du bon fonctionnement du routage et des règles de filtrage.

## Objectif final

Disposer d'un réseau complet, bien structuré et sécurisé, démontrable en environnement virtualisé. Le système intègre :

- Un routeur Ubuntu configuré pour gérer le routage, le DHCP, le DNS et le firewall.
- Un portail captif opérationnel qui authentifie les utilisateurs via un formulaire web en PHP et redirige vers Internet après une authentification réussie.
- Des clients Ubuntu configurés pour tester la connectivité et la sécurité du réseau.
