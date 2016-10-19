# Jekyll #

Les sites en HTTPS sont mieux référencés 

Jekyll est un générateur de site codé en Ruby

Installer Jekyll : 

* sudo apt install ruby ( Installer Ruby )
* sudo apt install jekyll ( Installer Jekyll )
* jekyll ( Informations sur Jekyll )
* jekyll serve ( Lancer un serveur )
* Jekyll build ( Créé un dossier avec l'ensemble de notre site dedans ; prend le site et créé un autre )

Cela nous permet de voir les modifications sans passer par GitHub 

Les fichier avec un underscore ne sont pas générés dans le site 

On ne travaille pas dans le fichier généré !

## Principe du _Includes ## 

Permet de simplifier le code et d'éviter de tout retaper à chaque fois 

Pour cela :

* mkdir _includes ( Créer le répertoire )
* touch head.html ; touch header.html ; touch footer.html ( créer un fichier pour chaque parties du HTML dans le répertoire _includes )
* On coupe / colle le code du index.html pour chaque parties correspondantes 
* On ajoute le code suivant pour chaue parties correspondantes : {% include footer.html %}

## Créer un Layout ## 

C'est la structure de notre site 

Pour cela : 

* mkdir _layouts ( on créé un répertoire layout )
* touch default.html ( dans le répertoire layout, on créé le fichier default )
* Dans ce fichier, on copie et on colle l'intégralité du code index sauf le main et on écrit {{ content }}
* Puis dans le fichier index on écrit en plus du main et entre les lignes en pointillées ce code-ci : layout: default