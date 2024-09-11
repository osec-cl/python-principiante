# Fundamentos de la Programación en Python

## Instalación de entorno de trabajo

### Visual Studio Code (VSCode)

1.- Descargar Visual Studio Code

Abre tu navegador y ve al sitio web oficial de Visual Studio Code.

En la página principal, busca el botón que dice Download for Windows, Download for macOS o Download for Linux, dependiendo del sistema operativo que uses. Haz clic en el botón correspondiente para descargar el archivo de instalación.

2.- Iniciar el instalador

Una vez descargado, abre el archivo de instalación. Este archivo suele tener un nombre como VSCodeSetup.exe (para Windows).

Haz doble clic en el archivo para iniciar el instalador.

3.- Aceptar los términos de licencia

El instalador mostrará los términos y condiciones. Marca la casilla que dice I accept the agreement (Acepto el acuerdo) y haz clic en Next (Siguiente).

4.- Elegir ubicación de instalación

En la siguiente pantalla, te pedirá que elijas una ubicación para instalar Visual Studio Code. Puedes dejar la ubicación predeterminada o cambiarla si prefieres instalarlo en otro lugar. Haz clic en Next para continuar.

5.- Seleccionar tareas adicionales

A continuación, tendrás la opción de seleccionar tareas adicionales, como:

* Crear un acceso directo en el escritorio.
* Agregar Visual Studio Code al menú de inicio.
* Registrar la aplicación para abrir archivos desde el explorador.

Marca las opciones que desees y haz clic en Next.

6.- Instalar

Haz clic en el botón Install (Instalar) para comenzar la instalación.

El proceso de instalación tomará unos momentos. Verás una barra de progreso mientras se copian los archivos.

7.- Finalizar la instalación

Cuando el instalador termine, verás una pantalla con la opción de Launch Visual Studio Code (Lanzar Visual Studio Code). Si quieres abrir el programa inmediatamente, deja marcada esta opción y haz clic en Finish (Finalizar).

8.- Primer lanzamiento de Visual Studio Code

Al abrir Visual Studio Code por primera vez, aparecerá una pantalla de bienvenida. Aquí puedes comenzar un nuevo proyecto o abrir un archivo existente.

Si presentas algún problema para instalarlo no dudes consultarlo a mi mail <MAILTO:luis.vasquez.s@usach.cl>. A continuación les dejaré un link donde quedará más claro. 

> https://www.youtube.com/watch?v=X_Z7d04x9-E

Se les deja el siguiente video donde se enseña a instalar VS y algunas extensiones que les ayudará mejor a entender cómo se utiliza esta gran herramienta que utilizarás en toda esta hermosa carrera llamada **informática**.

### Jupyter Notebook

> Esta sección asume una instalación de Python en el sistema. Si es su primera vez instalando python, favor **marque añadir Python al PATH en el instalador.**

> El ejecutable python.exe debe poder invocarse en PowerShell (o la shell de VSCode). Si esto no funciona, revisar [este tutorial](https://realpython.com/add-python-to-path/).

1. Instalar el entorno virtual

> Esta es un entorno auto-contenido que permite instalar programas sin alterar el Python del sistema, favor realizarlo dentro de la carpeta clonada desde GitHub.

```
python -m venv .env
```

2. Entrar al entorno virtual

```
. .\venv\Scripts\Activate.ps1
```

3. Instalar Jupyter Notebook

```
pip install jupyter
```

4. Instalar la extensión de VSCode

Ir a la pestaña lateral de *Extensiones*, buscar *Jupyter* e instalar la extensión con más de 2 millones de descargas.

5. Ejecutar Jupyter Notebook

Si no aparece el menú de opciones de Jupyter Notebook (+Code, +Markdown, Run All, etc), cerrar VSCode y volver a abrirlo. Este debería reconocer el entorno viritual de python automáticamente y ejecutar Jupyter Notebook.

Si existen dudas sobre esta sección, favor abran un issue y hagan @tvillega en conjunto con su consulta.
