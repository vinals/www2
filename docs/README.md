In a local deployment use /assets as the root URL

On GitHub just use assets (no /) on index.html and /www2/assets/ .. in
other subpages.

The root seems to be vinals.github.io and /www2/ is the root for the site.
docs gets completely ignored. This is with _conf.yml:

baseurl: "/www2" # the subpath of your site, e.g. /blog
url: "https://vinals.github.io" # the base hostname & protocol for your site, e.g. http://example.com

