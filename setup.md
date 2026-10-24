.\mvnw.cmd spring-boot:run

http://localhost:8080/api/tasks

----\***\*\*\*\*\*\*\***----

curl -o backend.zip "https://start.spring.io/starter.zip?type=maven-project&language=java&groupId=com.taskmanager&artifactId=backend&name=backend&packageName=com.taskmanager.backend&javaVersion=21&dependencies=web,data-jpa,validation"

tar -xf backend.zip -C backend

del backend.zip

.\mvnw.cmd clean

.\mvnw.cmd spring-boot:run

# **\*\***\*\*\***\*\***

Angular
↓
Controller ← HTTP
↓
Service ← Business logic
↓
Repository ← Database operations
↓
Entity ← Data structure
↓
postgresql

- Controller Waiter — receives your order
- Service Chef — decides how to prepare it
- Spring Restaurant
- Repository Kitchen/storage — gets or saves ingredients
- Entity The actual dish/data

## Spring Boot is essentially the framework that lets you build your Java backend/API without having to build the web server, database integration, dependency management, and configuration from scratch.

-------------------**\*\***\***\*\***-------------------------
ng generate interface models/task
ng g c components/task-list --style=scss
ng g c components/task-form --style=scss
ng generate service services/task

curl -o taskmanager.zip "https://start.spring.io/starter.zip?type=maven-project&language=java&groupId=com.taskmanager&artifactId=taskmanager&name=taskmanager&packageName=com.taskmanager&javaVersion=21&dependencies=web,data-jpa,validation"
