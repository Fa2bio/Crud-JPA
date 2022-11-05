<h1>Crud-JPA</h1>

> Status: Finished ✔️

### Contents
  
* [What is it?](#what-is-it)
* [Requirements](#requirements)
* [Technologies Used](#technologies)
* [Installation](#installation)
* [Run Application](#run-application)

## <a name="what-is-it"></a>What is it?

A back-end project of a CRUD using Java and JPA.

## <a name="requirements"></a>Requirements

- Java 8+
- MySQL 5+

## <a name="technologies"></a>Technologies Used

- Java
- MySQL
- JPA
- Hibernate

## <a name="installation"></a>Installation

- Clone the repository for your device
- Import it as a Maven Project in your IDE...
- Create a new SCHEMA in the database with the name JPACrud
- Under /src/main/java/META-INF/persistenceModel.xml modify the file name persistenceModel.xml to persistence.xml
- Edit the VALUE of USER and PASSWORD of your MySQL database

### persistence.xml
```xml
<property name="javax.persistence.jdbc.user" value=" " />
<property name="javax.persistence.jdbc.password" value=" "/>
```
## <a name="run-application"></a>Run Application

After meeting the requirements and installation, run the main methods as a java project in the controller.basico

* To do a GET findById, run the class ObterUsuario.java
* To do a GET findAll, run the class ObterUsuarios.java
* To do a Post addUser, run the class NovoUsuario.java
* To do a Delete delUser, run the class RemoverUsuario.java