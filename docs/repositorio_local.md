# Repositorio local

Para crear un repositorio local, primero se usan los siguientes comandos para configurar el nombre de usuario y el correo:  
```
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@ejemplo.com"
```  
Luego, se usa el comando `git init` para iniciar el repositorio. Si se encuentra en la rama master, se usa el comando `git branch -m main`. A partir de aquí, comenzamos a navegar entre los archivos y directorios, realizando las modificaciones necesarias. Después de modificar uno o más archivos, usamos el comando `git status`, que nos mostrará cuáles archivos están desactualizados en la rama principal. Para pasar esos archivos al stage, usamos el comando git add seguido del nombre del archivo. Luego, si volvemos a ejecutar git status, básicamente nos indicará que el archivo está listo para ser confirmado, como si estuviéramos tomándole una "foto". Para ello, usamos el comando `git commit -m "comentario"`, donde agregamos un comentario descriptivo.    

Además, en este repositorio también podemos usar o crear archivos `.gitignore`, que le indican a Git qué archivos debe ignorar. Esto es útil para evitar que se incluyan archivos confidenciales, irrelevantes o de otro tipo.   

Si necesitamos editar un commit previamente realizado, podemos usar el comando `git commit --amend`, lo que nos permitirá modificar el último commit realizado. Para ver el historial de commits, podemos utilizar el comando `git log`, que nos mostrará una lista de todos los commits realizados en el repositorio.

**Por ejemplo:**  
![Configuración](../imagenes/configuracion.jpeg)  
Aca se puede observar la configuracion del repositorio.  

![commit](../imagenes/dcs_uso_de_consola.jpeg)  
Aca se puede ver como se usa el `git add` y el `git commit`