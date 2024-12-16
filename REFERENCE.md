# Guía de Referencia - Aplicación Deportes

## Descripción Técnica

Esta sección proporciona una visión técnica detallada sobre cómo está construida la aplicación Deportes.

### Arquitectura

La aplicación sigue una arquitectura basada en componentes reutilizables y modulares.

### Estructura del Proyecto

- `MainActivity`: Clase principal que maneja la interacción del usuario.
- `TarjetaDeportes`: Representa un deporte.
- `TarjetaDeportesAdapter`: Adaptador para manejar la visualización de deportes en un RecyclerView.

## APIs y Endpoints

### Endpoints Disponibles

- **GET /api/deportes**: Obtiene la lista de deportes.
- **POST /api/pedidos**: Crea un nuevo pedido.

## Estructura de Datos

### Clases Principales

#### TarjetaDeportes

```kotlin
data class TarjetaDeportes(
    val nombre: String,
    val imagen: Int,
    val seleccionado: Boolean
)
