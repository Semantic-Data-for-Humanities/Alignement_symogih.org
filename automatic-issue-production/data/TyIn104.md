### Résumé

**Scope note**

Cette information indique la présence d'un acteur ou d'un acteur collectif (par exemple une famille) à un évènement. L'évènement en question est rattaché via le rôle 'être l'objet'. Pour toute présence à un événement, même connu seulement dans ses traits généraux, on doit par conséquent créer une Information concernant cet évènement afin d'y rattacher l'Info 'présence'.	Si on souhaite signaler la présence d'une personne dans un lieu, on peut utiliser l'Info 'Présence' sans la rattacher à une autre information, et spécifier la raison de la présence avec un AbOb associé via le rôle justifier (TyRo72). Toutefois, la présence serait alors ponctuelle car pour décrire un séjour, une présence qui dure dans le temps, il est préférable d'utiliser une information de type 'Séjour' (TyIn138).	Si le nom précis de la personne présente n'est pas connu, mais seulement sa qualité, on utilise le rôle 'qualifier', avec sa spécification 'concerner'.	Si la présence à un évènement se fait sous forme d'une participation active il est préférable d'utiliser le type d'information 'Intervention' (TyIn139) : le TyIn104 indique une présence générique à un évènement, alors que une 'Intervention', ou plusieurs 'Interventions' de la même personne pour le même évènement, précisent sous quelle forme, avec quel impact cette présence a eu lieu.	Par conséquet, pour traiter des cas plus complexes (par exemple, le fait que tel acteur est présent à un Concile en qualité d'archevêque de Lyon et, en même temps, qu'il intervient en tant qu'ambassadeur de roi de France), il faut créer plusieurs informations, de type 'Présence, 'Représentation' ou 'Intervention'. 

**Lien**

[https://ontome.net/ns/symogih/TyIn104](https://ontome.net/ns/symogih/TyIn104)

### Alignement

**Alignement proposé** :

#### Alignement des rôles

| Rôle (tel qu'apparaissant dans OntoME) | Range | Alignement | Notes |
| ----- | ----- | ----- | ----- |
| [sym:TyRo95_TyIn104 qualifier](https://ontome.net/ns/symogih/TyRo95_TyIn104) | [sym:GenSoCh](https://ontome.net/ns/symogih/GenSoCh) |   |   |
| [sym:TyRo7_TyIn104 être présent](https://ontome.net/ns/symogih/TyRo7_TyIn104) | [sym:Actor](https://ontome.net/ns/symogih/Actor) |   |   |
| [sym:TyRo8_TyIn104 localiser](https://ontome.net/ns/symogih/TyRo8_TyIn104) | [sym:LoOb](https://ontome.net/ns/symogih/LoOb) |   |   |
| [sym:TyRo13_TyIn104 être l'objet](https://ontome.net/ns/symogih/TyRo13_TyIn104) | [sym:Info](https://ontome.net/ns/symogih/Info) |   |   |
| [sym:TyRo21_TyIn104 être concerné](https://ontome.net/ns/symogih/TyRo21_TyIn104) | [sym:Group](https://ontome.net/ns/symogih/Group) |   |   |

### Commentaires