# Check mod_rewrite

![Banner](.images/banner.png)

**French text below**

To make sure `mod_rewrite` is well enabled on the hoster, sometimes `phpinfo` isn't clear enough: the presence of `mod_rewrite` isn't listed in the list of loaded modules but seems (if we have to believe the hosting company) well loaded.

So, to make sure that mod_rewrite is enabled or not, just test it.

This repository contains three files; get a copy of each of them and save them onto your website:

1. Make a download of this repository so you'll get a copy of each file; namely `mod_rewrite_installed.php`, `mod_rewrite_not_installed.php` and `.htaccess`,
2. Start your FTP client and connect to your website,
3. Create a new folder in your root like `/tests`,
4. Upload the three files mentioned here above in the `/tests` folder.

You're ready.

Start a browser, surf to your website and just type `/tests` at the end of your URL so, if your URL is `https://mysite.fr` so go to `https://mysite.fr/tests`.

You'll get immediately the result.

* `mod_rewrite is enabled on your server`: congrats, mod_rewrite is well enabled
* `mod_rewrite is NOT enabled on your server`: now, you are sure, mod_rewrite is not loaded and thus will not work. This means that URL rewriting to get "nice" URLs won't work (in term of Joomla: you'll still see `index.php` in your URLs).

---

Afin de s'assurer que `mod_rewrite` soit bien activé sur votre hébergement, parfois `phpinfo` n'est pas assez précis : la présence de `mod_rewrite` n'est pas listée dans la liste des modules chargés mais semble (si l'on doit croire l'hébergeur) bien chargée.

Donc, pour vous assurer que `mod_rewrite` est activé ou non, testez-le.

Ce dépôt contient trois fichiers; récupérez une copie de chacun d'entre eux et enregistrez-les sur votre site Web :

1. Télécharger ce dépôt pour obtenir une copie de chaque fichier, à savoir `mod_rewrite_installed.php`, `mod_rewrite_not_installed.php` et `.htaccess`,
2. Démarrez votre client FTP et connectez-vous à votre site Web,
3. Créez un nouveau dossier à la racine comme `/tests',
4. Envoyez (`upload`) les trois fichiers mentionnés ci-dessus dans le dossier `/tests`.

Vous êtes prêt.

Démarrez un navigateur, rendez-vous sur votre site Web et tapez simplement `/tests` à la fin de votre URL, donc si votre URL est `https://mysite.fr` allez sur `https://mysite.fr/tests`.

Vous obtiendrez immédiatement le résultat.

* `mod_rewrite est activé sur votre serveur` : félicitations, `mod_rewrite` est bien activé
* `mod_rewrite n'est PAS activé sur votre serveur` : maintenant, vous en êtes certain, `mod_rewrite` n'est pas chargé et ne fonctionnera donc pas. Cela signifie que la réécriture d'URL pour obtenir de "belles" URLs ne fonctionnera pas (en termes de Joomla : vous verrez toujours `index.php` dans vos URLs).
