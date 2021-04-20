# simple-astronomy-lib

## Membres
Yacine Mokrane
Biache Raphael
Lecomte Quentin
Deliessche Quentin

## Objectif
Mettre en place une intégration continue sur un projet déja existant.
Ici nous avons repris le projet Simple Astronomy (https://github.com/SimpleAstronomy/simple-astronomy-lib) qui est en Java.

## Etapes
Nous avons mis en place Jenkins pour l'intégration continue, il faudra donc créer un Pipeline sur Jenkins avec un script from SCM qui se trouve sur le repo ici, le fichier Jenkinsfile.

Faire attention sur la variable JAVA_HOME='/usr/lib/jvm/java-1.11.0-openjdk-amd64'.

