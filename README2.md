# Back End



COMO INICIAR

Crear el entorno
pipenv shell

Instalar dependencias
pipenv install

Crear las migraciones
pipenv run init
pipenv run migrate (skip if you have not made changes to the models on the `./src/api/models.py`)
pipenv run upgrade

Ejecutar la API
pipenv run start
