---
id: contributing-overview
title: Contribuir a Single-spa
sidebar_label: Visión General
---

[Lista de los contribuidores actuales](/contributors)

Gracias por probar single-spa! Nos entusiasma escuchar y aprender de ti.

Hemos reunido las siguientes guías para ayudarte a conocer en donde puedes ser de mayor apoyo.

## Tabla de contenidos

0. [Tipos de contribuidores que estamos buscando](#tipos-de-contribuidores-que-estamos-buscando)
0. [Reglas de juego y expectativas](#reglas-de-juego-y-expectativas)
0. [Cómo contribuir](#cómo-contribuir)
0. [Configurando tu entorno](#configurando-tu-entorno)
0. [Comunidad](#comunidad)

## Tipos de contribuidores que estamos buscando

Existen multiples maneras de contribuir directamente a las guias 
There are many ways you can directly contribute to the guides (en orden descendente de necesidad):

* Ejemplos
* Librerías auxiliares (Cómo single-spa-react) para frameworks faltantes
* Solución de errores
* Responder inquietudes en el canal de slack
* nuevos paquetes auxiliares para frameworks

Estás interesado en contribuir? Sigue leyendo!

## Reglas de juego y expectativas

Antes de empezar, éstas son algunas cosas que esperamos de ti (Y debes esperar de otros):

* Sé amable y considerado en tus conversaciones al rededor de este proyecto. Todos venimos de todos venimos de orígenes y proyectos diferentes, lo que significa que probablemente tenemos perspectivas diferentes sobre "cómo desarrollar código abierto." Intenta escuchar a otros en vez de convencerlos que tu manera es la correcta.
* Por favor lee el [Código de conducta del contribuidor](/docs/code-of-conduct/). Al participar en este proyecto, aceptas cumplir sus terminos.
* Si creas una solicitud de revisión de código, por favor asegurate de que tu colaboración pase todas las pruebas. Si fallan las pruebas, deberás corregirlas antes de que podamos mezclar tu contribución.
* Cuando agregues contenido, por favor considera si es realmente valioso. Por favor no agregues referencias a enlaces o cosas que tu o tu empleador haya creado pues otros harán lo mismo si les gusta la idea.

## Cómo contribuir

Si te interesa contribuir, empieza indagando el listado de [issues](https://github.com/single-spa/single-spa/issues) y [pull requests](https://github.com/single-spa/single-spa/pulls) para ver si alguien a escalado una idea o pregunta similar.

Si no ves la idea listada, y consideras que encaja en los objetivos de esta guía, haz lo siguiente

* **Si tu colaboración es menor,** tal como un error pequeño de tipografía o la solución de un error, abre un pull request.
* **Si tu contribución es mayor,** tal como una nueva funcionalidad, Empieza creando un 'issue'. De esta manera, otros podrán  participar en la discusión y opinar antes de que realices cualquier trabajo.

## Configurando tu entorno

### Prerrequisitos

1. Git
1. Node: insatala la version 8.4 o superior
1. Yarn: visita [El sitio de Yarn para ver las instrucciones de instalación](https://yarnpkg.com/lang/en/docs/install/)
1. Bifurcar el [repositorio single-spa](https://github.com/single-spa/single-spa)
1. Clonar el repositorio en tu máquina local

### Instalación

1. `cd single-spa` para ir a la raíz del proyecto
1. `yarn` para instalar las dependencias de single-spa

### Crear una rama

1. `git checkout master` desde cualquier carpeta en tu repositorio local de `single-spa` 
1. `git pull origin master` para asegurarte de tener la versión más reciente del código principal
1. `git checkout -b el-nombre-de-mi-rama` (remplazando `el-nombre-de-mi-rama` con un nombre adecuado) para crear una rama

### Probar los cambios

1. Ejecuta `yarn test` desde la raíz del proyecto.

### Súbelos

1. `git add . && git commit -m "Mi mensaje"` (remplazando `Mi mensaje` con un mensaje de confirmación, tal como `Ajustes sobre el ciclo de vida de la aplicación`) para recopilar o confirmar tus cambios
1. `git push my-fork-name el-nombre-de-mi-rama`
1. Ve al [repositorio single-spa](https://github.com/single-spa/single-spa) y podrás ver las ramas recientemente cargadas.
1. Sigue las instrucciones de GitHub's enviar un nuevo Pull Request.

## Comunidad

Las discusiones sobre single-spa tienen lugar en las secciones [Issues](https://github.com/single-spa/single-spa/issues) y [Pull Requests](https://github.com/single-spa/single-spa/pulls) del repositorio de single-spa. Cualquiera es bienvenido a unirse a estas conversaciones. También existe una [comunidad de slack](https://join.slack.com/t/single-spa/shared_invite/enQtODAwNTIyMzc4OTE1LWUxMTUwY2M1MTY0ZGMzOTUzMGNkMzI1NzRiYzYwOWM1MTEzZDM1NDAyNWM3ZmViOTAzZThkMDcwMWZmNTFmMWQ) para actualizaciones regulares.

Siempre que sea posible, no lleves estas conversaciones a canales privados, inclusive contactar a los administradores directamente. Mantener las conversaciones públicas significa que otros se podrán beneficiar y aprender de las mismas.