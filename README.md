# Introducci-n-MarkDown
Ejercicios para MarkDown

# Esto es un ecabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6

Palabra en **negrita**  
Palabra en *cursiva*

**Resaltar comando**
En esta frase estamos resaltado el comando `ls -la.`

```
Texto en bloque de codigo
```
```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```
**Enlaces**

[Enlace a la página web del IES Celia Viñas](https://iescelia.org)

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

[1]: https://iescelia.org
[2]: https://github.com

**Imagen**

![https://iescelia.org](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)

**Lista desordenada**

* Item 1
* Item 2
* Item 3
* Item 4

**Lista desordenada anidada**

* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4

**Lista ordenada**

1. Item 1
2. Item 2
3. Item 3
4. Item 4

**Lista ordenada anidada**

1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2  
2. Item 2  
  2.1 Item 2.1  
3. Item 3  
4. Item 4  

**Tablas**   

| Encabezado 1 | Encabezado 2 | Encabezado 3  
| --- | --- | --- | ---  
| Fila 1.1 | Fila 1.2 | Fila 1.3  
| Fila 2.1 | Fila 2.2 | Fila 2.3  
| Fila 3.1 | Fila 3.2 | Fila 3.3  

**Salto de linea** 
 
```  
Hemos forzado el  
salto de linea  
```

**Citar texto**

> Este texto está citado.

**Comentarios**

Párrafo 1.  
 
<!Este texto es un comentario y no será renderizado-->

Párrafo 2.  

**Ejercicio 3.**

![](https://i.ytimg.com/vi/qBIzK7DMHl0/maxresdefault.jpg
)

**Ejercicio 4.**

![](./images/FamR-zhXEAYhdrw.jpg)

[Enlace a Archivo Markdown](./archivo%20mackdown)