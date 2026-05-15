<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/1046/1046857.png" />

# 🏠 Rental House Management System

### Plataforma web para administración de propiedades y rentas 🚀

<p align="center">
  <b>Rental House Management System</b> es una plataforma web desarrollada para la gestión de propiedades, arrendatarios, pagos y administración inmobiliaria desde un entorno moderno, práctico y escalable.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-Web%20Application-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Bootstrap-Responsive%20UI-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Project-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-vistas-del-sistema">Vistas</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Rental House Management System** es un sistema web desarrollado originalmente en 2018 para facilitar la administración de propiedades, habitaciones y contratos de renta.

El sistema fue diseñado inicialmente para:

- 🏢 Gestión administrativa inmobiliaria
- 👥 Control de inquilinos
- 💳 Gestión de pagos
- 📩 Comunicación mediante SMS
- 🧾 Administración documental
- 📊 Monitoreo de propiedades

Con el paso del tiempo, el proyecto evolucionó mejorando:

- 🔒 Seguridad
- ⚡ Rendimiento
- 🧠 Arquitectura interna
- 🌐 Estabilidad
- 📱 Compatibilidad móvil

Actualmente sirve como una excelente base educativa para aprender:

- PHP clásico
- Programación orientada a objetos
- Arquitectura web
- Integración con MySQL
- Sistemas administrativos inmobiliarios

---

# ✨ Características

## 🏠 Gestión inmobiliaria

- 🏢 Registro de propiedades
- 🛏️ Gestión de habitaciones
- 📋 Listado de inmuebles
- 📍 Administración de unidades
- 📸 Visualización de propiedades

---

## 👥 Gestión de inquilinos

- 👤 Registro de arrendatarios
- 📄 Contratos de renta
- 📅 Historial de ocupación
- 📞 Información de contacto
- 📋 Administración de perfiles

---

## 💳 Gestión financiera

- 💰 Control de pagos
- 🧾 Generación de recibos
- 📊 Seguimiento financiero
- ⚠️ Alertas administrativas
- 📈 Reportes del sistema

---

## 📩 Sistema de notificaciones

- 📲 Integración SMS
- 🔔 Alertas automáticas
- 📧 Comunicación administrativa
- 📨 Notificaciones de pagos
- 📢 Herramientas de marketing

---

## 🌐 Plataforma web

- 📱 Responsive Design
- 🎨 Interfaz administrativa
- 📰 Blog integrado
- 🔐 Panel de administración
- ⚡ Navegación optimizada

---

# 🛠️ Tecnologías utilizadas

## 🌐 Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- Programación imperativa
- Programación orientada a objetos
- Arquitectura web tradicional

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- PHPMyAdmin
- Persistencia relacional
- Gestión de registros

---

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap" />
</p>

- HTML5
- CSS3
- JavaScript
- Bootstrap
- W3.CSS
- LESS
- Font Awesome

---

## ⚙️ Librerías JavaScript

- jQuery
- FancyBox
- AJAX
- Modernizr
- Bootstrap JS

---

# 📂 Estructura del proyecto

```bash
PlataformaGestionInmoviliaria/
│
├── admin/
│   ├── functions/
│   └── dashboard/
│
├── database/
│   └── Company.sql
│
├── assets/
│
├── blog/
│
├── index.php
├── README.md
│
└── screenshots/
```

---

# ⚡ Instalación

## 📋 Requisitos

- XAMPP / WAMP
- PHP 7+
- MySQL
- Apache Server
- Navegador web

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaGestionInmoviliaria.git
```

---

## 2️⃣ Crear base de datos

Crear una base de datos llamada:

```bash
Company
```

---

## 3️⃣ Importar SQL

Importar el archivo:

```bash
database/Company.sql
```

usando PHPMyAdmin.

---

## 4️⃣ Configurar conexión

Editar el archivo:

```bash
admin/functions/db.php
```

Configurar:

```php
$host= 'YourHost';
$user='YourDatabaseUserName';
$usrpassword='YourDBPassword';
$database='YourDBName';
```

---

## 5️⃣ Configurar SMS

Actualizar:

```php
$sms_apiKey = "YourAPIKey";
$sms_partnerID = "YourPartinerID";
$sms_shortcode = "TextSMS";
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/
```

Panel administrador:

```bash
http://localhost/admin/
```

---

# 🔑 Credenciales de prueba

## 👨‍💼 Panel administrador

```txt
Usuario: obed@example.com
Contraseña: mimi
```

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/dashboard_clear.png" />

</div>

---

# 🖥️ Vistas del sistema

## 📊 Dashboard administrativo

<div align="center">

<img width="1000" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/dashboard-2.png" />

</div>

---

## 🏠 Listado de propiedades

<div align="center">

<img width="1000" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/houses%20listing.png" />

</div>

---

## 👥 Registro de inquilinos

<div align="center">

<img width="1000" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/form-admit%20tenant.png" />

</div>

---

## 📰 Blog integrado

<div align="center">

<img width="1000" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/Blog.png" />

</div>

---

# 📱 Vista móvil

## 📲 Dashboard móvil

<div align="center">

<img width="300" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/phone_dashboard.png" />

</div>

---

## 👤 Gestión móvil de inquilinos

<div align="center">

<img width="300" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/phone_tenants.png" />

</div>

---

## 🔔 SMS y notificaciones

<div align="center">

<img width="300" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/Screenshot_2021-06-09-09-02-47.png" />

<img width="300" src="https://github.com/ObedNyakundi/Rental-house-management-system/blob/main/Screenshot_2021-06-09-09-03-02.png" />

</div>

---

# 🚀 Nueva versión Laravel

El proyecto cuenta con una versión moderna desarrollada en Laravel con mejoras importantes:

## ✨ Nuevas funciones

- 🏢 Gestión avanzada de apartamentos
- 🛏️ Unidades de renta
- 🧾 Facturación automatizada
- 💳 Pagos integrados
- 📄 Recibos imprimibles
- 👨‍💼 Roles administrativos
- 📲 Marketing SMS masivo
- 🎨 Personalización visual

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y práctica

- PHP clásico
- Arquitectura MVC
- Gestión inmobiliaria
- Integración SMS
- MySQL
- Administración web
- Sistemas empresariales




---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Créditos

<div align="center">

## Proyecto desarrollado por Isai Reyes

Sistema administrativo inmobiliario 🏢

</div>

---



# 📜 Licencia

Proyecto open source utilizado con fines educativos, administrativos y de aprendizaje en tecnologías web PHP.

---

<div align="center">

### 🏠 Rental House Management System — administración inmobiliaria moderna 🚀

</div>
