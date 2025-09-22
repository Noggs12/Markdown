# Etiquetas básicas de Markdown

Este documento recoge los principales elementos de **Markdown** con su sintaxis y su resultado renderizado en GitHub.

---

## 1.2.1 Encabezados

`markdown
# Esto es un encabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6

## Negrita y Cursiva

| Estilo  | Sintaxis          | Ejemplo                | Salida               |
| ------- | ----------------- | ---------------------- | -------------------- |
| Negrita | `** **` o `__ __` | `**Texto en negrita**` | **Texto en negrita** |
| Cursiva | `* *` o `_ _`     | `*Texto en cursiva*`   | *Texto en cursiva*   |


 Resaltar un comando:
En esta frase estamos resaltado el comando ls -la

Bloques de codigo:

sudo systemctl start apache2

#!/bin/bash
echo "Hola mundo"

celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')

version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html

Enlaces:

[Enlace a la página web del IES Celia Viñas](https://iescelia.org)

 Otra forma de gestionar enlaces:

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

[1]: https://iescelia.org
[2]: https://github.com

 imagenes

![](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)


Listas

* Item 1
* Item 2
* Item 3
* Item 4

Listas desordenadas anidadas

* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4

 Listas ordenadas

1. Item 1
2. Item 2
3. Item 3
4. Item 4


 Listas ordenadas anidadas

1. Item 1  
   1.1 Item 1.1  
   1.2 Item 1.2  
2. Item 2  
   2.1 Item 2.1  
3. Item 3  
4. Item 4  

Tablas

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|--------------|--------------|--------------|
| Fila 1.1     | Fila 1.2     | Fila 1.3     |
| Fila 2.1     | Fila 2.2     | Fila 2.3     |
| Fila 3.1     | Fila 3.2     | Fila 3.3     |


 Forzar un salto de líneas

Por ejemplo, en esta frase  
hemos forzado un salto de línea.

Citar textos:

Este texto no es una cita.
> Este texto daría como resultado una cita.

Comentarios:

Párrafo 1.

<!-- Este texto es un comentario y no será renderizado -->

Párrafo 2.


# Mi Proyecto

Este es el README principal del repositorio.

Aquí encontrarás un enlace al documento adicional:  
👉 [Ir al documento](documentoprueba.md)
