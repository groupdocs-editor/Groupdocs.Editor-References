---
title: "EditableDocument"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Documento intermedio que contiene el contenido antes y después de la edición"
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Documento intermedio, que contiene contenido antes y después de la edición.


*** ** * ** ***

Una instancia de la clase EditableDocument puede ser producida por el método Editor.edit() o creada por el propio usuario mediante fábricas estáticas. EditableDocument almacena internamente el documento en su propio formato cerrado, que es compatible (convertible) con todos los formatos de importación y exportación que soporta GroupDocs.Editor. Para que el documento sea editable en cualquier editor WYSIWYG del lado del cliente (como CKEditor o TinyMCE), EditableDocument proporciona métodos para generar marcado HTML y producir recursos que pueden ser aceptados por el usuario.

<br />


## Campos

| Campo | Descripción |
| --- | --- |
| [Disposed](#Disposed) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getImages()](#getImages--) | Permite obtener recursos de imagen externos (imágenes raster), que se utilizan |
por este documento HTML
|
|  | [getFonts()](#getFonts--) | Permite obtener recursos de fuentes externos, que se utilizan por este HTML |
documento
|
|  | [getCss()](#getCss--) | Devuelve una lista de recursos CSS |
|
|  | [getAudio()](#getAudio--) | Devuelve una lista de recursos de audio |
|
|  | [getAllResources()](#getAllResources--) | Devuelve una lista de todos los recursos existentes: todas las hojas de estilo, imágenes de |
HTML y todas las hojas de estilo, fuentes
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Devuelve el contenido total del documento HTML como un flujo de bytes al escribir este contenido en el flujo especificado con la codificación de texto especificada |
|
|  | [getBodyContent()](#getBodyContent--) | Devuelve el cuerpo del documento HTML (contenido entre la apertura y el cierre |
etiquetas BODY sin estas etiquetas) como una cadena.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Devuelve el cuerpo del documento HTML (contenido entre la apertura y el cierre |
etiquetas BODY sin estas etiquetas) como una cadena, donde los enlaces a los externos
recursos contienen el prefijo especificado.
|
|  | [getContent()](#getContent--) | Devuelve el contenido total del documento HTML como una cadena. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Devuelve el contenido total del documento HTML como una cadena, donde los enlaces a |
los recursos externos contienen el prefijo especificado.
|
|  | [getCssContent()](#getCssContent--) | Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde |
una cadena representa una hoja de estilo.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde |
una cadena representa una hoja de estilo.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Devuelve todo el contenido de este documento HTML con todos los recursos relacionados en un |
formato de una única cadena, donde todos los recursos están incrustados dentro del HTML
marcado en forma codificada en base64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Guarda este documento HTML en el archivo en la ruta especificada, donde el marcado HTML |
se almacenará, y en la carpeta adjunta con los recursos.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Guarda este documento HTML en el archivo en la ruta especificada, donde el marcado HTML |
se almacenará, y en la carpeta adjunta con los recursos, que es
ubicada en la ruta especificada.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Fábrica estática, que crea una instancia de EditableDocument a partir de |
el marcado HTML especificado y un conjunto de recursos vinculados correspondientes
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Fábrica estática, que crea una instancia de EditableDocument a partir de un marcado HTML especificado y de recursos, ubicados en la carpeta, especificada por la ruta completa |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Fábrica estática, que crea una instancia de EditableDocument a partir de un HTML |
archivo, que se especifica mediante una ruta al propio archivo \*.html y una carpeta
con recursos vinculados
|
|  | [dispose()](#dispose--) | Descarta esta instancia de documento Editable, descartando su contenido y |
haciendo que sus métodos y propiedades no funcionen
|
|  | [isDisposed()](#isDisposed--) | Determina si este documento Editable ya fue descartado (true) o |
no (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Permite obtener recursos de imagen externos (imágenes raster), que se utilizan
por este documento HTML


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Permite obtener recursos de fuentes externos, que se utilizan por este HTML
documento


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Devuelve una lista de recursos CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Devuelve una lista de recursos de audio


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Devuelve una lista de todos los recursos existentes: todas las hojas de estilo, imágenes de
HTML y todas las hojas de estilo, fuentes


*** ** * ** ***

Esta propiedad devuelve un resultado concatenado de las propiedades 'Images', 'Fonts' y 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Devuelve el contenido total del documento HTML como un flujo de bytes al escribir este contenido en el flujo especificado con la codificación de texto especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | almacenamiento | java.io.OutputStream | Secuencia de bytes no nula, que admite escritura |
|
|  | codificación | java.nio.charset.Charset | Codificación de texto no nula, que debe aplicarse al escribir contenido de texto en el almacenamiento especificado |


TStream
: Cualquier implementación de java.io.InputStream
|

**Returns:**
java.io.OutputStream - Instancia del almacenamiento especificado

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Devuelve el cuerpo del documento HTML (contenido entre la apertura y el cierre
etiquetas BODY sin estas etiquetas) como una cadena.


**Returns:**
java.lang.String - Cadena, que contiene el cuerpo del documento HTML


*** ** * ** ***

Los editores WYSIWYG operan con el cuerpo del documento y no pueden procesar correctamente su información meta del bloque HEAD. Este método está diseñado para esos casos. Esta sobrecarga no permite ajustar URIs para solicitudes de recursos externos.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Devuelve el cuerpo del documento HTML (contenido entre la apertura y el cierre
etiquetas BODY sin estas etiquetas) como una cadena, donde los enlaces a los externos
recursos contienen el prefijo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | A través de este parámetro se puede especificar un prefijo, que se añadirá a los enlaces de todas las imágenes externas en los elementos IMG, que estarán presentes en la cadena HTML resultante. Si es NULL o está vacío, no se añadirán prefijos. |


*** ** * ** ***

Los editores WYSIWYG operan con el cuerpo del documento y no pueden procesar correctamente su información meta del bloque HEAD. Este método está diseñado para esos casos. Esta sobrecarga permite ajustar URIs para solicitudes de recursos externos.

<br />

|

**Returns:**
java.lang.String - Cadena, que contiene el cuerpo del documento HTML con enlaces, ajustados a las imágenes externas

### getContent() {#getContent--}
```
public String getContent()
```


Devuelve el contenido total del documento HTML como una cadena.


**Returns:**
java.lang.String - Cadena, que contiene el contenido del documento HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Devuelve el contenido total del documento HTML como una cadena, donde los enlaces a
los recursos externos contienen el prefijo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | A través de este parámetro se puede especificar un prefijo, que se añadirá a los enlaces de todas las imágenes externas en los elementos IMG, que estarán presentes en la cadena HTML resultante. Si es NULL o está vacío, no se añadirán prefijos. |
|
|  | externalCssTemplate | java.lang.String | A través de este parámetro se puede especificar un prefijo, que se añadirá a los enlaces de todas las hojas de estilo externas en los elementos LINK, que estarán presentes en la cadena HTML resultante. Si es NULL o está vacío, no se añadirán prefijos. |
|

**Returns:**
java.lang.String - Cadena, que contiene el contenido del documento HTML con enlaces, ajustados a los recursos externos

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde
Una cadena representa una hoja de estilo. Devuelve una lista vacía, si no hay
CSS para este documento.


**Returns:**
java.util.List<java.lang.String> - Una lista de cadenas, donde cada cadena contiene el contenido de un documento CSS

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde
Una cadena representa una hoja de estilo. El prefijo especificado se aplicará a
cada enlace al recurso externo en cada hoja de estilo resultante.
Devuelve una lista vacía, si no hay CSS para este documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | A través de este parámetro se puede especificar un prefijo, que se añadirá a los enlaces de todas las imágenes externas, que estarán presentes en las declaraciones CSS de las cadenas CSS resultantes. Si es NULL o está vacío, no se añadirán prefijos. |
|
|  | externalFontsPrefix | java.lang.String | A través de este parámetro se puede especificar un prefijo, que se añadirá a los enlaces de todas las fuentes externas en el |
|

**Returns:**
java.util.List<java.lang.String> - Una lista de cadenas, donde cada cadena contiene el contenido de un documento CSS

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Devuelve todo el contenido de este documento HTML con todos los recursos relacionados en un
formato de una única cadena, donde todos los recursos están incrustados dentro del HTML
marcado en forma codificada en base64.


**Returns:**
java.lang.String - String, que no es NULL ni está vacío en ningún caso

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Guarda este documento HTML en el archivo en la ruta especificada, donde el marcado HTML
se almacenará, y en la carpeta adjunta con los recursos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Ruta completa al archivo donde se almacenará el marcado HTML. El archivo será creado o sobrescrito, si existe. La carpeta de recursos adjunta se creará en la misma carpeta donde exista el archivo HTML. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Guarda este documento HTML en el archivo en la ruta especificada, donde el marcado HTML
se almacenará, y en la carpeta adjunta con los recursos, que es
ubicada en la ruta especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Ruta completa al archivo donde se almacenará el marcado HTML. No puede ser NULL ni estar vacío. El archivo será creado o sobrescrito, si existe. |
|
|  | resourcesFolderPath | java.lang.String | Ruta completa a la carpeta adjunta, donde se almacenarán todos los recursos relacionados. Si es NULL o está vacía, la carpeta se creará automáticamente en el mismo directorio donde se encuentre el archivo \*.html. Si se especifica y no existe, se creará. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Fábrica estática, que crea una instancia de EditableDocument a partir de
el marcado HTML especificado y un conjunto de recursos vinculados correspondientes


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, que contiene el marcado HTML sin procesar, que debe ser analizado. No puede ser NULL, estar vacío o ser inválido. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Colección de todos los recursos (imágenes, hojas de estilo, fuentes) que se utilizan en el documento HTML, especificada en el parámetro  newHtmlContent . Puede estar ausente (NULL o colección vacía). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Fábrica estática, que crea una instancia de EditableDocument a partir de un marcado HTML especificado y de recursos, ubicados en la carpeta, especificada por la ruta completa


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, que contiene el marcado HTML sin procesar, que debe ser analizado. No puede ser NULL, estar vacío o ser inválido. |
|
|  | resourceFolderPath | java.lang.String | Ruta obligatoria a la carpeta con recursos. Todas las hojas de estilo ubicadas en esta carpeta se utilizarán. No puede ser NULL ni una cadena vacía, y esta carpeta debe existir. |

<br />

*** ** * ** ***

Esta fábrica estática es útil cuando el contenido del documento HTML se presenta como una cadena, pero todos los recursos se encuentran en alguna carpeta, y con frecuencia los enlaces a estos recursos en el marcado HTML son inválidos o están ausentes. Al invocar este método, escanea la carpeta especificada y aplica automáticamente todas las hojas de estilo encontradas al documento. Este método es muy útil al obtener contenido de diferentes editores HTML, que normalmente recortan los metadatos del documento, etc.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Fábrica estática, que crea una instancia de EditableDocument a partir de un HTML
archivo, que se especifica mediante una ruta al propio archivo \*.html y una carpeta
con recursos vinculados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, que contiene una ruta completa al archivo HTML. No puede ser null, debe ser una ruta de archivo válida, y el propio archivo debe existir. |
|
|  | resourceFolderPath | java.lang.String | Ruta opcional a la carpeta con recursos HTML. Si es NULL, inválida o dicha carpeta no existe, el Editor intentará encontrar esta carpeta por sí mismo, analizando el marcado HTML. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Descarta esta instancia de documento Editable, descartando su contenido y
haciendo que sus métodos y propiedades no funcionen


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determina si este documento Editable ya fue descartado (true) o
no (false)


**Returns:**
booleano
