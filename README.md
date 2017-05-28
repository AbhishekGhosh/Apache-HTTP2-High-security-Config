# Apache High Security Config

Apache High security Config With Geotrust DV

````
etc
 |
 apache2
       |
       sites-available
                     |- 000-default.conf
                     |- default-ssl.conf
                     |- 000-default-le-ssl.conf
                     |- le-redirect-www.abhishekghosh.pro.conf

000-default.conf = thecustomizewindows.com:80 -301-> https://thecustomizewindows.com
le-redirect-www.abhishekghosh.pro.conf = www.thecustomizewindows.com:80 -301-> https://thecustomizewindows.com
default-ssl.conf = www.thecustomizewindows.com:443 -301-> https://thecustomizewindows.com
000-default-le-ssl.conf = thecustomizewindows.com:443


/etc/letsencrypt/options-ssl-apache.conf is cipher and is options-ssl-apache.conf in this repo.

````
