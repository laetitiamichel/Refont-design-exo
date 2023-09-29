#**Refont web : développement** 🚀 
![cover](./cover.PNG)
>Cette interface web à l’apparence très propre et bien designée, présente des erreurs de structuration. Les entêtes du document ne sont pas renseignées.
Par simple analyse écrite, minimum une page. Détaillez les points forts et faibles de cette page structurée en  HTML (_div vs semantique_) et css. Dans le validator W3C il y a 9 erreurs à corriger. Du coté css il faut appliquer l'unité de mesure REM :  n'oublié pas de déclarer la racine. Argumentez les erreurs que le développeur commet dans son approche techniques. Il y a également des erreurs d'accessiblité: veuillez m'en décrire quelques uns et m'expliquer la raison. A la fin de votre analyse réalisez la refonte de la page

> *Pour travailler plus confortablement procédez à un clône de ce dépôt git*.
> A la fin de votre réalisation créez un dépôt git avec l'affichage de la page d'index sur le navigateur.
> Trasmettez moi le lien sur mon spread-sheet que je vous est partagé. 
> L'exercice sera  noté /20

![AUR license](https://img.shields.io/aur/license/c)

##LIEN du site: [https://github.com/laetitiamichel/Refont-design-exo]

#**HTML:**
Dans le HEAD, il manque :
    *les méta pour l'accessibilité des non-voyants
    *pour la compatibilité sur les différents supports
    *méta description pour le référencement naturel

    *<meta charset="UTF-8">
    *<meta http-equiv="X-UA-Compatible" content="ie=edge">
    *<meta name="viewport" content="width=device-width, initial-scale=1.0">
    *<meta name="description" content="web design and developpment">

###pour les link, il manque :
    *type="text/css" dans le link de la CSS
    *il n'y a pas de link FAVICON ni de manifest
    *link rel="manifest" href="favicon/site.webmanifest"

##Dans le Body:
    *il n'y a pas de HEADER ni de MAIN pour structurer le HTML:
