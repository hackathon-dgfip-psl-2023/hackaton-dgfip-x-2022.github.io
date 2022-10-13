![Logo du hackaton](/docs/assets/images/logo-final-x.png)

### Bonjour à tous 👋

La Direction Générale des Finances Publiques ("DGFiP") organise un hackathon visant à mettre en valeur ses données ouvertes. Cette compétition se tiendra du 29 avril au 22 mai 2022.
Les étudiants des meilleures écoles d’ingénieurs et universités françaises sont invités à concourir.

Ce document vous donne toutes les informations pratiques :
- Présentation du concours
- Données ouvertes
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

À ce titre, les candidats sont invités, par équipes de 1 à 5 personnes, à s’approprier une problématique et à produire une solution technique ouverte et réutilisable qui y réponde en utilisant *a minima* un jeu de données de la DGFiP.

### B. Choix du sujet

Cette solution portera sur l’un des sujets suivants :

- Sujet 1 - à partir du jeu de données des **Coordonnées des Structures DGFiP** :

> *“La couverture du territoire par les structures DGFiP est-elle optimale et assure-t-elle un égal accès de tous au service public ?”*

- Sujet 2 - à partir du jeu de données des **Parcelles des Personnes Morales** :

> *“La proportion d'entreprises propriétaires de leurs locaux sur un territoire est-elle un marqueur de bonne santé économique ?”*

- *Sujet Libre* - à partir d’un jeu de données DGFiP ouvert **au choix**

> Les candidats peuvent s’ils le souhaitent composer leur propre sujet à partir de leur analyse des ressources à disposition.

Dans ce cas, ils devront également fournir une problématique sous la forme d’une question, à laquelle leur solution technique apportera une réponse, en se basant sur un jeu de données ouvert DGFiP au choix. 

___

**NB : Dans le cas des sujets 1 et 2, les problématiques sont fournies à titre d’exemple. Les participants sont libres de les amender ou d’en proposer de nouvelles, à partir du même jeu de données.**

___

### C. Jeux de données ouverts de la DGFiP

L’ensemble des jeux de données ouverts de la DGFiP est disponible à [cette adresse](https://data.economie.gouv.fr/explore/?sort=modified&refine.publisher=DGFiP) 

> ***Coordonnées des structures DGFiP ( Sujet 1 )***

 
Points d’accueil et services de la DGFiP sur l’ensemble du territoire

> ***Locaux et parcelles des personnes morales ( Sujet 2 )***


Propriété des parcelles cadastrales des personnes morales et leur évolution

> ***Balances Comptables de l’ensemble des collectivités***


Balances des Communes, Départements, Régions, EPCI et Syndicats

> ***Comptes individuels des collectivités***


Comptabilité intégrale des collectivités utilisant la double écriture

> ***Demandes de valeurs foncières***


Transactions immobilières intervenues sur le territoire au cours des 5 dernières années, 
issues des actes notariés et déclarations cadastrales

> ***Service des retraites de l’État***
>

Cube de données agrégées reprenant les nouvelles pensions de droit direct liquidées par le Service des Retraites de l’État

### D. Croisements avec d'autres sources de données ouvertes 

Vos analyses et travaux peuvent se faire en conjonction avec des données ouvertes hors DGFiP.

Par exemple :

- Données socio-économiques et démographiques de l’INSEE
- Autres données du Ministère de l’Économie, des Finances et de la Relance
- Données Infogreffe sur l’immatriculation des entreprises auprès des tribunaux de commerce
- Fichiers de la Banque de France sur la démographie des entreprises
- Données de la Caisse des Dépôts
- Données liées aux investissements “France Relance”
- Données de la commande publique
[...] 

Pour commencer :
- [Data.Gouv](https://data.gouv.fr)
- [Data.Economie.Gouv](https://data.economie.gouv.fr)
- [Données Banque de France sur la démographie des entreprises](http://webstat.banque-france.fr/fr/#/node/5385687)

Soyez créatifs et inventifs dans le choix des ensembles de données à croiser ! 

### E. Technologie, Langages et Outils

#### Visualisation de données

Si le format de restitution est laissé à la discrétion des candidats, la solution de BI Tableau doit être utilisée pour des projets consistant en des visualisations de données.

Les candidats peuvent créer un compte gratuit [ici](https://public.tableau.com/en-us/s/).

Le dashboard public à réaliser devra comporter le tag #OpenDataDGFiP

Des Ressources Tableau peuvent être trouvées (en français) sur le site de [Tableau Public](https://public.tableau.com/fr-fr/s/resources)
  
#### Langages de programmation 

Les équipes Data de la DTNum travaillent sur les langages R et Python. Les participants, bien que libres du choix de leurs technologies, sont encouragés à utiliser ces langages. 

## III. Rendu attendu

### A. Contenu du dossier à remettre

Les équipes devront restituer leurs productions dans un repository Github qui leur sera communiqué au lancement du concours. 
Le dossier à remettre doit comporter les éléments suivants : 

   **- Solution technique**

Si le livrable des candidats consiste en une visualisation Tableau, la restitution sur Github devra faire figurer un lien vers le(s) dashboard(s) publique(s) produit(s) et comportant le tag #OpenDataDGFIP2022.

Si le livrable des candidats contient du code R ou Python, l’ensemble des sources produites devront être déposées sur le repository Github de l’équipe.


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

- Inscriptions jusqu'au 29 Avril
- Rendu des projets le 22 Mai
- Délibérations du jury le 26 Mai
- Restitution pour les lauréats au cour d'un événement OpenData à Bercy le 3 Juin 

### C. Inscription

Pour vous inscrire, renseignez le formulaire en ligne par équipe à cette adresse avant le 29 Avril :

[https://framaforms.org/inscription-au-hackathon-open-data-des-finances-publiques-1647856985](https://framaforms.org/inscription-au-hackathon-open-data-des-finances-publiques-1647856985)

Pour concourir et valider le formulaire d'inscription, il vous sera demandé :

- Le nom de votre équipe
- L’école ou université de rattachement
- Les nom, prénom, et identifiant GitHub de chaque membre de l’équipe
- L’identifiant Github qui servira à la soumission
- Le sujet choisi
- La problématisation du sujet choisi sous la forme d’une question
- Un descriptif sommaire de la manière dont vous envisagez d’apporter une réponse à cette problématique
- Quelles raisons vous ont motivé à vous inscrire à ce hackaton ? 

### D. Jury 

- **Gilles Tauzin** - Délégué à la Transformation Numérique - DGFiP 
*Président du jury*

- **Su Yang** - Responsable du Pôle Données - DTNum/DGFiP

- **Pr. Salima Benbernou** - Professeur des Universités - Paris Descartes

- **Guillaume Coldre** - Administrateur Ministériel des Données - Bercy Hub / MEFR

- **Nicolas Truet** - Fondateur de Finestia

- **Thomas Lefebvre** - VP Data Science - MeilleursAgents

### E. Calendrier détaillé

- Date limite de dépôt des inscriptions : 29 Avril 2022 à 23h59
- Date limite de dépôt des projets : 22 Mai 2022 à 23h59
- Jury de sélection des lauréats : 26 Mai 2022
- Événement Open Data DGFiP : 3 Juin 2022


### F. Critères d'évaluation

Le Jury sera particulièrement attentif aux éléments suivants :

##### PERTINENCE ET IMPACT 40%

- Pertinence par rapport au thème choisi
- Originalité et finesse de la problématique
- Ingéniosité dans le choix des données croisées
- Bénéfice d’usage potentiel pour la DGFiP ou la société civile

##### TECHNICITÉ 30%

- Qualité du code ou du modèle (si pertinent par rapport à votre solution)
- Exploitabilité
- Conformité aux standards 

##### ERGONOMIE 30%

- Facilité d’utilisation
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

> **Consulter le [réglement](https://github.com/hackaton-dgfip-2022/hackaton-dgfip-2022.github.io/blob/main/R%C3%A8glement.md)**

___


## V. FAQ

### 1. Que doivent-contenir les soumissions ?

Votre rendu devra *a minima* contenir les éléments suivants :

- L'ensemble du code source produit pour parvenir à votre solution.
- Un document de synthèse au format PDF (max 20 pages), Markdown ou vidéo (max 3 minutes) contenant
    - une problématique explicite sous la forme d'une question
    - Une explication de la démarche poursuivie pour répondre au problème identifié
    - Un bref descriptif de la solution mise en oeuvre pour y répondre
- Une documentation technique au format Markdown ou PDF contenant
    - Une présentation étayée des choix techniques retenus si pertinent
    - Les instructions nécessaires à l'installation et à la reproduction de la solution.
    - La liste des sources de données exploitée s, leur url, licence, et les mentions légales relatives à leur réutilisation si pertinent.

### 2. Premiers pas sur GitHub

Vous n'êtes pas familier avec Git ? 

Découvrez ce qu'est Git sur sa page Wikipedia en français - [https://fr.wikipedia.org/wiki/Git](https://fr.wikipedia.org/wiki/Git)

De nombreux tutoriels gratuits sont disponibles pour vous former à cet outil. Liste non exhaustive : 
- Sur le site du W3C (en anglais) [https://www.w3schools.com/git/default.asp?remote=github](https://www.w3schools.com/git/default.asp?remote=github)
- Sur OpenClassrooms (en français) [https://openclassrooms.com/fr/courses/7162856-gerez-du-code-avec-git-et-github](https://openclassrooms.com/fr/courses/7162856-gerez-du-code-avec-git-et-github)

### 3. Premiers pas avec Markdown

Le Markdown est un langage de balisage léger permettant d'offrir une syntaxe facile à lire et à écrire, pouvant être facilement interprété en HTML. Il concerne les fichiers ayant l'extension ".md". 

Retrouvez plus d'information sur ce langage sur la page Wikipédia qui lui est dédiée
[https://fr.wikipedia.org/wiki/Markdown](https://fr.wikipedia.org/wiki/Markdown)

Il est idéal pour rédiger de la documentation. Plus d'informations sur sa syntaxe sur ce guide [https://www.markdownguide.org/basic-syntax](https://www.markdownguide.org/basic-syntax).

> Astuce: Le contenu du fichier `README.md` à la racine de votre dépôt Git est affiché sur la page d'accueil de votre repository dans l'interface web. Vous êtes bien entendus libres de manipuler ce fichier à votre convenance.
C'est le point d'entrée de votre projet pour une personne extérieure à l'équipe, apportez-lui une attention particulière ;-)

### 4. Limitation du stockage des repo à 500 mo

La taille de stockage des repositories GitHub est limitée à 500 Mo.

> ⚠️ 
> Les ensembles de données que vous utilisez ne doivent pas être téléversés (”uploadés”) sur votre dépôt GitHub
> 

Vous pouvez créer un fichier `.gitignore` à la racine de votre dépôt local pour lister les fichiers et répertoires de votre repository qui ne doivent pas être uploadés.

Toutes les infos nécessaires sur le fichier `.gitignore` et son utilisation sont accessibles à cette adresse [https://www.w3schools.com/git/git_ignore.asp?remote=github](https://www.w3schools.com/git/git_ignore.asp?remote=github).

