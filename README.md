# 1. Description du projet
Ce projet a consisté a créer un eBook au format ePub de A à Z. En commençant ce projet, j'avais déjà quelques connaissances concernant le fonctionnement des feuilles de style CSS et du langage de balisage XML (qui est finalement très similaire au XHTML utilisé pour la création d'un livre au format ePub). J'avais également connaissance de l'existence du logiciel Sigil, qui nous avait été présenté pendant le cours. Pour réaliser ce projet, j'ai suivi les étapes suivantes : 
## 1.1	Visionnage d'un tutoriel sur YouTube expliquant de manière détaillée le processus de création d'un eBook avec Sigil
Le tutoriel en question est disponible à l'adresse suivante : (https://www.youtube.com/watch?v=-CpzHoTtZlQ)
Le visionnage (à deux reprise) et la prise de notes, la compréhension des différentes étapes, la consultation de documentation annexe et les premiers tests ont représenté environ deux jours de travail.  
## 1.2 Océrisation du document PDF et restauration d'une mise en page lisible
Le texte étant à l'origine un PDF, il a fallu procéder à une océrisation afin de pouvoir manipuler le texte et les images, une étape effectuée avec Adobe. La mise en page originelle (2 x 2 colonnes par page affichée) a eu pour conséquence un résultat très anarchique de l'océrisation, puisque le texte, les images et les notes de bas de pages ne suivaient plus du tout l'ordre original. Il a donc fallu réordonner le texte. Cette étape a également nécessité environ une journée de travail. Il a finalement été décider de ne pas conserver la mise en page originale, qui est certes très esthétique mais cause des difficultés de lecture. L'accessibilité et l'ergonomie ont de manière générale été des préoccupations constante lors de l'élaboration du eBook (descriptions alternatives des images, choix d'une police sans empâtements, contraste suffisant entre le texte et le fonds, aptabilité de la taille des images aux conditions d’affichage…)
## 1.3 Balisage du texte et ajout des images
Cette étape a pu être réalisée en partie grâce à l’usage d’expressions régulières. En plus du balisage, j’ai testé différents formats pour les images, notamment le SVG, avant d’adopter le format JPG. Temps de travail : 1 jour. 
## 1.4 Ajout des notes de bas de pages et des liens cliquables dans les bibliographies
Cette étape comprend une petite partie de recherche pour trouver la solution la plus adéquate pour les notes de bas de pages, étant donné que la notion de « page » n’est pas pertinente dans le cadre d’un eBook qui fonctionne par défilement. Comme quasiment toute cette partie a été faite manuellement, il a fallu compter également sur un jour de travail.
## 1.5 Réalisation de la feuille de style CSS, de la page de garde, de la couverture et de la table des matières
La réalisation en elle-même n’a pas pris beaucoup de temps, mais il a fallu que j’aille me rafraîchir la mémoire concernant le fonctionnement des feuilles de style. J’ai également ajouté les classes dans les pages XHTML. Également environ un jour de travail. 
## 1.6 Réalisation de tests d’affichages et corrections
Le eBook étant achevé, j’ai essayé de le lire sur différents écrans (tablette, smartphone et ordinateur). Il m’est ensuite apparu qu’il serait intéressant que le eBook soit lisible sur les liseuses Kindle, j’ai donc encore converti le eBook. Temps de travail : 1 jour
## 1.7 Conclusion
La réalisation totale de ce projet aura pris environ un semaine. Cela peut sembler beaucoup, mais je suis vraiment partie avec presque aucune connaisance sur la manière de réaliser un eBook et très peu de connaissances techniques. J'ai du chercher ce qui me semblait la meilleure manière de faire à chaque étape. Le processus décrit ci-dessus n'a évidemment pas été totalement linéaire. 

# 2. Lecture des fichiers 
Le dossier « XHTML_Images_CSS » contient tous les fichiers qui composent le e-pub.
Le dossier « ePub_mobi » contient l’eBook aux formats ePub et mobi. Ces fichiers sont lisibles à priori par n’importe que lecteur prenant en charge ce type de fichiers. J’utilise l’application Icecream Ebook Reader sur mon ordinateur et ReadEra sur mon smatphone (Android).
Le document pdf est le document qui a été océrisé.
