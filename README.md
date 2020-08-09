
## GUIDE

 https://blog.ssdnodes.com/blog/host-multiple-ssl-websites-docker-nginx/


# In case of new setup on new server
0. docker network create nginx-proxy

1. run $ curl https://raw.githubusercontent.com/jwilder/nginx-proxy/master/nginx.tmpl > nginx.tmpl
into the nginx-proxy folder

2. docker-compose up -d (in the ngxin-proxy folder)

2.1 update the .env in the UI folder with the name of the restaurant
2.2 update the faivcon link in the index.html int he public folder
3. docker-compose up -d (in the general folder)