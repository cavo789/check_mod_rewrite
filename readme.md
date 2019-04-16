# Check mod_rewrite

![Banner](.images/banner.png)

To make sure mod_rewrite is well enabled on the hoster, sometimes `phpinfo` isn't clear enough: the presence of `mod_rewrite` isn't listed in the list of loaded modules but seems (if we have to believe the hosting company) well loaded.

So, to make sure that mod_rewrite is enabled or not, just test it.

This repository contains three files; get a copy of each of them and save them onto your website:

1. Make a download of this repository so you'll get a copy of each file; namely `mod_rewrite_installed.php`, `mod_rewrite_not_installed.php` and `.htaccess`
2. Start your FTP client and connect to your website
3. Create a new folder in your root like `/tests`
4. Upload the three files mentioned here above in the `/tests` folder

You're ready.

Start a browser, surf to your website and just type `/tests` at the end of your URL so, if your URL is `https://mysite.fr` so go to `https://mysite.fr/tests`.

You'll get immediately the result.

* `mod_rewrite is enabled on your server`: congrats, mod_rewrite is well enabled
* `mod_rewrite is NOT enabled on your server`: now, you are sure, mod_rewrite is not loaded and thus will not work. This means that URL rewriting to get "nice" URLs won't work (in term of Joomla: you'll still see `index.php` in your URLs).
