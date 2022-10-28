![Logo du hackaton](/docs/assets/images/logo_v2.png)

### Bonjour à tous 👋

La direction générale des Finances publiques ("DGFiP") organise un hackathon qui se tiendra les 1 et 2 décembre 2022.

___

# I. Qui sommes-nous ?

La DGFiP participe à la gestion des Finances publiques en France, en matière de dépenses et de recettes : elle gère notamment la fiscalité de l’État et des collectivités territoriales qui s’impose aux particuliers et aux entreprises, et en assure le recouvrement au moyen de son réseau territorial.

Elle est placée sous la tutelle du ministère de l'Économie, des Finances et de la Relance ("MEFR"). 

La Délégation à la Transformation Numérique (“DTNum”) mène la transformation numérique de la DGFiP. Une cinquantaine de personnes travaille au sein de trois pôles dédiés : Données (open data, datascience), Culture numérique, et Expérience utilisateur.

Elle a été créée en 2021.

___


# II. Appel à projets

Les participants devront par équipes de 5 (constituées le jour-même ou à l'avance) réaliser l'un des 2 défis suivants:

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

___

# III. Calendrier et inscription

### A. Calendrier détaillé

- Inscriptions : jusqu’au 18 novembre 2022
- Hackathon : 1 et 2 décembre 2022
- Délibérations du jury et désignation des gagnants : 2 décembre 2022

### B. Inscription

Pour vous inscrire, renseignez le formulaire en ligne par équipe à cette adresse avant le 18 novembre 2022.

**NB : les participants devront se doter de leur ordinateur personnel afin de concourir au hackathon.**

Pour s'inscrire:
[https://www.galileo.finances.gouv.fr/index.php/195926?lang=fr](https://www.galileo.finances.gouv.fr/index.php/195926?lang=fr)

___


# IV. Rendu attendu

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

### B. Jury 

- **Gilles Tauzin** - Délégué à la Transformation Numérique - DGFiP 
*Président du jury*

- **Su Yang** - Responsable du Pôle Données - DTNum/DGFiP

- **Frédéric Iannuci** - Chef du service du contrôle fiscal

- **Philippe-Emmanuel de Beer** - Directeur de la direction nationale d’enquête fiscal

- **Pierre Boyer** - Professeur à l’école polytechnique–CREST

- **Natkamon Tovanitch** - Post-doctorant au sein de la chaire blockchain et expert  visualisation blockchain à l’école polytechnique


### C. Critères d'évaluation

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

### D. Récompenses

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


# V. Réglement et Contact   


### RÈGLEMENT DE L’APPEL À PROJET HACKATHON DE LA DGFiP - Version au 14 octobre 2022
   

### Préambule :

L’Appel à Projet Hackathon de la Direction Générale des Finances Publiques ("DGFiP") s’inscrit dans la politique d’ouverture des données que la DGFiP a mise en place conformément aux dispositions des lois Valter (2015) et Lemaire (2016), ainsi que dans une démarche propre qui s'attache à resserrer ses liens avec l'écosystème de l'innovation numérique et renforcer son attractivité sur les métiers du numérique.

### Article 1 – Organisateur :

L’entité organisatrice du présent Appel à Projet Hackathon est la DGFiP du Ministère de l’Économie, des Finances et de la Relance ("MEFR").


### Article 2 – Objet de l’Appel à Projet Hackathon :

La DGFiP organise un Appel à Projet Hackathon (ci-après également désigné « l’appel à projet»).   

Le terme d’"Appel à Projet Hackathon" désigne un concours destiné à développer des projets à partir de jeux de données en libre accès, technologiques ou non, de manière continue durant une période de temps donnée.   

La durée du concours ainsi que le calendrier détaillé de l'événement sont disponibles en annexe du présent document.   

L’objectif de cet appel à projet est de développer des projets utiles à la DGFiP à partir de ressources à la disposition des participants.   

Les réalisations des participants à l’appel à projet devront s’inscrire dans le thème de l’Appel à Projet Hackathon préalablement choisi par la DGFiP.
 
### Article 3 – Annonce de l’Appel à Projet Hackathon :

L’Appel à Projet Hackathon est annoncé par l’envoi d’une présentation aux bureaux des élèves des écoles et universités ciblées.   

### Article 4 – Conditions et modalités de participation à l'appel à projet :

#### 4.1 – Conditions d’inscription à l’appel à projet :

L’appel à projet est ouvert à tous les étudiants étant inscrits à l’Institut Polytechnique de Paris pour l’année 2022/2023.   

Les candidatures ne remplissant pas ces conditions pourront se voir proposer de concourir hors compétition.

#### 4.2 - Participation hors compétition

Les équipes qui acceptent de concourir hors compétition renoncent au versement des récompenses listées à l'article **7.1**. Elles restent liées par les autres termes du présent règlement, qui demeurent inchangés.

### 4.3 – Conditions de participation à l'appel à projet :

Les participants à l'appel à projet devront réaliser un projet conforme à l’objet de l'appel à projet.

### Article 5 – Programme de l’appel à projet :

### 5.1 – Informations générales :

L’appel à projet se déroule pendant une période précisée dans la partie "Calendrier et inscriptions" de ce document.  


### 5.2 – Rendu :

Le rendu doit s'effectuer sur un repository Github du nom de l'équipe. Ce repository sera créé par les organisateurs après validation de l'inscription de l'équipe.

Selon les choix faits par les participants, le rendu devra contenir :

- l'ensemble du code source produit ;
- un lien vers le ou les DashBoard Tableau publiques produits le cas échéant, comportant le label #openDataDGFiP.

En tout état de cause, chaque rendu devra contenir a minima:

- un document de synthèse (ci-après désigné "le document de synthèse") au format PDF ou vidéo comportant :
    - une explication de la démarche poursuivie ;
    - la formulation d'une problématique explicite sous la forme d'une question ;
    - un bref descriptif de la solution mise en œuvre pour y répondre.

Dans le cas d'un rendu au format vidéo, il ne devra pas excéder 3 ('trois') minutes. Dans le cas d'un rendu au format PDF, il ne devra pas excéder 20 ('vingt') pages.

*Les participants sont libres de produire s'ils le souhaitent une vidéo et un pdf explicatif.*

Dne documentation technique (ci-après désignée "la documentation technique") au format Markdown ou PDF. Cette documentation technique devra contenir a minima :

- les instructions nécessaires à l'installation et à la reproduction de la solution technique ;
- une présentation étayée des choix techniques retenus si pertinents ;
- la liste de chacune des sources de données exploitées, leur url, licence, et la reproduction des mentions légales relatives à la réutilisation de ces jeux de données selon leur type de licence.


### 5.3 – Données mises à disposition des participants :

Le présent appel à projet vise à faire exploiter par les participants les jeux de données ouverts de la DGFiP. Les jeux de données ouverts produits par la DGFiP sont accessibles par le biais de serveurs mis à disposition des étudiants par la DGFiP.

### Article 6 – Présentation des projets à la DGFiP :

Le livrable du projet (ci-après le « livrable ») est constitué de l’ensemble de la documentation technique, du document de synthèse, de tout script, code et paramétrage permettant la mise en œuvre de la solution technique, de tout élément de configuration ou paramétrage du graphe et de toute idée menée et utilisé aux fins de la compétition.

### Article 7 – Sélection des lauréats par La DGFiP :

Le jury de l’appel à projet (ci-après désigné « le jury ») choisira les projets qu'il estime les plus aboutis dans l'exploitation des jeux de données ouverts de la DGFiP.

Le jury est composé de personnels qualifiés de la DGFiP et de personnalités extérieures reconnues pour leur expertise en matière technologique, d’innovation ou d’usage de données.   

Les participants sont alertés sur le fait que la composition du jury telle qu'annoncée dans le document de présentation du concours est susceptible d'évolution, et ne revêt pas de caractère contractuel.     

Le jury évaluera les projets soumis par les participants de l’Appel à Projet Hackathon en fonction de différents critères, énoncés ci-après : 

- Pertinence par rapport au thème général, intérêt pour la DGFiP, portée et impact pour les utilisateurs (40 % de la note) ;
- Qualité technique : exploitabilité, conformité aux standards, choix de l’architecture et des technologies (30% de la note) ;
- Ergonomie : facilité d’utilisation et design de l'information (30% de la note) ;

Le jury de l’Appel à Projet Hackathon de la DGFiP se réserve le droit d'exclure de la participation à l’appel à projet, avec avis motivé, les projets  

- non conformes à l’objet de l’appel à projet;
- non conformes au thème de l’appel à projet;
- reçus après la date de clôture annoncée.


#### 7.1 - Récompenses

Les trois équipes lauréates de l’appel à projet recevront les lots désignés ci-après.  

Première place :

- 3000 euros ("trois mille euros") pour l'équipe
- Incubation du projet gagnant dans un service informatique de la DGFiP.

> L’incubation du projet ne revêt aucun caractère obligatoire, elle relève d’une opportunité basée sur le volontariat de la part de l’équipe gagnante.
> 

Deuxième place :

- 1500 euros ("mille cinq cent euros") pour l’équipe
- Possibilité pour les membres de l'équipe de réaliser un stage au sein d'un projet informatique de la DGFiP.

> La possibilité d'un stage ne revêt aucun caractère obligatoire, elle relève d’une opportunité basée sur le volontariat de la part de l’équipe lauréate.
> 

Troisième place:

- 500euros ("cinq cents euros") pour l’équipe
- possibilité pour les membres de l'équipe de réaliser un stage au sein d'un projet informatique de la DGFiP.

> La possibilité d'un stage ne revêt aucun caractère obligatoire, elle relève d’une opportunité basée sur le volontariat de la part de l’équipe lauréate.
> 

Répartition des lots : la responsabilité de la répartition des lots au sein de son équipe incombe au responsable d'équipe, auquel sera versée la récompense.

### Article 8 – Garanties et responsabilités :

8.1 – Le participant s’engage à fournir, dans son formulaire d’inscription à l’appel à projet, des informations réelles et sérieuses le concernant.   

8.2 – Le participant s’engager à signer la charte du participant communiqué en annexe avant le début du hackathon 2022 et à respecter toutes les obligations décrites dans la charte susmentionnée.   

8.3 – Le participant est seul responsable de ses matériels et logiciels, dont il conserve la garde, et des éventuels dommages qui pourraient survenir sur ses matériels et logiciels dans le cadre de l’Appel à Projet Hackathon de la DGFiP.   

8.4 – Le participant déclare et garantit à la DGFiP qu’elle dispose de l’intégralité et de l’exclusivité des droits de propriété intellectuelle afférents aux créations constitutives du projet qu’il réalise dans le cadre de l'appel à projet et à sa documentation afférente, ou qu’il est dûment autorisé à agir au nom et pour le compte du ou des autres titulaire(s) des droits sur ce projet et sur la documentation afférente.   

Le participant garantit la DGFiP contre tout recours de tiers à cet égard et reconnaît être informé qu’il sera tenu pour seul responsable en cas de violation de la présente obligation de garantie.
Ces déclarations et garanties couvrent l’intégralité des éléments du livrable.   

8.5 – La DGFiP se réserve le droit d’écourter, modifier ou annuler le présent appel à projet à tout moment, sans préavis et sans qu’il puisse être prétendu à aucune indemnité par les participants.
Leur responsabilité ne saurait être engagée du fait de ces modifications, ni celle de la DGFiP.   

8.6 – Il est expressément rappelé qu’Internet n’est pas un réseau sécurisé. La DGFiP ne saurait donc être tenue pour responsable de la contamination par d’éventuels virus ou de l’intrusion d’un tiers dans le système terminal des participants et décline toute responsabilité quant aux conséquences de la connexion des participants au réseau Internet.   

Il appartient à tout participant de prendre toutes les mesures appropriées de façon à protéger ses propres données et/ou logiciels stockés sur son équipement informatique contre toute atteinte.  

La DGFiP ne saurait être tenue pour responsable d’éventuels dysfonctionnements liés au réseau Internet lui-même ou liés à toute intrusion, tentative d’intrusion ou fraude ayant entraîné des défaillances dans l’administration, la sécurité, l’équité, l’intégrité ou la gestion de l’appel à projet.   

La DGFiP ne saurait être déclarée responsable pour toutes erreurs, omissions, interruptions, effacement, perte de toute donnée de ce fait.  

La DGFiP ne saurait être tenue responsable si les données relatives à l’inscription d’un participant ne leur parvenaient pas pour une quelconque raison ou lui arrivaient illisibles ou impossibles à traiter.   

8.7 – La DGFiP se réserve le droit d’exclure de la participation au présent appel à projet toute personne troublant son déroulement.

### Article 9 – Droits d’auteur et Propriété Intellectuelle :

Il est rappelé qu’un logiciel se présente sous deux formes : un Code Source, qui est un langage particulier, et qui peut être écrit et compris par un être humain ; et un Code Exécutable (Objet) généré à partir du Code Source et destiné à être lu par une machine.   

Le droit d’auteur français protège le code source comme s’il s’agissait d’une œuvre littéraire. Toutefois c’est la manière de structurer le code source, telle qu’elle est matérialisée par une suite de signes, qui fera l’objet de la protection par le droit d’auteur, sachant que la fonctionnalité n’est pas protégeable ni protégée.    

Les groupes participants à l’événement Hackathon 2022 resteront ainsi titulaires du code source qu’ils ont développé et jouiront de toutes les prérogatives qui y sont liées au niveau des droit moraux, conformément aux principes du Code de la Propriété Intellectuelle.    

Néanmoins la DGFiP, dans un souci de contribution collective à l'esprit d'ouverture des données publiques, invite les participants à adopter une licence libre parmi les suivantes pour développer leur projet : _CeCILL 2.1 _Etalab 2.0    

Il est précisé que la DGFiP utilise la licence CeCILL 2.1, dans le cadre de la loi pour une République numérique, et, à ce titre, elle encourage fortement les groupes participants à développer leur projet sous ladite licence.

Ce faisant, les Groupes participants concèdent à la DGFIP les droits suivants :

1. Droits d’Utilisation du logiciel, à savoir : a) la reproduction permanente ou provisoire du Logiciel en tout ou partie par tout moyen et sous toute forme. b) le chargement, l'affichage, l'exécution, ou le stockage du Logiciel sur tout support. c) la possibilité d'en observer, d'en étudier, ou d'en tester le fonctionnement afin de déterminer les idées et principes qui sont à la base de n'importe quel élément du Logiciel ; et ceci, lorsque la DGFIP effectue toute opération de chargement, d'affichage, d'exécution, de transmission ou de stockage du Logiciel qu'il est en droit d'effectuer en vertu de la licence libre.
2. Droit d’apporter des contributions (traduire, adapter, arranger ou apporter toute autre modification)
3. Droits de distribution (droit de diffuser, de transmettre et de communiquer le Logiciel au public sur tout support et par tout moyen) La DGFIP s'engage à ne pas supprimer ou modifier de quelque manière que ce soit les mentions de propriété intellectuelle apposées sur le Logiciel (respect du droit à la paternité de l’œuvre) ; ni à reproduire à l'identique lesdites mentions de propriété intellectuelle sur les copies du Logiciel modifié ou non.

### Article 10 – Autorisation de réutilisation non commerciale de l’image et des interventions des participants :

Le participant à l'appel à projet autorise la DGFiP à réaliser des photos ainsi que des enregistrements sonores et/ou audiovisuels (ci-après désignés « les enregistrements ») de son image et des éventuelles interventions orales qu’il pourra réaliser durant l’appel à projet.   

Il cède gracieusement à la DGFiP, au titre de son droit à l’image et de son droit d’auteur sur ses interventions, le droit de reproduire et de représenter son image et ses interventions par voie de photos et d’enregistrements à des fins non commerciales et conformément à ce qui est défini ci-dessous :

- le droit de reproduire les photos et enregistrements, en intégralité ou par extraits, par tous procédés connus et inconnus à ce jour (notamment par voie graphique, par enregistrement magnétique, optique, numérique ou électronique…) et sur tous supports (notamment sur papier ou tout support graphique, sur CD-Rom, DVD-Rom, disques durs, clés USB...), aux fins d’archivage et de communication au public dans les conditions sujetnies ci-après ;
- le droit de représenter les photos et enregistrements, en intégralité ou par extraits, par tous procédés de communication au public connus et inconnus à ce jour (notamment via le réseau hertzien, le câble, le satellite, la télécommunication et/ou tout procédé de communication par voie numérique ou électronique) aux fins de diffusions gratuites telles que ci-après définies : diffusion dans les enceintes de la DGFiP sur tout type d’écrans, tant à destination du public que du personnel de la DGFiP ; diffusion en ligne sur les sites Internet de la DGFiP, et sur tous les portails donnant accès à ces sites, ainsi que sur toutes les plateformes et réseaux sociaux lui étant associés (tels que Flickr, Youtube, Facebook, Twitter, …), avec possibilité de téléchargement par les internautes pour leur strict usage personnel, à des fins de communication sur l’Appel à Projet Hackathon de la DGFiP et plus généralement sur les activités de la DGFiP ; utilisation dans le cadre de la communication interne et externe de la DGFiP, de la promotion de l’établissement et de ses activités.

L’autorisation concédée à la DGFiP par le participant au titre de son droit à l’image est cédée pour le monde entier et sans limitation de durée.

### Article 11 – Données à caractère personnel des participants :

Les informations recueillies à partir du courriel d’inscription à l’Appel à Projet Hackathon de la DGFiP font l'objet d'un traitement informatique réalisé par la DGFiP, située au 120 rue de Bercy (75 772 PARIS CEDEX 12), laquelle agit dans le cadre de l’exécution d’une mission relevant de l’exercice de l’autorité publique dont elle est investie.   

Les données mentionnées pour l’inscription (Nom, Prénom, Adresse mail, Numéro de téléphone, Sujet retenu) sont obligatoires pour le participant ou pour chacun des participants dans le cas d’une inscription collective. À défaut, l’inscription ne saurait être prise en compte.   

Ce traitement a pour finalité l’organisation de l’appel à projet sous forme de «jeu-concours» Appel à Projet Hackathon uniquement, comprenant la gestion administrative des inscriptions à l’Appel à Projet Hackathon, la réalisation de statistiques sur la composition des  groupes de participants et l'envoi d'informations pratiques relatives aux inscriptions. Le responsable du traitement est l’organisateur mentionné à l’article 1.   

Les données sont conservées à compter de la date d’inscription pour une durée de 3 mois.   

Elles sont destinées aux agents habilités de la DGFiP dans le cadre de leurs attributions et conformément au besoin d’en connaître.  

Conformément à la loi « Informatique et Libertés » du 6 janvier 1978 modifiée et au Règlement Général sur la Protection des Données n°2016/679 (RGPD), vous disposez des droits suivants :

- droit d'accès et de rectification de vos données personnelles ;
- droit d'effacement de vos données personnelles sauf dans les cas limitativement énumérés à l’article 17.3 du RGPD ;
- droit d’opposition, sauf s’il existe des motifs légitimes et impérieux pour le traitement prévalant sur les intérêts et droits et libertés de la personne concernée ou pour la constatation, l’exercice ou la défense de droits en justice ;
- droit à la limitation du traitement.

Pour toute demande relative à l'exercice de droits sur des données personnelles, il convient de nous contacter par courriel à l'adresse suivante :
[dtnum.communication@dgfip.finances.gouv.fr](mailto:dtnum.communication@dgfip.finances.gouv.fr)

Vous avez également la possibilité d’adresser votre demande au délégué à la protection des données du ministère de l’Économie, des Finances et de la Relance par voie électronique ([le-delegue-a-la-protection-des-donnees-personnelles@finances.gouv.fr](mailto:le-delegue-a-la-protection-des-donnees-personnelles@finances.gouv.fr)) ou par voie postale (139 rue de Bercy, Télédoc 322, 75572 PARIS CEDEX 12).

Si vous estimez que le traitement de vos données à caractère personnel n'est pas conforme aux dispositions légales et réglementaires, vous disposez, en outre, du droit d'introduire une réclamation auprès de la Commission nationale de l’informatique et des libertés (CNIL) par le biais de son formulaire en ligne sur son site internet ou par voie postale.

### Article 12 – Acceptation du règlement :

La participation à cet Appel à Projet Hackathon implique l’acceptation pleine et entière des modalités énoncées dans le présent règlement.   

L'inscription d'une équipe vaut acceptation du présent règlement par l'ensemble de ses membres.   

L’acceptation du règlement de l’appel à projet vaut pour la création que le participant soumettra.   

### Article 13 – Publication du règlement :

Les organisateurs se réservent le droit de modifier le présent règlement à tout moment sous la forme d'un avenant.   
Toute personne refusant la ou les modification(s) intervenue(s) ne pourra participer à l’Appel à Projet Hackathon.

### Article 14 – Fraude :

Toute fraude, ou tentative de fraude, manifestée par un commencement d'exécution et commise en vue de percevoir indûment un gain, fera l'objet de poursuites.

### Article 15 – Litiges :

Les parties s'efforceront de résoudre à l'amiable tout différend né de la validité, de l'interprétation ou de l'exécution du présent règlement. Si le désaccord persiste au-delà d'un mois, il sera soumis aux tribunaux compétents français.

### Article 16 – Loi applicable et opposabilité du règlement :

Le présent règlement est soumis au droit français. Le fait de s’inscrire et de participer à l'Appel à Projet Hackathon de la DGFiP implique l’acceptation sans réserve du présent règlement.



Des questions sur l’appel à projets ? Besoin d’informations complémentaires ?

**Contactez-nous à : [dtnum.communication@dgfip.finances.gouv.fr](mailto:dtnum.communication@dgfip.finances.gouv.fr)**
>
<!-- > **Consulter le [réglement](https://github.com/hackaton-dgfip-2022/hackaton-dgfip-2022.github.io/blob/main/R%C3%A8glement.md)** -->

___


# VI. Charte du participant

**Consulter la [Charte du participant](https://github.com/hackaton-dgfip-x-2022/hackaton-dgfip-x-2022.github.io/blob/master/Hackathon_Charte%20du%20participant-V1.odt?raw=true)**
