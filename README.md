
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://kouwei2223.github.io/aiot/index.html$1 [R,L]
