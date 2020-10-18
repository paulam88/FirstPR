# RECOPIA-FirstPullRequest

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# ¡Bienvenido a tú primer pull request sobre habilidades!
Hola, este repositorio tiene como finalidad crear tu primer pull request, si ya lo has hecho, no te preocupes, también como objetivo está en publicar tus habilidades y así conocernos entre quienes colaboramos en el proyecto.

Este proyecto se enfoca en ser una guía y en simplificar la forma en la que los principiantes hacen su primera contribución. Si quieres hacer tu primera contribución y publican sus habilidades, sigue los pasos que se muestran a continuación.

#### *Si no estás familiarizado con la línea de comandos, [aquí hay tutoriales usando herramientas con Interfaz Gráfica (GUI)]( #tutoriales-con-otras-herramientas )*

<img align="right" width="300" src="assets/fork.png" alt="fork de este repositorio" />

Si no tienes git en tu equipo, puedes encontrar instrucciones para instalarlo en [este enlace]( https://help.github.com/articles/set-up-git/ ).

## Bifurca (*Fork*) este repositorio

Haz un *fork* de este repositorio haciendo click en el botón "*Fork*" en la parte superior derecha en esta página.
Esto creará una copia de este repositorio en tu cuenta.

## Clona (*Clone*) el repositorio

<img align="right" width="300" src="assets/clone.png" alt="clonar este repositorio" />

Ahora clona este repositorio en tu equipo. Dirígete a tu cuenta de GitHub, haz click en el botón "*clone or download*" y luego haz click en el icono para *copiar al portapapeles*.

Abre tu consola o terminal y ejecuta el siguiente comando de git:

```
git clone "url que acabas de copiar"
```

Donde "url que acabas de copiar" (sin las comillas dobles) es la *url* a este repositorio (tu *fork* a este proyecto). Mira los pasos previos para obtener la *url*.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copiar URL al portapapeles" />

Por ejemplo:
```
git clone https://github.com/este-eres-tu/PrimerPR-Habilidades.git
```
Donde `este-eres-tu` es tu usuario de GitHub. Aquí estás copiando los contenidos del repositorio *first-contributions* en GitHub a tu equipo.

## Crea una rama (*Branch*)

Cambia al directorio del repositorio en tu equipo (si es que no estás ahí ya).

```
cd PrimerPR-Habilidades
```

Ahora crea una rama (*branch*) usando el comando  `git checkout`:
```
git checkout -b <añade tu nombre>
```

Por ejemplo:
```
git checkout -b add-alonzo-church
```
(El nombre de la rama no tiene por qué contener la palabra *add*, pero es razonable que lo tenga porque el objetivo de esta rama es añadir tu nombre a la lista.)

## Haz los cambios necesarios y confirma (*Commit*) esos cambios

Abre el archivo `Contributors.md` en un editor de texto y añade tu nombre. No lo añadas ni al principio ni al final del archivo, hazlo en cualquier otro sitio. Guarda el archivo.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />

Si vas al directorio del proyecto y ejecutas el comando  `git status`, verás que hay cambios.

Agrega esos cambios a la rama (*branch*) que creaste anteriormente usando el comando `git add`:

```
git add Contributors.md
```

Ahora haz un *commit* sobre estos cambios ejecutando el comando `git commit`:
```
git commit -m "Add <tu-nombre> to Contributors list"
```
cambiando `<tu-nombre>` con tu nombre.

## Manda (*Push*) tus cambios a GitHub

Haz *push* de tus cambios usando el comando `git push`:
```
git push origin <añade-el-nombre-de-la-rama>
```
Reemplaza `<añade-el-nombre-de-la-rama>` con el nombre de la rama que creaste anteriormente.

## Envía (*Submit*) tus cambios para ser revisados

Si vas a tu repositorio en GitHub, verás un botón `Compare & pull request`. Haz click sobre este botón.

<img style="float: right;" src="assets/compare-and-pull.png" alt="crea una pull request" />

Ahora envía la *pull request*.

<img style="float: right;" src="assets/submit-pull-request.png" alt="enviar la pull request" />

Pronto estaré fusionando tus cambios (haciendo *merge*) con la rama master de este proyecto. Recibirás una notificación por correo electrónico cuando los cambios hayan sido fusionados.

## ¿Cuáles son los siguientes pasos?

¡Enhorabuena! ¡Has completado el flujo de trabajo *_fork -> clone -> edit -> PR_* que encontrarás habitualmente como contribuidor!

También podrías unirte a nuestro *equipo* de Slack en caso de que necesites ayuda o tengas alguna pregunta. [Únete a nuestro Slack](https://join.slack.com/t/primerpr-habilidades/shared_invite/enQtNzgxODU0OTEzNzE5LWFmMzIxM2Y4ZGIyNjY0MGM4Zjg5MzQ2YTMyMDU3MGVhY2M4ZWZmOTRkM2VkZGZjZGI4OTNhZTJhN2UxZDExOWM).

Ahora empieza a contribuir a otros proyectos.



## Auto promoción

Si te gustó este proyecto, márcalo como favorito con una estrella en [GitHub](https://github.com/jhonatanoc96/FirstPullRequest).
Si te sientes agradecido, sigue a [Jhonatan Ocampo] en
[Instagram](https://www.instagram.com/jhonatanocampoa/) y
[GitHub](https://github.com/jhonatanoc96).
# FirstPR
