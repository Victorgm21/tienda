# 🏪 Proyecto Tienda | Gestión de Productos con Django

## 📝 Descripción del Proyecto

Permite realizar las operaciones CRUD completas sobre los productos: **Crear**, **Listar**, **Actualizar** y **Eliminar**.

La aplicación ofrece una **interfaz web** completa utilizando plantillas HTML de Django. Todas las operaciones pueden ser probadas cómodamente desde el navegador

## 🛠️ Requisitos del Sistema

Para ejecutar este proyecto, necesitas tener instalados los siguientes componentes:

* **Python** (>3.10)
* **Django** (>4.0)

## 🚀 Instalación y Configuración

Sigue estos pasos para poner en marcha el proyecto:

### 1. Clonar el Repositorio

Abre tu terminal y clona el repositorio del proyecto.

```bash
git clone <url-del-repo>

cd tienda
```

### 2. Crear y Activar Entorno Virtual

Crear el entorno virtual:
python -m venv venv

Activar el entorno virtual en Windows:

```bash


```

Activar el entorno virtual en Windows:

```bash
venv\Scripts\activate
```


Activar el entorno virtual en Linux/macOS:

```bash
source venv/bin/activate
```

### 3. Instalar Dependencias

```bash
pip install -r requirements.txt
```

### 4. Aplicar Migraciones

```bash
python manage.py makemigrations

python manage.py migrate
```

### 5. Crear Superusuario (Opcional)

```bash
python manage.py createsuperuser
```

### 6. Ejecutar el Servidor de Desarrollo

```bash
python manage.py runserver
```