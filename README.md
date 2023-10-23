<!-- Documentación del Código -->

# 📚 Documentación del Código

Este documento proporciona una descripción detallada y el uso del código JavaScript que se encarga de filtrar y mostrar una lista de autos de acuerdo con varios criterios. El código incluye eventos, funciones y objetos para realizar búsquedas específicas.

## 📦 Estructura del Código

El código se divide en las siguientes secciones:

- Declaración de variables: Se inicializan las variables para los elementos del formulario y se crea un objeto llamado `datosBusqueda` para almacenar los filtros de búsqueda.

- Eventos: El código agrega eventos para detectar cambios en los campos del formulario, como marca, año, precio, puertas, transmisión y color.

- Funciones: Se definen varias funciones, incluyendo `mostrarAutos`, `limpiarHtml`, `llamarSelect` y varias funciones de filtrado, como `filtrarMarca`, `filtrarYear`, `filtrarMinimo`, `filtrarMaximo`, `filtrarPuertas`, `filtrarTransmision` y `filtrarColor`.

- Función `mostrarAutos`: Muestra una lista de autos en el resultado.

- Función `limpiarHtml`: Limpia el contenido anterior del resultado.

- Función `llamarSelect`: Genera las opciones del selector de años.

- Función `filtrarAuto`: Filtra autos en función de los criterios de búsqueda.

- Función `noResultado`: Muestra un mensaje de "No Hay Resultados" cuando no se encuentran coincidencias.

- Funciones de filtrado: Realizan la filtración de autos según diferentes criterios, como marca, año, precio, etc.

## 🚀 Uso

1. Ingresa tus criterios de búsqueda en el formulario. Puedes especificar la marca, el año, el precio mínimo y máximo, la cantidad de puertas, la transmisión y el color.

2. Con cada cambio en los campos del formulario, el código realizará la búsqueda en tiempo real.

3. Los autos que coincidan con los criterios se mostrarán en el resultado.

4. Si no se encuentran resultados, se mostrará un mensaje de "No Hay Resultados" y se eliminarán los resultados anteriores.

## 📄 Tecnologías Utilizadas

- HTML: La estructura del formulario y los elementos HTML.
- JavaScript: La lógica y funcionalidad del código.
- CSS (Clases Tailwind CSS): Estilos y diseño básico de la página.

## 📣 Contribuir

Si deseas contribuir a este código o mejorarlo, puedes seguir estos pasos:

1. Haz un fork del repositorio.

2. Crea una nueva rama con el nombre de tu característica o corrección: `git checkout -b mi-caracteristica`.

3. Realiza tus cambios y asegúrate de seguir las mejores prácticas de codificación.

4. Realiza un commit de tus cambios: `git commit -m 'Agrega mi característica'`.

5. Sube tus cambios a tu repositorio: `git push origin mi-caracteristica`.

6. Crea un Pull Request en este repositorio.

## 📄 Licencia

Este código está disponible bajo la Licencia MIT. Consulta el archivo `LICENSE` para obtener más detalles.

## ✉️ Contacto

Si tienes preguntas o sugerencias, puedes contactarme a través de [lucho_l.f@hotmail.com].

¡Gracias por utilizar este código! 🚀
