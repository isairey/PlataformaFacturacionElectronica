<div align="center">

<img width="220" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Achille_a_Sciro2.JPG/220px-Achille_a_Sciro2.JPG" />

# 🇲🇽 Pirra SAT

### Plataforma de facturación electrónica CFDI 4.0 para México 🚀

<p align="center">
  <b>Pirra SAT</b> es un sistema moderno de facturación electrónica desarrollado para integrarse con el SAT de México, permitiendo emitir, administrar y validar comprobantes CFDI 4.0 de manera profesional y escalable.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Django-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/CFDI-4.0-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/SAT-México-006847?style=for-the-badge">
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

**Pirra SAT** es una plataforma backend enfocada en la emisión y administración de comprobantes fiscales digitales CFDI 4.0 compatibles con el SAT de México.

Inspirado en la historia mitológica de Aquiles oculto bajo el nombre de **Pirra**, este sistema busca ofrecer una solución robusta y moderna para la automatización fiscal empresarial.

El sistema permite:

- 🧾 Facturación electrónica CFDI
- 🏢 Gestión multiempresa
- 📄 Administración de comprobantes fiscales
- 💰 Control tributario
- 📊 Reportes administrativos
- 👥 Gestión de usuarios
- 🔐 Seguridad y autenticación
- 📦 Configuración fiscal SAT

El proyecto fue desarrollado para practicar:

- Desarrollo backend con Django
- Integración SAT México
- Arquitectura empresarial
- PostgreSQL
- Dockerización
- Automatización DevOps

---

# ✨ Características

## 🧾 Facturación electrónica CFDI

- ✅ CFDI 4.0
- ✅ Facturas electrónicas
- ✅ Notas de crédito
- ✅ Notas de débito
- ✅ Generación XML SAT
- ✅ Timbrado fiscal

---

## 🏢 Gestión empresarial

- 👥 Multiempresa
- 🏬 Administración de sucursales
- 📋 Configuración fiscal
- 🔐 Gestión de accesos

---

## 📊 Administración

- 📈 Dashboard administrativo
- 📄 Historial de comprobantes
- 💰 Reportes fiscales
- 📦 Gestión documental

---

## 🔒 Seguridad

- 🔑 Autenticación de usuarios
- 🛡️ Protección de endpoints
- 🔒 Configuración segura
- 👨‍💻 Roles y permisos

---

## 🐳 DevOps

- 🐳 Docker Compose
- ⚙️ Automatización con Ansible
- 📦 Virtualización con Vagrant
- 🚀 Deploy local y producción

---

# 🛠️ Tecnologías utilizadas

## 🌐 Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,django" />
</p>

- Python 3
- Django
- Django ORM
- APIs REST

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=postgresql,redis" />
</p>

- PostgreSQL
- Redis
- SQL

---

## 🎨 Frontend y herramientas

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,npm" />
</p>

- HTML5
- CSS3
- JavaScript
- NPM

---

## 🐳 DevOps

<p>
  <img src="https://skillicons.dev/icons?i=docker,git,github,ansible" />
</p>

- Docker
- Docker Compose
- Git
- GitHub
- Ansible
- Vagrant

---

# 📂 Estructura del proyecto

```bash
pirra-sat/
│
├── sat/
│
├── deploy/
│   ├── ansible/
│   └── vagrant/
│
├── pirra_web/
│   ├── settings/
│   ├── templates/
│   └── static/
│
├── requirements/
│
├── manage.py
│
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3
- PostgreSQL
- Redis
- Docker
- Node.js y NPM
- Virtualenv

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/usuario/pirra-sat.git
```

---

## 2️⃣ Crear entorno virtual

```bash
mkvirtualenv -p python3 pirra-sat
workon pirra-sat
```

---

## 3️⃣ Instalar dependencias Python

```bash
pip3 install -r requirements/dev.txt
```

---

## 4️⃣ Configurar variables de entorno

```bash
cp pirra_web/settings/dev.template.py pirra_web/settings/dev.py
```

---

## 5️⃣ Instalar dependencias NPM

```bash
npm install
```

---

## 6️⃣ Configurar base de datos

```bash
sudo -u postgres createdb pirra_sat
```

---

## 7️⃣ Ejecutar migraciones

```bash
python manage.py migrate
```

---

## 8️⃣ Crear superusuario

```bash
python manage.py createsuperuser
```

---

## 9️⃣ Registrar empresa SAT

```bash
python manage.py init_empresa [RFC] [EMPRESA]
```

---

## 🔟 Cargar configuraciones fiscales SAT

```bash
python manage.py loaddata sat/fixtures/initial_data.json
```

---

## 1️⃣1️⃣ Ejecutar servidor

```bash
python manage.py runserver
npm run watch
```

---

## 🌐 Acceder al sistema

Sistema:

```bash
http://localhost:8000
```

---

# 🐳 Docker

## 🚀 Ejecutar con Docker Compose

```bash
docker-compose up
```

---

# ⚙️ Deploy con Vagrant

## 📦 Requisitos

- Ansible
- VirtualBox
- Vagrant

---

## 🚀 Levantar entorno

```bash
cd deploy
vagrant up
```

---

## 🌐 Acceso

```bash
http://localhost:8080
```

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://images.unsplash.com/photo-1554224154-26032ffc0d07?q=80&w=1200&auto=format&fit=crop" />

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Django
- PostgreSQL
- CFDI 4.0
- Integración SAT
- Docker
- Redis
- DevOps
- Arquitectura backend

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📊 Dashboard avanzado
- ☁️ Deploy cloud
- 📱 Diseño responsive
- 🤖 Automatización fiscal
- 🔔 Notificaciones inteligentes
- 📄 Exportación avanzada de comprobantes

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

# 👨‍💻 Autor

<div align="center">

## Comunidad Pirra SAT

Desarrolladores enfocados en automatización fiscal, CFDI y plataformas empresariales modernas.

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto educativo y empresarial desarrollado para prácticas de integración SAT, automatización fiscal y sistemas modernos de facturación electrónica CFDI 4.0.

---

<div align="center">

### 🇲🇽 Pirra SAT — facturación electrónica CFDI como los dioses mandan ⚡

</div>
