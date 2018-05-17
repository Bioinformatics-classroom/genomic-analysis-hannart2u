# UE génétique médicale 2018-05-17
* Alicia Hannart
## Exercice 1

### Q1
La séquence de référence correspond à *NC* pour les variations génomiques (ADN).

### Q2
NC_0000*18*.9:g.52895514_52895515delGA : Ces variants proviennent du chromosome 18.

### Q3
1. NC_000018.9:g.52895531T>C --> NM_001243236.1:c.1449A>G
2. NC_000018.9:g.52999284delG --> NM_001243232.1:c.336+18306delC
On sait que l'ADN complémentaire (cDNA) correspond aux bases complémentaires de l'ADN de référence. Or, étant donné que les bases sont changées (T devient A et C devient G dans la première séquence), on peut en conclure que la séquence donnée est située sur le brin anti-sens car si elle avait été sur le brin sens, la base n'aurait pas changé dans l'ADNc.

3. NC_000018.9:g. 53331929C>A --> Variant non contenu dans la base de données. (Cf question 5 : La séquence est intronique donc elle ne peut pas être dans la base de données).

### Q4
Remarque : Pour chercher une délétion dans gnomAD : il faut préciser la base qui précède la délétion dans le sens génomique (5′3′). Pour rechercher *NC_000018.9: g.11111delA*, le format d’entrée dans gnomAD est *18-11110-TA-T*.

2. NC_000018.9:g.52999284delG --> 18-52999283-TG-T : La fréquence dans la population générale de ce variant est 0.02478.
1. NC_000018.9:g.52895531T>C --> 18-52895531-T-C : La fréquence dans la population générale de ce variant est 0.3750.
3. NC_000018.9:g. 53331929C>A --> 18-53331929-C-A : La fréquence dans la population générale de ce variant est 0.000008164.

### Q5

2. NC_000018.9:g.52895531T>C : D'après GnomAD, la séquence est intronique et n'a donc aucune conséquence protéique.
1. NC_000018.9:g.52895531T>C : Ce variant est observé dans 23 transcrits dont 22 sont "synonymes" c'est-à-dire que les protéines produites sont identiques. Le 23ème transcrit est situé dans un exon non codant, donc que la protéine n'est pas produite (traduite) et ne peut par conséquent pas avoir de conséquence protéique.
3. NC_000018.9:g. 53331929C>A : Ce variant est trouvé dans 1 transcrit et entraîne la formation d'un codon STOP et donc d'une protéine tronquée potentiellement non fonctionnelle.

### Q6

Le variant n°3 (NC_000018.9:g. 53331929C>A) seble mériter uen étude plus approfondie car il est le seul a avoir un impact protéique et statistiquement, il est beaucoup moins présent dans la population générale à l'image du syndrome de Pitt-Hopkin étudié ici.




