# Proyecto Frontend Cafe Bot

Funciones del bot:

- [x] Bienvenida:
    - Da la bienvenida a los usuarios que entran al servidor de FrontendCafé por primera vez.
- [x] Recordatorios de eventos:
    - El bot envía recordatorios con cierta frecuencia antes del evento (para uso general).
    - Se pueden realizar recordatorios únicos con hora y fecha, o recordatorios semanales o mensuales (periódicos).
- [x] Generador de encuestas:
    - Permite generar encuestas, hacer votaciones y finalizarlas.
- [x] Busquedas web:
    - Permite buscar mediante palabras clave y mostrar los resultados encontrados.

## Instalación

```sh
git clone https://github.com/frontendcafe/matebot
cd matebot
python3 -m venv venv
pip install -r requirements.txt
```

Variables de entorno:
Estas variables pueden estar colocadas en un archivo `.env` dentro de la carpeta `matebot`.


## Inicio el bot:

```sh
python3 src/bot.py
```


[Licencia MIT](./LICENSE)
