🚀 FastAPI - Primer Conexión
👨‍🎓 Alumno: Laureano ROel
📚 Práctica de clase: Primeros pasos con FastAPI, Alembic y SQLite

🧠 ¿Qué vas a encontrar en este proyecto?
🟢 Una app básica de FastAPI (main.py)

🗂️ Estructura modular organizada

🧪 Base de datos SQLite lista para usar

⚙️ Alembic configurado para el manejo de esquemas y migraciones

📦 Archivo requirements.txt para instalación rápida

⚙️ Requisitos
Python 3.10 o superior

Git (opcional, para clonar el repo)

🛠️ Instrucciones para levantar la app
1. Clonar el repositorio
bash
Copiar
Editar
git clone https://github.com/teotronic5438/fastapibackend.git
cd fastapibackend
2. Crear y activar el entorno virtual
bash
Copiar
Editar
# Crear entorno virtual
python -m venv env

# Activar entorno en Windows
.\env\Scripts\activate

# Activar entorno en Mac / Linux
source env/bin/activate
3. Instalar las dependencias
bash
Copiar
Editar
pip install -r requirements.txt
4. Ejecutar las migraciones de Alembic
bash
Copiar
Editar
alembic upgrade head
5. Levantar el servidor
bash
Copiar
Editar
uvicorn app.main:app --reload
🌐 Acceso a la API
Si todo salió bien, deberías ver en consola algo como esto:

nginx
Copiar
Editar
Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
📄 Documentación automática disponible en:

http://127.0.0.1:8000/docs
