---
title: "PdfLoadOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Contiene opciones para cargar documentos PDF en la clase Editor"
type: docs
weight: 30
url: /es/nodejs-java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Contiene opciones para cargar documentos PDF en la clase Editor

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar y obtener la contraseña que se usará para abrir un documento PDF, si está codificado. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar y obtener la contraseña que se usará para abrir un documento PDF, si está codificado. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar y obtener la contraseña que se usará para abrir un documento PDF, si está codificado.
Establecer a NULL o cadena vacía para no usar la contraseña (valor predeterminado).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar y obtener la contraseña que se usará para abrir un documento PDF, si está codificado.
Establecer a NULL o cadena vacía para no usar la contraseña (valor predeterminado).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

