# Estándar de codificación - Equipo 7
Lenguaje(s) del proyecto formativo: ...

## 1. Nombrado
1. ¿Español o inglés?La regla de oro es no mezclar idiomas (cero Spanglish). Evita combinaciones como getUsuario(), crearUser() o btn_save_datos.Opción recomendada para proyecto formativo: Español en todo el código de negocio (variables, funciones, tablas y campos), ya que coincide con los requerimientos y la documentación académica.Opción estándar de la industria: Inglés en todo el proyecto, ideal si buscan simular un entorno laboral internacional.Regla obligatoria si eligen español: Nunca usar tildes, diéresis, espacios ni la letra ñ (ej. usar descripcion, anio, contrasena, telefono).2. Convenciones de nombradoElementoConvenciónEjemplo (Español)Regla claveVariables (PHP / JS)camelCase$totalVenta, correoUsuarioSustantivos claros que indiquen qué guardan.Funciones / Métodos (PHP / JS)camelCasecalcularDescuento(), registrarPago()Empezar siempre con un verbo de acción.Clases (PHP / JS)PascalCaseUsuarioController, ConexionDBSustantivos en singular.Constantes (PHP / JS)UPPER_SNAKE_CASEMAX_INTENTOS, DB_HOSTTodo en mayúsculas separado por guion bajo.Archivos de clases (PHP)PascalCaseUsuario.php, ProductoModel.phpMismo nombre exacto que la clase (estándar PSR-4).Otros archivos (Vistas, CSS, JS)kebab-caseiniciar-sesion.php, estilos-base.css, validar-form.jsTodo en minúsculas separado por guion medio.Carpetaskebab-case (minúsculas)controllers/, assets/img/, views/admin/Sin mayúsculas ni espacios (evita errores en servidores Linux).Tablas de BD (MySQL)snake_case (plural)usuarios, detalle_facturasTodo en minúsculas y en plural.Campos de BD (MySQL)snake_case (singular)id_usuario, fecha_creacion, precio_unitarioMinúsculas; llaves primarias como id o id_tabla, foráneas como id_tabla_referenciada.Clases e IDs (HTML5 / CSS3)kebab-case.tarjeta-producto, #btn-enviarMinúsculas y nombres que describan la función, no el color (.btn-primario en vez de .btn-azul).3. Reglas rápidas de calidadSin abreviaturas confusas: Escribe $fechaNacimiento en lugar de $fecNac o $fn. Solo se permiten abreviaturas universales como id, url, html o db.Booleanos como pregunta: Las variables o funciones que devuelven true/false deben empezar con prefijos como es, tiene o esta (ej. $esAdmin, tienePermiso(), estaActivo).Consistencia en llaves de BD: Si la tabla usuarios tiene como llave primaria id_usuario, todas las tablas que se relacionen con ella deben usar el mismo nombre id_usuario como llave foránea.

## 2. Formato
(pendiente)

## 3. Comentarios y documentación
(pendiente)

## 4. Estructura de carpetas
(pendiente)

## 5. Git: ramas, commits y pull requests
(pendiente)