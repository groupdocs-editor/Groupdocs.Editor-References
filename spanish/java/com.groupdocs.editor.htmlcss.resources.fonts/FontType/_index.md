---
title: "FontType"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un tipo de fuente soportable."
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Representa un tipo de fuente soportable.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontType()](#FontType--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Valor especial que indica una fuente indefinida, desconocida o no soportada |
recurso
|
|  | [getWoff()](#getWoff--) | Representa un tipo de fuente WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Representa un tipo de fuente WOFF2 (Web Open Font Format versión 2) |
|
|  | [getTtf()](#getTtf--) | Representa un tipo de fuente TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Representa un tipo de fuente OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Representa una fuente TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Representa un tipo de fuente EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Devuelve el nombre compatible con CSS de este tipo de fuente, que se usa en el |
|
|  | [getFormalName()](#getFormalName--) | Devuelve un nombre formal de este tipo de fuente |
|
|  | [getFileExtension()](#getFileExtension--) | Extensión de archivo (sin el carácter de punto) para este tipo de fuente |
|
|  | [getFontFormat()](#getFontFormat--) | Formato de fuente para el formato @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | Código MIME de un tipo de fuente particular |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Devuelve el valor FontType, que es equivalente al CSS compatible especificado |
nombre del tipo de fuente
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Devuelve el valor FontType, que es equivalente a la extensión de archivo, que |
se extrae del nombre de archivo especificado
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Devuelve el valor FontType, que es equivalente al código MIME especificado |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Devuelve el primer tipo de fuente del conjunto especificado, que no es un "Undefined" |
valor, o tipo de fuente "Undefined" en caso contrario (cuando todos los elementos son
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Determina si esta instancia es igual a la "FontType" especificada |
instancia
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual al objeto sin convertir especificado, |
que presumiblemente es otra instancia "FontType"
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Comprueba si dos valores "FontType" son iguales |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Comprueba si dos valores "FontType" no son iguales |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash, que es un número constante para este valor específico |
tipo
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Valor especial que indica una fuente indefinida, desconocida o no soportada
recurso


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Representa un tipo de fuente WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Representa un tipo de fuente WOFF2 (Web Open Font Format versión 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Representa un tipo de fuente TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Representa un tipo de fuente OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Representa una fuente TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Representa un tipo de fuente EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Devuelve el nombre compatible con CSS de este tipo de fuente, que se usa en el


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Devuelve un nombre formal de este tipo de fuente


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extensión de archivo (sin el carácter de punto) para este tipo de fuente


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Formato de fuente para el formato @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Código MIME de un tipo de fuente particular


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Devuelve el valor FontType, que es equivalente al CSS compatible especificado
nombre del tipo de fuente


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | Nombre compatible con CSS del tipo de fuente |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Devuelve el valor FontType, que es equivalente a la extensión de archivo, que
se extrae del nombre de archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre de archivo | java.lang.String | Nombre de archivo con extensión, puede ser un nombre completo |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Devuelve el valor FontType, que es equivalente al código MIME especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Código MIME |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Devuelve el primer tipo de fuente del conjunto especificado, que no es un "Undefined"
valor, o tipo de fuente "Undefined" en caso contrario (cuando todos los elementos son
"Undefined")


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Uno o más valores FontType, NULL o colección vacía no están permitidos |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Determina si esta instancia es igual a la "FontType" especificada
instancia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Otra instancia FontType para comparar con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual al objeto sin convertir especificado,
que presumiblemente es otra instancia "FontType"


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia presumiblemente de la estructura FontType, que fue encapsulada a System.Object |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Comprueba si dos valores "FontType" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Primer FontType a comprobar |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Segundo FontType a comprobar |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Comprueba si dos valores "FontType" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Primer FontType a comprobar |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Segundo FontType a comprobar |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash, que es un número constante para este valor específico
tipo


**Returns:**
int - entero con signo de 4 bytes, 0 para valor Undefined

