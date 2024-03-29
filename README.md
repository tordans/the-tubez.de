# the-tubez.de

Jekyll Website for the choir "The Tubez" from Berlin.


# Notizen

- ```jekyll serve```
- ```jekyll build```


# Domain


* [Setting up a www subdomain](https://help.github.com/articles/setting-up-a-www-subdomain/)
 - IST: `CNAME` to `tordans.github.io`
* [Setting up an apex domain](https://help.github.com/articles/setting-up-an-apex-domain/)
 - SOLL: `A` to `192.30.252.153`
 - IST: Wir können den A Record nicht setzen, das der Hoster immer automatisch einen nicht löschbaren *.-A-Record setzt. Das sorgt für Probleme (siehe unten). Daher liegt jetzt auf dem Server eine `.htaccess`-Datei die den Redirect durchführt (siehe Ordner "_redirct-…" hier).
 - Warum wir keinen *.-A-Record verwenden dürfen: "Danger: Do not use wildcard DNS records (e.g. *.example.com) with GitHub Pages! A wildcard DNS record will allow anyone to host a GitHub Pages site at one of your subdomains." - https://help.github.com/articles/setting-up-a-custom-subdomain/


# License

- Theme "Agency Theme for Jekyll": [Apache License, Version 2.0, January 2004](LICENSE)
- Content: [Creative Commons Namensnennung-Nicht kommerziell 4.0 International Lizenz](http://creativecommons.org/licenses/by-nc/4.0/)


# Theme

**The one we use**

- https://github.com/y7kim/agency-jekyll-theme / http://themes.jekyllrc.org/agency/

**Other good themes**

- https://html5up.net/strata
- http://arkadianriver.github.io/spectral/
- https://inded.xyz/Jekyll_modern-blog/
- http://shaneweng.com/landing-page-theme/
- http://jeromelachaud.github.io/grayscale-theme/
- http://the-development.github.io/flex/
- https://nandomoreira.me/nandomoreira-jekyll-theme/
- http://gayan.me/gaya/about/
- https://jekyll-demos.github.io/herring-cove/
