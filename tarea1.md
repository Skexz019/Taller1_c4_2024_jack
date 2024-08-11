# Tarea 1

## Conceptos Fundamentales

### ¿Qué es un servicio REST?
Un servicio REST (Representational State Transfer) es una arquitectura para diseñar servicios web que permiten la comunicación entre sistemas a través de HTTP. Utiliza recursos identificados por URLs y métodos HTTP estándar.

### ¿Cuáles son los principios del diseño RESTful?
1. **Identificación de recursos:** Usar URIs para cada recurso.
2. **Manipulación a través de representaciones:** Interacción mediante JSON, XML, etc.
3. **Stateless:** Cada solicitud debe ser independiente.
4. **Uso de métodos HTTP estándar:** GET, POST, PUT, DELETE.
5. **HATEOAS:** Navegación a través de hipervínculos.

### ¿Qué es HTTP y cuáles son los métodos HTTP más comunes?
HTTP es un protocolo de comunicación para la web. Métodos comunes:
- **GET:** Solicita un recurso.
- **POST:** Crea un nuevo recurso.
- **PUT:** Actualiza un recurso.
- **DELETE:** Elimina un recurso.

### ¿Qué es un recurso en el contexto de un servicio REST?
Un recurso es cualquier entidad identificable por una URI, como un documento o servicio web.

### ¿Qué es un endpoint?
Un endpoint es una URL específica que representa un recurso o acción en un servicio REST.

## Estructura de un Servicio REST

### ¿Qué es un URI y cómo se define?
Un URI (Uniform Resource Identifier) identifica de manera única un recurso en la web.

**Ejemplo:** `https://api.ejemplo.com/recursos/123`

### ¿Qué es una API RESTful?
Una API que sigue los principios de REST, permitiendo la interacción entre sistemas a través de HTTP.

### ¿Qué son los códigos de estado HTTP y cómo se usan en REST?
Códigos de tres dígitos que indican el resultado de una solicitud HTTP.

#### Códigos HTTP Comunes
| Código | Significado             |
|--------|-------------------------|
| 200    | OK - Solicitud exitosa   |
| 201    | Created - Recurso creado |
| 204    | No Content - Sin contenido |
| 400    | Bad Request - Solicitud inválida |
| 401    | Unauthorized - No autenticado |
| 403    | Forbidden - Sin permiso  |
| 404    | Not Found - No encontrado |
| 500    | Internal Server Error - Error del servidor |

### ¿Qué es JSON y por qué se usa comúnmente en APIs REST?
JSON es un formato ligero para el intercambio de datos, fácil de leer/escribir y ampliamente usado en APIs REST.
