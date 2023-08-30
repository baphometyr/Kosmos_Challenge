# Desafío Kosmos: Extracción de Entidades Nombradas con API Flask

Este repositorio contiene una solución para el desafío técnico propuesto por Kosmos. El objetivo del desafío es crear una API Flask que tome una lista de oraciones y retorne las entidades nombradas detectadas en cada oración. El desafío se implementó utilizando Flask y se probaron las funcionalidades con Postman.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```
   git clone https://github.com/baphometyr/Kosmos_Challenge.git
   ```

2. Crea un entorno virtual (opcional pero recomendado):

   ```
   python -m venv venv
   ```

3. Activa el entorno virtual:

   - En Windows:

     ```
     venv\Scripts\activate
     ```

   - En macOS y Linux:

     ```
     source venv/bin/activate
     ```

4. Instala las dependencias:

   ```
   pip install -r requirements.txt
   ```

## Uso

1. Ejecuta el notebook jupyer (por comodidad se realizo de esta manera, lo recomendable es pasarlo a un script llamado app.py y ejecutar lo siguiente)

   ```
   python app.py
   ```

2. Para pruebas abre Postman y crea una solicitud POST a la URL `http://localhost:5000/`.

3. En el cuerpo de la solicitud, agrega una lista de oraciones en formato JSON:

   ```json
   {
     "oraciones": [
     "Apple está buscando comprar una startup del Reino Unido por mil millones de dólares.",
     "San Francisco considera prohibir los robots de entrega en la acera."
     ]
   }

   ```

4. Envía la solicitud y obtén las entidades nombradas detectadas en cada oración.
