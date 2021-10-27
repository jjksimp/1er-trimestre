
# Imagenes: 
Las imagenes se guardan dijitalmente de dos maneras. por un lado (ráster) podemos hacer: la matiz 
de puntos (mapa de bits) y a cada punto le asignamos un color (píxel)

Propiedades de una imagen ráster : resolución. Un mapa de bits tiene un tamaño convret de AxB.
La resolución se puede expresar de diferentes formas - Nº total de píxeles. normalmente MP (megapíxeles) esto es el número que resulta 
de AxB en millones de píxeles - 3MP
Líneas horizontales. En el video se utiliza la cantidad de líneas horizontales, normalmente se asume una proporción concreta entre A y B, por ejemplo 3/4 o 16/9 (cine)

Las líneas horizontales suelen ser:
- 240 p
- 480g
- 720 g
- 1080g (hd)
- 2k
- 4k (4096 píxeles de alto)

Un archivo puede expresar su resolución diciendo AxB.
Por ejemplo una imagen de 350x250 píxeles se utiliza cuando hablamos de archivos concretos

No confundir con la resolución de impresión metida en puntos por pulgada (ppp) o (dpi) dots per inch.
- Espacios de color 
- sistemas para detallar colores 
- RGB (red green blue) para pantallas
- CYMK (cyan magenta yellow black) para imprimir
- Colores indexados - gifs

-- Canal ( como los tres canales de RGB ) de transgregación
Este canal se llama canal alfa. Los PNG pueden tenerlo , los gif y los jpg no.


# FORMATOS COMUNES

## JPG 
 
 ![imagen](https://user-images.githubusercontent.com/90753482/138061788-a3c414b2-ff24-4156-a39b-2b702d0fba1d.png)

## GIF

![imagen](https://user-images.githubusercontent.com/90753482/138062987-b8e149e4-cf34-474c-80a4-b5c0f249507f.png)

##  PNG

![imagen](https://user-images.githubusercontent.com/90753482/138062652-14278ac1-5ca4-41c6-8484-ffa7b0326fbf.png)


- TIFF
- OTROS PARTICULARES .PSD

### Imagen ráster:
formada por píxeles

### Imágenes vectoriales
Se define la imagen como un conjunto de formas ( líneas, puntos, etc) cada una de estas formas está definida matemáticamente.

          vectorizar➝
Imagen ráster -- imagen vectorial

         rasterizar ←
         
Rasterizamos una imagen, cuando pasamos de una imagen vectorial a una imagen ráster (mapa de bits).

Vectorizar es pasar de una imagen ráste a una vectorial.

### Ejercicio vectorización

Vamos a tomar la imagen del cuadro del león de Rosa Bonheur.

Esta es la imagen rasterizada original

![imagen](https://user-images.githubusercontent.com/90753482/138074869-f9f05fe3-c90a-4ff4-aa08-a12177b1f679.png)

[fuente:](https://elpais.com/cultura/2019/09/30/actualidad/1569858378_536299.html)

Descargamos la imagen

### Archivo: propiedades del documento.

- Tamaño personalizado ancho 600 alto 1000 (poner en px)
- carramos ventana
- Añadimos la imagen de internet
- archivo- importar
- arrastrar la imagen
- copiar y pegar
- clic derecho en la imagen - vectorizar mapa de bits

![Captura de pantalla de 2021-10-20 12-55-05](https://user-images.githubusercontent.com/90753482/138084712-29797654-b0ff-47d6-b25f-3592570e413a.png)


### - Explicación del cuadro de victorizar

Existen varias opciones; lo primero es decidir si el programa hará una o más pasadas. Con una única pasada
siempre obtendremos una imagen en blanco y negro (que después podremos colorear)
Una única pasada / cuantización de colores- agrupa dos o más en colores similares
corte de luminosidad - junta todos los píxeles más oscuros que un gral(?)

Varias pasadas: nos permite hacer una imagen vectorial más compleja, con varios grises o colores.
Esto necesita más capacidad de proceso .
León1.SGV
Después de importar el león vamos a ajustar el lienzo.
Para ello vamos a propiedades de documento
En tamaño vamos a ajustar página a contenido seleccionamos la imagen y pulsamos el botón  ajustar página al contenido o selección

![Captura de pantalla de 2021-10-20 13-24-56](https://user-images.githubusercontent.com/90753482/138084501-36d16937-f181-45ca-8a23-337f15de7df7.png)

- Vectorizamos el león con las siguientes caractersticas: múltiples pasadas, colores, 8 pasadas
- Borramos el ráster
- guardamos como león.SGV

- Subimos al [github](https://github.com/jjksimp/1er-trimestre/blob/main/LE%C3%93N.svg)

![Captura de pantalla de 2021-10-20 13-35-19](https://user-images.githubusercontent.com/90753482/138085402-c905f0fa-0082-4c89-ac45-659d42dd9876.png)

### 3 LEONES

Todas las imágenes fueron modificadas con la herramienta de filtros, todos distintos para cada uma.
![Captura de pantalla de 2021-10-20 13-53-37](https://user-images.githubusercontent.com/90753482/138088032-979dc3c1-69bd-4864-b238-44d14fe7d06c.png)
![Captura de pantalla de 2021-10-20 13-54-43](https://user-images.githubusercontent.com/90753482/138088038-b6c946b2-6aff-4265-8409-3a7a5ae6d5a3.png)
![Captura de pantalla de 2021-10-20 13-59-32](https://user-images.githubusercontent.com/90753482/138088582-66f80fcc-87d4-42e8-b1d2-a0abddd52a88.png)


### Rasterizar
En este caso sólo se ve un fragmento del león porque el león no estaba ajustado el liezo. Para hacerlo correctamente
hay que estar seguros de que el león se encuentre dentro del lienzo o pasará lo mismo otra vez.

- León 1: 16 x 21px

![LEON1](https://user-images.githubusercontent.com/90753482/139020702-4853b6cd-fd22-4417-aef8-14f3850e6604.png)

- León 2: 160 px

![LEON2](https://user-images.githubusercontent.com/90753482/139021110-33b4666d-8fdb-4697-8931-b745e3e4bad4.png)

- León 3: 350 px

![LEON3](https://user-images.githubusercontent.com/90753482/139021232-46167b61-4311-423f-bdf8-4a15df38416c.png)

- León 4: 800 px

![LEON4](https://user-images.githubusercontent.com/90753482/139021360-a400c003-6e26-4413-85da-becfc617623c.png)

- León 5: 1500 px

![LEON5](https://user-images.githubusercontent.com/90753482/139021463-bb67c244-8762-4838-8dc6-34061116bfbe.png)

----------

![Captura de pantalla de 2021-10-27 10-17-55](https://user-images.githubusercontent.com/90753482/139027577-e7df7f1f-048d-46b2-9b3b-dee7f89507b6.png)

