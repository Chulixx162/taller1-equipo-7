# Estándar de codificación - Equipo 7
Lenguaje(s) del proyecto formativo: ...

## 1. Nombrado
(pendiente)

## 2. Formato
(pendiente)

## 3. Comentarios y documentación
1. Cuándo comentarLa regla general es que el código explica qué hace (mediante buenos nombres) y los comentarios explican por qué se hizo así.En PHP y JavaScript:Sí comentar: Reglas de negocio no obvias (ej. cálculos de impuestos o validaciones específicas), soluciones temporales (// FIXME:) y tareas pendientes (// TODO:).No comentar: Código obvio (// Suma 1 al contador), código muerto o comentado (para eso está Git) ni credenciales.En MySQL:Sí comentar: Consultas complejas con múltiples JOIN, subconsultas, triggers o procedimientos almacenados, explicando qué problema resuelven o qué regla de integridad protegen.En HTML5 y CSS3:Sí comentar: Únicamente para separar secciones grandes en plantillas largas (ej. <!-- Sección de filtros -->) o justificar reglas CSS inusuales (ej. /* z-index alto para quedar sobre el modal de Bootstrap */).2. Cómo documentar funciones y scriptsCada tecnología del proyecto maneja su propio estándar:TecnologíaEstándarQué documentar obligatoriamentePHPPHPDocFunciones, métodos de clases, controladores y endpoints.JavaScriptJSDocFunciones reutilizables, peticiones fetch y lógica de negocio.MySQLComentarios SQL (-- / /* */)Encabezado de scripts .sql, procedimientos almacenados y vistas.HTML5 / CSS3Comentarios de bloqueSolo inicio de secciones principales o componentes reutilizables.Ejemplo en PHP (PHPDoc)PHP/**
 * Registra un nuevo usuario en la base de datos con contraseña encriptada.
 *
 * @param mysqli $conexion Conexión activa a MySQL.
 * @param string $correo Correo electrónico único del usuario.
 * @param string $clave Contraseña en texto plano antes del hash.
 * @return bool True si el registro fue exitoso, false en caso contrario.
 */
function registrarUsuario(mysqli $conexion, string $correo, string $clave): bool {
    // Lógica de inserción...
}
Ejemplo en JavaScript (JSDoc)JavaScript/**
 * Valida que el monto ingresado sea un número positivo.
 *
 * @param {number|string} monto - Valor capturado del formulario.
 * @returns {boolean} True si es válido, false si es negativo o no numérico.
 */
function validarMonto(monto) {
    return !isNaN(monto) && Number(monto) > 0;
}
Ejemplo en MySQLSQL/*
 * Script: schema_inicial.sql
 * Descripción: Crea las tablas base y relaciones del sistema.
 * Motor: InnoDB | Cotejamiento: utf8mb4_unicode_ci
 */
3. Qué debe tener el READMEEl archivo README.md en la raíz del repositorio debe permitir que cualquier integrante del equipo o evaluador levante el proyecto en local sin preguntar nada. Debe incluir estas 7 secciones:Nombre y descripción del proyecto: Qué hace la aplicación y qué problema resuelve en máximo 3 líneas.Tecnologías utilizadas: Lista con versiones exactas (ej. PHP 8.2, MySQL 8.0, HTML5, CSS3, JavaScript ES6+).Requisitos previos: Software necesario para ejecutarlo en local (ej. Laragon o XAMPP, Git y navegador actualizado).Instalación paso a paso:Cómo clonar el repositorio y en qué carpeta ubicarlo (ej. www/ o htdocs/).Cómo crear la base de datos e importar el archivo .sql (indicando la ruta exacta del script, ej. database/schema.sql).Configuración de conexión: Instrucciones para configurar las credenciales de MySQL (ej. copiar config/db.example.php o .env.example y colocar host, usuario, contraseña y nombre de la base de datos).Ejecución y acceso: URL local para abrir el proyecto (ej. http://localhost/nombre-proyecto) y, si aplica, credenciales de un usuario de prueba para iniciar sesión.Estructura de carpetas y autores: Mapa breve de los directorios principales (assets/, controllers/, models/, views/, database/) y nombres de los integrantes del equipo.
## 4. Estructura de carpetas
(pendiente)

## 5. Git: ramas, commits y pull requests
(pendiente)