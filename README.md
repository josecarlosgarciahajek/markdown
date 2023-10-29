# Esto es un ecabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6

En esta frase estamos resaltado el comando `ls -la`.

```
sudo systemctl start apache2
```
```bash
#!/bin/bash
echo "Hola mundo"
```
```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
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

[Enlace a la página web del IES Jaume II El Just](https://portal.edu.gva.es/iesjaumeeljust/)


Enlaces a la página web del [IES Jaume II El Just][1] y a [GitHub][2].

[1]: https://portal.edu.gva.es/iesjaumeeljust/
[2]: https://github.com

![](https://portal.edu.gva.es/iesjaumeeljust/wp-content/uploads/sites/33/2019/05/cropped-logo_text_groc.png)
---
![](img/jaume.jpg)


* Item 1
* Item 2
* Item 3
* Item 4 

---

* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4

---
1. Item 1
2. Item 2
3. Item 3
4. Item 4

---

1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2  
2. Item 2  
  2.1 Item 2.1  
3. Item 3  
4. Item 4  

---

| Encabezado 1 | Encabezado 2 | Encabezado 3
| --- | --- | --- 
| Fila 1.1 | Fila 1.2 | Fila 1.3
| Fila 2.1 | Fila 2.2 | Fila 2.3
| Fila 3.1 | Fila 3.2 | Fila 3.3

Por ejemplo, en esta frase  
hemos forzado un salto de línea.

El simbolo ">" Se usa para poner una cita.
> Este texto daría como resultado una cita.

Párrafo 1.

<!-- Este texto es un comentario y no será renderizado -->
<!Este texto es un comentario y no será renderizado>

Párrafo 2.

