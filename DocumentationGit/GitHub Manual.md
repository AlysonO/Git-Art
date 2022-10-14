- Creation compte
    1-

         Allez sur https://github.com/join dans votre navigateur. Vous pouvez utiliser n’importe quel navigateur sur votre ordinateur, téléphone ou tablette pour vous inscrire.

         Certains bloqueurs de publicité, comme uBlock Origin, peuvent empêcher le puzzle de vérification CAPTCHA de s’afficher. Pour éviter tout problème, désactivez le bloqueur de publicités de votre navigateur lors de votre inscription.

    2-
         Saisissez vos informations personnelles. En plus de créer un nom d’utilisateur et de taper votre adresse email, il vous faudra créer un mot de passe. Il doit être composé d’au moins 15 caractères ou avoir au moins 8 caractères, dont un chiffre et une lettre minuscule.

    3-
        Cliquez sur le bouton vert "Créer un compte". Il se trouve sous le formulaire.

    4-
         Faites le puzzle CAPTCHA. Les instructions peuvent varier, mais il vous suffit de suivre les directives qui s’affichent pour confirmer que vous êtes bien humain.
    
    5- 
         liquez sur le bouton Choisir pour sélectionner votre plan. Une fois que vous avez fait votre choix, GitHub va vous envoyer un email de confirmation sur l’adresse email que vous aviez saisie. Les quatre options de plans proposées sont listées ci-dessous .

        Free : repositories publics et privés illimités, maximum de 3 collaborateurs, suivi des problèmes techniques et bugs et outils de gestion de projet.
        Pro : accès illimité à tous les repositories, nombre illimité de collaborateurs, suivi des problèmes techniques et bugs et outils et perspectives avancés.
        Team : tout ce qui est inclus dans les offres précédentes, plus des contrôles d’accès de l’équipe et la gestion des utilisateurs.
        Enterprise : tout ce qui est inclus dans l’offre Team, plus l’autohébergement ou dans le cloud, un support prioritaire, une authentification unique SAML et bien plus encore.

    6- 
         Cliquez sur Vérifier mon adresse email. Ce bouton se trouve dans l’email envoyé par GitHub, va vous permettre de confirmer votre adresse email et vous redirigera vers le processus de création de comptes.
    
    7-
         Vérifiez le plan que vous avez sélectionné et cliquez sur Continuer. Vous pouvez également choisir de recevoir ou non des mises à jour de GitHub par email en cochant ou décochant la boite Envoyez-moi des mises à jour.

         Si vous avez sélectionné un plan payant, vous devrez saisir vos détails de paiement quand cela vous est demandé afin de pouvoir continuerSi vous avez sélectionné un plan payant, vous devrez saisir vos détails de paiement quand cela vous est demandé afin de pouvoir continueVérifiez le plan que vous avez sélectionné et cliquez sur Continuer. Vous pouvez également choisir de recevoir ou non des mises à jour de GitHub par email en cochant ou décochant la boite Envoyez-moi des mises à jour.

    8- 
         Choisissez vos préférences et cliquez sur Soumettre. Un court questionnaire s’affiche pour vous aider à adapter votre expérience à ce que vous recherchez. Une fois que vous y avez répondu, vous serez conduit vers une page qui vous permettra de créer votre premier repository.

         Si vous voulez passer à un plan supérieur plus tard, cliquez sur le menu en haut à droite, choisissez Paramètres et cliquez sur Facturation pour voir les options proposées.

      
        -Pour aller sur votre tableau de bord GitHub, cliquez sur l’icône du chat en haut à gauche de la page.
        -Pour personnaliser votre profil, cliquez sur le menu en haut à droite de la page et sélectionnez Votre profil.
    

- Creation depot - projet - repository
    
    1-
         
         Vous pouvez principalement démarrer un dépôt Git de deux manières.
             1- Vous pouvez prendre un répertoire existant et le transformer en dépot Git.

             2- Vous pouvez cloner un dépôt Git existant sur un autre serveur.
        
         Si vous commencez à suivre dans Git un projet existant qui n’est pas suivi en gestion de version, vous n’avez qu’à vous positionner dans le répertoire du projet. Si vous ne l’avez jamais fait, cela se présente de différentes manières selon votre système d’exploitation :

            pour Linux:
                        $ cd /home/user/my_project
            pour macOS:
                        $ cd /Users/user/my_project
            pour Windows:
                        $ cd C:/Users/user/my_project
            et entrez :
                        $ git init

- Ajout membre

    Pour donner accès à des collaborateurs à votre dépot github, procédez comme suit:

     -Demandez le nom d'utilisateur de la personne que vous invitez en tant que collaborateur. Si elle n'a pas encore de nom d'utilisateur, elle doit -s'inscrire sur GitHub.
     -Sur GitHub, accédez à la page principale du dépot.
     -Sous le nom de votre projet, cliquez sur Paramètres.
     -Dans la barre latérale de gauche, cliquez sur Collaborateurs.
     -Sous Collaborateurs, commencez à taper le nom d'utilisateur du collaborateur.
     -Sélectionnez le nom d'utilisateur du collaborateur dans le menu déroulant.
     -Cliquez sur Ajouter un collaborateur.
     -L'utilisateur recevra un e-mail l'invitant au repository. Une fois qu'il aura accepté votre invitation, il aura un accès collaborateur à votre dépôt.

- Clone
     La commande git-clone est utilisée pour cloner un repository git distant dans un répertoire local. Par défaut, la commande recrée le répertoire contenant le dossier .git et y télécharge le contenu du repository. 

      git clone git@github.com:monDossier

     #Le contenu sera directement téléchargé dans le répertoire repertoire

        git clone git@github.com:monDossier repertoire

     #Le contenu sera téléchargé dans le dossier où vous vous situez

        git clone git@github.com:monDossier .

- Push

     La commande git push est utilisée pour charger le contenu d'un dépôt local vers un dépôt distant. Le push vous permet de transférer les commits de votre dépôt local vers un dépôt distant. Le push est susceptible d'écraser les changements. Vous devez donc prendre des précautions lorsque vous l'exécutez. 
           git push <remote> <branch>

- Pull request

     Désormais nous allons voir comment récupérer un projet qui se trouve sur GitHub qui nous permettra de travailler très facilement sur notre projet depuis n’importe quel ordinateur on se connecte et on récupérer notre projet ont fais des modifications et puis on met notre projet GitHub à jour grâce à la commande:
            git pull [<options>] [<dépôt> [<spécification-de-référence>…​]]


