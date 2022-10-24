# php-nginx-HA-Scale

## Running docker
- docker-compose up --build --scale webserver=3

## View Configuration HAProxy
- docker exec php-nginx-ha-lb-scale_load_balancer_1 cat haproxy.cfg

## Docker log view
- docker-compose logs -f
