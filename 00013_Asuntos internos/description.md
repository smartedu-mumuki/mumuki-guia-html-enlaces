Los enlaces que vimos hasta ahora siempre nos llevaron a algo fuera de nuestra página web. Pero... ¿si quisiéramos navegar dentro de ella? :ocean::boat:

Para eso, primero vamos a tener que **identificar unívocamente** a los elementos destino de nuestra página mediante el atributo `id`. Por ejemplo, si quisiéramos identificar un encabezado `h1` como el primer cuento del libro [_"Cuentos de la selva"_](https://es.wikipedia.org/wiki/Cuentos_de_la_selva), lo haríamos así:

``` html
<h1 id="cuento_1">La tortuga gigante</h1>
```

_¿Alcanzará con eso?_ :thought_balloon:
No. También vamos a tener que decirle al elemento `a` que va a dirigirse a un _fragmento_ de nuestra página usando el símbolo `#` en el `href`. Entonces, por ejemplo, si quisiéramos un link al primer cuento, tendríamos esto:

``` hrml
<a href="#cuento_1">Primer cuento</a>
```


> ¡Ahora te toca a vos! Agregá el listado de links que nos llevan a las diferentes descripciones físicas del universo, copiando esto donde lo indica el `body`:
>
> ``` html
><ul>
>  <li><a href="#tamanio">Tamaño del universo</a></li>
>  <li><a href="#forma">Forma</a></li>
>  <li><a href="#color">Color</a></li>
>  <li><a href="#estructura_cuantica">Estructura cuántica</a></li>
></ul>
>```
> Hacé click en los enlaces para ver qué pasa. :eyes:
