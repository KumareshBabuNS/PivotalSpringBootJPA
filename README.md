<h1>Pivotal CF - Spring Boot / Spring Data JPA / Thymeleaf with Bootstrap demo</h1>

The following demo is a PWS Workshop known as Level 100, to get started on PWS. The application is 
set to use an embedded H2 database in non-PaaS environments and can be run locally as shown below. To 
take advantage of Pivotal CF's auto-configuration for services you should create a MYSQL service
prior to deploying this as shown below

```
> cf create-service cleardb spark pas-mysql
```

Detailed instructions can be found here, including materials for this workshop as either PPT, keynote or PDF

```
> https://dl.dropboxusercontent.com/u/15829935/platform-demos/workshop/level100/index.html
```


<h2>Pivotal Albums Page</h2>

![alt tag](https://dl.dropboxusercontent.com/u/15829935/platform-demos/workshop/level100/image1.png)

<h2> Steps to Run Locally </h2>

- Clone as follows

```
> git clone https://github.com/papicella/PivotalSpringBootJPA.git
```

- package as shown below

```
> mvn package
```

- Run as follows

```
mvn spring-boot:run
```

- Access as follows

```
http://localhost:8080/
```

<hr />
<i>
Pas Apicella [papicella at pivotal.io] is a Senior Platform Architect at Pivotal Australia
</i>

