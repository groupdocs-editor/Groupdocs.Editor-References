---
title: "AudioType"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa un formato de tipo de audio soportado"
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Representa un tipo de audio soportado (formato).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Nombre formal de este formato de audio |
|
|  | [getFileExtension()](#getFileExtension--) | Extensión de nombre de archivo (sin el carácter punto) para este formato de audio |
|
|  | [getMimeCode()](#getMimeCode--) | Código MIME para este formato de audio |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Determina si esta instancia es igual a la instancia "AudioType" especificada |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual al objeto no casteado especificado, que presumiblemente es otra instancia "AudioType" |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Comprueba si dos valores "AudioType" son iguales |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Comprueba si dos valores "AudioType" no son iguales |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash, que es un número constante para este tipo de valor específico |
|
|  | [getUndefined()](#getUndefined--) | Valor especial, que marca un formato de audio indefinido, desconocido o no soportado |
|
|  | [getMp3()](#getMp3--) | Representa un formato de audio MPEG-1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Devuelve el valor AudioType, que es equivalente a la extensión de nombre de archivo, extraída del nombre de archivo especificado |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Nombre formal de este formato de audio


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extensión de nombre de archivo (sin el carácter punto) para este formato de audio


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Código MIME para este formato de audio


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Determina si esta instancia es igual a la instancia "AudioType" especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Otra instancia de AudioType para comprobar con esta |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual al objeto no casteado especificado, que presumiblemente es otra instancia "AudioType"


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia, presumiblemente de la estructura AudioType, que fue encapsulada a System.Object |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Comprueba si dos valores "AudioType" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Primer AudioType a comprobar |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Segundo AudioType a comprobar |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Comprueba si dos valores "AudioType" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Primer AudioType a comprobar |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Segundo AudioType a comprobar |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash, que es un número constante para este tipo de valor específico


**Returns:**
int - entero con signo de 4 bytes, 0 para valor Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Valor especial, que marca un formato de audio indefinido, desconocido o no soportado


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Representa un formato de audio MPEG-1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Devuelve el valor AudioType, que es equivalente a la extensión de nombre de archivo, extraída del nombre de archivo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre de archivo | java.lang.String | Nombre de archivo arbitrario, puede ser una ruta relativa o completa |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

