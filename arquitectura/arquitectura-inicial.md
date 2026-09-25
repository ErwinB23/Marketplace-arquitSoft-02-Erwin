# Arquitectura inicial del sistema

## Arquitectura en tres capas

La arquitectura inicial del marketplace se organiza en tres capas principales:

### 1. Capa de Presentación

Esta capa permite la interacción de los usuarios con el sistema.

**Elementos:**
- Aplicación Web
- API REST

### 2. Capa de Lógica de Negocio

Esta capa contiene las principales funcionalidades y reglas del sistema.

**Módulos:**
- Usuarios
- Sellers
- Catálogo
- Carrito
- Pedidos

### 3. Capa de Datos

Esta capa se encarga del almacenamiento de la información del sistema.

**Elemento:**
- Base de datos

## Organización de las capas

| Capa | Pregunta que responde |
|---|---|
| Presentación | ¿Cómo interactúa el usuario? |
| Lógica de negocio | ¿Qué hace el sistema? |
| Datos | ¿Dónde se almacena la información? |