## Despliegue de apps Spring Boot
1. Crear cuenta en heroku.com
2. Tener configurado git en el ordenador 
  1. "git config --global user.name "chIvonneBelen""
  2. "git config --global user.mail"
3. Subir el proyecto a Githun desde Intellij IDEA desde la opcion: VCS > Share project on Github
4. Desde Heroku crear app y elegir metodo Github y buscar el repositorio subidi
5. Habilitar deploy automatico y ejecutat el deploy

## Ejercicio1
* probar a empaquetar la app con maven package desde intellij IDEA
* Desde terminal en intellij IDEA verificar que se ejecute correctamente el comando

java -jar target/spring-deploy-1.0.jar

* Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador 

## Ejercicio 2
Deplegar el API REST de Laptops en Heroku y verificar funcionamiento desde POSTMAN

## Proveedores Cloud
* Heroku -- Java, Spring, PostgresSQL
* Netlify -- Frontend (REact, Angular ...)
* Vercel -- Frontend (React, Angular..)