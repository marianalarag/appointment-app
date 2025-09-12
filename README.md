# Proyecto Laravel: Appointment App

## Descripción del proyecto

Este proyecto es una aplicación desarrollada en Laravel para gestionar citas médicas (appointment system). Permite la creación de usuarios, gestión de citas, autenticación y control de accesos, con integración a base de datos MySQL y personalización básica de la interfaz.  

Está diseñado para servir como base de futuras funcionalidades y adaptaciones en entornos de producción o pruebas.

---

## Funcionalidades principales

- Registro e inicio de sesión de usuarios.
- Gestión de citas (crear, editar, eliminar).
- Control de roles y permisos.
- Gestión de tokens personales (para API o autenticación).
- Visualización de datos en tablas y reportes básicos.

---

## Configuraciones técnicas del proyecto

### 1. Base de datos

- Conexión a **MySQL** configurada en `.env`:
```env
DB_CONNECTION=mysql
DB_HOST=172.26.112.241    # IP del servidor WSL
DB_PORT=3306
DB_DATABASE=appointment_db
DB_USERNAME=laravel
DB_PASSWORD=tu_contraseña

# Proyecto Laravel: Appointment App

## 2. Idioma y zona horaria

- **Idioma por defecto:** español
```php
'locale' => 'es',
