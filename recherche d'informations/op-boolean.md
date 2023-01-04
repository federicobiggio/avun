La logique booléennepermet de représenter trois types de relations entre les termes d’une équation ou des ensembles de documents. 
Ces relations sont: 
* la relation d’union, que l’on représente avec l’opérateur OU, 
* la relation d’intersection, que l’on représente avec l’opérateur ET, et 
* la relation d’exclusion, que l’on représente avec l’opérateur SAUF

Opérateurs booléens pour préciser la recherche : 

ET, OU, SAUF (AND, OR, NOT)           : inclure, exclude
"…"                                   : recherche l’expression exacte
- (es : veille -ecran)                : exclure un terme de la recherche
.. (abonnement Internet 20..30 euros) : recherche les valeurs comprises entre deux nombres
()                                    : Elles permettent de limiter la portée des opérateurs booléens et/ou d’introduire un ordre de priorité entre les                                            différentes parties d’une requête. Exemple : (commerce OU paiement) ET électronique repérera les entrées qui                                                contiennent à la fois électronique et soit commerce soit paiement soit ces deux termes.

ADJ  - trouver des documents dans lesquels les termes choisis sont simultanément présents et de sorte qu'un terme est immédiatement suivi d'un autre. 

NEAR – Trouver des documents dans lesquels les termes choisis sont simultanément présents et disposés dans de manière à ce qu'ils soient proches les uns des autres (généralement à un distance entre 5 et 10 mots) mais quel que soit l'ordre dans lequel ils apparaissent dans le document

? – Inséré à la fin du mot recherché à la place de la dernière lettre, il renvoie tous les documents dans lesquels le mot apparaît au masculin ou au féminin. le féminin et/ou le singulier ou le pluriel

use * – Inséré après la racine du mot recherché, il renvoie tous les documents dans lesquels des termes ayant la même racine sont présents

site:google.fr«---»                   : recherche un terme dans un site

cache: google.fr                      : recherche des versions mises en cache par Google

define:veille                         : define

filetype:pdf veille                   : rechercher un format de document precis
