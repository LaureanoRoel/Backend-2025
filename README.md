# 🚀 FastAPI - Primer Conexión

👨‍🎓 **Alumno:** Laureano Roel
📚 **Práctica de clase:** Primeros pasos con FastAPI, Alembic y SQLite

---

## 🧠 ¿Qué vas a encontrar en este proyecto?

- 🟢 Una app básica de **FastAPI** (`main.py`)
- 🗂️ Estructura modular organizada
- 🧪 Base de datos **SQLite** lista para usar
- ⚙️ **Alembic** configurado para el manejo de esquemas y migraciones
- 📦 Archivo `requirements.txt` para instalación rápida

---

## ⚙️ Requisitos

- Python 3.10 o superior
- Git (opcional, para clonar el repo)

---

## 🛠️ Instrucciones para levantar la app

### 1. Clonar el repositorio

```bash
git clone https://github.com/teotronic5438/fastapibackend.git
cd fastapibackend
# Crear entorno virtual
python -m venv env

# Activar entorno en Windows
.\env\Scripts\activate
### 1. Clonar el repositorio
# Creación del entorno virtual
python -m venv env

# En Windows
.\env\Scripts\activate

# En Mac / Linux
source env/bin/activate

** Crear y activar el entorno visual**
pip install -r requirements.txt
alembic upgrade head
uvicorn app.main:app --reload
