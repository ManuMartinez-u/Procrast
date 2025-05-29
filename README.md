🧠 ProcrastV1
ProcrastV1 es una aplicación web desarrollada con Python 3 y Flask, diseñada para ayudarte a gestionar tus tareas de forma sencilla. Con ella puedes registrar usuarios, iniciar sesión, añadir tareas, marcarlas como completadas y visualizarlas mediante filtros. Ideal como herramienta de productividad o como proyecto académico.

🚀 Tecnologías Utilizadas
Lenguaje: Python 3.x

Framework: Flask

Base de Datos: SQLite

Frontend: HTML, CSS, Bootstrap

Control de versiones: Git + GitHub

🧩 Módulos Principales
✅ Módulo de Gestión
Registro de usuarios

Inicio de sesión y cierre de sesión

Gestión de tareas (crear, marcar completada, eliminar)

🔍 Módulo de Visualización y Consulta
Listado de tareas por usuario

Filtros por estado de la tarea (completadas / pendientes)

Búsqueda por nombre de tarea

🛠 Instalación y Ejecución
1. Clona el repositorio
bash
Copiar
Editar
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
2. Crea y activa un entorno virtual (opcional pero recomendado)
bash
Copiar
Editar
python -m venv venv
venv\Scripts\activate  # En Windows
# o
source venv/bin/activate  # En Linux/macOS
3. Instala las dependencias
bash
Copiar
Editar
pip install -r requirements.txt
4. Ejecuta la aplicación
bash
Copiar
Editar
python app.py
La app estará disponible en: http://127.0.0.1:5000/

⚙️ Variables de Entorno
Puedes crear un archivo .env para definir tu clave secreta:

env
Copiar
Editar
SECRET_KEY=tu_clave_secreta
O bien configurarla directamente en el archivo app.py.

🗃 Estructura del Proyecto
cpp
Copiar
Editar
├── app.py
├── models.py
├── templates/
│   ├── login.html
│   ├── register.html
│   └── index.html
├── static/
│   └── (archivos CSS, JS, etc.)
├── requirements.txt
└── README.md
📽 Video de Demostración
📎 Incluye aquí el enlace a YouTube o el archivo del video en el repositorio o drive compartido.

📌 Notas
Proyecto creado como parte de una entrega académica.

Puede adaptarse fácilmente a otros contextos de productividad o ampliarse con nuevas funcionalidades