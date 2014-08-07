# awesome hosting

here's what I really want, and what I'd be willing to pay $10 a month for
(possibly more, though probably not much more than $15)

*n.b.* I'm going to use the word "unlimited" here a lot, and what I actually mean is
"some number sufficiently high such that I don't have to worry about it, ever",
kinda like how github gives me "unlimited" free repos but would probably cut me
off if I tried automatically creating a repo per byte as an alternative video
distribution channel.

1. static asset hosting for unlimited sites (say, up to 20 or 30MB)
2. custom domain / cname support (including multiple aliases & redirects to a single domain
3. custom ssl cert hosting - let me upload my own key and cert. bonus points for supporting
   passphrase-protected pfx archives
4. publish via git-push a la dokku or heroku
5. git pull support with webhook triggers to sync the site from eg a github repo
6. clean url support, eg /foo.html -> /foo

Bonus points for making the software / scripts to do this available so I can run on my own hardware or IaaS if I want.
