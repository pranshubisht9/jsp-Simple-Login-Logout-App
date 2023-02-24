# User-Registration-Login-SpringBoot

Still in development. User Registration using Spring Boot, Data JPA, in-memory MySQL db .

## Run Locally

Clone the project

```bash
  git clone https://github.com/pranshubisht9/codeCov.io.git
```

## Technologies we used

In this project we have used the following technologies:

- Java JDK 1.8
- Maven 
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL database
- JSP
- Hibernate


##Steps for running different modules:

###1)/signup
  localhost:8888/
  Select signup link.
  Add details for signup.
  User details are saved in embeded H2 database
  localhost:8888/h2-console
  User is directed to successful signup page.
###2)/login
  localhost:8888/
  Select login link.
  Add email and password.
  User is redirected to dummy page after successful login.
Note- Embedded database is used so every time project is relaunched signup must be done before login
      or Else, sample data is stored in resources/data.sql file
