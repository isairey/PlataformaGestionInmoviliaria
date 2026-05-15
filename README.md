<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3135/3135768.png" />

# 🏢 MicroRealEstate MX

### Plataforma de gestión inmobiliaria y rentas 🚀

<p align="center">
  <b>MicroRealEstate MX</b> es una plataforma open source diseñada para la administración de propiedades, inquilinos, contratos y pagos de renta desde un sistema centralizado, moderno y escalable.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RealEstate-Management-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Platform-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**MicroRealEstate MX** es un sistema de administración inmobiliaria enfocado en propietarios, administradores y empresas de bienes raíces.

La plataforma permite:

- 🏢 Gestión de propiedades
- 👥 Administración de inquilinos
- 📄 Creación de contratos
- 💳 Seguimiento de pagos
- 📧 Envío de notificaciones
- 📑 Generación de documentos
- 🤝 Colaboración entre administradores
- 📊 Control de rentas y finanzas

El proyecto fue desarrollado para practicar:

- Arquitectura Full Stack
- Dockerización
- Gestión inmobiliaria
- Bases de datos NoSQL
- Automatización documental
- Aplicaciones escalables

---

# ✨ Características

## 🏢 Gestión de propiedades

- 🏠 Registro de propiedades
- 📋 Información detallada
- 📍 Administración de ubicaciones
- 📸 Gestión de imágenes
- 🧾 Historial de propiedades

---

## 👥 Gestión de inquilinos

- 👤 Registro de arrendatarios
- 📄 Información contractual
- 📧 Datos de contacto
- 📋 Historial de pagos
- 🔔 Notificaciones automáticas

---

## 💳 Gestión de pagos

- 💰 Control de rentas
- 📅 Seguimiento de pagos
- ⚠️ Alertas de adeudos
- 🧾 Recibos digitales
- 📊 Reportes financieros

---

## 📄 Documentos y contratos

- 📝 Plantillas de contratos
- 📑 Generación automática
- 📧 Envío por correo
- 🖨️ Exportación PDF
- 📂 Almacenamiento documental

---

## 🤝 Colaboración

- 👨‍💼 Gestión de miembros
- 🔐 Roles y permisos
- 🏢 Equipos inmobiliarios
- 📊 Coordinación administrativa
- 🌐 Multiusuario

---

# 🛠️ Tecnologías utilizadas

## 🌐 Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express" />
</p>

- Node.js
- Express
- APIs REST
- Arquitectura modular

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mongodb" />
</p>

- MongoDB
- NoSQL
- Gestión documental
- Persistencia distribuida

---

## 🐳 DevOps

<p>
  <img src="https://skillicons.dev/icons?i=docker,git,github" />
</p>

- Docker
- Docker Compose
- Git
- GitHub

---

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- HTML5
- CSS3
- JavaScript
- Responsive Design

---

# 📂 Estructura del proyecto

```bash
PlataformaGestionInmoviliaria/
│
├── backend/
│
├── frontend/
│
├── documentation/
│   ├── pictures/
│   └── DEVELOPER.md
│
├── docker-compose.yml
├── .env
│
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Docker
- Docker Compose
- Git
- Node.js (opcional para desarrollo)

---

# 🚀 Configuración del proyecto

## 1️⃣ Crear directorio

```bash
mkdir mre
cd mre
```

---

## 2️⃣ Descargar archivos

```bash
curl https://raw.githubusercontent.com/isairey/PlataformaGestionInmoviliaria/main/docker-compose.yml > docker-compose.yml

curl https://raw.githubusercontent.com/isairey/PlataformaGestionInmoviliaria/main/.env.domain > .env
```

---

## 3️⃣ Configurar variables

Editar el archivo:

```bash
.env
```

Configurar:

- Tokens
- Secrets
- Mongo URL
- APP_DOMAIN
- APP_PORT

---

# 🐳 Ejecutar con Docker

## 🌐 Localhost

```bash
APP_PORT=8080 docker compose --profile local up
```

Aplicación disponible en:

```bash
http://localhost:8080/landlord
http://localhost:8080/tenant
```

---

## 🌍 Configuración con IP

```bash
sudo APP_DOMAIN=x.x.x.x docker compose up
```

---

## 🔒 Configuración HTTPS

```bash
sudo APP_DOMAIN=app.example.com APP_PROTOCOL=https docker compose up
```

---

# 💾 Backup y restauración

## 📦 Backup

```bash
docker compose run mongo /usr/bin/mongodump --uri=mongodb://mongo/mredb --gzip --archive=./backup/mredb-$(date +%F_%T).dump
```

---

## ♻️ Restaurar backup

```bash
docker compose run mongo /usr/bin/mongorestore --uri=mongodb://mongo/mredb --drop --gzip --archive=./backup/mredb-XXXX.dump
```

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://images.unsplash.com/photo-1560518883-ce09059eeffa?q=80&w=1200&auto=format&fit=crop" />

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Docker
- MongoDB
- Gestión inmobiliaria
- Arquitectura escalable
- APIs REST
- Sistemas multiusuario
- Administración financiera

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- 🤖 Automatización inteligente
- 📊 Dashboard avanzado
- ☁️ Integración cloud
- 🔔 Notificaciones push
- 💳 Integración bancaria
- 📑 Firma electrónica

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

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por la creación de plataformas modernas, sistemas administrativos, aplicaciones Full Stack y soluciones escalables 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT para fines educativos, empresariales y de administración inmobiliaria moderna.

---

<div align="center">

### 🏢 MicroRealEstate MX — administración inteligente de propiedades y rentas 🚀

</div>
