---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para generar y guardar documentos PDF Portable Document Format"
type: docs
weight: 31
url: /es/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar PDF (Portable
Document Format) documentos

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Contraseña, que se aplicará al documento PDF generado como contraseña de usuario, requerida para abrir. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Contraseña, que se aplicará al documento PDF generado como contraseña de usuario, requerida para abrir. |
|
|  | [getCompliance()](#getCompliance--) | Especifica el nivel de cumplimiento de los estándares PDF para los documentos de salida. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Especifica el nivel de cumplimiento de los estándares PDF para los documentos de salida. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsable de incrustar los recursos de fuentes en el documento PDF resultante, que se utilizan en el documento original. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Responsable de incrustar los recursos de fuentes en el documento PDF resultante, que se utilizan en el documento original. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Contraseña, que se aplicará al documento PDF generado como contraseña de usuario, requerida para abrir.
Si es NULL o está vacío, no se aplicará ninguna contraseña al documento. De lo contrario, el documento se encriptará con RC4 (longitud de clave de 128 bits).
Por defecto es NULL \u2014 no se aplica contraseña.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Contraseña, que se aplicará al documento PDF generado como contraseña de usuario, requerida para abrir.
Si es NULL o está vacío, no se aplicará ninguna contraseña al documento. De lo contrario, el documento se encriptará con RC4 (longitud de clave de 128 bits).
Por defecto es NULL \u2014 no se aplica contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Especifica el nivel de cumplimiento de los estándares PDF para los documentos de salida. Por defecto es PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Especifica el nivel de cumplimiento de los estándares PDF para los documentos de salida. Por defecto es PdfCompliance.Pdf17.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsable de incrustar los recursos de fuentes en el documento PDF resultante, que se utilizan en el documento original. Por defecto no incrusta ninguna fuente (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsable de incrustar los recursos de fuentes en el documento PDF resultante, que se utilizan en el documento original. Por defecto no incrusta ninguna fuente (NotEmbed).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción en true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción en true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

