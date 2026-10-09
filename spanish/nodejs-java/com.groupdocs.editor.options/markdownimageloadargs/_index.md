---
title: "MarkdownImageLoadArgs"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Proporciona datos para el evento MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /es/nodejs-java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Proporciona datos para el

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

evento.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Obtiene o establece el nombre de archivo (tal como está en el documento Markdown) que será |
procesado.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Obtiene o establece el nombre de archivo (tal como está en el documento Markdown) que será |
procesado.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Obtenga un valor que indique si esta imagen tiene un enlace URI absoluto. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Obtenga un valor que indique si esta imagen tiene un enlace URI absoluto. |
|
|  | [setData(byte[] data)](#setData-byte---) | Establece los datos proporcionados por el usuario del recurso que se utilizan si |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Obtiene o establece el nombre de archivo (tal como está en el documento Markdown) que será
procesado.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Obtiene o establece el nombre de archivo (tal como está en el documento Markdown) que será
procesado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Obtenga un valor que indique si esta imagen tiene un enlace URI absoluto.
Valor:  true  si esta imagen tiene un enlace URI absoluto; de lo contrario,  false .


**Returns:**
booleano
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Obtenga un valor que indique si esta imagen tiene un enlace URI absoluto.
Valor:  true  si esta imagen tiene un enlace URI absoluto; de lo contrario,  false .


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Establece los datos proporcionados por el usuario del recurso que se utilizan si

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] |  |

