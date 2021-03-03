# Atelier 1 Déploiement Windows Serveur

## Définition

### AD
Active Directory est un service d'annuaire créé par Microsoft en 1996 et destiné à être installé sur les Windows Server 2000, 2003, 2008, 2012 et 2016.
En stockant dans une base de données les renseignements relatifs aux ressources réseau d'un domaine, Active Directory a pour objectif premier de centraliser 
l'identification et l'authentification d'un réseau de postes Windows. Ses fonctions additionnelles permettent aux administrateurs de gérer efficacement une stratégie de 
groupe, ainsi que l'installation des logiciels et des mises à jour sur les stations du réseau.


### Serveur autonome
Un ordinateur qui exécute Windows Server, mais ne participe pas à un domaine. 
Un serveur autonome a seulement sa propre base de données des utilisateurs finaux, et il traite les demandes d'ouverture de session par lui-même. 
Il ne partage pas les informations de compte avec n'importe quel autre ordinateur et ne peut pas fournir l'accès aux comptes de domaine.

### Contrôleur de domaine
Un contrôleur de domaine est un serveur qui répond aux demandes d’authentification et contrôle les utilisateurs des réseaux informatiques.
Les domaines eux, sont un moyen hiérarchique d’organiser les utilisateurs et ordinateurs travaillant de concert sur le même réseau.
Le contrôleur de domaine permet donc d’organiser et de sécuriser toutes les données.

Le contrôleur de domaine (DC) est le coffret qui contient les clefs du royaume : l’Active Directory (AD). 
Si les hackers disposent de toutes sortes d’astuces pour élever leurs droits d’accès sur les réseaux et attaquer le DC lui-même, 
vous pouvez non seulement protéger vos DC contre les hackers mais également les utiliser pour détecter les cyberattaques en cours.


### Serveur Membre 
Un Serveur membre est un serveur qui est configuré dans un environnment réseau déjà piloté par un ou deux Controleurs de Domaine (PDC et BDC).
Donc le Serveur membre est juste utilisé pour le système d'exploitation


### Forêt
Une forêt Active Directory (forêt AD) représente le plus haut niveau de conteneur logique dans une configuration Active Directory contenant des domaines, 
utilisateurs, ordinateurs et règles de groupe.


### Groupe de travail
Un groupe de travail est un regroupement d'ordinateurs d'un réseau local, conçu pour aider les utilisateurs à trouver des ressources partagées à l'intérieur de ce groupe.
