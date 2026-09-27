# Lenguaje de Marcas — UD1

## Concepto de los lenguajes de marcas

### ¿Qué es un lenguaje de marcas?

Un lenguaje de marcas es un sistema que permite **organizar y estructurar información utilizando etiquetas o marcas**. Estas marcas indican cómo se debe interpretar, organizar o presentar cada parte del contenido.

Gracias a este tipo de lenguajes, es posible estructurar documentos de una manera que facilite tanto su lectura como su procesamiento por parte de diferentes programas.

### Principales tipos de lenguajes de marcas

Los lenguajes de marcas pueden utilizarse con diferentes objetivos dependiendo de la forma en la que se quiera trabajar con la información.

| **Tipo**                                | **Finalidad**                                                                                                      | **Ejemplos**             |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------ |
| **Lenguajes de presentación**           | Se utilizan principalmente para definir cómo se muestra y se presenta la información al usuario.                   | **HTML, CSS**            |
| **Lenguajes descriptivos**              | Permiten representar, organizar y facilitar el intercambio de información entre diferentes sistemas.               | **XML, JSON**            |
| **Lenguajes para documentar proyectos** | Están orientados a crear documentación de manera sencilla y estructurada, especialmente en proyectos informáticos. | **Markdown (MD), LaTeX** |

---

## Instalación y configuración del entorno de trabajo

Para trabajar con lenguajes de marcas es necesario disponer de un entorno adecuado que permita escribir, editar y comprobar los documentos creados.

### 1. Instalación de Visual Studio Code

En primer lugar, se debe instalar **Visual Studio Code**, un editor de código que permite trabajar cómodamente con diferentes lenguajes y archivos.

[Descargar Visual Studio Code](https://code.visualstudio.com/)

### 2. Instalación de extensiones

Una vez instalado Visual Studio Code, se recomienda añadir diferentes extensiones que faciliten el trabajo con los distintos lenguajes de marcas.

Las extensiones utilizadas son:

* **HTML CSS Support:** ayuda a escribir código HTML y CSS proporcionando funciones de autocompletado.
* **Live Preview:** permite visualizar directamente el resultado de un documento HTML mientras se trabaja en él.
* **Markdown All in One:** incorpora herramientas que facilitan la creación y edición de archivos escritos en Markdown.
* **XML - Red Hat:** proporciona funcionalidades para trabajar con documentos XML, incluyendo herramientas para su edición y validación.
* **Live Server:** permite iniciar un servidor local para visualizar páginas web y comprobar los cambios realizados de forma rápida.

### 3. Instalación de Git

También es necesario instalar **Git**, una herramienta utilizada para gestionar y controlar los cambios realizados en los archivos de un proyecto.

En sistemas basados en Ubuntu o Debian, Git puede instalarse mediante el siguiente comando:

```bash
sudo apt install git
```

### 4. Añadir los archivos y guardar los cambios en Git

Una vez creado el repositorio, se pueden añadir los archivos modificados y registrar los cambios realizados mediante un *commit*.

Primero se añaden los archivos:

```bash
git add .
```

Después se crea un *commit* indicando una descripción de los cambios:

```bash
git commit -m "Descripción de los cambios"
```

Finalmente, los cambios pueden enviarse al repositorio remoto mediante:

```bash
git push origin main
```

De esta forma, los cambios realizados en el proyecto quedan registrados y pueden enviarse al repositorio remoto.

---

## Extensiones instaladas

A continuación se muestran las extensiones utilizadas en el entorno de trabajo y la función que desempeña cada una:

| **Extensión**           | **Imagen**                                                                                                                                                    | **Función**                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **HTML CSS Support**    | ![HTML CSS Support](https://ecmel.gallerycdn.vsassets.io/extensions/ecmel/vscode-html-css/2.0.14/1770897391434/Microsoft.VisualStudio.Services.Icons.Default) | Facilita la escritura de código HTML y CSS mediante funciones de autocompletado.                              |
| **Live Preview**        | ![Live Preview](img/livepreview.png)                                                                                                                          | Permite abrir una vista previa del contenido HTML y comprobar cómo se muestra.                                |
| **Markdown All in One** | ![Markdown All in One](img/allinone.png)                                                                                                                      | Ofrece herramientas para crear y editar documentos Markdown de forma más sencilla.                            |
| **XML - Red Hat**       | ![XML - Red Hat](img/redhat.png)                                                                                                                              | Incluye herramientas destinadas a la edición y validación de archivos XML.                                    |
| **Live Server**         | ![Live Server](img/liveserver.png)                                                                                                                            | Ejecuta la página web mediante un servidor local y permite visualizar automáticamente los cambios realizados. |
