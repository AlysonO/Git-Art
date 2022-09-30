
Git pour Les Nuls

Résumé

Explication

git clone

git add

commit
Explication:
    Commande qui permet d'enregistrer les modifications dans le dépôt.
    La commande git commit capture un instantané des changements actuellement stagés du projet. Les instantanés commités peuvent être considérés comme des versions « sûres » d'un projet.
    Les commits constituent les piliers d'une chronologie de projet Git. Ils sont créés grâce à la commande git commit pour capturer l'état d'un projet à un point dans le temps.

    Il ne vous oblige pas à interagir avec le dépôt centralisé tant que vous n'êtes pas prêt. À l'instar de la zone de staging exemple: git commit -m 
    "Modification du titre"
    qui agit comme un tampon entre le dépôt de travail et l'historique de projet, le dépôt local de chaque développeur constitue un tampon entre ses contributions et le dépôt centralisé.

EXEMPLES:

     git commit -a
     Commitez un instantané de tous les changements apportés au répertoire de travail.

     git commit -m "commit message" 
     Une commande de raccourci qui crée immédiatement un commit avec un message de commit transmis.

     git commit -am "commit message"
     Cette combinaison crée immédiatement un commit de tous les changements stagés et insère un message de commit contextuel.


push

pull
