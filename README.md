# Crear Proyecto JS

Este script en Bash permite crear una estructura básica de archivos para proyectos de **Vanilla JavaScript** de manera rápida y sencilla.

## Características

- Crea una estructura de directorios organizada.
- Incluye archivos básicos para comenzar el desarrollo.
- Genera un archivo `index.html` con una plantilla básica.
- Soporte para pruebas en un directorio separado.

## Estructura de Archivos

Al ejecutar el script, se creará la siguiente estructura de archivos:

```
<nombre_del_proyecto>/
├── dist/
├── src/
│   ├── index.html
│   └── js/
│       └── app.js
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   └── img/
└── tests/
    └── test_app.js
```

## Requisitos

- Linux (o un entorno compatible con Bash).
- Permisos para ejecutar scripts.

## Instalación

1. **Clona el repositorio:**

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. **Navega al directorio del repositorio:**

   ```bash
   cd <nombre_del_repositorio>
   ```

3. **Haz que el script sea ejecutable:**

   ```bash
   chmod +x crear_proyecto_js
   ```

4. **(Opcional) Mueve el script a un directorio en tu PATH:**

   ```bash
   mv crear_proyecto_js ~/bin/crear_proyecto_js
   ```

   Asegúrate de que `~/bin` esté en tu `PATH` para poder ejecutar el script desde cualquier ubicación.

## Uso

1. **Ejecuta el script:**

   ```bash
   create-project-js
   ```

2. **Ingresa el nombre del proyecto** cuando se te solicite.

3. **Verifica la estructura de archivos** creada en el directorio actual.

## Contribuciones

Si deseas contribuir, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz un commit (`git commit -m 'Agrega nueva funcionalidad'`).
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

## Contacto

Para cualquier consulta o comentario, puedes contactarme a través de [tu_correo@example.com](mailto:tu_correo@example.com).
