Github link in corner `ES`
============================================================
-   Agrega un enlace a tu github con el siguiente html

-   All the credits to [**@tholman**](https://github.com/tholman). The code provided in this repo belongs to Tim Holman: [**github-corners**](https://github.com/tholman/github-corners).

Descarga el html de esta repo y agrega el header.html al YAML
============================================================

Entonces: 
-   Descarga el html (header.html) de esta repo y agrega el "header.html" al YAML en tu Rmd. 
-   Tus archivos deben estar en la misma carpeta: el html y el rmd.


```{r}
---
title: "raaa"

output: 
  html_document:
    includes:
      in_header: header.html
---
```

También puedes cambiar el color o la posición 
============================================================
-   Pueden revisar las diferentes ocpiones aquí: [**GitHub Corners**](https://tholman.com/github-corners/) hecho por Tim Holman.

-   Por ejemplo, este es el código para que la imagen del gato interactivo tenga un fondo negro y esté ubicado al lado superior derecho:


`<a href="https://your-url" class="github-corner" aria-label="View source on GitHub"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#151513; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg></a><style>.github-corner:hover .octo-arm{animation:octocat-wave 560ms ease-in-out}@keyframes octocat-wave{0%,100%{transform:rotate(0)}20%,60%{transform:rotate(-25deg)}40%,80%{transform:rotate(10deg)}}@media (max-width:500px){.github-corner:hover .octo-arm{animation:none}.github-corner .octo-arm{animation:octocat-wave 560ms ease-in-out}}</style>`

-   Entonces, acá `https://your-url` debes colocar el url/enlace/link a tu perfil de github
-   Del mismo modo, puedes cambiar el color y la posición del gatito. Revisa el enlace de arriba para que veas las opciones.

IMPORTANTE:

1 OPCION: Una vez

-   Lo que hice yo fue descargar el html y subirlo a mi repositorio de github. Luego lo edité de acuerdo con el código de mi interés (para color y posición). 

-   Y lo volví a descargar en mi Desktop y lo guardé en mi entorno de trabajo.

2 OPCION: Editar manualmente

-   Descarga el Html de este repositorio en tu entorno de trabajo.

-   En un Rmd, pega el YAML de arriba y en la siguiente linea de codigo pega el codigo de Tim Holman (No es necesario hacerlo en un chunk, de frente en el script).

-   Ya en tu editor de script, puedes editar el enlace a tu descripcion y también el color y la posicion de tu gatito.



### Puedes revisar este Rpubs de Gustavo Martínez Valdes para mejorar tu YAML: 

-   **[Diseño de YAML**](https://rpubs.com/gustavomtzv/874870)


esotoesotoesoto... por ahora...
