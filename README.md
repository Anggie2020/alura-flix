# Alura Flix 🎥

**Alura Flix** es una aplicación web desarrollada como parte de un reto frontend utilizando **React**, **HTML**, **CSS**, y un servidor mock proporcionado por **json-server**. Este sistema permite gestionar una lista de videos, organizados por categorías, con opciones para crear, editar y eliminar videos.

## 🛠️ Tecnologías utilizadas

- **React**: Para la creación de componentes dinámicos y la gestión del estado.
- **HTML y CSS**: Para el diseño y la estructura de la interfaz de usuario.
- **json-server**: Para simular un servidor backend y almacenar los datos de los videos. 
  - Servidor utilizado: [My JSON Server](https://my-json-server.typicode.com/Anggie2020/alura-flix).

---

## ✨ Funcionalidades

1. **Gestión de videos:**
   - Crear nuevos videos con título, descripción, URL y categoría asignada.
   - Listar videos por categoría.
   - Editar la información de un video existente.
   - Eliminar un video de la lista.

2. **Categorías dinámicas:**
   - Los videos se agrupan automáticamente según la categoría asignada.

3. **Persistencia de datos:**
   - Los datos de los videos y categorías se manejan a través del servidor mock proporcionado por `json-server`.

---

## 🚀 Instalación y configuración

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tuusuario/alura-flix.git
   cd alura-flix
   ```

2. **Instalar las dependencias:**
   Asegúrate de tener Node.js instalado y ejecuta:
   ```bash
   npm install
   ```

3. **Ejecutar el servidor mock:**
   El proyecto utiliza el servidor en línea de `json-server`. No es necesario instalar nada adicional, ya que los datos están alojados en [My JSON Server](https://my-json-server.typicode.com/Anggie2020/alura-flix).

4. **Iniciar la aplicación:**
   ```bash
   npm start
   ```
---

## 📌 Notas importantes

- **Servidor Mock:** La URL del servidor `https://my-json-server.typicode.com/Anggie2020/alura-flix` contiene los datos de ejemplo utilizados para probar la funcionalidad.
- **Personalización:** Si deseas probar con datos personalizados, puedes crear un archivo `db.json` y configurarlo para usar un servidor local con `json-server`.

---