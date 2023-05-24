# index.artandcode.org.git
This is the landing page for artandcode.org. artandcode.org redirects to
index.artandcode.org.

## Why this redirect?
The original artandcode.org websites were WordPress websites hosted at
subdirectories (i.e. `/one`, `/3d`, etc.). In order to maintain the permalinks,
we use the STUDIO's main web server to service the static archives of these
websites and to redirect these subdirectories to their new subdomains. So
visiting `artandcode.org/3d` will redirect you to `3d.artandcode.org/`.

This method also allows for new websites to be created with GitHub Pages to
avoid the need for a system administrator to continue to add new websites to
the STUDIO's server. Additional subdomains can be added by editing DNS settings
alone.

Because the STUDIO server hosts these redirects for artandcode.org and we don't
want to require an administrator to edit the website, we simply redirect the
`artandcode.org` home page to `index.artandcode.org`. A reverse proxy is also
possible but ultimately more likely to require maintenance in the future. 
