### Ajouter un membre au domaine
Exemple avec  un serveur membre,

Je vais dans la config IP, 
- Je mets sous le même réseau
- Adresse passerelle celle de son Vyos Correspondant
- Adresse DNS   = 172.16.10.1
- Je change son nom
- Redéamarrer


### NAT 
set nat source rule 10 outbound-interface eth0
set nat source rule 10 source address 192.168.2.0/24
set nat source rule 10 translation address masquerade

### Vyos
set console keymap pour changer vyos en FR


### GPO 
Les stratégies de groupe sont gérées à travers des objets de stratégie de groupe communément appelés GPO (Group Policy Objects).

### PSO
Les stratégies de mots de passe affinées correspondent à des objets « Paramètres de mots de passe » et sont également appelées « PSO » pour « Password Settings Object ».


## Groupes locaux
Les groupes locaux sont vraiment locaux. Ils sont définis et disponibles uniquement pour l’ordinateur spécifique sur lequel ils ont été créés. Ne créez pas de nouveaux groupes locaux sur les postes de travail ; dans la plupart des cas, les seuls groupes locaux qu’il faut gérer sont les groupes d’utilisateurs et d’administrateurs.

### Pour créer : 
- On se co sur une de machine
- Sur server manager on clique sur "tools" --> "Computer Management"
- ensuite on clique sur Local Users and Groups
- Puis groupe
- Clique droit "new group"
- puis add des users


### Groupes du domaines
Les groupes locaux de domaine permettent de gérer les autorisations des ressources, car ils peuvent être appliqués partout dans le domaine. Un groupe local de domaine peut inclure des membres du domaine de tout type et des membres issus de domaines de confiance. Supposons par exemple que vous deviez gérer l’accès à une collection de dossiers sur un ou plusieurs serveurs contenant des informations destinées aux responsables. Le groupe que vous créez dans ce but doit être un groupe local de domaine (par exemple, « DL_Managers_Modify »).


### Groupes Universels
Les groupes universels d’Active Directory sont utiles dans les forêts multi-domaines. Ils vous permettent de définir des rôles ou de gérer des ressources couvrant plusieurs domaines. Chaque groupe universel est stocké dans le domaine dans lequel il a été créé, mais son appartenance aux groupes est stockée dans le catalogue global et répercutée à l’ensemble de la forêt. N’utilisez pas les groupes universels si vous n’avez qu’un seul domaine.

### Groupes globaux
Les groupes globaux servent principalement à définir des collections d’objets de domaine (utilisateurs, autres groupes globaux et ordinateurs) en fonction des rôles métier, ce qui signifie qu’ils servent principalement de groupes de rôles. Les groupes d’utilisateurs basés sur des rôles (par exemple, « RH » ou « Marketing ») et les groupes d’ordinateurs basés sur des rôles (par exemple, « Postes de travail marketing ») sont généralement des groupes globaux
