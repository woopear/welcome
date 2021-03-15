# Les commandes Linux de base

## 1. La commande <span style="color: #26B260">pwd</span>

Cette commande vous permet d'afficher l'emplacement dans le quel vous vous trouvez

```
[davidcaignaert]# pwd
 /Documents/Woopear
```

## 2. La commande <span style="color: #26B260">cd</span>

Cette commande vous permet de changer de répertoire :

- cd Documents/Woopear => vous serez redirigés vers le dossier Woopear.
- cd .. => vous serez redirigés dans le dossier parent.
- cd - => vous retournerez sur le dossier précédent.
- cd / => vous permet de remonter au répertoire racine du système de fichier.

## 3. La commande <span style="color: #26B260">ls</span>

Cette commande vous permet de lister :

- ls => retourne les fichiers et dossiers du répértoire.
- ls -a => retourne en plus tous les fichiers et dossiers cachés.
- lspci ou lsusb => afficher les périphériques PCI ou USB connectés.
- lshw => affiche les caractéristiques de tout le matériel physique, non-logiciel (hardware).

## 4. La commande <span style="color: #26B260">mkdir</span>

Cette commande vous permet de créer un dossier.

```
[davidcaignaert]# mkdir MonNvoDossier
[davidcaignaert]# ls
MonNvoDossier
```

=> dans cette exemple, je crée un nouveau dossier appelé MonNvoDossier.

## 5. La commande <span style="color: #26B260">rmdir</span>

Cette commande vous permet de supprimer un dossier.

```
[davidcaignaert]# rmdir MonNvoDossier
[davidcaignaert]# ls
```

=> dans cette exemple, je viens de supprimer le dossier que j'avais créé juste avant.

## 6. La commande <span style="color: #26B260">cp</span>

Cette commande vous permet de copier un fichier ou un dossier.

```
[davidcaignaert]# ls
rules-globals.md
[davidcaignaert]# cp rules-globals.md ~/Documents/Programmation/Ionic-cordova
[davidcaignaert]# cd ~/Documents/Programmation/Ionic-cordova
[davidcaignaert]# ls
IONIC_-_CORDOVA.pptx  rules-globals.md
```

=> dans cette exemple, je viens de copier le fichier rules-globals.md et je l'ai envoyé dans le dossier ~/Documents/Programmation/Ionic-cordova.

## 7. La commande <span style="color: #26B260">rm</span>

Cette commande vous permet de supprimer un fichier ou un dossier.

## 8. La commande <span style="color: #26B260">mv</span>

Cette commande vous permet de renommer ou déplacer un fichier ou un répertoire.

```
 [davidcaignaert]# ls
Document  Jeu   Autres
 [davidcaignaert]# mv Jeu Jeux
 [davidcaignaert]# ls
Document  Jeux   Autres
```

=> dans cette exemple, j'ai changé le nom du fichier jeu en jeux.
