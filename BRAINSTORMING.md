### 08/05/2018

En marge de la première reflexion, on peut constater les points suivants:

Les applications opendata de type CKAN ou du module DKAN sont certes aux normes et offrent une API correct si à la base l'inventaire des données a été fait correctement.

Si il s'agit d'une plateforme faite pour les applications qui accéderont aux données via les différents accès possibles pour par exemple la réutilisation ou juste en usage comme lien vers la source d'origine, alors oui, les outils présents sont éfficaces inaliénablement.

Le problème à présent c'est qu'on à l'impression d'oublier le citoyen qui n'est pas forcément informaticien, qui voudrait avoir une donnée claire et une réutilisation rapidement généré et la ... une plateforme en pure CKAN (puisqu'il semblerait que cela soit la référence) ne suffit plus. L'utilisateur qui utilisera du pure CKAN devra passer par un ensemble de liens constitués de méta données pour finalement arriver à la données primaire et dans quelques cas une visualisation basique.

Nous avons donc la possibilité de refaire un développement spécifique (PHP / Python / Java) qui permettrait de répondre à nos besoins, mais qui ne sera pas si Agile que ca auf ou cette application est modulaire et permet donc de greffer à tout moment une nouvelle extension (plugin/addon) supportant la nouvelle fonctionalité. 

Notre soucis est d'avoir un outil qui soit fonctionnel, efficace, modulaire et durable mais aussi comme pour le partage des données, pourquoi ne pas partager l'outil mis en place. Nous sommes des informaticiens et pour nous une installation ou un upgrade se résumera à quelques lignes dde commandes par ci par la, éventuellement des requêtes aux niveau de la base de donnée et à une modification de quelques fichiers de configuration à l'exécution (les fichiers de bootstrap).
Qu'en est il des non informaticiens?

Nous essairons donc de mettre en place une solution à base de Wordpress et d'un thème qui permettra de comporter via le fichiers functions.php

La question quant au couplage wordpress mongodb reste en suspent ainsi que celui de wordpress et NodeJS qui nous permettrait de profiter des modules node de conversion du format des fichiers de données (XLS, XLSX, CSV, JSON).
