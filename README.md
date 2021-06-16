# Home-Dicom
Caranx Medical's technical challenge


## Requirements
* Java 1.8
* Maven 3.6.3
* Papaya : https://github.com/rii-mango/Papaya.git

##  [Demo](https://homeandfamily.fr/Home-Dicom/login)
* login : caranxmedical
* password : 42caranx42

##  Quickstart Guide
From a terminal :
* Clone this repository
* 'cd' to folder ./Home-Dicom
* You can change the credentials (login/password) in file src/main/java/com/caranxmedical/dicom/config/WebSecurityConfig.java
* Set "app.env = DEV" in file src/main/resources/application.properties
* mvn clean package
* mvn spring-boot:run -Dserver.port=2021
* open your favorite browser and got to http://localhost:2021/login
* login : caranxmedical
* password : 42caranx42
