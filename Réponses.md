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

## Exercice 2

### Q1
La variation se trouve dans le gène SHOX.

### Q2
1. SHORT STATURE, IDIOPATHIC, X-LINKED : Syndrome de Turner
2. LERI-WEILL DYSCHONDROSTEOSIS 
3. LANGER MESOMELIC DYSPLASIA

### Q3
L''absence du gène SHOX (dûe à l'absence du chromosome X dans le caryotype des femmes atteintes par ce syndrome) provoque notamment la petite taille des individues.

### Q4
La notation HGVS de cette variation au niveau génomique est : NM_000451.3:c.399G>C.

### Q5
NC : Complete genomic molecules
_000023 : Chromosome X
.10 : 1àème version du gène
g. : ADN génomique
595474G>C : en position 595474 : substitution du G (référence) par un C (alternatif)

### Q6
NM_000451.3(SHOX_i001):p.(Glu133Asp)

### Q7
NM : mRNA
_000451 : Numéro correspondant au transcrit
.3 : Version de ce gène
(SHOX_i001) : nom du gène et n° d'isoforme
p. : affection au niveau de la protéine
(Glu133Asp) : La Glu en position 133 est remplacée par un Asp.

### Q8
Il s'agit d'une mutation faux-sens par le remplacement d'un acide glutamique (GAG) par un acide aspartique (GAC) sans création de codon stop, sans décalage de l'ORF.

### Q9
(http://genome.ucsc.edu/cgi-bin/hgTracks?db=hg19&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chrX%3A595464%2D595484&hgsid=669218391_4Byvn1ugtEfyEFAemHnRIZGKQrMU)

### Q10
On trouve que le brin est le brin positif. Donc le gène est situé sur le brin sens.

### Q11
Il comporte 6 exons.

### Q12
Il s'agit du 3èm exon sur -;

### Q13
Il se trouve dans une région peu conservée parmi les espèces.

### Q14
Le variant se trouve dans le domaine "homeobox".

### Q15
(https://www.ncbi.nlm.nih.gov/pubmed/7815426)
(https://www.ncbi.nlm.nih.gov/pubmed/6954848)

### Q16
(https://www.ensembl.org/Homo_sapiens/Tools/VEP/Results?db=core;tl=7rm6pftTnUvoEB2s-4193828)

### Q17
Certaines séquences sont Ensembl et d'autres refseq. Certaines séquences sont déterminées bioinformatiquement (XR)

### Q18

### Q19
(http://wannovar.wglab.org/done/159927/jURFPaXB_fBjR868/index.html)

### Q20
DOI: 10.1038/gim.2015.30 (https://www.nature.com/articles/gim201530)

### Q21


### Q22



