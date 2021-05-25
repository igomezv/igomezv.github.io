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

Se asumirán situaciones en las que ya se tiene instalado Git, cuenta y repositorio de GitHub. Para instalar Git desde cero, navegar en la plataforma web de GitHub y otras cuestiones más básicas, se recomienda *googlear*.

## commit

Un <code>commit</code> es una confirmación de los cambios realizados en el código y Git mediante esa instrucción le asigna un identificador al bloque de cambios involucrados. Además, uno puede asignar un mensaje o descripción para recordar en qué consistieron esos cambios. En la práctica, la forma que me ha resultado más fácil es: 

```bash
git commit -m "descripción del cambio" script_mod1.py script_mod2.py
```
Si no se indican los archivos modificados, el  <code>commit</code> incluirá todos los cambios realizados en el repositorio. La bandera  <code>-m</code> le dice a Git que le pasaremos, dentro de la misma instrucción, un mensaje (o descripción) del cambio. 

[EN PROCESO]

## Push: cómo subir mis cambios

## Pull

## Repositorio remoto (upstream)

![Figura](https://igomezv.github.io/assets/img/avatar-icon.jpeg)




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMTc1ODQ3ODEsODc5ODE4MDMxLC00NT
I2MjI5MDRdfQ==
-->