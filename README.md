# carlevaro.ar
Source de la web carlevaro.ar

## Instalar Jekyll y clonar

Para instalar Jekyll ver:
    https://jekyllrb.com/docs/installation/ubuntu/

Una vez instalado, clonar el sitio con los archivos fuente:
    `git clone git@github.com:manuxch/carlevaro.ar.git`

Entrar a carlevaro.ar y ejecutar:
    `bunlde install`

## Editar la web y publicar

1. Editar la página
 - en web/carlevaro.ar ejecutar
        bundle exec jekyll serve --livereload
   de ese modo se puede ver en vivo los cambios locales 
   en el navegador.

2. Construir el sitio
    `bundle exec jekyll build`

3. Copiar a web/manuxch.github.io
    `cp web/carlevaro.ar/_site/* web/manuxch.github.io/`

4. Push 
        
