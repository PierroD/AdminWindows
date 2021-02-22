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

