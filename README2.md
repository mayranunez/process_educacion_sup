## Paso1: Redirigete a la carpeta del proyecto

## Paso2: Cree el ambiente virtual
python -m venv myenv

## Paso3: Activar el entorno virtual
myenv\Scripts\activate

### Observacion: Si esta en MacOs o Linux debe usar:
source myenv/bin/activate

## Paso4: Instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso5: Luego descargar el csv mas reciente de la siguiente url:
https://datosabiertos.mineduc.cl/
titulados-en-educacion-superior/

## Paso6: ejecutar la aplicacion
python get_excel_resumen_es.py
