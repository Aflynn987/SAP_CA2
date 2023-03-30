# SAP_CA2

Git branch name: main


```
// Create a docker network
docker network create my-network

// run a mysql:latest docker image
docker run --name db -e MYSQL_ROOT_PASSWORD=my-secret-password -d mysql:latest

// run docker image phpmyadmin/phpmyadmin to port 80
docker run --name phpmyadmin --network my-network -p 8080:80 -d phpmyadmin/phpmyadmin
```