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

El diagrama fue generado automáticamente con `eralchemy`.  
📁 Archivo generado: `diagram.png`

![Diagrama UML](diagram.png)

---

## ⚙️ Tecnologías usadas

- Python 3
- SQLAlchemy
- ERAlchemy
- pipenv
- Graphviz

---

## 🛠️ Cómo ejecutar el proyecto

1. Clona este repositorio:

```bash
git clone https://github.com/tu-usuario/modelo-instagram.git
cd modelo-instagram

