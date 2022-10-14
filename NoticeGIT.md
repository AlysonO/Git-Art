Git pour Les Nuls

Résumé: Git est un système de controle de version. En d'autres termes, il aide à gérer, contrôler et sauvegarder un projet et son déroulement.

Commandes de bases :

**git clone**:
EXPLICATION:
la commande <code> git clone 'url'</code> permet de 'prendre' un document sur github et le mettre sur sa machine à soi.

**git add**:
EXPLICATION:

Cette commande met à jour l’index en utilisant le contenu actuel trouvé dans l’arbre de travail.
git add est une commande importante car sans elle, il est impossible de commit.

EXEMPLES
     Ajouter le contenu de tous les fichiers *.txt sous le répertoire Documentation et ses sous-répertoires :

     $ git add Documentation/\*.txt
     Remarquez que l’astérisque * est échappé du shell dans cet exemple ; cela permet d’inclure les fichiers dans les sous-répertoires du répertoire Documentation/.

**commit**:
EXPLICATION:
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

**push**:
EXPLICATION:
Commande permettant d'envoyer les modifications réalisées sur les documents du dossier sur Github.

EXEMPLES:

    Vous venez de modifier des fichiers du dossier sur votre ordinateur.
    git push
    Les modifications que vous avez réalisées sont maintenant aussi sauvegardées sur Github.

**pull**:
EXPLICATION:
Commande permettant de mettre à jour les fichiers locaux avec les versions de Github.

EXEMPLES:
Votre collègue a mis à jour les documents sur Github, mais vous n'avez pas ces modifications sur les fichiers de votre ordinateur.
<code>git pull</code>
Les documents sur votre ordinateur sont maintenant identiques à ceux sur Github. Vous avez maintenant les modifications que votre collègue a réalisées de son côté.

**pull --rebase**:
EXPLICATION:
Le git rebase déplace les commits de l'une des branches au-dessus de l'autre.

**status**:
EXPLICATION:
Commande permettant de voir l'état de sauvegarde git des documents. Lorsque vous modifiez un document il y a plusieurs étapes avant qu'il ne soit pris en compte par Git.
Il doit d'abord être sauvegardé, puis les modifications doivent être ajoutées à la "staging area" et enfin être "committed". Cette commande permet de voir l'état des différents fichiers.


**branch**:
EXPLICATION:
La git branchcommande vous permet de créer, répertorier, renommer et supprimer des branches. Il ne vous permet pas de basculer entre les branches ou de reconstituer un historique fourchu.


EXEMPLES:
![image](https://user-images.githubusercontent.com/114221175/195804906-77cca2b2-f907-4a1a-b133-8d6abb8983c4.png)
Le diagramme ci-dessus visualise un référentiel avec deux lignes de développement isolées, une pour une petite fonctionnalité et une pour une fonctionnalité plus longue. En les développant en branches, il est non seulement possible de travailler sur les deux en parallèle, mais cela permet également de garder la  main branche exempte de code douteux.

