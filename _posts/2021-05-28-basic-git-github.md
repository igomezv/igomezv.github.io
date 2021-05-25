---
layout: post
title: Recetas Git/GithHub
subtitle: [EN CONSTRUCCION Manual  de supervivencia]
gh-repo: igomezv
gh-badge: [star, fork, follow]
tags: [Git, GitHub]
comments: false
---

Git es un controlador de cambios de código abierto (open source) y GitHub una plataforma de desarrollo colaborativo basada en Git. 

Un controlador de cambios te permite ir reportando cada modificación en tu código, así como tener diferentes versiones de manera simultanea y la posibilidad de regresar a una versión anterior por lejana que sea. Esto hace que Git sea muy interesante y útil. Existen varias plataformas de desarrollo que utilizan Git como base: GitLab, SourceForge, GitHub y Bitbucket, entre otras. 

La intención de esta entrada es describir algunos comandos de Git (para GitHub, en particular) que en mi caso personal considero muy útiles y que no encontré tan rápido en la red la primera vez que intenté usarlos. 

Se asumirán situaciones en las que ya se tiene instalado Git, cuenta y repositorio de GitHub. Para instalar Git desde cero, navegar en la plataforma web de GitHub y otras cuestiones hay mucha información en Internet, entre otras fuentes:

- https://rogerdudler.github.io/git-guide/index.es.html
- https://guides.github.com/activities/hello-world/

## commit

Un <code>commit</code> es una confirmación de los cambios realizados en el código y Git mediante esa instrucción le asigna un identificador al bloque de cambios involucrados. Además, uno puede asignar un mensaje o descripción para recordar en qué consistieron esos cambios. En la práctica, la forma que me ha resultado más fácil es: 

```bash
git commit -m "descripción del cambio" script_mod1.py script_mod2.py
```
Si no se indican los archivos modificados, el  <code>commit</code> incluirá todos los cambios realizados en el repositorio. La bandera  <code>-m</code> le dice a Git que le pasaremos, dentro de la misma instrucción, un mensaje (o descripción) del cambio. 
Todas las opciones de <code>commit</code>: https://git-scm.com/docs/git-commit
## push
Para "empujar"  los cambios indicados en un <code>commit</code> al repositorio remoto se utiliza el comando <code>push</code>.

```bash
git push
```
En la forma que más suelo usar este comando es así, a secas. De esta manera, Git busca en su configuración dónde debe enviarse los nuevos cambios, y si no encuentra configuración alguna, lo hace en <code>origin</code>. 

Documentación completa de este comando: 
https://git-scm.com/docs/git-push


## pull

## Repositorio remoto (upstream)

![Figura](https://igomezv.github.io/assets/img/avatar-icon.jpeg)




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NTE3MTk3MjAsMTE5NjI4NjcwOSw2MT
M1NDM5MzcsODc5ODE4MDMxLC00NTI2MjI5MDRdfQ==
-->