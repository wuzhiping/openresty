docker-compose exec openresty openresty -s reload

ab -n100 -c5 http://localhost:8088/lua/xyz

