# Sistema-SS
Proyecto Ingeniería de Software

## Entorno virtual
Para este proyecto se utilizará **Python 3.12**, que es una versión más estable de Python y en el que muchas versiones de las 
librerías son compatibles entre sí.
Python 3.12 se puede descargar de la Microsoft Store:
https://apps.microsoft.com/detail/9NCVDN91XZQP?hl=neutral&gl=MX&ocid=pdpshare

### Instalación del entorno virtual
```bash
python -m venv .venv
```

### Acceder al entorno virtual en Windows
```bash
.venv\Scripts\activate.bat
```
o
```bash
.venv\Scripts\Activate.ps1
```

### Acceder al entorno virtual en Mac o Linux
```bash
source .venv/bin/activate
```

### Instalar las librerías necesarias (requirements.txt)
```bash
pip install -r requirements.txt
```

#### Verificar qué se instaló
```bash
pip list
```

### Usar y desactivar el entorno
```bash
deactivate
```

## Ver versión instalada de Python
```bash
python --version
```
## GIT IGNORE
Por cuestiones de seguridad se ocultan las siguientes cosas: 
 - La base de datos: Los datos de los usuarios NO deben ser visibles en la BD.
 - El correo y el token generado para enviar un e-mail para la recuperación de la contraseña: El token que se genera es un dato muy sensible y se tiene 
 que ocultar porque alguien más puede suplantar la identidad de nosotros, pudiendo enviar spam o un link sospechoso o peligroso.