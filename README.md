
## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtime.version
```

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el pc:
   1. `git config user.name "Nombre usuario"`
   2. `git config user.email Correo github`
3. Subir el proyecto a GitHub desde Intellij IDEA desde la opción: VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir método Github y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy
