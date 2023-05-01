- This repository hosts a Laravel 9 application which needs to be dockerized.
- The public folder is /public
- There are 2 routes defined in the application /container1 and /container2
  - Both these routes should be working on separate container
  - so if I access /container1 it should be routed to container 1 and same thing for container 2
- storage folder should be available even after the containers are destroyed and recreated
----------------------------
Here, we are using traefik to do the above task
----------------------------
simple execute:
$docker-compose build
$docker-compose up
-----------------------------
Go to traefik dashboard ---> http and look for the ip address that traffik has alloted.

http://<ap_address>:8000/container1
http://<ap_address>:8000/container2


