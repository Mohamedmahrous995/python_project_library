# crud-application-using-flask-and-mysql
A simple CRUD application using Flask and MySQL

#### Built With

* Python
* Python Libraries: flask and pymysql
* MySQL
* AdminLTE 2

#### Running on Docker and docker-compose via hub.sh script

./hub.sh

```
docker-compose up -d
```

After executing, you will have 2 running cointainers on your Docker host: `phonebook-app` and `phonebook-mysql`. For accessing the web application, open your browser and go to http://your-docker-host-ip-address:8181

To destroy the containers, execute:

```
docker-compose down --rmi all
```
#### Runing APP on minikube

```
create deployment and service for app
```
to run all created objects
# kubectl apply -f .

# you need to expose service to be accessible outside the node

```
minikube service phonebook-mysql

```
# crudApp_k8s
# crud-_app-k8s
# crud-_app-k8s
# python_project
