# blog-flaskr

### Ejecutar los siguientes comando en powershell

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned

py -3 -m venv venv

.\venv\Scripts\activate

pip install -e .

$env:FLASK_APP = "flaskr"

$env:FLASK_ENV = "development"

flask run

entrar a http://127.0.0.1:5000 y revisar
