# Siel2026 / Formation BNRM
## Linked open data et culture / formation a la BNRM
On installe [OSDS](https://osds.openlinksw.com/) dans son navigateur.

### Démo d'intro.
Je demdande à une IA de créer une page Web documentée d'un "Event" de formation à la bibliothèque Royale du Maroc (Wikidata) le 4 mai 2026. Présentée par une "Person" Gérald Kembellec (sous la forme d'ISNI / ORCI), avec un titre, une image, un résumé.

Nous proposons de préparer des information "fiables" à partir du schéma de données de schema.org.
Par exemple, pour une personne : [https://schema.org/Person](https://schema.org/Person).

Les données seront travaillées de manière collaboratives ici : via [Gsheet](https://docs.google.com/spreadsheets/d/1jSb2ZWotyIK6_gjBdg0ogsA4TR3nbOWDt53a1bAPAss/edit?usp=sharing) puis enrichies avec [OpenRefine](https://openrefine.org/) en utilisant les données de Wikidata.
Ex. la page de Ibn Battuta aura pour 
- URN : Q7331
- URI : https://www.wikidata.org/wiki/Q7331
et il pourra être décrit avec le schéma : Person
Grace à OpenRefine on pourra aussi connaitre son "occupation", ses dates et lieux de naissance, de mort, son oeuvre principale...

Les jeux seront publiés ici :
- Les personnes
- Les faits
- les lieux

On mettra les données en formes avec une IA sous la forme de microdonnées ou de json-ld (... et on va vérifier avec [OSDS](https://osds.openlinksw.com/) et le [validateur de schema.org](https://validator.schema.org/)).

Puis on intègre tout ça dans une page Web publiée en ligne. On la vérifie.

Et après, on fait un agent IA ?
