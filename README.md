# Convertir PDF a JPG con Python

## Pasos

1. **Descargar e instalar Python:** Descarga Python desde https://www.python.org/downloads/, ejecuta el instalador, marca la casilla **"Add Python to PATH"** e instálalo. Luego verifica en la terminal con `python --version` y `pip --version`.

2. **Instalar las librerías necesarias:** Abre una terminal en la carpeta del proyecto y ejecuta `pip install pdf2image Pillow`. En Windows, `pdf2image` también necesita **Poppler**: descárgalo desde https://github.com/oschwartz10612/poppler-windows/releases/, descomprímelo (por ejemplo en `C:\poppler`) y agrega la carpeta `bin` al PATH de Windows; si prefieres no modificar el PATH, indica la ruta en el código con `poppler_path=r"C:\poppler\Library\bin"`.

3. **Ejecutar el código:** Coloca tu archivo PDF en la carpeta del proyecto y ejecuta en la terminal `python nombre_de_tu_script.py`, cambiando `nombre_de_tu_script.py` por el nombre real de tu archivo Python.
