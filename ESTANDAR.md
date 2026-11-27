# Estándar de codificación - Equipo 7
Lenguaje(s) del proyecto formativo: PHP, MySQL, HTML5, CSS3 y JavaScript.

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

```text
proyecto/
├── app/
│   ├── config/          # Conexión a BD y variables globales
│   ├── controllers/     # Lógica de negocio y peticiones
│   ├── models/          # Consultas SQL y acceso a datos
│   └── views/           # Plantillas HTML/PHP organizadas por módulo
├── public/              # Punto de entrada (index.php) y recursos públicos
│   ├── css/             # Hojas de estilo
│   ├── js/              # Scripts del cliente
│   └── img/             # Imágenes e íconos
├── database/            # Scripts SQL (estructura y datos de prueba)
├── .editorconfig        # Reglas automáticas de formato
├── .gitignore           # Archivos excluidos del repositorio
├── ESTANDAR.md          # Estándar de codificación del equipo
└── README.md            # Documentación principal

## 5. Git: ramas, commits y pull requests
(pendiente)