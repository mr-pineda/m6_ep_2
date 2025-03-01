# Pagina demo de Hospital Nacional

## Contexto

En este proyecto, los estudiantes deberán implementar el consumo de una API para obtener y mostrar datos del sistema del hospital, como la información de doctores o servicios médicos.
Utilizando useEffect y useState, se espera que realicen peticiones asíncronas, gestionen el estado y manejen los errores de manera eficiente. Podrán utilizar Fetch API o Axios según su preferencia.

Trabajo práctico para desarrollar una página web de hospital que debe contener las siguientes páginas:

1. Vista Principal Home
2. Vista del About
3. Vista de Contact

## Cómo correr el proyecto:

1. Descargar el contenido de este repositorio en el computador. Puede ser clonando el repositorio o descargando el .zip:

   - **Clonar el repositorio**: Puede hacerlo con cualquier gestor de repositorios. Si tiene git instalado, puede abrir una terminal en algun diretorio y ejecutar:

   ```bash
   git clone url_de_este_repo
   ```

   - Si no tiene git instalado puede presionar el botón verde `<> Code` que está en esta página y seleccionar la opción `Download ZIP`.
     1. Descargue el archivo .zip en algun directorio conocido _(ej: Escritorio, Documentos, etc.)_.
     2. Descomprima el archivo .zip

2. Abrir una terminal denntro de la carpeta.
3. Para que pueda ser ejecutado primero se debe hacer la build de la aplicaicón y despues el despliegue:

   1. Ejecutar en la terminal `yarn build`
   2. Ejecutar en la terminal `yarn preview`

   OPCIONAL: Se puede ejecutar `yarn buildpreview` para ejecutar los 2 scipts.

4. Despues de ejecutar el **preview** se mostrará una dirección en la terminal para ver la applicación.

## TO-DO (Rúbrica):

1. Implementación de Almacenamiento Web (2 puntos)

   - [ ] Configura un sistema de almacenamiento para la PWA del hospital usando **LocalStorage** o **SessionStorage**:

     - [ ] Almacena datos de usuario o información importante para que persista incluso después de recargar la página.
     - [ ] Asegúrate de que el almacenamiento se realice de manera eficiente y que los datos almacenados puedan ser recuperados correctamente.

   **Tip**: Considera almacenar preferencias del usuario, configuración de la sesión, o cualquier dato que deba ser accesible en diferentes sesiones.

2. Implementación de IndexedDB (2 puntos)

   - [ ] Implementa una base de datos con IndexedDB o una biblioteca como PouchDB para manejar datos más complejos o a mayor escala:
     - [ ] Almacena en **IndexedDB** datos relevantes como información de citas, doctores o pacientes del hospital.
     - [ ] Asegúrate de que los datos sean almacenados y recuperados correctamente de **IndexedDB**.

   **Tip**: Usa **IndexedDB** cuando necesites manejar datos más complejos o voluminosos que no sean adecuados para **LocalStorage**.

3. Despliegue y Configuración del Service Worker Personalizado (1.5 puntos)

   - [x] Personaliza y despliega un **Service Worker** que gestione los archivos de caché y soporte el almacenamiento offline:
     - [ ] Asegúrate de que el **Service Worker** funcione adecuadamente para manejar la caché de los archivos y el almacenamiento en **LocalStorage** o **IndexedDB**.
     - [x] Verifica que la PWA esté desplegada correctamente y sea accesible offline.

4. Pruebas de Rendimiento con Lighthouse (1.5 puntos)

   - [ ] Ejecuta **Lighthouse** para validar el rendimiento de la PWA:
     - [ ] Verifica que la aplicación sea **instalable**, funcione **offline**, y tenga un **buen rendimiento** en términos de velocidad y accesibilidad.
     - [ ] Revisa el informe de Lighthouse y mejora los aspectos recomendados por la herramienta.

   **Tip**: Asegúrate de que la calificación de **Lighthouse** sea positiva, con un enfoque en rendimiento y accesibilidad.
