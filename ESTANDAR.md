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
## 4. Estructura de carpetas

El proyecto formativo sigue una arquitectura **MVC (Modelo - Vista - Controlador)** separando la lógica del servidor, el acceso a datos y los recursos públicos accesibles desde el navegador.

```text
proyecto-formativo/
├── app/                        # Núcleo de la aplicación (no accesible directamente por URL)
│   ├── config/                 # Configuración general, constantes y conexión a base de datos
│   ├── controllers/            # Controladores que reciben peticiones y coordinan la lógica
│   ├── models/                 # Modelos y consultas SQL hacia la base de datos
│   └── views/                  # Vistas HTML/PHP organizadas por módulos
│       ├── auth/               # Login, registro y recuperación de contraseña
│       ├── dashboard/          # Panel principal y estadísticas
│       └── layouts/            # Plantillas reutilizables (header, navbar, footer)
├── public/                     # Raíz pública del servidor web (única carpeta expuesta)
│   ├── assets/                 # Recursos estáticos del frontend
│   │   ├── css/                # Hojas de estilo propias y librerías
│   │   ├── js/                 # Scripts de interacción y validaciones
│   │   └── img/                # Logotipos, íconos e imágenes del sistema
│   └── index.php               # Punto de entrada único (Front Controller)
├── database/                   # Scripts de base de datos y respaldos
│   ├── schema.sql              # Estructura de tablas, llaves y relaciones
│   └── seeds.sql               # Datos iniciales de prueba
├── .editorconfig               # Estandarización automática de formato en el editor
├── .gitignore                  # Exclusión de archivos locales, logs y credenciales
├── ESTANDAR.md                 # Estándar de codificación del equipo
└── README.md                   # Documentación general e instrucciones de instalación

## 5. Git: ramas, commits y pull requests
(pendiente)