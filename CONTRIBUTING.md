# Guía de contribución

¡Gracias por querer contribuir a este proyecto! Para mantener un flujo de trabajo organizado y asegurar la calidad de los cambios, todas las contribuciones deben seguir los pasos descritos a continuación.

## Flujo de contribución

### 1. Crear una Issue

Antes de comenzar a trabajar, se debe crear una *Issue* utilizando la plantilla correspondiente del repositorio:

- **Bug:** Para reportar errores o comportamientos inesperados.
- **Feature:** Para proponer o implementar nuevas funcionalidades.
- **Docs:** Para solicitar cambios, correcciones o mejoras en la documentación.

La issue debe incluir una descripción clara del problema o del cambio propuesto.

### 2. Crear una rama

Una vez creada la issue, se debe crear una nueva rama para trabajar en la contribución.

Se recomienda utilizar la siguiente convención de nombres:

- `feature/<numero-issue>-<descripcion>` para nuevas funcionalidades.
- `bugfix/<numero-issue>-<descripcion>` para correcciones de errores.
- `docs/<numero-issue>-<descripcion>` para cambios en la documentación.

**Ejemplo:** `feature/12-autenticacion-usuarios`

Cada rama debe estar asociada a una issue existente.

### 3. Realizar la contribución

Implementar los cambios definidos en la issue correspondiente.

Durante el desarrollo se debe:

- Mantener los cambios enfocados en el objetivo de la issue.
- Respetar la estructura y las convenciones existentes del proyecto.
- Probar los cambios antes de enviarlos.
- Evitar modificaciones innecesarias que no estén relacionadas con la contribución.

### 4. Crear un Pull Request (PR)

Una vez finalizado el trabajo, se debe crear un Pull Request desde la rama de trabajo hacia la rama de destino del repositorio.

El Pull Request debe incluir:

- Un título claro que describa los cambios realizados.
- Una descripción de lo implementado, corregido o modificado.
- Una referencia a la issue relacionada, utilizando, por ejemplo, `Closes #12`.
- Información relevante sobre las pruebas realizadas.

La descripción debe permitir que el reviewer comprenda el propósito y el alcance de los cambios sin necesidad de investigar por su cuenta.

### 5. Esperar la aprobación del reviewer

Todos los Pull Requests deben ser revisados y aprobados antes de integrarse a la rama de destino.

El colaborador debe:

- Esperar la revisión del reviewer asignado.
- Realizar las modificaciones solicitadas, si corresponde.
- Subir los cambios adicionales a la misma rama.
- Esperar la aprobación antes de realizar el merge.

**No se debe integrar un Pull Request sin la aprobación de un reviewer.**

## Consideraciones generales

- Toda contribución debe estar asociada a una issue.
- Se debe respetar el flujo de trabajo definido: **Issue → Rama → Contribución → Pull Request → Revisión y aprobación**.
- Los Pull Requests deben contener cambios claros y fáciles de revisar.
- Las discusiones y revisiones deben mantenerse en un marco de respeto y colaboración.
- No se debe omitir el proceso de revisión establecido.

¡Gracias por contribuir al proyecto!