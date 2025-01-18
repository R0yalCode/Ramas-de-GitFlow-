# Ramas de GitFlow
![flujo de trabajo](https://github.com/user-attachments/assets/5f4428e9-4b57-4594-9539-5751689ee619)
> Flujo de trabajo

# Ramas
## main
 Es la rama central donde se realiza la integración final del proyecto. Cualquier cambio importante o funcionalidad terminada se fusiona en esta rama.
 - Es la rama principal y suele contener el código que está listo para producción o la versión estable del software. Todo el trabajo que se fusiona a esta rama debe estar completamente probado y listo para ser desplegado.
## develop
Es la rama donde el equipo de desarrollo realiza la mayor parte del trabajo. Se utiliza para probar nuevas características antes de que se fusionen con la rama main.
- Es la rama de desarrollo donde se integran las características en curso y las correcciones. Esta rama se mantiene generalmente con una versión más inestable que la de main, ya que en ella se implementan las nuevas funcionalidades que aún están en desarrollo.
## releases
Una vez que la funcionalidad principal ha sido integrada en develop, se crea una rama de release para hacer pruebas finales, corregir errores y documentar la versión antes de integrarla en la rama main.
- Se utiliza para preparar nuevas versiones o lanzamientos del software. Cuando el equipo está listo para lanzar una nueva versión estable, se crea una rama de release desde develop para hacer ajustes finales y correcciones de errores antes del lanzamiento.
## feature
Cada nueva característica o funcionalidad se desarrolla en una rama feature derivada de la rama develop. Una vez terminada la funcionalidad, se fusiona de nuevo con develop.
- Se utilizan para desarrollar nuevas características o funcionalidades de manera aislada y sin afectar el código principal. Las ramas feature permiten que los desarrolladores trabajen en tareas específicas sin interrumpir la estabilidad de las otras ramas.
## hotfixes 
Una rama hotfix se crea desde main para corregir problemas urgentes. Después de realizar la corrección, los cambios se fusionan tanto en main como en develop para asegurar que el arreglo esté presente en ambas ramas.
- Se utiliza para corregir errores críticos en producción que deben solucionarse de inmediato sin esperar a que se liberen nuevas versiones.
