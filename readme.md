## Iview pour SPIP

iView est un slider JavaScript facile d'utilisation initialement publiée sur [iprodev.com](http://iprodev.com/iview/) (demo).

Les sources JavaScript sont sur leur [Github](https://github.com/iprodev/iView).

### Utilisation

Via l'interface d'administration, vous pouvez créer des slides et des slideshows. Les slides se lient à des slideshows.
Les logos des slides sont les images du slideshow, ne les oublier donc pas !

Il suffit ensuite d'inclure le squelette slider.html et de lui passer en argument l'id du slideshow que vous voulez afficher.

	<INCLURE{fond=slider, env, id_slideshow=1}>

### Style

iView est livré avec un style de base, mais vous pouvez le modifié comme bon vous semble.

**Attention que si vous surcharger les fichiers CSS vous devez aussi surcharger les images dans le dossier squelettes !**