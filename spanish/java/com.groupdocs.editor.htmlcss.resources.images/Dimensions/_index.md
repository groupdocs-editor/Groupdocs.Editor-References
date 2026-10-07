---
title: "Dimensiones"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa las dimensiones lineales de ancho y alto de una imagen raster rectangular en una unidad arbitraria."
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Representa las dimensiones lineales (ancho y alto) de un raster rectangular
imagen en unidad arbitraria. Estructura inmutable.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Crea una nueva instancia a partir del ancho y alto especificados |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Devuelve el ancho de la imagen |
|
|  | [getHeight()](#getHeight--) | Devuelve el alto de la imagen |
|
|  | [isSquare()](#isSquare--) | Determina si el 'Dimensions' especificado representa un cuadrado, es decir, |
|
|  | [getArea()](#getArea--) | Devuelve un área (Ancho x Alto) |
|
|  | [isEmpty()](#isEmpty--) | Determina si esta instancia "Dimensions" está vacía y es la predeterminada, es decir, |
|
|  | [getAspectRatio()](#getAspectRatio--) | Relación de aspecto de estas dimensiones como ancho/alto |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Crea y devuelve una nueva instancia "Dimensions", que es proporcionalmente |
redimensionada a partir de la actual, basada en el ancho especificado
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Crea y devuelve una nueva instancia "Dimensions", que es proporcionalmente |
redimensionada a partir de la actual, basada en el alto especificado
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Determina si esta instancia es igual a la "Dimensions" especificada |
instancia
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual al objeto sin convertir especificado, |
que presumiblemente es otra instancia "Dimensions"
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia, que no puede ser modificado durante su |
vida útil
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Comprueba si dos valores "Dimensions" son iguales, es decir, |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Comprueba si dos valores "Dimensions" no son iguales, es decir, |
|
|  | [toString()](#toString--) | Devuelve una representación en cadena de este "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Devuelve una copia completa de esta instancia |
|
|  | [getEmpty()](#getEmpty--) | Devuelve una instancia Dimensions vacía |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Crea una nueva instancia a partir del ancho y alto especificados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | ancho | int | Ancho de la imagen |
|
|  | alto | int | Alto de la imagen |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Devuelve el ancho de la imagen


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Devuelve el alto de la imagen


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Determina si el 'Dimensions' especificado representa un cuadrado, es decir, si
el ancho es igual al alto


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Devuelve un área (Ancho x Alto)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Determina si esta instancia "Dimensions" está vacía y es la predeterminada, es decir,
no almacena el ancho y la altura correctos


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Relación de aspecto de estas dimensiones como ancho/alto


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Crea y devuelve una nueva instancia "Dimensions", que es proporcionalmente
redimensionada a partir de la actual, basada en el ancho especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | targetWidth | int | Nuevo ancho objetivo, que estará presente en la Dimensión resultante |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Crea y devuelve una nueva instancia "Dimensions", que es proporcionalmente
redimensionada a partir de la actual, basada en el alto especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | targetHeight | int | Nuevo alto objetivo, que estará presente en la Dimensión resultante |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Determina si esta instancia es igual a la "Dimensions" especificada
instancia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Otra instancia de "Dimensions" para comprobar la igualdad |
|

**Returns:**
booleano - Verdadero si son iguales, falso si no lo son

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual al objeto sin convertir especificado,
que presumiblemente es otra instancia "Dimensions"


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otro objeto, que presumiblemente es del tipo "Dimensions", que debe comprobarse la igualdad con este |
|

**Returns:**
booleano - Verdadero si son iguales, falso si no lo son

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia, que no puede ser modificado durante su
vida útil


**Returns:**
int - Código hash inmutable (para esta instancia) como entero con signo de 4 bytes

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Comprueba si dos valores de "Dimensions" son iguales, es decir, tienen iguales
ancho y alto, o ambos están vacíos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Primera instancia a comprobar |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Segunda instancia a comprobar |
|

**Returns:**
booleano - Verdadero si son iguales, falso si no lo son

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Comprueba si dos valores de "Dimensions" no son iguales, es decir, sus
el ancho y/o alto correspondientes son diferentes


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Primera instancia a comprobar |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Segunda instancia a comprobar |
|

**Returns:**
booleano - Verdadero si son desiguales, falso si son iguales

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en cadena de este "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - Instancia de String, que contiene un ancho y alto en formato W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Devuelve una copia completa de esta instancia


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Devuelve una instancia Dimensions vacía


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
