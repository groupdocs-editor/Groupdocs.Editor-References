---
title: "WordProcessingLoadOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Contiene opciones para cargar documentos compatibles con WordProcessing (compatibles con Word) como DOCX, RTF, ODT, etc."
type: docs
weight: 45
url: /es/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Contiene opciones para cargar documentos WordProcessing (compatibles con Word) como
DOC(X), RTF, ODT, etc. en la clase Editor

## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abrir el documento WordProcessing, si está codificado.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abrir el documento WordProcessing, si está codificado.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abriendo documento WordProcessing, si está codificado. Establecer a NULL o vacío
cadena para no usar la contraseña (valor predeterminado).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abriendo documento WordProcessing, si está codificado. Establecer a NULL o vacío
cadena para no usar la contraseña (valor predeterminado).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

