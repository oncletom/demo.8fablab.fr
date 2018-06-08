# demo.8fablab.fr

Terrain de jeu pour apprendre à faire un site statique en reprenant le [site
web du 8FabLab/Coworking](http://8fablab.fr/) ⛰ Drôme.

# Prérequis

Le logiciel [jekyll](https://jekyllrb.com/) qui est utilisé pour générer le
site à partir de fichiers texte nécessite le langage de programmation
[ruby](https://www.ruby-lang.org/en/documentation/installation/).

Une fois `ruby` (et son utilitaire `gem`) installés, il faut installer
l'utilitaire `bundler` qui permet d'installer tous les prérequis suivants:

```
sudo gem install bundler
```

# Installer

Récupérer les fichiers de base en [téléchargeant
l'archive](https://github.com/oncletom/demo.8fablab.fr/archive/master.zip).

Une fois les fichiers récupérés, il reste à installer tous les prérequis
spécifiques à ce projet:

```
$ cd demo.8fablab.fr
$ bundle install
```

# Prévisualiser

```
$ bundle exec jekyll serve

> Server address: http://127.0.0.1:4000/
> Server running... press ctrl-c to stop.
```

Le site est maintenant visible en local sur http://127.0.0.1:4000/
