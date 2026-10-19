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
