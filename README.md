## Recursos de clase sobre cartorgafía temática

1) Para reproducir el mapa de minard:

[link al mapa](https://upload.wikimedia.org/wikipedia/commons/2/29/Minard.png)

Se puede usar la información en [Minard-data](minard-data)

para generar los tramos que tendrán distinto grosor se puede usar
en una planilla de cálculo una celda con algo como 

```
=CONCATENAR("LINESTRING(",<x origen>," ",<y origen>,",",<x destino>," ",<y destino>,")")
```

ver: [este link](https://en.wikipedia.org/wiki/Well-known_text_representation_of_geometry)

2) Para reproducir el mapa de John snow:

[link al mapa](https://upload.wikimedia.org/wikipedia/commons/2/27/Snow-cholera-map-1.jpg)

Se puede usar la información en [snow-data](snow-data)

Notar que faltaría un mapa base, se puede utilizar XYZ Tiles, que tiene un plugin en QGis

Tutorial en: 
[este link](https://mappinggis.com/2018/03/como-anadir-mapas-base-en-qgis-3-0-openstreetmap-google-carto-stamen/)

Queda muy bien el mapa si se usan las tiles "stamen toner", que en la misma pagina de arriba
se indican.

3) Datos de menciones en diario La Nacion por ciudad.

Agrego datos y un ejemplo construido en QGis (version 2.algo), de un mapa que levanta las 
menciones que cada localidad Argentina tuvo en el diario La Nacion desde que empezó la versión
digital hasta 2014. Obtenidas a partir del buscador del diario, cuando todavía no tenía restricciones
por suscripción.

Para estos datos, Licencia: Copyright Javier J. Clavijo, en los terminos de la licencia
Creative Commons Cc-BY-SA-4.0: https://creativecommons.org/licenses/by-sa/4.0/ 

Se agrega un ejemplo de carta terminada (en png), que correpsonde al proyecto de QGis que se incluye.

[Link a los datos](Federal)

4) Apunte de clase del Agrim. Jorge Ginzburg, Facultad de Ingeniería, Universidad de Buenos Aires,
No soy el propietario de los derechos de autor, pero entiendo que es de reproducción libre.

[Apunte Cartografía Temática](bibliografia/Ginzburg.pdf)

5) Guia de preguntas orientativas sobre datos para construir una carta temática.

Licencia: Copyright Javier J. Clavijo, en los terminos de la licencia
Creative Commons Cc-BY-SA-4.0: https://creativecommons.org/licenses/by-sa/4.0/ 

[Cuestrionario](bibliografia/Cuestionario-tematica.pdf)
