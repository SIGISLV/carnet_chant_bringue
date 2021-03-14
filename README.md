# Carnet chant bringue

## Historique
En tant que tahitien nous avons tous entendu parler de ce [carnet de chant] (https://tahitiansongs.fr/?page_id=19) 
Un peu frustré que les chansons ne s'enchainent pas naturellement, j'ai décidé de commencer ce modeste projet.
J'ai contacté l'auteur du projet mais je n'ai pas eu de réponse.

Je pars donc de zéro et je constitue un répertoire de chant dans un format spécifique.
Ce format est expliqué dans la [documentation](https://patacrep.readthedocs.io/fr/latest/song/latex.html#autres).
Je préconise d'écrire les chants en format Latex (.sg) car il offre plus de possibilités avec notamment la possibilité 
d'ajouter des tablatures via lilypond.

# Démarche

## Pour la création du carnet de chant

Il faut être à l'aise avec l'installation de bibliothèque python. Il faut installer dans un environnent virtuel la bibliothèque
patacrep.

Il faudra télécharger depuis github ce projet et se positionner dans le répertoire "/books" on lance alors la commande :

    songbook carnet_bringue.yaml
    
On obtiend alors un pdf qui peut être imprimé.

Toutefois, on peut changer l'ordre des chants en modifiant le fichier carnet_bringue.yaml dans la section "content".

## Ajouter un chant qui n'existe pas

Il certainement probable que vous ne trouver pas un chant dans le répertoire. Pour le rajouter dans votre carnet il faudra
d'abord le chercher dans le dossier "songs" de "datadir". Ce dossier est rangé par artiste, si vous ne trouvé pas l'artiste
il faudra rajouter un dossier au nom de l'artiste. Il faudra créer un fichier du type latex comme expliquer plus haut.

Si comme moi vous utiliser le site de tontonremy, je vous recommande de copier le chant puis avec [le site song formater](http://ukegeeks.com/tools/songformater)
vous pourrez le mettre en forme pour écrire dans le format latex. Il faudra insérer les parties dans les sections qui convient tel que refrain ("chorus") ou couplet ("verse").