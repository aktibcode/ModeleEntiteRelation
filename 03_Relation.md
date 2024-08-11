# Chapitre : RELATION


# Relation

* Une relation représente des liens entre des occurrences d’entités.
* Plusieurs employés travaillent dans le service « département_1 ».
* La relation modélise la relation ou l'association entre les entités département et employé

![](https://i.imgur.com/s18qLnB.png)

# Relation

![](https://i.imgur.com/it4VJQb.png)

Une relation peut avoir plus d'informations (attributs)

![](https://i.imgur.com/KJUaOiM.png)

# Cardinalités

* Les cardinalités font partie des propriétés d'une association.
* Dans un SGBD, la cardinalité fait référence à la relation entre deux entités. Nous devons avoir deux termes de cardinalités, de chaque côté de chaque entité.
* Il modélise le nombre de fois (minimum-maximum) de participation de l'entité dans la relation.
* La valeur minimale est soit 0 soit 1 et la valeur maximale varie entre 1 et N

# Cardinalités

![](https://i.imgur.com/NsnVmge.png)

* Un employé travaille dans un service
* Un département embauche entre un et N employés
* Il existe 4 types de cardinalités : **0..1, 0..N, 1..1, 1..N**

# Types de relations

* Le type d’une relation donnée peut être identifié en fonction des cardinalités de chaque côté.
* Il existe 3 types de relations :
  * Un à un **(1..1)**
  * Un à plusieurs **(1..N)**
  * PlusieursàPlusieurs **(N..N)**

![](https://i.imgur.com/ZRDtLfo.png)

« Works_for » est une relation OnetoMany.

### Ces ressources peuvent vous aider

relation

[http://www.agiledata.org/essays/dataModeling101.html](http://www.agiledata.org/essays/dataModeling101.html)
