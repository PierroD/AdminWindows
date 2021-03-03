


### Approche systémique 
Approche avec une vue global.

### Définition d’un système
« Ensemble d’éléments en interaction dynamique,
organisé en vue d’atteindre un but commun » Joël
De Rosnay «Le macroscope », éditions du seuil,
1975

### L'entreprise comme système:
- Système de pilotage 
Décide et contrôle

- Système d'information
Mémorise, traite et diffuse

-Système Opérant
Transforme et produit

## Exercice
### Diapo 50 EX1
(10^2)*(10^3)=100000
Code articulé
Code séquentielle



### Les clés de contrôle modulo 23
Clé= lettre correspondant au rang donné par Code
modulo 23 + 1 (I, O, S exclus pour ne pas confondre
avec 1, 0, 5)
• Exemple: 159357 Modulo 23 = 13 ;
Alphabet(13+1) = « P »;
donc le code avec sa clé est 159357P
• Inconvénient: domaine des restes restreint, donc
plusieurs codes peuvent avoir la même clé.


### Clé de contrôle modulo 97
Clé= code MODULO 97
• Exemple : 159357 Modulo 97 = 83
donc le code avec sa clé est 15935783
• Inconvénient: clé sur deux caractères pouvant être
eux-mêmes sources d'erreur

### Clé de contrôle complément à 9
• clé= complément à 9 de chaque position du code.
• Exemple: code= 159357
Son complément à 9 est 840642 ; le code avec sa clé
est 159357 840642
• Inconvénient: bien qu'étant une méthode sûre
(bijection entre les codes et les clés), ce procédé
conduit à doubler la longueur du code.



### Clé de contrôle modulo 9
• Clé= (somme des chiffres du code) MODULO 9.
• Exemple: code= 159357
Somme des chiffres = 1+5+9+3+5+7= 30
30 Modulo 9 = 3 ;
• Donc code avec sa clé est 1593573
• Inconvénient: ne détecte pas les erreurs d'inversion
de deux chiffres.


### Exo Diapo 68 
[TypeDuDoc](1,2ou3) [Spé](CH ou SN) [SousSpé](1à5 et 1à9) [NumSéquentiel](AutoIncrement) 
CléControleModulo9

## Développement de systèmes d’information
### Quatre étapes incontournables
• La phase d'analyse des besoins: la formalisation des
besoins du le client et de l'ensemble des contraintes,
puis l'estimation de la faisabilité de ces besoins (un
cahier des charges)
• La phase de conception: fournir une description
fonctionnelle du système, avoir un modèle du système
• La phase de réalisation: c'est la traduction dans un
langage de programmation des fonctionnalités définies
lors de phases de conception
• La phase de mise place et maintenance: c'est le
déploiement sur site du SI, maintenance corrective et
évolutive 

• Le cycle de vie est la description d’un processus qui
couvre les phases de création, de distribution sur le
marché et de la disparition d’un produit (SI,
logiciel,…)
• Le but d’un tel découpage est de :
• Maitriser les risques
• Maitriser au mieux le délai et les coûts
• Obtenir une qualité conforme aux besoins



