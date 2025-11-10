# Awesome application

## 1. ¿Cómo ejecutar la aplicación localmente?

### 1.1. Crear el entorno virtual

```sh
  python -m venv .venv
```

### 1.2. Activar el entorno virtual

```sh
  source .venv/bin/activate
```

### 1.3. Actualizar pip

```sh
  pip install --upgrade pip
```

### 1.4. Instalar las dependencias

```sh
  pip install -r requirements.txt
```

### 1.5. Ejecutar las migraciones de base de datos

```sh
  python manage.py migrate
```

### 1.6. Ejecutar el servidor de aplicación

```sh
  python manage.py runserver
```
