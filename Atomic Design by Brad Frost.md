# Atomic Design by Brad Frost 



 

 

Atomic Design *by*  Brad Frost

 

 

### Analyse de cas

 

 

Master PUN – ENSSIB 

 

Piloter un projet d’édition numérique – Antoine Fauchié 

 

.18 / .19


 

 


 

a.      

# Introduction 

 

 

​      **2013.** 

Le point de départ de Brad Frost est un constat : la multiplication des appareils de lecture exige de repenser la conception web. Or, le web est un flux, et pourtant il reste structuré par la page. 

L’expérience du web est déterminée par les technologies que l’on utilise pour le concevoir. Et la notion de page est centrale dans cette expérience et conditionne ainsi notre expérience d’utilisateur. Si les technologies de lecture ont beaucoup évolué depuis l’invention du codex, le concept de page, lui, est resté fondamentale jusqu’à nos jours. Or, sur le web, il n’existe que des flux de données. La page est construite *a posteriori*, de manière artificielle, dans le but de structurer nos informations dans un format auquel nous sommes habitués. Elle est un repère utile, mais surtout confortable. Ainsi, le format de la page qui est fixe et uniforme ne convient plus au web devenu interactif, fluide et interdépendant. 

Il est donc temps de « déchirer la page » et de passer à une conception modulaire. On parle alors de ‘*Modular Design’*. Ce concept est ancien en informatique, mais il ne trouve son importance que depuis le développement des différents appareils, tailles d’écrans, d’affichage, environnements web… 

 

Brad Frost, auteur d’*Atomic Design*, est web designer et consacre toute son activité à concevoir des méthodes et des outils pour réaliser des systèmes de design résilients et adaptatifs. 

Son livre existe sous trois formats : 

·       Ebook :10 $ (formats ePub, mobi et PDF) ; 

·       Livre-web : gratuit ;

·       Livre papier : 20 $ (format de poche).

 

# I.                                           Une méthode de *responsive design* 

 

 

## a.      La méthode *Atomic Design*

 

Comment créer des objets web complexes tout en utilisant des systèmes modulaires ? Pour répondre à cette question, B. Frost s’appuie sur une analogie chimique : l’association des molécules entre elles, qui ensemble parviennent à former des corps complexes, dont les éléments les plus simples sont les atomes.

L’enjeu de la méthode est de développer une approche holistique, c’est-à-dire qui pense l’ensemble du projet comme un tout. Cette approche systémique du design d’interface permet d’éviter de morceler le site en pages fixes et offre un point de vue global à tout moment. Cela se fait en divisant le tout en un ensemble d’éléments distincts et hiérarchisé :

\1.     Les atomes

Ces éléments sont les plus simples. Ils servent de blocs solides, comme les fondations d’un bâtiment. Ils contiennent un code HTML. Chaque atome a un rôle précis comme de déterminer un titre de niveau 1.

 

\2.     Les molécules

Ce sont des groupes simples d’atomes qui fonctionnent en tant qu’unité. 

 

\3.     Les organismes

Ce sont des éléments plus complexes composés à la fois d’atomes et de molécules. 

 

\4.     Les templates

Ce niveau articule la mise en page des différents éléments. Il s’agit de la structure sous-jacente, le squelette de la mise en page. 

 

\5.     Les pages

Instances dans lesquelles on a appliqué les contenus réels, ce que verront les utilisateurs. 

 

En travaillant sur la structure sous-jacente et non pas directement sur le rendu final, on peut se concentrer sur la logique d’ensemble et garder à l’esprit la cohésion du tout. Ce système se met en place via un ‘*Pattern Lab’*, un site sur lequel seront déposés tous les éléments nécessaires à la construction du site. Ce système permet de faire des changements et mise à jour très rapidement en ciblant des éléments et permet à tous les membres du projet de travailler ensemble. Cette méthode consiste donc à décomposer le projet web en ses différents éléments, au lieu de chercher à concevoir une page web d’emblée, ce qui le rend entièrement modulable. 

​            

 

## b.      Responsive design 

 

​            Le *design responsive* renvoie à un ensemble d’outils et de méthodes visant à adapter une interface à son support. Plutôt que de multiplier les interfaces, il s’agit d’en créer une seule capable de s’adapter partout pour que l’expérience utilisateur soit toujours optimale et que soit préservée la qualité des contenus. Le mot d’ordre est : *« Get your content ready to go anywhere because it’s going to go everywhere. »*

 

### Atomic Design pour l’édition numérique ?

 

​            Le livre numérique est confronté aux mêmes problématiques que le web : la page n’existe plus et les dispositifs de lecture sont très nombreux. Un système modulaire est une solution pour s’assurer de la compatibilité de ses fichiers numériques partout. Le contenu doit pouvoir s’adapter aux différents écrans et paramètres utilisateurs sans perdre en qualité. Un environnement de développement modulaire facilite la résilience des fichiers.  Si quelque chose ne convient pas dans l’apparence final de la page, il est facile de modifier les éléments, puisque l’on peut les déconstruire partie par partie et ainsi cibler la résolution du problème. 


 

# II.                                     Un livre autoédité & ouvert 

 

**2015 – 2016.**

*« This book is a work in progress ».* 

La culture du web de l’auteur façonne sa manière d’envisager l’édition et le conduit à proposer un objet éditorial nouveau, qui correspond à son identité numérique : ouvert, libre et collaboratif. 

 

## a.      Les étapes du projet 

 

Dans son article *« Self publishing a book for fun and profit* [[1\]](#_ftn1) *»*, disponible sur son site, B. Frost relate son processus éditorial.

·       L’auteur exige que le livre soit publié en ligne et reste totalement accessible. L’éditeur contacté refusera cette exigence. B. Frost se tourne vers l’autoédition. 

·       La rédaction du livre se fera chapitre par chapitre et l’auteur communiquera à chaque nouvelle parution. Les chapitres seront publiés sans attendre que le livre ne soit achevé. Et chaque nouvelle avancée fera l’objet d’une communication via la newsletter.

·       Le 8 janvier 2015 : annonce de lancement du projet. 

·       En janvier 2016, B. Frost commence une collaboration avec un éditeur indépendant : Owen Gregory. Il propose ses modifications sur GitHub. 

·       En septembre 2016, il commence à travailler avec Rachel Andrew pour la version ebook, et avec Rachel Arnold Sager pour la version print.

·       En novembre 2016, le bon pour impression est envoyé à l’imprimeur pour 1 000 livres. 

 

## b.      Les choix éditoriaux 

 

### L’autoédition

 

Le premier choix éditorial qu’il effectue est celui de l’autoédition. S’agissant de son premier livre, il était risqué de prendre cette décision. Cependant, il bénéficiait déjà d’une certaine audience en ligne, due à la tenue d’un blog pendant une dizaine d’année, mais aussi à ses divers projets et conférences. L’autoédition reste donc tout de même un choix risqué pour d’autres auteurs qui ne bénéficieraient pas de cette visibilité de départ. 

Ce choix est également motivé par une certaine méfiance vis-à-vis des éditeurs. Le système éditorial se révèle être empreint d’un certain nombre de contraintes pour les auteurs, que ce soit en termes d’outils à utiliser, de liberté dans le contenu et la forme du texte, ou encore sur le plan de la répartition non équitable des revenus. 

 

### Le processus d’écriture 

 

​            Le processus d’écriture est ouvert dès le départ. B. Frost fait le choix d’un environnement nativement numérique et utilise les technologies web pour rédiger son livre. En voici les étapes :

·       Le contenu textuel est d’abord écrit localement en Markdown ;

·       Les changements sont ensuite envoyés dans un répertoire en ligne via la plate-forme Github ;

·       Ces changements sont automatiquement affichés sur le site web du livre ;

·       Les gens sont alertés lorsque des changements majeurs sont produits ;

·       Le texte en cours d’écriture est ainsi lisible par tous dans sa totalité ;

·       La possibilité est donnée de pouvoir précommander l’ebook pour 10$.

 

### Les outils du workflow éditorial

 

​            Dans une volonté de garder un processus ouvert et libre, le choix des outils à utiliser est déterminant. Voici les technologies utilisées dans le workflow :

·       **L’éditeur de texte utilisé est IA Writer,** une application simple qui formate le texte en Markdown ; 

·       **Le site est généré par Jekyll**, un générateur de site statique basé dans un environnement Ruby ;

·       **Les dossiers du livre sont déposés dans un répertoire GitHub.** GitHub permet d’effectuer des changements et se trouve donc très utile pour le travail éditorial. Couplé à Jekyll, il permet d’héberger les pages de son propre site. Ces deux outils sont donc appropriés pour un workflow éditorial pour le web ;

·       **DeployBot est une technologie utilisée pour automatiser les alertes** lorsque des changements importants sont enregistrés dans le dépôt Git ;

·       **MailChimp est l’outil de newsletter** utilisé pour envoyer la progression en cours. 

 

### Versions ebook & print 

​            

​            Pour l’ebook, B. Frost travaille avec la web designer Rachel Andrew qui va gérer les format ePub, Mobi pour Kindle et Pdf. Pour la version print, c’est Rachel Arnold Sager qui s’occupe des choix des illustrations et du bookdesign. Le choix de la typographie n’a pas été d’un grand enjeu puisqu’il dit a propos de cela : *« I chose the typeface for the book I think by Googling "Good Google Font pairings" or something* [**\*[2\]***](#_ftn2) *».* Enfin, les choix de l’imprimeur, ainsi que du papier et des matériaux pour la couverture et les pages intérieures se sont fait sur les conseils de la designer R. A. Sager. 

 

### L’ebook : design & ergonomie 

 

​            Les choix de design pour l’ebook restent simples et en tout point similaire à la version web. Brad Frost reprendre son identité graphique déjà développée pour ses projets web. Les liens hypertextes sont également les mêmes. Quant au contenu, l’ebook n’en offre pas davantage par rapport à la version web. Cela laisse penser que l’achat de l’ebook sert surtout à rémunérer l’auteur pour son travail plutôt qu’à accéder à un nouveau contenu. L’auteur respecte ici son souhait d’offrir à tout le monde son travail de manière gratuite. Mais on peut regretter que ne soient pas intégrés dans l’ebook plus de contenus multimédias, ou de tutoriels. 

 

## c.       Aspects commerciaux 

 

### Vente 

Le système commercial du livre, et la communication autour ont de gros atouts et se montrent très efficaces. Dès le début, il met en place un système de précommande. Précommander le livre signifiait payer pour un contenu non définitif et incomplet. En compensation, B. Frost proposait d’autres avantages et contenus en dehors du livre, comme une réduction sur le livre imprimé, ou des tutoriaux. 

Ce système est plutôt performant, puisqu’une semaine après l’annonce de lancement du projet, il comptabilisait déjà une commande de 4 000 ebooks. On remarque ici une différence majeure avec un processus éditorial traditionnel, pendant lequel l’auteur rédige son livre, sans avoir aucune idée des retours qu’il pourra en avoir. Au contraire, B. Frost vend son livre, avant même de l’avoir écrit.  

 

### Distribution 

 

Pour la distribution, il utilise deux grandes applications : Shopify et Sendowl. Shopify est un service en ligne qui offre à ses utilisateurs la possibilité de créer sa propre boutique d’e-commerce. Shopify propose également des solutions d’expédition dont B. Frost s’est également servi pour l’envoi de ses livres. En ce qui concerne Sendowl, il s’agit d’une plateforme permettant la vente de contenu numérique. Cela est donc particulièrement bien adapté pour la vente de l’ebook. 


 

# Des mises en question 

Analyse critique du projet éditorial

​            

Sur le plan éditorial, le modèle de B. Frost apparait innovant et original puisqu’il n’épouse pas le chemin de l’édition traditionnelle, encadré par une maison d’édition dont l’existence seule suffit, aux yeux des lecteurs, à asseoir une légitimité. Néanmoins, une fois resitué dans le contexte de la culture web, des modes d’écriture et de partage qui s’y jouent et des types de lectorat qui y sont présents, ce modèle apparaît plus évident. Il s’inscrit en effet dans un environnement qui le rend possible et opérationnel. Et Brad Frost tire profit des outils web à sa disposition, et se les approprie pour concevoir son projet éditorial. Déjà en 2013, donc, l’édition se refaçonne et se réinvente à partir des technologies du web et de sa culture, c’est-à-dire de ses manières spécifiques de concevoir, de produire et de diffuser des contenus.

 

## a. Abandon de l’auctorialité ? 

 

​            En rendant son processus d’écriture accessible et ouvert à tous, B. Frost déstabilise les limites auparavant bien tracées entre l’auteur et ses lecteurs. Puisque le projet est désormais collaboratif, le texte s’écrit et s’élabore à plusieurs. L’œuvre peut être dite collective, même si l’horizontalité entre Brad Frost et les autres n’est pas totale. 

 

​            La figure de l’auteur est longue à s’instituer[[3\]](#_ftn3) et il faut attendre le 18ème siècle et l’apparition des droits d’auteur pour que se forme un cadre juridique et social correspondant à la figure auctoriale. Dans la culture imprimée, le nom de l’auteur apparait sur la page de couverture, et ainsi existe une paternité officielle et reconnue de l’auteur vis-à-vis de son texte. On se représente alors très clairement l’auteur comme instance individuelle à l’origine du texte. 

 

L’environnement numérique vient bouleverser cette assignation bien délimitée entre l’auteur et son texte, mais aussi entre l’auteur et ses lecteurs. La manière de lire *Atomic Design* pour le lecteur abonné à la newsletter est totalement différente puisque celui-ci est incité à participer au processus de rédaction, et peut commenter immédiatement sa lecture auprès d’une communauté dont l’auteur fait partie. Que ce soit via le blog ou via la plateforme GitHub, le lecteur se fait auteur par sa participation et ses réactions lisibles, voulues et prises en compte par l’auteur. Une autorité significative est attribuée aux lecteurs, qui se font par là co-auteurs. 

Les fonctions auctoriales ne sont pas toutes assumées par la même personne, comme c’est le cas dans le modèle imprimé. B. Frost se tient comme la personne juridique responsable du livre. Il en détient la responsabilité morale. Cependant, en termes d’écriture, la possibilité de participation laissée aux lecteurs mène à reconsidérer la paternité textuelle de l’ouvrage. *Atomic Design* est écrit par Brad Frost, mais réécrit, en partie au moins, par ses lecteurs. Par ces aspects collaboratifs et collectifs, une continuité s’instaure entre l’auteur et les lecteurs, par un dialogue constant entre tous. Tout cela fait du texte un objet mouvant[[4\]](#_ftn4), sur lequel chacun peut intervenir en proposant des modifications, des avis, des commentaires. C’est donc l’individualisation de la posture de l’écrivain qui est ici remise en question. 

 

## b. Autoédition ou co-édition ? 

 

​            Si Brad Frost fait le choix de l’autoédition, il ne travaille pourtant pas seul, et d’autres personnes que lui prennent en charge des fonctions éditoriales. 

Si l’autoédition signifie, pour l’auteur, de s’affranchir d’une maison d’édition, cela n’implique pas de réaliser tout le processus seul. L’auteur délègue des fonctions éditoriales. Cependant, il ne bénéficiera pas de la visibilité d’une maison d’édition pour communiquer sur son livre, ni de l’inscription de son œuvre dans une collection d’ouvrages. Autoédition signifie que l’auteur prend lui-même en charge le processus d’édition, qu’il s’agisse de faire certaines choses par lui-même ou de trouver des personnes ou des organismes capables de faire certaines choses pour lui. 

​            

### Une nouvelle forme de légitimité éditoriale 

 

​            La légitimation d’un contenu est une des fonctions éditoriales principales.[[5\]](#_ftn5) L’éditeur possède un pouvoir symbolique garantissant la qualité du contenu qu’il choisit de publier. Ce pouvoir varie selon l’instance éditoriale. Mais de manière générale, le lecteur reconnait cette autorité qui en émane, et s’appuie dessus pour accorder, ou non, sa confiance quant à la valeur du texte qu’il va lire.

​            

L’autoédition peut être vue comme une forme d’amateurisme.  Avec l’essor des moyens de publication en ligne comme les blogs et l’accessibilité des moyens d’édition numérique, l’autoédition s’est beaucoup développée dans l’environnement digital. Dès lors que publier un livre est à la portée de tous, la question de la légitimité se pose en de nouveaux termes : une publication numérique suffit-elle à se faire auteur ? Comment juger de la qualité des textes et de leur fiabilité s’ils ne sont pas passés par l’intermédiaire de l’autorité et de l’expertise d’une maison d’édition ? 

Le travail éditorial permet de garantir l’authenticité d’un texte, de se prémunir contre le plagiat, de préserver une certaine moralité (de ne pas diffuser de texte à caractère explicitement raciste par exemple) sans contrevenir à la liberté d’expression ; de manière plus générale, la maison d’édition veille à la lisibilité des textes et permet de les inscrire dans un certain contexte (collection d’ouvrage, maison d’édition spécialisée …). Dans le cas de l’autoédition, tout cela disparait. 

​            

En revanche, l’avantage de l’autoédition est précisément d’outrepasser ces formes de contrôle qu’exerce une maison d’édition. C’est d’ailleurs la première raison qu’évoque Brad Frost lorsqu’il explique le choix éditorial qu’il fait. Mais cela ne signifie pour autant pas qu’il ne dispose d’aucune légitimité à publier un livre. **Au contraire, Atomic Design est un exemple d’une nouvelle forme de légitimité éditoriale à l’œuvre.** 

Dans le cas de l’autoédition, nombreux sont ceux à déposer leur fichier numérique sur des plateformes de diffusion et de vente comme Amazon. Les fichiers sont alors soumis aux logiques de recommandation algorithmique. Brad Frost ne fait pas ce choix, et reste indépendant en proposant son livre avec des outils libres, affranchi de la publicité. Sa légitimité n’est pas d’ordre algorithmique, c’est-à-dire que le succès de son livre n’est pas dû à cette logique de recommandation, comme cela est le cas pour de nombreux livres autoédités.[[6\]](#_ftn6) 

La légitimité de l’ouvrage de Brad Frost a plusieurs caractéristiques. Elle vient tout d’abord de la profession même de l’auteur : web designer, il écrit sur ce qu’il connaît. Ensuite, son identité numérique est très marquée : il a écrit de nombreux articles en ligne et participe à la création de ressources pour web designer[[7\]](#_ftn7). 

Ensuite et surtout, en choisissant un processus de publication ouvert, Brad Frost donne la possibilité à d’autres professionnels du domaine de réagir à ce qu’il écrit. Ces derniers exercent ainsi une forme de contrôle sur ce qui est écrit, ce qui empêche l’auteur de dire n’importe quoi. De même, les nombreux relecteurs du texte garantissent une certaine qualité au texte. On peut même se demander si ce processus n’assure pas une plus grande légitimité au texte que ceux d’une maison d’édition dans la mesure où, ici, ce n’est pas seulement un éditeur ou une poignée de personnes qui relisent le texte, mais un grand nombre d’experts qui s’intéressent au même domaine que Brad Frost. Ainsi, si les lecteurs possèdent, par les aspects collectifs de l’écriture, des fonctions auctoriales, ils possèdent également des fonctions éditoriales fondamentales en contribuant à la légitimité du livre. Cette légitimité est due à cette organisation particulière. Elle n’est donc pas présente pour tous projets d’autoédition.

 

# Conclusion 

 

*Atomic Design* est un projet éditorial qui montre que l’écriture peut être un véritable espace collectif. Même si dans l’imprimé, il est possible de co-écrire un ouvrage, ou de compiler des textes de divers auteurs au sein d’un même livre, l’aspect collectif n’atteint pas le niveau permis par les technologies numériques.  

Loin d’être disqualifié par l’autoédition, ce livre jouit d’une nouvelle forme de légitimité permise par les outils numériques collaboratifs qui exercent un contrôle d’objectivité sur le texte et veille à sa qualité. 

On pourrait dire de ce livre qu’il est un ‘livre des communs[[8\]](#_ftn8)’. Tout d’abord au sens où B. Frost ne cache pas sa volonté de mise en commun du savoir. Ensuite parce que pour réaliser son projet, il met en place un mode d’organisation sociale collectif et autogéré. Or, les communs ne sont pas seulement une manière de rendre accessible des savoirs grâce au numérique, mais impliquent aussi une communauté qui s’organise autour de ces ressources, interagissent et les gouvernent ensemble. C’est parce que Brad Frost conçoit internet comme un commun en lui-même qu’il peut proposer un modèle éditorial qui y correspond, et par là promouvoir l’importance du numérique dans le partage de la connaissance.

 

 

------

[[1\]](#_ftnref1) http://bradfrost.com/blog/post/self-publishing-a-book-for-fun-and-profit/

[[2\]](#_ftnref2) Cette citation est extraite d’un échange de mail avec Brad Frost pour les besoins de ce travail. 

[[3\]](#_ftnref3) Neeman Elsa, « Culture numérique et auctorialité : réflexions sur un bouleversement », *A contrario*, 2012/1 (n° 17), p. 3-36. URL : https://www.cairn.info/revue-a-contrario-2012-1.htm-page-3.htm

[[4\]](#_ftnref4) On lit d’ailleurs sur la page d’accueil du livre-web : « *This book is a work in progress.* »

[[5\]](#_ftnref5) Sur la fonction de légitimation, voir Epron, Benoît, et Marcello Vitali-Rosati. *L’édition à l’ère numérique.* La Découverte, 2018

[[6\]](#_ftnref6) Voir Epron, Benoît, et Marcello Vitali-Rosati. *L’édition à l’ère numérique.* La Découverte, 2018, p. 59.

[[7\]](#_ftnref7) Notamment : <https://patternlab.io/> ; <http://styleguides.io/> ; <http://bradfrost.github.io/this-is-responsive/> 

[[8\]](#_ftnref8) Pour une définition de la notion de commun de la connaissance dans l’environnement numérique, voir : **Hervé LE** CROSNIER, « Une introduction aux communs de la connaissance », *tic&société*, Vol. 12, N° 1 | -1, 13-41.