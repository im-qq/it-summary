全站无cache
需要在返回请求头里面加上:
Cache-Control:no-cache, no-store

sudo a2enmod headers

Header merge Cache-Control no-cache
Header merge Cache-Control no-store