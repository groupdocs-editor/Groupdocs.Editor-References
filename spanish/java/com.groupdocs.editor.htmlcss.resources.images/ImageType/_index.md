---
title: "ImageType"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un formato de tipo de imagen soportable que admite tanto formatos raster como vectoriales"
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Representa un tipo de imagen soportable (formato), admite tanto formatos raster como vectoriales.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Tipo de imagen indefinido - valor especial, que normalmente no debería ocurrir |
|
|  | [getJpeg()](#getJpeg--) | Tipo de imagen JPEG |
|
|  | [getPng()](#getPng--) | Tipo de imagen PNG |
|
|  | [getBmp()](#getBmp--) | Tipo de imagen BMP |
|
|  | [getGif()](#getGif--) | Tipo de imagen GIF |
|
|  | [getIcon()](#getIcon--) | Tipo de imagen ICON |
|
|  | [getSvg()](#getSvg--) | Tipo de imagen vectorial SVG |
|
|  | [getWmf()](#getWmf--) | Tipo de imagen vectorial WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | Tipo de imagen vectorial EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | Tipo de imagen raster TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Devuelve un nombre formal de este formato de imagen. |
|
|  | [isVector()](#isVector--) | Indica si este formato particular es vectorial (true) o raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Extensión de archivo (sin el carácter de punto inicial) de un tipo de imagen particular |
en minúsculas.
|
|  | [toString()](#toString--) | Devuelve la propiedad FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | Código MIME de un tipo de imagen particular como cadena. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Determina si esta instancia es igual a la "ImageType" especificada |
instancia
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual al objeto sin convertir especificado, |
que presumiblemente es otra instancia de "ImageType"
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Define si dos instancias específicas de ImageType son iguales |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Define si dos instancias específicas de ImageType no son iguales |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash, que es un número inmutable para este específico |
instancia
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Devuelve el valor ImageType, que es equivalente a la extensión del nombre de archivo, que |
se extrae del nombre de archivo especificado
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Devuelve el valor ImageType, que es equivalente al código MIME especificado |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Tipo de imagen indefinido - valor especial, que normalmente no debería ocurrir


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


Tipo de imagen JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


Tipo de imagen PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


Tipo de imagen BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


Tipo de imagen GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


Tipo de imagen ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


Tipo de imagen vectorial SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


Tipo de imagen vectorial WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


Tipo de imagen vectorial EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


Tipo de imagen raster TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Devuelve un nombre formal de este formato de imagen. Nunca devuelve NULL. Si
la instancia no está corrupta, nunca lanza una excepción.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Indica si este formato particular es vectorial (true) o raster
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extensión de archivo (sin el carácter de punto inicial) de un tipo de imagen particular
en minúsculas. Para el tipo Undefined devuelve la cadena 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Devuelve la propiedad FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Código MIME de un tipo de imagen particular como cadena. Para el tipo Undefined
devuelve la cadena 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Determina si esta instancia es igual a la "ImageType" especificada
instancia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Otra instancia de ImageType para comprobar la igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual al objeto sin convertir especificado,
que presumiblemente es otra instancia de "ImageType"


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia de System.Object, que presumiblemente es del tipo ImageType, para comprobar la igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Define si dos instancias específicas de ImageType son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Primera instancia de ImageType para comprobar |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Segunda instancia de ImageType para comprobar |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Define si dos instancias específicas de ImageType no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Primera instancia de ImageType para comprobar |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Segunda instancia de ImageType para comprobar |
|

**Returns:**
booleano - Verdadero si son desiguales, falso si son iguales

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash, que es un número inmutable para este específico
instancia


**Returns:**
int - Entero con signo de 4 bytes

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Devuelve el valor ImageType, que es equivalente a la extensión del nombre de archivo, que
se extrae del nombre de archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre de archivo | java.lang.String | Nombre de archivo arbitrario, puede ser una ruta relativa o completa |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Devuelve el valor ImageType, que es equivalente al código MIME especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Código MIME arbitrario |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

