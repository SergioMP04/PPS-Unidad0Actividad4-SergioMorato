# PPS-Unidad0Actividad4-SergioMorato

Este proyecto consiste en crear y configurar un repositorio para una página web sencilla que se podrá visualizar a través de un pequeño servidor PHP. A continuación se detallan los pasos realizados para completar la actividad.

## 1. Configuración inicial de Git

Configura el editor de comandos en Git:

```bash
   git config --global core.editor nano
```

Para ver que todo se haya ido editando correctamente podremos hacer un:

```bash
   git config --global --get core.editor

```

![Config Nano](imagenes\Config_Nano.png)
Configura la visualización de git diff y git log para mostrar todo el mensaje sin un editor adicional:

```bash
git config --global core.pager ''
```

Comprueba las variables de configuración de Git:

```bash
git config --help
```

![Help](imagenes\help.png)

Ajusta los valores de las variables de color en Git:

```bash
git config --global color.status auto
git config --global color.branch auto
git config --global color.interactive auto
git config --global color.diff auto
```

![Conf](imagenes\Configuraciones_Git.png)

## 2. Creación de Proyecto y repositorio

 Inicializa el repositorio Git en la carpeta

```bash
git init
```

Agregaremos todos los archivos al repositorio:

```bash
git add .
```

Realizaremos un commit inicial:

```bash
git commit -m "Initial commit"
```

Enlazaremos el repositorio local con el remoto en GitHub. Si aún no tienes el repositorio en GitHub, créalo y copia la URL SSH o HTTPS. Luego, reemplaza la URL en el siguiente comando:

```bash
git remote add origin git@github.com:SergioMP04/PPS-Unidad0Actividad4-SergioMorato.git
```

Subiremos el proyecto a GitHub:

```bash
git push -u origin master
```

![Subida del repositorio](imagenes\Subidad_Repo.png)

## 3. Iniciando Proyecto

Como en mi caso lo que he hecho has sido ir redactando este readme a medida que iba haceiendo el ejercicio ya lo tengo creado y en local, por lo que vamos a subirlo a un repositorio que he creado el cual se llama como la actividad, a continuación los pasos.

Dado que ya tienes la carpeta del proyecto en tu sistema, aquí tienes los pasos para subirla a GitHub:

Accede al directorio del proyecto (si aún no estás en él):

```bash
cd ~/Desktop/PPS-Unidad0Actividad4-SergioMorato
```

Veremos los archivos y las ramas que contiene el repositorio:

```bash
tree -a
```
![Subida del repositorio](imagenes\Tree.png)

En mi caso y como digo anteriormente ya tengo creado el readme donde estoy readtando esto por lo que no hace falta crear el readme.
Comprobaremos el estado del repositorio:

```bash
git status -s
```

Agregaremos todos los archivos al repositorio:

```bash
git add .
```

Realizaremos un commit inicial:

```bash
git commit -m "Initial commit"
```

Enlazaremos el repositorio local con el remoto en GitHub. Si aún no tienes el repositorio en GitHub, créalo y copia la URL SSH o HTTPS. Luego, reemplaza la URL en el siguiente comando:

```bash
git remote add origin git@github.com:SergioMorato/PPS-Unidad0Actividad4-SergioMorato.git
```

Subiremos el proyecto a GitHub:

```bash
git push -u origin main
```

Después de estos pasos, nuestro proyecto estará disponible en GitHub.

