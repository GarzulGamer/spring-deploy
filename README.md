
## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:

``` 
java.runtime.version=17
```

1. Crear cuenta en heroku.com y en github.com
2. Tener configurado git en el ordenador:
    1. `git config --global user.name "Garzul"`
    2. `git config --global user.email gabry@example.com`
3. Subir el proyecto a Github desde IntelliJ IDEA desde la opcion CVS > Share project on Github
4. Desde Heroku, crear app y elegir el modo Github y buscar el repositorio subido
5. Habilitar deploy automatico y ejecutar el Deploy