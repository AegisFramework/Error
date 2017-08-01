# Error pages
Aegis Framework custom error pages


## Apache
To make them work under an Apache Server, add the following lines to your `.htaccess` file:

```markup
# ----------------------------------------------------------------------
# Error Documents
# ----------------------------------------------------------------------
ErrorDocument 400 /error/400.html
ErrorDocument 401 /error/401.html
ErrorDocument 403 /error/403.html
ErrorDocument 404 /error/404.html
ErrorDocument 405 /error/405.html
ErrorDocument 408 /error/408.html
ErrorDocument 429 /error/429.html
ErrorDocument 500 /error/500.html
ErrorDocument 503 /error/503.html
```

## Nginx
To make them work under an Nginx Server, add the following lines to your configuration file:

```markup
error_page 400 /error/400.html
error_page 401 /error/401.html
error_page 403 /error/403.html
error_page 404 /error/404.html
error_page 405 /error/405.html
error_page 408 /error/408.html
error_page 429 /error/429.html
error_page 500 /error/500.html
error_page 503 /error/503.html
```