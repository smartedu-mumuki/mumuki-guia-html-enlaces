En Netfix, nuestra plataforma amiga :stuck_out_tongue_closed_eyes:, podemos buscar y ver películas y series, visitándola desde `https://netfix.io`. Entonces, si quisiéramos un enlace al listado de películas de terror en NetFix podríamos hacer:

``` html
<a href="https://netfix.io/peliculas/genero/terror">Pelis de terror</a>
```

Esto ya lo vimos, ¿no? :sweat_smile: Sí, pero nunca dijimos que se llama _enlace absoluto_ porque apunta a una URL completa. Y como todo se complementa en la vida: la luna :last_quarter_moon_with_face: y el sol :sun_with_face:, blanco :white_circle: y negro :black_circle:... vamos a tener enlaces absolutos y _enlaces relativos_. 

El enlace relativo al listado de películas de terror sería:

``` html
<a href="/peliculas/genero/terror">Pelis de terror</a>
```

¿Viste eso :eyes:? La parte de la URL `https://netfix.io` no la escribimos. Eso es porque el enlace relativo apunta a una URL incompleta.

Pero, ¡claro!, como le falta información, es ultra necesario conocer la URL de origen para que el enlace relativo sepa a donde dirigirnos. En este caso, para que funcione debemos estar en `https://netfix.com`, así el navegador saca por contexto cómo completar la URL. :wink:

> Veamos si se entendió, seleccioná todas las afirmaciones correctas.
