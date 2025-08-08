# 📸 Modelo de Datos - Instagram

Este proyecto modela la estructura de datos de una aplicación tipo Instagram, usando **SQLAlchemy** para definir las relaciones entre los usuarios, publicaciones, comentarios, likes y seguidores.  

Incluye la generación automática de un **diagrama UML** para visualizar las relaciones entre las entidades.

---

## 🧱 Tablas del modelo

- **User**: Registro de usuarios (username, email, password, fecha de creación).
- **Post**: Publicaciones realizadas por los usuarios (imagen, caption, fecha).
- **Comment**: Comentarios asociados a publicaciones.
- **Like**: Likes que los usuarios hacen en los posts.
- **Follower**: Relación de seguimiento entre usuarios (quién sigue a quién).

---

## 📷 Diagrama UML generado

Diagrama generado desde el código:  
![Diagrama UML generado](diagram.png)

Vista del entorno en VS Code mostrando el diagrama abierto:  
![VS Code con diagrama](visualstudio-workspace.png)

Repositorio completo disponible en:  
🔗 https://github.com/alejandrabarcena/flask-rest-hello

---

## ⚙️ Tecnologías usadas

- Python 3
- SQLAlchemy
- ERAlchemy
- pipenv
- Graphviz


## 🛠️ Cómo ejecutar el proyecto

1. Clona este repositorio:

```bash
git clone https://github.com/alejandrabarcena/flask-rest-hello.git
cd flask-rest-hello


Instala las dependencias en un entorno virtual con pipenv:

bash
Copiar
Editar
pipenv install
pipenv shell
Genera el diagrama UML desde el archivo src/models.py:

bash
Copiar
Editar
pipenv run python render.py
El archivo diagram.png se generará automáticamente en la raíz del proyecto.

✅ Resultado final
Este proyecto representa la base de datos relacional de una red social estilo Instagram, con todas las relaciones correctamente modeladas, visualizadas y documentadas.

🧠 Autor
Alejandra Bárcena
💻 Bootcamp Full Stack Developer
🐾 Con amor, desde el mundo de Patsy

