# sapho-mysql-docker-azure
# Deployment of Sapho/Tomcat+MySQL Containers with Docker Compose


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Flodotek%2Fsapho-mysql-docker-azure%2Fmaster%2Fazuredeploy.json" target="_blank">
	<img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Flodotek%2Fsapho-mysql-docker-azure%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>


TESTING:
[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/?repository=https://github.com/lodotek/sapho-mysql-docker-azure)


This template allows you to deploy an Ubuntu Server 16.04.0-LTS VM with Docker (using the [Docker Extension][ext])
and starts a Tomcat container with Sapho listening an port 80 which uses MySQL database running
in a separate but linked Docker container, which are created using [Docker Compose][compose]
capabilities of the [Azure Docker Extension][ext].


[ext]: https://github.com/Azure/azure-docker-extension
[compose]: https://docs.docker.com/compose
