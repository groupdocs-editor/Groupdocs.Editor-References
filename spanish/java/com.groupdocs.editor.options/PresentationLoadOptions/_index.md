---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para cargar documentos de todos los formatos de presentación compatibles, como PPTX, PPTM, PPSX, etc."
type: docs
weight: 33
url: /es/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Permite especificar opciones personalizadas para cargar documentos de todos los compatibles
Formatos de presentación como PPT(X), PPTM, PPS(X), etc.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abrir el documento de presentación, si está codificado.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abrir el documento de presentación, si está codificado.
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
abrir el documento de presentación, si está codificado. Establezca en NULL o vacío
cadena para eliminar la contraseña.


*** ** * ** ***

Por defecto, esta propiedad tiene el valor NULL — la contraseña no está establecida. Si el documento de presentación de entrada está protegido con contraseña, la contraseña es obligatoria y se lanzará una excepción si no se especifica o es inválida. Si el documento de presentación de entrada NO está protegido con contraseña, pero se establece una contraseña, será ignorada.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abrir el documento de presentación, si está codificado. Establezca en NULL o vacío
cadena para eliminar la contraseña.


*** ** * ** ***

Por defecto, esta propiedad tiene el valor NULL — la contraseña no está establecida. Si el documento de presentación de entrada está protegido con contraseña, la contraseña es obligatoria y se lanzará una excepción si no se especifica o es inválida. Si el documento de presentación de entrada NO está protegido con contraseña, pero se establece una contraseña, será ignorada.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

