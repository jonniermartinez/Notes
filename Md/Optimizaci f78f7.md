# Optimización de imágenes

Tamaño máximo recomendado para una imágen:
* 70kb

**Herramientas para optimizar imágenes:**

* [Tiny PNG](https://tinypng.com/): Comprime el tamaño de una imagen, para hacerla más ligera.

* [Verefix](https://www.verexif.com/): Elimina los metadatos de una imagen, para reducir su tamaño.

* [Optimizilla](https://imagecompressor.com/es/): optimizador de imagen en línea.

* [I💖img](https://www.iloveimg.com/): Herramientas online para la edición de imágenes

* Bancos de imagenes
    * [Pexels](https://www.pexels.com/):
    * [Pixabay](https://pixabay.com/):
    * [Freerange](https://www.freerangestock.com/):
    * [Realistic Shots](https://realisticshots.com/):
    * [PicJumbo](https://picjumbo.com/):
    * [Magdeleine](https://magdeleine.co/):
    * [Creativecom](https://search.creativecommons.org/):

* [Compressor.io](https://compressor.io/): Comprime sin perder calidad (mejor todavia Tinypng)
* [Picresize](https://picresize.com/): Comprime y recorta el tamaño de la imagen
* [Convertio](https://convertio.co/es/jpg-svg/): convierte jpg, png a svg (esta pagina es muy buena puede convertir de todo a otros formatos es gratis, chequenla y comenten que les parecio )
* [Coverr](https://coverr.co/): Free videos

**Atributo loading**

El atributo loading permite al navegador retrasar la carga de imáges y de iframes que están fuera de pantalla, hasta que el usuario haga scroll cerca de ellas. Éste atributo soporta 3 valores:

* **lazy:** Retrasa la carga de la imagen hasta que el usuario alcanza con el scroll una distancia calculada desde el viewport.
* **eager:** Carga la imagen inmediatamente, sin importar donde está situada o colocada en la pantalla. En resumen, no hace lazy-loading.
* **auto:** Implementa el comportamiento por defecto del navegador para la carga de las imágenes. En resumen, poner auto es lo mismo que no poner el atributo loading.

```html
<img loading="lazy"  src="manzana.png" alt="People"> 
```