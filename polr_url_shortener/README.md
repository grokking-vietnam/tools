Polr is an open-sourced URL shortener (like bit.ly, but without extended analytics).
This is the docker image for it, hosted at `r.grokking.org`


## What's inside
- Nginx
- PHP FPM (FastCGI Process Manager)
- MySQL (5.7, community version)


## Alternatives to Polr
- <https://github.com/search?o=desc&q=url+shortener&s=stars&type=Repositories&utf8=%E2%9C%93>
- Yourls is a very prominent candidate with better analytics,
but setting it up inside docker was hard, especially going through the Apache rewrite rules

## Links
https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-in-ubuntu-16-04
