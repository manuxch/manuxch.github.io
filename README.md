# carlevaro.ar
Source de la web carlevaro.ar

## Instalar Quarto y clonar

Para instar Quarto ver su [web](https://quarto.org/)

Además instalar la extensión [Iconify](https://github.com/mcanouil/quarto-iconify).

Una vez instalado, clonar el sitio con los archivos fuente:

    `git clone git@github.com:manuxch/carlevaro.ar.git`

Entrar a carlevaro.ar y ejecutar:
    
    `quarto preview`

## Editar la web y publicar

1. Editar la página. En web/carlevaro.ar ejecutar

        `quarto preview`

de ese modo se puede ver en vivo los cambios locales  en el navegador.

2. Construir el sitio

    `quarto render`

Esto genera el directorio `_site/` que contiene el sitio web.

3. Copiar a web/manuxch.github.io

    `cp -r web/carlevaro.ar/_site/* web/manuxch.github.io/`

4. Push 
        
