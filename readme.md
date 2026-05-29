# 🎬 Movies Django

Aplicación web desarrollada con Django para la gestión y visualización de un catálogo de películas.

## 📖 Descripción

Movies Django es una aplicación web que permite visualizar un listado de películas almacenadas en una base de datos y consultar la información detallada de cada una de ellas.

El proyecto fue desarrollado utilizando Django siguiendo el patrón MVT (Model - View - Template), implementando modelos, vistas, rutas y plantillas HTML para la presentación de la información.

## 🚀 Funcionalidades

* Visualización de catálogo de películas.
* Página de detalle para cada película.
* Gestión de películas mediante Django Admin.
* Almacenamiento de información en base de datos.
* Carga y visualización de imágenes de películas.
* Navegación entre listado y detalle.

## 🛠️ Tecnologías Utilizadas

* Python 3
* Django 4.2
* HTML5
* CSS3
* SQLite / PostgreSQL
* Pillow

## 📂 Estructura del Proyecto

```text
movies-django/
│
├── examen2/
├── movies/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│
├── manage.py
├── requirements.txt
└── README.md
```

## ⚙️ Instalación

### Clonar repositorio

```bash
git clone https://github.com/Sebas95So/movies-django.git
cd movies-django
```

### Crear entorno virtual

Linux / Mac:

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

### Ejecutar migraciones

```bash
python manage.py migrate
```

### Iniciar servidor

```bash
python manage.py runserver
```

La aplicación estará disponible en:

```text
http://127.0.0.1:8000/
```

## 📸 Capturas

Agregar aquí capturas de pantalla de:

* Página principal.
* Detalle de película.
* Panel de administración.

## 🔮 Mejoras Futuras

* Búsqueda de películas.
* Filtros por género.
* Paginación.
* Sistema de usuarios.
* API REST con Django REST Framework.
* Diseño responsive con Bootstrap.

## 👨‍💻 Autor

**Sebastian Salazar Ramirez**

QA Tester | Analista Funcional | Python Developer

LinkedIn:
https://www.linkedin.com/in/sebas95so

GitHub:
https://github.com/Sebas95So
