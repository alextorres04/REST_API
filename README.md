# 🌍 Travel REST API

Una API REST construida con **Python**, **Flask** y **SQLAlchemy** para gestionar destinos turísticos.  
Permite realizar operaciones CRUD (Create, Read, Update, Delete) sobre una base de datos SQLite.

---

## 🚀 Características
- Framework: **Flask**
- ORM: **SQLAlchemy**
- Base de datos: **SQLite** (`travel.db`)
- Endpoints para listar, crear, actualizar y eliminar destinos

---

## 📦 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/travel-api.git
   cd travel-api

2. Crea y activa un entorno virtual:

python -m venv api_env 
# Windows PowerShell 
.\api_env\Scripts\Activate 
# Linux/Mac source 
api_env/bin/activate

3. Instala las dependencias:
pip install -r requirements.txt

4. Ejecuta la aplicación:
python app.py

La API estará disponible en:
👉 http://127.0.0.1:5000/


## 📖 Endpoints

| Método | Endpoint              | Descripción                       |
|--------|-----------------------|-----------------------------------|
| GET    | `/`                   | Mensaje de bienvenida             |
| GET    | `/destinations`       | Lista todos los destinos          |
| GET    | `/destinations/<id>`  | Obtiene un destino por ID         |
| POST   | `/destinations`       | Crea un nuevo destino             |
| PUT    | `/destinations/<id>`  | Actualiza un destino existente    |
| DELETE | `/destinations/<id>`  | Elimina un destino                |


🔮Mejoras futuras
Implementar Flask-Migrate para migraciones de base de datos.

Añadir autenticación con JWT.

Desplegar en un servicio cloud (Heroku, Render, Railway, etc.).

Tests automatizados con Pytest.


## 📜 Licencia
Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.
