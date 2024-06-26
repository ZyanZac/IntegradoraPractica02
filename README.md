# IntegradoraPractica02

En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones, documentación, desarrollo colaborativo y respaldo del proyecto integrador para la asignatura de Integradora I.

## Comandos básicos para la documentación, utilizando el estándar de Markdown (md)
Markdown es el estándar utilizado por Git y GitHub, para maquetar la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo. 

### 1. Encabezados o títulos (HEADERS)
Para poder realizar una buena documentación del proyecto, debemos distribuir correctamente los contenidos, para delimitar o hacer énfasis (enfatizar), es decir, resaltar las secciones importantes, podemos utilizar los siguientes: 

EJEMPLOS:
# Encabezado de nivel 1 - Similar a H1 en HTML
## Encabezado de nivel 2 - Similar a H2 en HTML
### Encabezado de nivel 3 - Similar a H3 en HTML
#### Encabezado de nivel 4 - Similar a H4 en HTML
##### Encabezado de nivel 5 - Similar a H5 en HTML
###### Encabezado de nivel 6 - Similar a H6 en HTML
####### Encabezado de nivel 7 - Sólo 6 son los niveles permitidos, a partir de este el maquetado será ignorado.

### 2. Separadores (SEPARATORS)
Si desea marcar una separación más visual de contenidos podemos utilizarlos indicando tres carácteres de "-" continuos, en el maquetado.

EJEMPLO
---
*Esto es similar a un tag de < HR > en HTML.

### 3. Párrados (PARAGRAPHS)
Son utilizados para presentar grandes secciones de texto que describren detalladamente las secciones de la documentación del proyecto.

EJEMPLO:
Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1.

Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2.

Lo que en una página utilizaríamos la etiqueta < P >.

También podemos aplicar estilos básicos de alineación:

Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto. Este párrafo está alineado a la izquierda por defecto.

<p align="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. Este párrafo está alineado a la derecha utilizando la propiedad de alineación. 
</p>

<p align="center">
Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. Este párrafo está centrado usando la propiedad de alineación. 
</p>

<p align="justify">
Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. Este párrafo está justificado utilizando la propiedad de alineación. 
</p>

### 4. Texto Enfatizado (BOLD, ITALIC, BOLD/ITALIC)
Si el texto que debemos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

##### Texto en Negrita (BOLD)
Para poder poner el texto en negrita, este deberá ser encerrado entre doble **.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto **Texto en negrita** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Cursiva (ITALIC)
Para poder poner el texto en cursiva, este deberá ser encerrado entre * o -.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto en cursiva* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Negrita/Cursiva (BOLD/ITALIC)
Para poder poner el texto en negrita/cursiva, este deberá ser encerrado entre triple ***.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto cursiva/negrita*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Subrayado (UNDERLINE)

Algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML usando el tag \<ins> y cerrando con \</ins>

**EJEMPLO**

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto subrayado</ins> Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 


# IntegradoraPractica03
Continuamos con los comandos básicos de Git y GitHub para el maquetado de la documentación.

### 5. Cuadros para Código o Reseñas  (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones específicas para la instalación, configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (\>).

**EJEMPLO**
Para listar las carpetas y archivos desde una terminal de sistema operativo Windows debemos ingresar el comando: 

> C:/dir

Después oprimimos la tecla "Enter". 

También podemos ingresar textos multilínea.

**EJEMPLO**

>Aquí se agrega un conjunto de instrucciones
>para explicar al usuario, cómo instalar el
>software que hemos diseñado.

Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el carácter - dentro del texto a documentar.

**Pasos para Instalar la Base de Datos**

>- Descargar MySQL Server del sitio oficial.
>- Instalar el Sistema Gestor de Base de Datos, definiendo el puerto y contraseña para el usuario ***root***.
>- Descargamos el archivo de respaldo de la Base de Datos (.sql)
>- Restauramos la Base de Datos usando el comando *mysql*.

>> C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password \< respaldo.sql


### 6. Listas Ordenadas y Listas Desordenadas

Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro podemos hacerlo utilizando los números con un punto decimal si las deseas ordenadas o un guión medio - si sólo queremos una viñeta. 

**EJEMPLO**

Para crear tu primer repositorio en GitHub deberás: 

1. Contar con cuenta de GitHub
2. Dar click en el botón: *Nuevo Repositorio*
3. Asignarle un nombre a tu repositorio, por ejemplo: *Práctica03-3B*
4. Asignarle un nivel de privacidad entre 
   - **Público:** Si quieres que esté disponible para todos los usuarios.
   - **Privado:** Deseas que solo a quien tu decidas puedan ver y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado: *README.md*
6. Definir si habrá exclusiones de archivo a través de archivo: *.gitignore*
7. Guardar los cambios.


### 7. Ligas (Hipervínculos)

Las ligas son utilizadas para vincular elementos o referencia del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando los corchetes \[ \], inmediatamente después pondremos la liga de referencia entre paréntesis \( \).

**EJEMPLO**

Mi buscador favorito es: [Google](https://www.google.com).

Pero si deseamos poner sólo las ligas directas o un correo electrónico podemos utilizar los símbolos c< \>

**EJEMPLO**

Documentación creada por: ***Zacatenco Pedroza Zyanya Ahuachtli*** 

<230852@utxicotepec.edu.mx> 


<http://www.uxticotepec.edu.mx>


### 8. Tablas (TABLES)

Si la documentación lo requiere, podemos presentar información en formato de tablas con filas y columnas, para maquetarlas podemos utilizar el carácter \| para delifitar las columnas \- para delimitar las filas

**EJEMPLO**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|--------------|--------------|--------------|--------------|
|Fila 1 Celda 1|Fila 1 Celda 2|Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 1|Fila 2 Celda 2|Fila 2 Celda 3|Fila 2 Celda 4|
|Fila 3 Celda 1|Fila 3 Celda 2|Fila 3 Celda 3|Fila 3 Celda 4|

En caso de necesitar la fusión de celdas en columnas usaremos la propiedad *colspan* del tag \<td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad *rowspan*.

**EJEMPLO**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|--------------|--------------|--------------|--------------|
|Fila 1 Celda 1|Fila 1 Celda 2|Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 1<td colspan=2>Fila 2 Celda 2|Fila 2 Celda 3|
|Fila 3 Celda 1|Fila 3 Celda 2|Fila 3 Celda 3|Fila 3 Celda 4|
|              |Fila 4 Celda 2|Fila 4 Celda 3|Fila 4 Celda 4|
|              |Fila 5 Celda 2|Fila 5 Celda 3|Fila 5 Celda 4|
|Fila 6 Celda 1|Fila 6 Celda 2|Fila 6 Celda 3|Fila 6 Celda 4|

Dado que en el ejemplo pasado usando solo markdown no se puede realizar la fusión de filas, debemos utilizar el estándar HTML, usando los tags: \<th> para los encabezados, \<tr> para las filas, y \<td> para las celdas, y en ellos utilizar la propiedad de *colspan* y *rowspan*

**EJEMPLO**

<table>
   <tr>
      <th>Encabezado 1</th>
      <th>Encabezado 2</th>
      <th>Encabezado 3</th>
      <th>Encabezado 4</th>
   </tr>
   <tr>
      <td>Fila 1 Celda 1</td>
      <td>Fila 1 Celda 2</td>
      <td>Fila 1 Celda 3</td>
      <td>Fila 1 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 2 Celda 1</td>
      <td colspan=3 align="center">Fila 2 Celda 2</td>
   </tr>
   <tr>
      <td rowspan=3>Fila 3 Celda 1</td>
      <td>Fila 3 Celda 2</td>
      <td>Fila 3 Celda 3</td>
      <td>Fila 3 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 4 Celda 2</td>
      <td>Fila 4 Celda 3</td>
      <td>Fila 4 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 5 Celda 2</td>
      <td>Fila 5 Celda 3</td>
      <td>Fila 5 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 6 Celda 1</td>
      <td>Fila 6 Celda 2</td>
      <td>Fila 6 Celda 3</td>
      <td>Fila 6 Celda 4</td>
   </tr>
</table>



### 9. Imágenes

Se puede añadir imágenes al ingresar en el repositorio, por medio de la opción **Add file**. Una vez hecho esto, para referenciar la imagen, se deberá usar la siguiente ruta y código:

<\img src=https://\raw.githubusercontent.com/usuario/repositorio/rama/ruta-al-asset/>


**EJEMPLO**


<img src=https://raw.githubusercontent.com/ZyanZac/IntegradoraPractica02/main/images.jpg>


Si la documentación requiere de incorporar imágenes, esquemas, modelos, fotografías, o cualquier representación gráfica, utilizaremos la estructura de las ligas, maquetando el nombre de la imagen entre corchetes con un signo de admiración de cierre y la liga de referencia a la imagen usando paréntesis.

!\[imagen](\ruta)

**EJEMPLO**

![Gato](https://static.eldiario.es/clip/ab74aa95-3656-424c-8ca1-dce590aabb97_16-9-discover-aspect-ratio_default_0.jpg)
