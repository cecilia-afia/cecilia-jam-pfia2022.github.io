## La génération du jour
Le casse-tête a fait tomber le sot

# Jam Génération de texte à PFIA 2022

Cette année, le Collège Cécilia de l’AFIA organise une **Jam de génération de texte** poétique, ou drôle, ou les deux.

Inspirée des Game Jams et Proc Jams, cet événement proposera a ses partipant·es de jouer ensemble à **générer des textes** en expérimentant avec des outils liés à la pratique de l'IA.

Une jam est un événement ludique où la créativité est mise en avant. C'est un moment de rencontres, et un lieu d'**expérimentation** où le partage de compétences et l'apprentissage de nouvelles techniques sont encouragés.

Présentation de l'événement lors de la journée PDIA en Avril 2022:
- [Support de présentation](https://github.com/cecilia-afia/cecilia-jam-pfia2022.github.io/blob/gh-pages/cecilia_pdia_diffuse.pdf)
- [Vidéo de la présentation](https://youtu.be/R6xgWjrhDnc)


## Lancement: Rendez-vous Lundi 17h30 [salle 121 à l'EMSE](https://ci.mines-stetienne.fr/pfia2022/infos-locales/acces/#salles-emse-1ET) pour dévoiler les défis et les premières inscriptions!

<img src="https://ci.mines-stetienne.fr/pfia2022/img/EMSE_2ET.png" width="800">

## Déroulement
La Jam se déroulera **tout le long de la semaine** de PFIA 2022. 

Des défis particuliers sont proposés par le collège et d'autres organisations (thèmes, contraintes sur la forme du texte généré). La jam a vocation à occuper les temps calmes de la conférence et à fournir un espace physique de sociabilité. La session de clôture se déroulera en mode hybride et permettra de rassembler les textes générés préférés des partipant·es et leurs impressions sur l'événement. 

Il sera possible de rejoindre l'événement à tout moment de PFIA. Si vous quittez la conférence avant l'événement de clôture, vous pourrez y participer à distance, et fournir vos textes générés préférés.

La salle 121 de l'EMSE sera à la disposition des partipant·e·s qui pourront venir échanger et développer en équipes, et choisir ensemble la génération du moment à afficher sur le tableau. 

Un serveur Discord permet aux partipant·es inscrits d'échanger.

## Participation
Vous pouvez rejoindre la jam à tout moment de PFIA. Vous inscrire dès son lancement (ou dès votre arrivée) vous garantira des sujets de conversations pendant les pauses café.

Votre inscription vous donnera accès à un groupe sur Discord.

Il vous suffira d'un ordinateur portable (nous ne prêtons pas de matériel), équipé de quoi développer avec les outils de votre choix.

Le thème de l'événement a été choisi car il peut très bien se décliner sous la forme de nombreuses techniques d'IA.

Vous pouvez bien sûr venir avec l'objectif d'illustrer la puissance créative de votre spécialité en IA, armé de votre modèle préalablement entraîné pour l'occasion. 

Mais vous pouvez également venir avec l'intention d'expérimenter simplement avec des techniques ou bibliothèques qui vous étaient jusqu'alors inconnues. 

Vous pouvez venir en équipes constituées décidées à travailler ensemble. 

Mais vous pouvez également venir seul·e et trouver à qui parler sur place.

## Défis
- Défi **Haikuweather**: les membres du collège Cécilia venant de l'ouest de la France vous proposent de générer des petits textes poétiques, ou drôles, ou les deux, au sujet du temps qu'il fait.
- Défi **Together**: les membres du collège Cécilia venant du sud de la France vous proposent de générer des petits textes poétiques, ou drôles, ou les deux, mettant en valeur le rôle de l'humain dans la création.
- Défi **Guybrush Threepwood**: le GT IA et Jeux du GDR IA vous propose de générer des petits textes poétiques, ou drôles, ou les deux, dans le style d'un personnage célèbre de jeu vidéo.
- Défi **Code Source**: l'IRILL vous  propose de générer des petits textes poétiques, ou drôles, ou les deux avec un code source comme l'une des entrées du système.

## Quelques Inspirations
- Un système de génération de jeux de mots en utilisant des modèles de langage ainsi que la distance sémantique pour créer un effet humoristique: [Pun Generation with Surprise](https://github.com/hhexiy/pungen)
- Un système pour créer des titres humoristiques à partir de titres ne l'étant pas: [Humorous Headline Generation via Style Transfer (a.k.a. Humor Translation)](https://github.com/orionw/humorTranslate)
- Le générateur poétique de Tim Van de Cruys, présenté lors d'éditions précédentes de PFIA [Automatic Poetry Generation from Prosaic Text](https://github.com/timvdc/poetry)
- Comment générer des jeux de mots et faire rire avec du tabou, à partir d'un corpus de SMS. *No ML* [“Let Everything Turn Well in Your Wife”: Generation of Adult Humor Using Lexical Constraints](https://aclanthology.org/P13-2044/)
- [Les contraintes de l'Oulipo](https://www.oulipo.net/fr/contraintes)
- [La page de Darius Kazemi, artiste en génération procédurale](https://tinysubversions.com/)
- et, bien sûr, [la Machine à écrire de Jean Baudot (1964)](https://archive.org/details/xfoml0001/page/n13/mode/2up)


## Quelques outils que vous pouvez trouver utiles, en plus de vos outils habituels
- [Lexique 3](http://www.lexique.org/), et le projet openlexicon (Boris New et Christophe Pallier). Ce lexique très riche pour la langue française vous permettra par exemple d'obtenir la forme phonétique, la fréquence d'utilisation, et beaucoup d'autres informations morphologiques et linguistiques pour traiter les mots avec vos programmes.
- Les réseaux sémantiques peuvent vous aider à calculer la distance sémantique des mots: par exemple [ConceptNet](https://conceptnet.io/) qui utilise des [word embeddings](https://github.com/commonsense/conceptnet-numberbatch).
- nous échangerons des liens vers des corpus qu'on peut utiliser avec des gros modèles de langage pré-entrainés sur le groupe Discord lors de l'événement comme par exemple le corpus de calembours recueillis lors de [l'atelier JOKER à CLEF 2022](https://www.joker-project.com/clef-2022/EN/project.html).

## Autres Ressources
Mini-projets en Français, réalisés par des étudiantes et étudiants en quelques jours:
- [génération interactive poétique en Français avec GPT2](https://git.enib.fr/deloor/poesygeneration/-/tree/pytorch)
- [essayer de générer des jeux de mots en Français avec le modèle de langage Jurassic, et Fastttext](https://gitlab.com/loicgle/computational-humor-pun-generation)

## Crédits

### Organisation
- Florence Bannay
- Anne-Gwenn Bosser, Lab-STICC, ENIB
- Victor Charpennay, EMSE
- Liana Ermakova, HCTI, UBO
- Nicolas Pépin-Hermann
### Animation de l'événement
- Florence Bannay, IRIT
- Anne-Gwenn Bosser, Lab-STICC, ENIB
- Victor Charpennay, EMSE
- Pierre De Loor, Lab-STICC, ENIB (à distance)
- Aymeric Henard, Lab-STICC, UBO
- Florian Marchal-Bornert, LORIA, agoraa et Université de Lorraine
- Alessandro Valitutti (à distance)
### Tests des ressources et outils
- Rym Bousrih, ENIB
- Erwan Claquin, ENIB
- Sarah Clauzade--Robert, ENIB
- Kevin Cornut, UBO
- Pierre De Loor, Lab-STICC, ENIB
- Loic Glémarec, UBO
- Oumaima Oumaadi, ENIB
- Maxime Yonnet, ENIB


