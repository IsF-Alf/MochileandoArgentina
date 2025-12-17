🧭 Mochileando Argentina

"Mochileando Argentina" es una aplicación web desarrollada con  Python 3.11  y  Django , pensada como un blog colaborativo de viajeros que recorren Argentina y comparten sus experiencias, recomendaciones y destinos.

El proyecto fue desarrollado de forma integral en Python, incluyendo  backend y frontend , utilizando Django Templates y  Tailwind CSS  para el diseño.

🌐  Sitio en producción:   
https://mochileandoargentina.pythonanywhere.com/

🎥  Video demo:   
https://youtu.be/n7NPHk_m_dk

📦  Repositorio:   
https://github.com/IsF-Alf/MochileandoArgentina

---

📌 Objetivo del proyecto

Este README tiene como objetivo:

- 📖 Documentar el proyecto para mantenimiento futuro  
- 👥 Facilitar la colaboración de otros desarrolladores  
- 💼 Servir como proyecto de portfolio para recruiters  
- 🚀 Proveer instrucciones claras de despliegue y ejecución  

---

🌎 Descripción funcional

La plataforma permite:

### Usuarios no registrados
- Navegar libremente por el sitio
- Ver posteos de otros viajeros
- Explorar categorías y contenidos

### Usuarios registrados
- Crear nuevos posteos
- Editar y eliminar sus propios posteos
- Gestionar su perfil de usuario

### Administrador
- Crear, editar y eliminar categorías
- Crear, editar y eliminar posteos de cualquier usuario
- Moderar el contenido desde el panel de administración de Django

---

🛠️ Tecnologías utilizadas

- 🐍  Python 3.11 
- 🌐  Django 
- 🎨  Tailwind CSS 
- 🗃️  SQLite3  (por defecto)
- 🚀  PythonAnywhere  (despliegue)
- 🔐 Autenticación integrada de Django

---

📂 Estructura del proyecto

```

MochileandoArgentina/
│
├── blog/                   # Aplicación principal
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── static/
│
├── tools/                  # Scripts auxiliares
├── manage.py
├── requirements.txt        # Dependencias
├── .env.example            # Variables de entorno de ejemplo
├── .gitignore
└── README.md

````

---

⚙️ Instalación y ejecución local

> Requiere  Python 3.11 o superior 

1️⃣ Clonar el repositorio

```bash
git clone https://github.com/IsF-Alf/MochileandoArgentina.git
cd MochileandoArgentina
````

2️⃣ Crear y activar entorno virtual

```bash
python -m venv venv
```

 Linux / macOS 

```bash
source venv/bin/activate
```

 Windows 

```bash
venv\Scripts\activate
```

3️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

4️⃣ Configurar variables de entorno

Copiar el archivo `.env.example` y renombrarlo a `.env`, luego completar los valores necesarios:

```env
SECRET_KEY=django-insecure-n)jqf&-%1u0rv&@5q2*%3^6n!-gal@z6dcn@ntb8)y(&)n$
DEBUG=True
```

5️⃣ Aplicar migraciones

```bash
python manage.py migrate
```

6️⃣ Crear superusuario (opcional)

```bash
python manage.py createsuperuser
```

7️⃣ Ejecutar el servidor

```bash
python manage.py runserver
```

Abrir en el navegador:

```
http://127.0.0.1:8000/
```

---

🚀 Despliegue

El proyecto se encuentra desplegado en  PythonAnywhere , utilizando:

* Entorno virtual
* Configuración WSGI
* Variables de entorno
* Base de datos SQLite

👉 Sitio en producción:
[https://mochileandoargentina.pythonanywhere.com/](https://mochileandoargentina.pythonanywhere.com/)

---

🤝 Contribuciones

Las contribuciones son bienvenidas.

Pasos sugeridos:

1. Fork del repositorio
2. Crear una nueva rama

   ```bash
   git checkout -b feature/nueva-feature
   ```
3. Commit de los cambios

   ```bash
   git commit -m "Agrega nueva feature"
   ```
4. Push a la rama

   ```bash
   git push origin feature/nueva-feature
   ```
5. Abrir un Pull Request

---

📄 Licencia

Proyecto de uso educativo y demostrativo.

⭐ Si este proyecto te resulta interesante o útil, no dudes en darle una estrella al repositorio.

