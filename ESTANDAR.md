# Estándar de codificación - Equipo 7
Lenguaje(s) del proyecto formativo: ...

## 1. Nombrado
(pendiente)

## Sección 2: Formato

### Indentación
- Se usan **espacios**, no tabulaciones.
- **4 espacios** por nivel (2 espacios en HTML, CSS y JSON).
- Configurar el editor para que convierta el Tab en espacios.

### Comillas
- **Comillas simples** (`'texto'`) para cadenas en el código (PHP/JavaScript).
- **Comillas dobles** (`"texto"`) en los atributos de HTML.
- Se usan comillas dobles en el código solo cuando la cadena lleva una comilla simple dentro o variables incrustadas.

### Largo máximo de línea
- Máximo **100 caracteres** por línea.
- Si una línea es más larga, se divide en varias líneas con la misma indentación.

### Llaves
- La llave de apertura va en la **misma línea** de la instrucción (`if`, `for`, `function`).
- La llave de cierre va en una línea aparte, alineada con el inicio de la instrucción.
- Siempre se usan llaves, aunque el bloque tenga una sola línea.

## 3. Comentarios y documentación
(pendiente)

## 4. Estructura de carpetas
(pendiente)

## 5. Git: ramas, commits y pull requests

### Nombres de ramas
- Formato: `tipo/descripcion-corta`, en minúsculas y separando palabras con guiones.
- Tipos permitidos:
  - `feature/` para nuevas funciones o archivos
  - `fix/` para corregir errores
  - `docs/` para documentación
  - `chore/` para tareas de mantenimiento (por ejemplo, `.gitignore`)
- Ejemplos: `feature/login-usuario`, `fix/error-conexion`, `docs/readme-equipo`.
- Nunca se trabaja directamente en `main`.

### Formato de commits
- Se usa **Conventional Commits**: `tipo: descripción corta`.
- Tipos: `feat`, `fix`, `docs`, `chore`.
- La descripción va en minúsculas, en presente y sin punto final (máximo 72 caracteres).
- Ejemplos:
  - `feat: agrega formulario de registro`
  - `fix: corrige error al guardar la cita`
  - `docs: completa README del equipo`
- Un commit debe hacer un solo cambio.

### Reglas de pull requests
- Todo cambio llega a `main` mediante un pull request.
- El título del PR sigue el mismo formato que los commits.
- La descripción explica brevemente qué se cambió y por qué.
- Cada PR debe estar vinculado a un issue (por ejemplo, `Closes #12` en la descripción).
- Cada PR debe ser revisado y **aprobado por al menos un compañero** antes de fusionarse.
- Nadie aprueba ni fusiona su propio PR.
- Los comentarios de la revisión se responden antes de fusionar.
- Después de fusionar, se actualiza el repositorio local con `git switch main` y `git pull origin main`.
- Las ramas se mantienen pequeñas y se eliminan una vez fusionadas.
