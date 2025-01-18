# Ramas de GitFlow
![flujo de trabajo](https://github.com/user-attachments/assets/5f4428e9-4b57-4594-9539-5751689ee619)
> Flujo de trabajo

# Ramas
## main
 Es la rama central donde se realiza la integración final del proyecto. Cualquier cambio importante o funcionalidad terminada se fusiona en esta rama.
## develop
Es la rama donde el equipo de desarrollo realiza la mayor parte del trabajo. Se utiliza para probar nuevas características antes de que se fusionen con la rama main.
## releases
Una vez que la funcionalidad principal ha sido integrada en develop, se crea una rama de release para hacer pruebas finales, corregir errores y documentar la versión antes de integrarla en la rama main.
## feature
Cada nueva característica o funcionalidad se desarrolla en una rama feature derivada de la rama develop. Una vez terminada la funcionalidad, se fusiona de nuevo con develop.
## hotfixes 
Una rama hotfix se crea desde main para corregir problemas urgentes. Después de realizar la corrección, los cambios se fusionan tanto en main como en develop para asegurar que el arreglo esté presente en ambas ramas.
