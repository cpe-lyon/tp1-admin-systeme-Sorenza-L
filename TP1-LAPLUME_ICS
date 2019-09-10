***``Sorenza Laplume``***

# Compte rendu TP1


```Exercice 2```

## Manuel
1. A l’aide du manuel, identifiez le rôle de la commande which

La commande Which à pour rôle de localiser une commande.

Which renvoie le chemin des fichiers (ou liens) qui seraient exécutés dans l'environnement
courant si ses arguments avaient été donnés comme commandes dans un interpréteur de commandes strictement conforme à POSIX. Pour ce faire, which cherche dans la variable PATH les fichiers exécutables corrrespondant aux noms des arguments. Which ne normalise pas les chemins.

2. Quand on consulte cette page, comment peut-on rechercher, par exemple, le mot option ?

Quand on consulte cette page, l'on peut rechercher le mot option en faisant la commande ***/options***

3. Comment quitte-t-on le manuel ?

L'on quitte le manuel en appuyant sur la touche ***"q"***.

4. Chaque section du manuel a une première page, qui présente le contenu de la section. Afficher la
première page de la section 6 ; de quoi parle cette section ?

Cette section parle des jeux et des petits programmes fun.

## Navigation dans l’arborescence des fichiers

1. allez dans le dossier /var/log

Pour aller dans le dossier /var/log il faut utiliser la commande : ***cd /var/log***.

2. remontez dans le dossier parent (/var) en utilisant un chemin relatif

Pourn remonter dans le dossier /var on utilise la commande: ***cd ..***.

3. retournez dans le dossier personnel

Pour retourner dans le dossier personnel il suffit de faire la commande : *cd* .

4. revenez au dossier précédent (/var)

Pour revenir au dossier précédent on utilise la commande : ***cd -***.

5. essayez d’accéder au dossier /root ; que se passe-t-il ?

Nous ne pouvons pas y accéder car nous n'avons pas la permission en tant que simple utilisateur.

6. essayez la commande sudo cd /root ; que se passe-t-il ? Expliquez

Cette commande n'est pas trouver car sudo attend un nom de programme hors cd est une commande intégré au système.

7. à partir de votre dossier personnel, créez l’arborescence :

Pour créer un dossier l'on utilise ***mkdir + nom du dossier***
Pour créer un répertoire entier on utilise la commande ***mkdir -p*** et pour créer un fichier on utilise la commande ***touch + nom du fichier***.

8. revenez dans votre dossier personnel ; à l’aide de la commande rm, essayez de supprimer Fichier1, puis
Dossier1 ; que se passe-t-il ?

Le Fichier1 étant dans le Dossier1 et non à la racine du répertoire je ne peux pas le supprimer.

On ne peut pas supprimer le Dossier1 car il n'est pas un fichier.

9. quelle commande permet de supprimer un dossier ?

La commande qui permet de supprimer un dossier est ***rmdir***.

10. que se passe-t-il quand on applique cette commande à Dossier2 ?

Il ne supprime pas le Dossier2 car celui-ci n'est pas vide.

11. comment supprimer en une seule commande Dossier2 et son contenu ?

On peut supprimer en une seule commande Dossier2 et son contenu en utilisant ***rm -rf + nom du dossier***

## Commandes importantes

1. Quelle commande permet d’afficher l’heure ? A quoi sert la commande time ?

La commande time permet de mesurer le temps d'exécution d'une commande. Elle fournit les temps réels(temps total), utilisateurs (durée nécessaire au processeur pour exécuter les ordres du programme) et systèmes (durée nécessaire au processeur pour traiter les ordres du système d'exploitation)

2. Dans votre dossier personnel, tapez successivement les commandes ls puis la ; que peut-on en déduire
sur les fichiers commençant par un point ?

Nous pouvons déduire que les fichiers commençant par un point sont des fichiers cachés.

3. Où se situe le programme ls ?

Le programme ***ls*** se situe dans les alias qui sont dans le ficher .bashrc.

4. Que fait la commande ll ? (indice : la commande alias peut vous aider)

La commande **ll** liste tous les dossier et fichier du répertoire dans lequel l'on se trouve. En effet cet alias est un raccourci de la commande ls -alF.

5. Quelle commande permet d’afficher les fichiers contenus dans le dossier /bin ?

Il faut dans un premier temps se mettre dans le dossier /bin en effectuant depuis le répertoire personnel ***cd /bin*** puis faire un ***ll***

6. Que fait la commande ls .. ?

La commande ***ls*** liste les dossier en ordre alphabétique en y appliquant une coloration syntaxique.

7. Quelle commande donne le chemin complet du dossier courant ?

La commande qui donne le chemin complet du dossier courant est : ***cd /home/nom_de_lamachine***.

8. Que fait la commande echo 'yo' > plop exécutée 2 fois ?

La commande ***echo 'yo' > plop*** exécutée 2 fois crée un fichier plop et inscrit le terme 'yo' dedans.

9. Que fait la commande echo 'yo' >> plop exécutée 2 fois ?

La commande ***echo 'yo' >> plop*** exécutée 2 fois ajoute une ligne au ficher plop contenant déjà le terme 'yo' et réécrit 'yo'.

10. A quoi sert la commande file ? Essayez la sur des fichiers de types différents.

La commande file nous donne le type du terme qui le suit.
> Exemple :
> File plop renvoie plop : ASCII text
> file Dossier1 renvoie : Dossier1 : directory


11. Créez un fichier toto qui contient la chaîne Hello Toto ! ; créer ensuite un lien titi vers ce fichier
avec la commande ln toto titi. Modifiez à présent le contenu de toto et affichez le contenu de titi :
qu’observe-t-on ? Supprimez le fichier toto ; quelle conséquence cela a-t-il sur titi ?

Supprimer le fichier toto rend le lien titi inutilisable.

12. Créez à présent un lien symbolique tutu sur titi avec la commande ln -s titi tutu. Modifiez le
contenu de titi ; quelle conséquence pour tutu ? Et inversement ? Supprimez le fichier titi ; quelle
conséquence cela a-t-il sur tutu ?

Lorsque que l'on écrit dans un des fichiers, l'autre contient la même chose.
Lorsque l'on supprime le fichier titi, le fichier tutu n'existe plus.

13. Affichez à l’écran le fichier /var/log/syslog. Quels raccourcis clavier permettent d’interrompre et
reprendre le défilement à l’écran ?

L'on peut interrompre le défilement à l'écran avec la commande ***:q***. Pour le reprendre il suffit de rappeler la commande avec la flèche du haut de notre clavier.

14. Affichez les 5 premières lignes du fichier /var/log/syslog, puis les 15 dernières, puis seulement les
lignes 10 à 20.

La commande ***head -5 syslog*** affiche les 5 première ligne du fichier /var/log/syslog.
La commande ***tail -15 syslog*** affiche les 15 dernières ligne du fichier var/log/syslog.
La commande ***head -10 syslog | tail -n20*** affiche seulement les ligne de 10 à 20.


15. Que fait la commande dmesg | less ?

La commande dmesg affiche la mémoire tampon de message du noyau et la commande less ne charge pas le fichier dans son intégralité. Donc ces 2 commande combiné affiche la mémoire tampon de message du noyau mais pas dans son intégralité.


16. Affichez à l’écran le fichier /etc/passwd ; que contient-il ? Quelle commande permet d’afficher la page de manuel de ce fichier ?

Le fichier ***/etc/passwd*** contient toutes les informatins concernant les utilisateurs (login, mots de passe...). 
La commande qui permet d'afficher la page du manuel de ce fichier est ***man -k passwd***.

17. Affichez seulement la première colonne triée par ordre alphabétique inverse

On peut utiliser la commande ***sort -r***.

18. Quelle commande nous donne le nombre d’utilisateurs ?



19. Combien de pages de manuel comportent le mot-clé conversion dans leur description ?

Il y a 4 pages de manuel comportant le mot-clé conversion dans leur description.

20. A l’aide de la commande find, recherchez tous les fichiers se nommant passwd présents sur la machine

21. Modifiez la commande précédente pour que la liste des fichiers trouvés soit enregistrée dans le fichier ~/list_passwd_files.txt et que les erreurs soient redirigées vers le fichier spécial /dev/null

22. Dans votre dossier personnel, utilisez la commande grep pour chercher où est défini l’alias ll vu précédemment

L'alias ll est défini dans le fichier.bashrc.

23. Utilisez la commande locate pour trouver le fichier history.log.

Le fichier history.log se trouve dans ***/var/log/apt/history.log***

24. Créer un fichier dans votre dossier personnel puis utilisez locate pour le trouver. Apparaît-il ? Pourquoi ?

```Travailler avec plusieurs shells```



```Exercice 4```

3. Le fichier .bashrc est lu au démarrage du shell ; pour le recharger, il faudrait donc se déconnecter puis se reconnecter ; mais il existe un autre moyen : la commande source .bashrc. Testez-la, l’invite
de commande devrait immédiatement passer en couleurs.

En effet l'invite de commande est passer en couleur.

4. Les couleurs par défauts (surtout celle du dossier courant) ne sont pas très visibles. Dans .bashrc, cherchez les lignes commençant par PS1= ;elles indiquent la mise en forme de l’invite de commande

Je n'ai pas remarqué de changements spécifiques.
