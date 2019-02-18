# spring-boot-angular7-maven

This code started as a fork of [](https://github.com/swathisprasad/spring-boot-angular6-maven-project) ..but I've since cut the ties.

Looking for a good place to start with an Angular 7 app with a Spring Boot "java -jar" deployment?  This is it.

# Getting Started
Build the pr0ject like this:

```./mvnw clean install```

...which will create this:

```backend/target/backend-0.0.1-SNAPSHOT.jar```

Then to run: 

```cd backend```

...and either this:

```../mvnw spring-boot:run```

or this:

```java -jar target/backend-0.0.1-SNAPSHOT.jar```

# Getting Started
Spring Security is enable by default, so every time you stat the app you'll be presented with this:

You can find the user/password at either [this](https://www.websparrow.org/spring/spring-security-how-to-change-default-username-and-password) [this](https://docs.spring.io/spring-boot/docs/2.0.0.RELEASE/reference/html/boot-features-security.html) or this link.


Once you log in successfully, you'll see this:


# Versions
```
npm version:
6.8.0

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 7.3.1
Node: 11.7.0
OS: darwin x64
Angular: 
... 

Package                             Version
-------------------------------------------------------------
@angular-devkit/architect           0.13.1
@angular-devkit/build-angular       0.13.1
@angular-devkit/build-optimizer     0.13.1
@angular-devkit/build-webpack       0.13.1
@angular-devkit/core                7.3.1
@angular-devkit/schematics          7.3.1
@angular/animations                 7.2.5
@angular/cli                        7.3.1
@angular/common                     7.2.5
@angular/compiler                   7.2.5
@angular/compiler-cli               7.2.5
@angular/core                       7.2.5
@angular/forms                      7.2.5
@angular/http                       7.2.5
@angular/language-service           7.2.5
@angular/platform-browser           7.2.5
@angular/platform-browser-dynamic   7.2.5
@angular/platform-server            7.2.5
@angular/router                     7.2.5
@ngtools/webpack                    7.3.1
@schematics/angular                 7.3.1
@schematics/update                  0.13.1
rxjs                                6.4.0
typescript                          3.3.3
webpack                             4.29.4

```
