# Proyecto de Animales

Este proyecto es una aplicación web simple que utiliza Flask para proporcionar información sobre diferentes animales y sus comportamientos.

## Estructura del Proyecto

- `src/models/`: Contiene las definiciones de las clases de los animales (`Gato`, `Perro`, `Huron`, `BoaConstrictor`).
- `src/routes/`: Contiene las rutas de la aplicación Flask.

## Instalación

1. Clona el repositorio:
    ```sh
    git clone <URL_DEL_REPOSITORIO>
    cd <NOMBRE_DEL_REPOSITORIO>
    ```

2. Crea un entorno virtual y actívalo:
    ```sh
    python -m venv venv
    source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
    ```

3. Instala las dependencias:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Ejecuta la aplicación Flask:
    ```sh
    export FLASK_APP=src/routes/animales.py  # En Windows usa `set FLASK_APP=src/routes/animales.py`
    flask run
    ```

2. Abre tu navegador y ve a `http://127.0.0.1:5000/como_hace/<animal>`, reemplazando `<animal>` con `gato`, `perro`, `huron` o `boa`.

## Ejemplos de Uso

- `http://127.0.0.1:5000/como_hace/gato`
- `http://127.0.0.1:5000/como_hace/perro`
- `http://127.0.0.1:5000/como_hace/huron`
- `http://127.0.0.1:5000/como_hace/boa`

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que te gustaría hacer.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.