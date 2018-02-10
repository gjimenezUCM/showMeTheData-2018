# Show me the data! Web scraping con Python
## Semana de la Informática 2018

Actividad realizada durante la [Semana de la Informática](http://informatica.ucm.es/iv-semana-de-la-informatica-2018) de la [Facultad de Informática de la UCM](http://informatica.ucm.es).

> Si los datos son el petróleo del siglo XXI el web scraping (_data harvesting_ o cosechado de datos) es la perforadora que ayuda a extraer ese valioso producto de los sitios web.
> 
> En este taller introduciremos cómo realizar web scraping utilizando Python. Se pondrán en práctica dos técnicas de scraping diferentes y las ejemplificaremos usando las librerías Beautiful Soup y Selenium. El taller concluirá con una reflexión sobre los problemas éticos que conlleva el web scraping.

En este repositorio están los notebooks interactivos utilizados durante la sesión presencial. Para ejecutarlos es necesario tener instalado Jupyter Notebook (una forma sencilla es instalando [la suite de Anaconda](https://www.anaconda.com/download/)) y el driver de Selenium para [Chrome](https://sites.google.com/a/chromium.org/chromedriver/) o [Firefox](https://github.com/mozilla/geckodriver/)

## Buenas prácticas al hacer web scraping

Extraído del artículo [Web Scraping: Best Practices to Follow](https://www.promptcloud.com/blog/web-scraping-best-practices) de Prompt Cloud.

- Respeta los [robots.txt](https://en.wikipedia.org/wiki/Robots.txt): Aquí tienes algunos ejemplos:
    + <https://www.facebook.com/robots.txt>
    + <https://www.fnac.es/robots.txt>
    + <https://www.imdb.com/robots.txt>
    + <https://www.amazon.es/robots.txt>
    + <https://www.yummly.com/robots.txt>
    + <https://www.filmin.es/robots.txt> (nos dan permiso para acceder a todo)
- No hagas que tus robots accedan demasiado a menudo ni muchos en paralelo al sitio web para no ralentizarlo ni tirarlo abajo.
- Intenta que tus robots no accedan a los sitios en horas punta del uso humano.
- Hazlo con responsabilidad: no lo uses para republicar los datos extraídos (seguramente infringirás leyes de copyright) y revisa los Términos y Condiciones de Uso del sitio para saber si está permitido.
- Sé paciente: si vas a utilizarlo de manera continuada, seguramente tendrás que realizar un mantenimiento constante ante los cambios que sufra el sitio web que estás procesando.

## Agradecimientos

- A Antonio Sánchez por sus incursiones con Selenium al Campus Virtual.
- A Sara Román por el material sobre _data harvesting_ que me ha ayudado a dar una breves pinceladas sobre la ética detrás de estas técnicas.
- A Yolanda García por introducirme en el mundo de los Jupyter Notebooks y el análisis de datos con Python.
