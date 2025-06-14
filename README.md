RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://ashisun.github.io/zili/index.html$1 [R,L]
