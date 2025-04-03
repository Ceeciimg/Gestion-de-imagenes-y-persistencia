# Gestion-de-imagenes-y-persistencia

# Fundamentos de Computación en la Nube - UT3 Práctica 2

## Parte 1 - Nextcloud
Estoy configurando una nube privada con **Nextcloud**. Esta herramienta me permite ofrecer servicios como almacenamiento de archivos y gestión de calendarios. 

### Lo que hago:
- Descargo la versión 30.0.8 con Apache usando Docker.
- Creo un contenedor con estas características:
  - Lo ejecuto en segundo plano (modo demonio).
  - Configuro los puertos y vinculo un volumen recomendado para Nextcloud.
- Subo un archivo a la sección de documentos.
- Elimino el contenedor y lo recreo para comprobar que el archivo sigue disponible, asegurándome de probar la persistencia de datos.

---

## Parte 2 - Entorno de desarrollo con Python
Estoy configurando un entorno de desarrollo en **Python** utilizando Docker, donde puedo trabajar cómodamente con bibliotecas como **NumPy**.

### Lo que hago:
- Creo una carpeta en mi escritorio para usarla como espacio de trabajo.
- Configuro un contenedor que:
  - Ejecuta scripts de Python.
  - Vincula la carpeta del host al directorio de trabajo del contenedor.
  - Me permite instalar bibliotecas necesarias.
- Escribo un archivo Python para generar estadísticas y trabajar con matrices, realizando operaciones como suma, multiplicación y producto punto.
- Finalmente, ejecuto el archivo dentro del contenedor y verifico los resultados.

---
