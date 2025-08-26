
###⚡ Backend - Proyecto Simposio

Este es el **backend** del sistema presentado en el Simposio, desarrollado con **FastAPI**.  
Se encarga de la lógica de negocio, validación de datos y exposición de servicios REST para el frontend (Vue.js).

## 🚀 Tecnologías
- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/) (ASGI server)
- [Pydantic](https://docs.pydantic.dev/) (validación de datos)
- [SQLAlchemy](https://www.sqlalchemy.org/) (ORM)
- Base de datos: PostgreSQL
- 
## 📌 Funcionalidades
- API REST con endpoints para CRUD.
- Validación de datos con Pydantic.
- Manejo de usuarios y autenticación (JWT o sesiones).
- Integración con base de datos.
- Documentación automática con **Swagger UI** y **ReDoc**.

## ⚙️ Instalación y uso
```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/proyecto-backend.git
cd proyecto-backend

# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # En Linux/Mac
venv\Scripts\activate     # En Windows

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar servidor
uvicorn main:app --reload
