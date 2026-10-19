# github_colaborativo_devops
Github git para taller devops

## Concepto a investigar: GitHub Flow

**GitHub Flow** es un flujo de trabajo ligero para colaborar con Git y GitHub. Lo propuso GitHub como alternativa más simple a Git Flow: en lugar de varias ramas de larga duración (`develop`, `release`, `hotfix`), todo gira alrededor de una sola rama principal, `main`, que debe estar siempre estable y lista para desplegar.

El ciclo de un cambio es este:

1. **Crear una rama** desde `main`, con un nombre que describa el trabajo (por ejemplo, `feature/login` o `fix/navbar`).
2. **Hacer commits** pequeños y frecuentes en esa rama, sin tocar `main` directamente.
3. **Abrir un pull request** cuando el cambio está listo para verse. Ahí el equipo revisa el código, deja comentarios y discute los ajustes.
4. **Probar** el cambio (en local, en CI o en un entorno de preview) antes de integrarlo.
5. **Fusionar** el pull request en `main` una vez aprobado y borrar la rama. `main` vuelve a quedar desplegable.

La idea central es que cada cambio entra a producción por el mismo camino corto: rama, pull request, revisión y merge. Sirve bien en equipos que despliegan seguido y no necesitan el esquema más pesado de Git Flow.


## Cómo contribuir

Cómo contribuir en un proyecto de GitHub
Contribuir a un proyecto de GitHub consiste en colaborar con otros desarrolladores para mejorar un software existente. Se puede participar corrigiendo errores, agregando funcionalidades, mejorando la documentación o realizando pruebas.
Pasos para contribuir
1. Elegir un proyecto: buscar un repositorio público en GitHub que sea de interés y revisar su documentación (README.md) para conocer su funcionamiento y las tecnologías utilizadas.

2. Hacer un Fork: crear una copia del repositorio en la propia cuenta de GitHub para poder trabajar sin modificar directamente el proyecto original.

3. Clonar el repositorio: descargar la copia al equipo local mediante Git para analizar el código y realizar modificaciones.

4. Crear una rama: generar una rama independiente para trabajar en una mejora o corrección sin afectar la rama principal.

5. Realizar los cambios: modificar el código, corregir errores o agregar funcionalidades, siguiendo las convenciones y recomendaciones del proyecto.

6. Probar las modificaciones: verificar que los cambios funcionen correctamente y que no generen errores en otras partes del sistema.

7. Crear un commit y subir los cambios: registrar las modificaciones con un mensaje descriptivo y enviarlas al repositorio propio.

8. Enviar un Pull Request: solicitar a los responsables del proyecto que revisen los cambios y, si los consideran adecuados, los incorporen al repositorio original.