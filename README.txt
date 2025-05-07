### CREAR ENVIROMENT 
python -m venv env

### entrar en enviroment (ENV)
.\env\Scripts\activate

### INSTALAR TODAS LAS LIBRERIAS NECESARIAS
pip install -r requirements.txt

### CORRER EL API 
uvicorn main:app --reload

### LINK PARA VER ITEMS en POSTMAN (GET)
http://127.0.0.1:8000/items/

### ESTRUCTURA PARA AGREGAR UN ZAPATO (POST) 
### en body >> raw >> JSON
{
    "name": "NOMBRE_DEL_ZAPATO",
    "description": "TEXTO_AQUI"
}




