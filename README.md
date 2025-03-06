# Projet : Mise en place d'un routeur sur linux avec VirtualBox (GEAY Raphaël et AGUER Hugo)

## Présentation du projet

Ce projet vise à mettre en place un **routeur** gérant différentes zones réseau pour une petite entreprise. En plus du routage, le routeur offrira des fonctionnalités supplémentaires telles que :

- **Firewall** pour la sécurité.
- **DHCP** pour l'attribution des adresses IP.
- **DNS** pour la résolution de noms.
- **Portail captif** pour la gestion des accès clients.

## Configuration des machines virtuelles

### **Routeur (Ubuntu)**

- Installation et configuration du système.
- Configuration des interfaces réseau.
- Activation du pare-feu et des règles de filtrage.
- Mise en place du DHCP et DNS.
- Configuration du portail captif.

### **Serveur (Rocky Linux)**

- Installation et mise en place des services internes (Web).
- Test d’accessibilité depuis le LAN et l’extérieur.

### **Client 1 et 2 (Ubuntu)**

- Configuration réseau en **DHCP** ou **IP statique**.
- Test de connexion aux services internes et à Internet.
- Vérification du bon fonctionnement du routage et du firewall.

***

**Objectif final :** Avoir un réseau bien structuré et sécurisé, avec un routage et des services fonctionnels, démontrable en environnement virtualisé.
