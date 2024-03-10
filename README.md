![iprofile-IaC Project](/images/project-architecture-gitops.png "GitOps Project")

# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
- SonarQube
- EKS
- Helm
- ECR
- Terraform
- GithubActions
- Docker

# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql
