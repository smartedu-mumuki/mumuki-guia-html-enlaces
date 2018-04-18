Quizás alguna vez te pasó que al hacer clic sobre una imagen te llevo a otra página, entonces… ¿una imagen también puede funcionar como enlace?
<p>Bueno, no. No precisamente, más bien, cualquier elemento puede funcionar como enlace. Para lograr esto, necesitamos anidar nuestro elemento dentro de un elemento `a`. El elemento `a` es el que nos proporciona el enlace.

> Veamos si se entiende, escribi el siguiente código en el cuadro de la derecha:
>
> ```
> <a href="https://wikipedia.com" target="_blank">
>   <img src="https://es.wikipedia.org/static/images/project-logos/eswiki-2x.png” alt=”Logo de Wikipedia">
> </a>
> ```
