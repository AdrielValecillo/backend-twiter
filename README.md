# FastAPI Microblog

Este es un proyecto de microblogging desarrollado con FastAPI. Proporciona funcionalidades de autenticación, gestión de usuarios y publicación de posts.

## Requisitos

- Python 3.8+
- FastAPI
- SQLAlchemy
- PyJWT
- Passlib

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/tu_usuario/tu_repositorio.git
    cd tu_repositorio
    ```

2. Crea y activa un entorno virtual:
    ```sh
    python -m venv env
    source env/bin/activate  # En Windows usa `env\Scripts\activate`
    ```

3. Instala las dependencias:
    ```sh
    pip install "fastapi[standard]" sqlalchemy pyjwt "passlib[bcrypt]"
    ```

4. Configura la base de datos:
    ```sh
    # Asegúrate de tener SQLite instalado o configura tu base de datos preferida en `app/database.py`
    ```

## Ejecución

Para ejecutar la aplicación en modo desarrollo:

```sh
uvicorn app.main:app --reload