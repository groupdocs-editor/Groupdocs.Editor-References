---
title: "PresentationLoadOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para cargar documentos de todos los formatos de Presentación compatibles, como PPTX, PPTM, PPSX, etc."
type: docs
weight: 33
url: /es/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Permite especificar opciones personalizadas para cargar documentos de todos los compatibles
Formatos de Presentación como PPT(X), PPTM, PPS(X), etc.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abriendo el documento Presentation, si está codificado.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abriendo el documento Presentation, si está codificado.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abriendo el documento Presentation, si está codificado. Establecer a NULL o vacío
cadena para eliminar la contraseña.


*** ** * ** ***

Por defecto, esta propiedad tiene el valor NULL \u2014 la contraseña no está establecida. Si el documento Presentation de entrada está protegido con contraseña, la contraseña es obligatoria y se lanzará una excepción si la contraseña no se especifica o es inválida. Si el documento Presentation de entrada NO está protegido con contraseña, pero la contraseña está establecida, se ignorará.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abriendo el documento Presentation, si está codificado. Establecer a NULL o vacío
cadena para eliminar la contraseña.


*** ** * ** ***

Por defecto, esta propiedad tiene el valor NULL \u2014 la contraseña no está establecida. Si el documento Presentation de entrada está protegido con contraseña, la contraseña es obligatoria y se lanzará una excepción si la contraseña no se especifica o es inválida. Si el documento Presentation de entrada NO está protegido con contraseña, pero la contraseña está establecida, se ignorará.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

