
## GUIDE

 https://blog.ssdnodes.com/blog/host-multiple-ssl-websites-docker-nginx/


# In case of new setup on new server
0. docker network create nginx-proxy

1. run $ curl https://raw.githubusercontent.com/jwilder/nginx-proxy/master/nginx.tmpl > nginx.tmpl
into the nginx-proxy folder

2. docker-compose up -d (in the ngxin-proxy folder)

3. docker-compose_domain_example up -d (in the general folder)