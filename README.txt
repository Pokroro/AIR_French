####### Patch français pour AIR #######
####### Rotome Traductions ####### 
####### V0.1 (Beta) - Build 27/05/2026 #######

##### Présentation #####

Ce patch propose une traduction complète et à la main de AIR de VisualArt's/Key (2000) en français. Plus précisément, ce patch est destiné à 'AIR Standard Edition' (PC, 2005, 18+).

Ce patch a beau être encore marqué comme "Beta", l'intégralité des textes du jeu, de même que l'intégralité des images contenant du texte en japonais, sont traduits. Les notes du traducteur s'affichent en cliquant sur le texte apparaissant dans une couleur différente du reste (ne fonctionne pas dans le log ; seul le texte "actuel" est cliquable).

##### Notes #####

- Si vous voyez de l'anglais dans le jeu, c'est que le texte était déjà en anglais dans le jeu original !
- Le menu "NAME" permettant de changer son nom est cassé. Vous êtes donc contraint de jouer en tant que ce bon vieux Yukito.
- Une poignée de chaînes de caractères apparaissant dans les menus contextuels sont encore en japonais. En effet, ceux-ci sont a priori impossible à remplacer à moins d'aller bidouiller jusqu'au moteur du jeu. "環境設定" signifie 'Préférences'.
- De même, vous remarquerez que dans ces menus contextuels, ainsi que dans les notes du traducteur, le texte n'est pas accentué pour des raisons similaires.

/!\
- Il est possible que les quelques caractères japonais restants vous apparaissent sous la forme de mojibake ("SAY`è" à la place de "環境設定", par exemple). 
- Actuellement, il est possible que certains caractères s'affiche curieusement, en particulier les points de suspension, en raison d'un problème d'encodage. 

Ces deux derniers points ne devraient poser aucun problème de gameplay, mais il est possible de les éviter en lançant le jeu avec un outil comme AppLocale/Locale Emulator ou en changeant les paramètres régionaux de votre ordinateur, voire simplement en changeant la police de caractères in-game.

/!\ /!\ /!\
- Notez qu'il arrive qu'une sauvegarde effectuée avec un jeu lancé avec des paramètres régionaux japonais soit illisible par le même jeu lancé avec des paramètres régionaux différents, et inversement. Par précaution, essayez de toujours lancer le jeu avec les mêmes paramètres régionaux.
- Il y a un fameux bug, sans doute lié aux outils de traduction, qui fait que le jeu plante si vous chargez une sauvegarde faite sur un choix depuis l'écran titre directement après avoir lancé le jeu. Pour le contourner, le plus simple est de lancer une "nouvelle partie" puis d'immédiatement charger votre sauvegarde depuis le menu "clic droit".

##### Installation #####

Il suffit de glisser-déposer l'ensemble des fichiers présents dans l'archive à la racine du dossier d'installation du jeu (là où se trouvent Gameexe.ini, RealLive.exe et Seen.txt), et d'accepter quand on vous demande d'écraser certains fichiers.

/!\ /!\ /!\
Si vous souhaitez pouvoir remettre votre jeu en japonais, faites une copie des fichiers concernés avant de les écraser.

##### Contenu du patch #####

1.2.9.5.map : Permet de bon fonctionnement de rlBabel.dll
Gameexe.ini : Fournit la traduction des chaînes de caractères présentes dans les menus contextuels
rlBabel.dll : Permet au jeu de supporter (entre autres) des caractères français (é, è, ç...)
README.txt : Ce que vous êtes en train de lire
Seen.TXT : Détermine quels textes, choix, animations, images... apparaissent à l'écran, et quand ils apparaissent
g00/ : Les images contenant du texte, traduites en français

##### Remerciements #####

Un énorme merci et une immense admiration à tous ceux qui ont contribué à cet outil merveilleux qu'est RLDev, et de même pour rlBabel sans lequel une traduction française n'aurait sans doute jamais pu voir le jour.

En outre, ce patch n'aurait probablement pas été possible sans les informations disponibles à https://forum.kazamatsuri.org/t/rldev-for-dummies/ qui m'ont aidé à prendre RLDev en main, et essentiellement convaincu de me lancer dans cette entreprise. Merci en particulier à tous ceux qui ont osé posé des questions dans ce fil et à ceux qui y ont répondu ; certaines réponses m'ont été d'un grand secours.

Enfin, merci à vous d'avoir téléchargé ce patch. En espérant que vous passerez un bon moment à (re)jouer à AIR en français !

##### Informations en vrac #####

- Le petit poème en anglais présent sur le menu principal peut être traduit de la manière suivante (notez que le poème original est écrit dans un anglais soit bancal, soit très, très littéraire, au choix...) :

"Les jours qui sont enveloppés dans la scène estivale et pour passer avec douceur
Une rencontre avec les filles répétée dans la lumière du soleil
L'été continue vers où de même
Elle attend dans l'air"

- Il est généralement conseillé de suivre les routes dans l'ordre Misuzu -> Kano -> Minagi, bien que ce ne soit pas indispensable

##### Futur du patch #####

- Pourquoi "Beta" si le jeu est intégralement traduit ?

Je compte encore relire le script traduit pour améliorer certaines tournures et corriger quelques fautes de frappe qui m'échappent sans doute encore. Je ne suis pas très doué en infographie, alors certaines images peuvent certainement être un rien plus jolies. Aussi, j'ai pour l'instant relativement peu vérifié le bon fonctionnement du patch in-game, au-delà de m'assurer que le jeu était globalement jouable.
Je vais peut-être aussi publier d'autres versions du patch :
- Si les problèmes d'affichage de certains caractères persistent, je publierai certainement une version "jeu de caractères réduit" qui remplace les caractères concernés
- Une version censurée ("all-ages"), bien que le jeu soit assez léger et "propre" au niveau du contenu pour adultes
- Une version "non-compilée" contenant les fichiers intermédiaires que sur lesquels j'ai travaillé, pour les curieux.

##### Contacts #####

Discord : pokroro_
Courriel : pokroro@gmail.com

N'hésitez pas à me contacter si vous avez des suggestions ou des critiques, si vous avez trouvé des erreurs, ou simplement pour discuter :-)
Vos retours sont les bienvenus.