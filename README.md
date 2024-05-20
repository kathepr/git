Configurar credenciales
* git config --global user.name "username"
* git config --global user.email "user email"
* comprobar los cambios: git config --list
* Renombrar la rama master a main: git branch -m master main


* Para crear un archivo denominado index.html: touch index.html

1. Inicializar repositorio: git init
2. ¿En que rama estoy parada? git branch
3. Ver configuración: nano ~/.gitconfig
4. Ver estado actual del repositorio: git status
5. Subir a Staged Changes un archivo: git add README.md (nombre del archivo)
6. Bajar /Revertir un archivo de Staged changes: git reset README.md (nombre del archivo)
7. Escribir commit: git commit -m "mensaje"
8. Para mostrar el historial de commits en una sola línea por cada commit: git log --oneline

9. Para cambiar el estado del árbol de trabajo y el HEAD al commit especificado: git checkout <commit> ejemplo: git checkout 0b48dd7, estás solicitando cambiar al commit con el identificador único (hash) 0b48dd7.

10. Para salirme: git checkout master/main (te vas de nuevo a la principal)

11. Para corregir un commit: git commit --amend







CONVENTIONAL COMMITS:
https://www.conventionalcommits.org/en/v1.0.0/
* Emojis: https://gitmoji.dev/


1. feat: Se utiliza cuando se añade una nueva característica al código.

2. fix: Indica una corrección de un error o un bug.

3. docs: Se emplea para cambios o mejoras en la documentación.

4. style: Refleja cambios en el formato del código, como ajustes de espacio en blanco, sangrías, etc., que no afectan al comportamiento del código.

5. refactor: Indica cambios en el código que no añaden nuevas características ni corrigen errores, sino que mejoran la estructura o legibilidad del código.

6. test: Se utiliza para adiciones o modificaciones en pruebas, tanto de código como de comportamiento.

7. chore: Refleja cambios en tareas de construcción o configuración, así como en otras actividades que no modifican el código fuente en sí.



HACER EL COMMIT:
ejemplo:
git commit -m "feat: :tada: Configutación básica de la web
> 
> Creación del entorno y archivo de documentación y configuración del gitignore
> 
> "

