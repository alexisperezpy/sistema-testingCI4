# Sistema Testing CI4

Este es un sistema de gestión y pruebas desarrollado con el framework **CodeIgniter 4**, enfocado en la eficiencia y escalabilidad. El test se realiza para evaluar la efecitividad, velocidad y capacidad de escalmiento del framework para el futuro desarrollo del Sistema Totum360 (para gestión de normas ISO)

## 🚀 Tecnologías Utilizadas

* **PHP:** 8.3+
* **Framework:** CodeIgniter 4.7
* **Base de Datos:** MariaDB
* **Frontend:** [ Bootstrap, PHP]

## 🛠️ Instalación y Configuración

Sigue estos pasos para montar el entorno de desarrollo local:

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com
   cd sistema-testingCI4
   ```
2. **Instalar dependencias:**

   ```bash
   composer install
   ```
3. **Configurar variables de entorno:**

   * Renombra el archivo `env` a `.env`:
     ```bash
     cp env .env
     ```
   * Abre el archivo `.env` y configura la base de datos y la URL:
     ```env
     database.default.hostname = localhost
     database.default.database = nombre_tu_bd
     database.default.username = root
     database.default.password = tu_password
     database.default.DBDriver = MySQLi
     app.baseURL = 'http://localhost:8080/'
     ```
4. **Ejecutar Migraciones (si aplica):**

   ```bash
   php spark migrate
   ```
5. **Iniciar Servidor:**

   ```bash
   php spark serve
   ```

## 📂 Estructura del Proyecto

* `/app`: Lógica central del sistema (Modelos, Vistas, Controladores).
* `/public`: Punto de entrada del servidor web.
* `/writable`: Almacenamiento de logs y archivos temporales.

## ✒️ Autor

* **Alexis Perez** - *Desarrollador Principal*
