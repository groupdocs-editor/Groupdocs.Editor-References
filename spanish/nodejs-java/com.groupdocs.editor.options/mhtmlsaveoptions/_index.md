---
title: "MhtmlSaveOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para generar y guardar la encapsulación MIME MHTML de documentos HTML agregados documentos"
type: docs
weight: 26
url: /es/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar los documentos MHTML (encapsulación MIME de documentos HTML agregados)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Especifica si se deben usar URLs CID (Content-ID) para referenciar recursos (imágenes, fuentes, CSS) incluidos en documentos MHTML. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Especifica si se deben usar URLs CID (Content-ID) para referenciar recursos (imágenes, fuentes, CSS) incluidos en documentos MHTML. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Especifica si se exportan las propiedades de documento incorporadas y personalizadas a MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Especifica si se exportan las propiedades de documento incorporadas y personalizadas a MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Especifica si la información de idioma se exporta a MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Especifica si la información de idioma se exporta a MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Especifica si se deben usar URLs CID (Content-ID) para referenciar recursos (imágenes, fuentes, CSS) incluidos en documentos MHTML. El valor predeterminado es
false
.

<br />

*** ** * ** ***


Por defecto, los recursos en los documentos MHTML se referencian por nombre de archivo (por ejemplo, "image.png"), que se comparan con los encabezados "Content-Location" de las partes MIME. Esta opción habilita un método alternativo, donde las referencias a los archivos de recursos se escriben como URLs CID (Content-ID) (por ejemplo, "cid:image.png") y se comparan con los encabezados "Content-ID".


En teoría, no debería haber diferencia entre los dos métodos de referencia y cualquiera de ellos debería funcionar correctamente en cualquier navegador o cliente de correo. En la práctica, sin embargo, algunos agentes no pueden obtener los recursos por nombre de archivo. Si tu navegador o cliente de correo se niega a cargar los recursos incluidos en un documento MTHML (no muestra imágenes o no carga estilos CSS), intenta exportar el documento con URLs CID.

<br />



**Returns:**
booleano
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Especifica si se deben usar URLs CID (Content-ID) para referenciar recursos (imágenes, fuentes, CSS) incluidos en documentos MHTML. El valor predeterminado es
false
.

<br />

*** ** * ** ***


Por defecto, los recursos en los documentos MHTML se referencian por nombre de archivo (por ejemplo, "image.png"), que se comparan con los encabezados "Content-Location" de las partes MIME. Esta opción habilita un método alternativo, donde las referencias a los archivos de recursos se escriben como URLs CID (Content-ID) (por ejemplo, "cid:image.png") y se comparan con los encabezados "Content-ID".


En teoría, no debería haber diferencia entre los dos métodos de referencia y cualquiera de ellos debería funcionar correctamente en cualquier navegador o cliente de correo. En la práctica, sin embargo, algunos agentes no pueden obtener los recursos por nombre de archivo. Si tu navegador o cliente de correo se niega a cargar los recursos incluidos en un documento MTHML (no muestra imágenes o no carga estilos CSS), intenta exportar el documento con URLs CID.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Especifica si se exportan las propiedades de documento incorporadas y personalizadas a MHTML. El valor predeterminado es
false
.


**Returns:**
booleano
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Especifica si se exportan las propiedades de documento incorporadas y personalizadas a MHTML. El valor predeterminado es
false
.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Especifica si la información de idioma se exporta a MHTML. El valor predeterminado es
false
.

<br />

*** ** * ** ***

Cuando esta propiedad se establece en  true , el GroupDocs.Editor genera el atributo HTML  lang  en los elementos del documento que especifican el idioma. Esto puede ser necesario para preservar la semántica relacionada con el idioma.

<br />



**Returns:**
booleano
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Especifica si la información de idioma se exporta a MHTML. El valor predeterminado es
false
.

<br />

*** ** * ** ***

Cuando esta propiedad se establece en  true , el GroupDocs.Editor genera el atributo HTML  lang  en los elementos del documento que especifican el idioma. Esto puede ser necesario para preservar la semántica relacionada con el idioma.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

