![Logo du hackaton](/docs/assets/images/logo-final-x.png)

### Bonjour à tous 👋

La Direction Générale des Finances Publiques ("DGFiP") organise un hackathon visant à mettre en valeur ses données ouvertes. Cette compétition se tiendra les 1 et 2 décembre 2022. Les étudiants des meilleures écoles d’ingénieurs et universités françaises sont invités à concourir.

Ce document vous donne toutes les informations pratiques :
- Présentation du concours
- Présentation des défis
- Conditions de participation
- Récompenses : + de 4 000€, mise en relations avec des experts de la data…

## I. Qui sommes-nous ?

La DGFiP participe à la gestion des finances publiques en France, en matière de dépenses et de recettes : elle gère notamment la fiscalité de l’État et des collectivités territoriales qui s’impose aux particuliers et aux entreprises, et en assure le recouvrement au moyen de son réseau territorial.

Elle est placée sous la tutelle du ministère de l'Économie, des Finances et de la Relance ("MEFR"). 

La Délégation à la Transformation numérique (“DTNum”) mène la transformation numérique de la DGFiP. Une cinquantaine de personnes travaille au sein de trois pôles dédiés: Données (open data, datascience), Culture numérique, et Expérience utilisateur.

Elle a été créée en 2021.

___


## II. Appel à projets

### A. Règles du jeu

Le présent concours vise à évaluer *le potentiel de réutilisation des jeux de données ouverts de la DGFiP*.

À ce titre, les candidats sont invités, par équipes de 1 à 5 personnes, à s’approprier une problématique et à produire une solution technique ouverte et réutilisable qui y réponde en utilisant a minima un jeu de données de la DGFiP.

### B. Choix du sujet

Cette solution portera sur l’un des sujets suivants :

**Défi 1** - Visualisation des transactions crypto à crypto via une base de données de type graphe :

> Le développement récent des actifs numériques s’est en partie accompagné, ces dernières années, d’une augmentation des manquements délibérés de déclaration des revenus issus des nombreux usages permis par les technologies sous-jacentes (cessions occasionnelles, trading, staking, minage...etc).
>
>À terme, à partir d’une adresse publique cryptographique, utilisée sur un registre public (une blockchain comme Bitcoin ou Ethereum), et dont ils ont déjà connaissance, les services du Contrôle Fiscal devront :
>- ppréhender l’ensemble des transactions entre cette adresse publique et d’autres adresses publiques cryptographiques formant un ensemble cohérent
>- identifier ensuite les entités qui effectuent ces transactions sous le pseudonymat des adresses publiques cryptographiques de chaque blockchain utilisée.
>
>Commande :  
> En utilisant l’outil Neo4j, vous représenterez sous la forme d’un graphe l’ensemble des adresses publiques cryptographiques d’un registre public distribué choisi [Bitcoin / Ethereum…]
>
>Plus précisément, sur l’écran affiché devant lui, un utilisateur doit pouvoir facilement:  
>1. visualiser une adresse publique cryptographique, qui correspond à un nœud sur une base graphe, et à un point ou rond de couleur pour l’utilisateur « néophyte »
>2. visualiser une transaction entre deux adresses, chaque transaction correspondant à une relation dans une base graphe, et à un trait (fléché? Coloré ?) pour l’utilisateur « néophyte »
>3. augmenter ou diminuer le niveau de détail entre les nœuds et les relations
>4. identifier les nœuds ayant davantage de relations que les autres (taille plus importante ou couleur différente) à partir d’un seuil laissé à l’appréciation des participants
>
>Moteur de base graphe : utilisation de Neo4j ou, si nécessaire, d’une alternative (TigerGraph, etc.)
>
>Jeux de données proposés  : Extraits des registres publics Bitcoin & Ethereum. 


**Défi 2** - Enrichissement des adresses publiques cryptographiques, représentant les transactions crypto-crypto, via l’osint :

>Le développement récent des actifs numériques s’est en partie accompagné, ces dernières années, d’une augmentation des manquements délibérés de déclaration des revenus imposables issus des nombreux usages permis par les technologies sous-jacentes (principalement les blockchains).
>
>À terme, à partir d’une adresse publique cryptographique, utilisée sur un registre public (une blockchain comme Bitcoin ou Ethereum), et dont ils ont déjà connaissance, les services du Contrôle Fiscal devront :
>- appréhender l’ensemble des transactions entre cette adresse publique et d’autres adresses publiques cryptographiques formant un ensemble cohérent
>- identifier ensuite les entités qui effectuent ces transactions sous le pseudonymat des adresses publiques cryptographiques de chaque blockchain utilisée.   
>
>Commande :    
>Via du moissonnage de données, vous veillerez à récupérer l’ensemble des informations disponibles en relation avec une adresse publique cryptographique, en fournissant les éléments de contexte de la page web dont elle est issue, par exemple si elle concerne une activité économique réalisée sur le territoire français.




## III. Rendu attendu

### A. Contenu du dossier à remettre

Les équipes devront restituer leurs productions dans qui leur sera communiqué au lancement du concours. Le dossier à remettre doit comporter les éléments suivants :

   **- Solution technique**

Si le livrable des candidats consiste en une visualisation (Neo4j, TigerGraph ou autre)

Si le livrable des candidats contient du code R, Python (ou autre), l’ensemble des sources produites devront être déposées sur le repository Github de l’équipe.


   **- Document explicatif (PDF ou Vidéo)**

Un document explicatif au format vidéo (maximum 3 minutes) ou PDF (maximum 20 pages) contenant a minima les éléments suivants:

  - Une explication de la démarche poursuivie
  - Une problématique formulée sous la forme d’une question. 

NB:  Cela est nécessaire dans le cadre du choix du sujet Libre. S’agissant des deux autres sujets, les participants ont la possibilité d’amender la question initiale s’ils l’estiment justifié. 

  - Un bref descriptif de la solution mise en oeuvre pour y répondre

Ce document pourra être enrichi par tout élément ou réflexion que les participants jugent pertinents (Utilisateurs pressentis, cas d’usage identifiés, qualité de la donnée source,  etc…)

   **- Documentation technique (PDF ou Markdown)**

Une documentation technique au format PDF ou Markdown contenant a minima les éléments suivants :
  - Une présentation des choix techniques faits
  - Les instructions nécessaires à la reproduction de la solution
  - la liste de chacune des sources de données exploitées, l’url de celles-ci, ainsi que les mentions légales relatives à la réutilisation de ces jeux de données selon leur licence. 

### B. Calendrier détaillé

- Inscriptions : 24 au 28 octobre 2022
- Hackathon : 1 et 2 décembre
- Délibérations du jury le 26 Mai
- Délibérations du jury et désignation des gagnants : 2 décembre

### C. Inscription

Pour vous inscrire, renseignez le formulaire en ligne par équipe à cette adresse avant le 29 Avril :

[https://www.galileo.finances.gouv.fr/index.php/195926?lang=fr](https://www.galileo.finances.gouv.fr/index.php/195926?lang=fr)

Pour concourir et valider le formulaire d'inscription, il vous sera demandé :

- Le nom de votre équipe
- L’école ou université de rattachement

### D. Jury 

- **Gilles Tauzin** - Délégué à la Transformation Numérique - DGFiP 
*Président du jury*

- **Su Yang** - Responsable du Pôle Données - DTNum/DGFiP

- **Frédéric Iannuci** - Chef du service du contrôle fiscal

- **Philippe-Emmanuel de Beer** - Directeur de la direction nationale d’enquête fiscal

- **Pierre Boyer** - Professeur à l’école polytechnique–CREST

- **Natkamon Tovanitch** - Post-doctorant au sein de la chaire blockchain et expert  visualisation blockchain à l’école polytechnique


### F. Critères d'évaluation

Le Jury sera particulièrement attentif aux éléments suivants :

##### PERTINENCE ET IMPACT 20%

- Originalité et finesse de la problématique (notamment pour la partie OSINT)
- Ingéniosité dans le choix des données croisées
- Bénéfice d’usage potentiel pour la DGFiP

##### TECHNICITÉ 40%

- Qualité du code ou du modèle (si pertinent par rapport à votre solution)
- Exploitabilité (Performance en temps de traitement, en utilisation de la RAM, etc …)
- Généricité de la solution envisagée
- Conformité aux standards

##### ERGONOMIE 40%

- Facilité d’utilisation
- Facilité de visualisation
- Facilité de requêtage
- Design de l’information

### G. Récompenses

> 🥇 **1er prix : 3000€ pour l’équipe**
> 
> Incubation possible du projet dans un service informatique de la DGFiP

> 🥈 **2ème prix : 1500€ pour l’équipe**
> 
> Stage possible au sein d'un projet informatique de la DGFiP

> 🥉 **3ème prix : 500€ pour l’équipe**
> 
> Stage possible au sein d'un projet informatique de la DGFiP


___


## IV. Contact et Réglement

> Des questions sur l’appel à projets ? Besoin d’informations complémentaires ?
> 
> **Contactez-nous à : [dtnum.donnees.open-data@dgfip.finances.gouv.fr](mailto:dtnum.donnees.open-data@dgfip.finances.gouv.fr)**
>
> **Consulter le [réglement](https://github.com/hackaton-dgfip-2022/hackaton-dgfip-2022.github.io/blob/main/R%C3%A8glement.md)**

___


## V. Charte du participant

**Consulter la [Charte du participant](https://github.com/hackaton-dgfip-x-2022/hackaton-dgfip-x-2022.github.io/blob/master/Hackathon_Charte%20du%20participant-V1.odt?raw=true)**
