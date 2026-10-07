---
title: "Editor"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Clase principal que encapsula los métodos de conversión."
type: docs
weight: 11
url: /es/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Clase principal, que encapsula los métodos de conversión.
La clase Editor proporciona métodos para cargar, editar y guardar documentos de todos los formatos compatibles. Es desechable, por lo que use una directiva 'using' o libere sus recursos manualmente mediante una llamada al método 'Dispose()'. La carga de documentos se realiza a través de constructores. La edición de documentos - mediante el método 'Edit', y el guardado del documento resultante después de la edición - mediante el método 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Inicializa una nueva instancia de la clase [Editor](../../com.groupdocs.editor/editor) y crea un nuevo documento vacío basado en el formato especificado. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un flujo) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un |
flujo) con sus opciones de carga y la configuración de Editor
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) con sus opciones de carga |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Abre un documento previamente cargado para su edición usando opciones específicas de formato, generando y devolviendo una instancia de la clase '' que, a su vez, contiene métodos para producir marcado HTML y recursos asociados. |
|
|  | [edit()](#edit--) | Abre un documento previamente cargado para su edición usando opciones predeterminadas por |
generando y devolviendo una instancia de la clase 'EditableDocument', que,
a su vez, contiene métodos para producir marcado HTML y asociados
recursos.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Convierte el documento editado especificado, representado como instancia de |
'EditableDocument', al documento resultante del formato especificado y
guarda su contenido en el flujo especificado
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Convierte el documento editado especificado, representado como instancia de '', al documento resultante del formato especificado y guarda su contenido en un archivo mediante la ruta de archivo especificada |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Convierte el documento editado especificado (representado por un [EditableDocument](../../com.groupdocs.editor/editabledocument)) a un documento de salida cuyo formato se determina a partir de la extensión del nombre de archivo, y lo guarda en la ruta de archivo especificada. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Convierte el documento original después de la modificación (por ejemplo, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
al documento resultante del formato especificado y guarda su contenido en el flujo proporcionado.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Guarde el contenido del documento actual en el flujo de salida especificado. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Devuelve los metadatos del documento que se cargó en esta instancia de 'Editor' |
|
|  | [dispose()](#dispose--) | Desecha esta instancia de Editor, de modo que libere todo lo interno |
recursos y deja de estar disponible para uso posterior
|
|  | [isDisposed()](#isDisposed--) | Indica si esta instancia de Editor ya fue eliminada y no puede ser |
utilizada más (true) o no, y está activa (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Inicializa una nueva instancia de la clase [Editor](../../com.groupdocs.editor/editor) y crea un nuevo documento vacío basado en el formato especificado.

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | representa el formato de archivo del documento que se creará. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un flujo)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | Delegado, que debe devolver un flujo con el contenido del documento. No debe ser NULL. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un
flujo) con sus opciones de carga y la configuración de Editor


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | Delegado, que debe devolver un flujo con el contenido del documento. No debe ser NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegado, que debe devolver opciones de carga del documento. Puede ser NULL y puede devolver null; en ese caso el tipo de documento se detectará automáticamente y se aplicarán las opciones de carga predeterminadas para ese tipo. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta completa al archivo. No debe ser NULL. Debe ser válida y el archivo debe existir. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) con sus opciones de carga


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta completa al archivo. No debe ser NULL. Debe ser válida y el archivo debe existir. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegado, que debe devolver opciones de carga del documento. Puede ser NULL y puede devolver null; en ese caso el tipo de documento se detectará automáticamente y se aplicarán las opciones de carga predeterminadas para ese tipo. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Abre un documento previamente cargado para su edición usando opciones específicas de formato, generando y devolviendo una instancia de la clase '' que, a su vez, contiene métodos para producir marcado HTML y recursos asociados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Opciones de documento específicas del formato, que permiten ajustar el proceso de conversión. No debe ser NULL. No debe entrar en conflicto con las opciones de carga aplicadas previamente. |


*** ** * ** ***

Cuando el documento original de entrada se carga en la instancia 'Editor' mediante el constructor, este método permite abrir el documento para su edición convirtiéndolo a un formato intermedio, que está encapsulado dentro de una instancia de la clase 'EditableDocument'. 'EditableDocument', devuelta por este método, contiene todos los métodos y propiedades necesarios para generar marcado HTML y los recursos correspondientes (como imágenes, fuentes y hojas de estilo) en todas las configuraciones necesarias para su posterior paso a cualquier editor HTML WYSIWYG. Esta sobrecarga obtiene opciones de edición específicas para familias de formatos.

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


Abre un documento previamente cargado para su edición usando opciones predeterminadas por
generando y devolviendo una instancia de la clase 'EditableDocument', que,
a su vez, contiene métodos para producir marcado HTML y asociados
recursos.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Cuando el documento original de entrada se carga en la instancia 'Editor' mediante el constructor, este método permite abrir el documento para su edición convirtiéndolo a un formato intermedio, que está encapsulado dentro de una instancia de la clase 'EditableDocument'. 'EditableDocument', devuelta por este método, contiene todos los métodos y propiedades necesarios para generar marcado HTML y los recursos correspondientes (como imágenes, fuentes y hojas de estilo) en todas las configuraciones necesarias para su posterior paso a cualquier editor HTML WYSIWYG. Esta sobrecarga aplica opciones de edición que son predeterminadas para el formato al que pertenece el documento de entrada.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Convierte el documento editado especificado, representado como instancia de
'EditableDocument', al documento resultante del formato especificado y
guarda su contenido en el flujo especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versión del documento de entrada, que fue editado en un editor HTML WYSIWYG y se almacena como instancia de la clase 'EditableDocument', la cual debe convertirse al documento de salida de un formato específico |
|
|  | outputDocument | java.io.OutputStream | Flujo de salida, en el que se registrará el contenido del documento resultante. No debe ser NULL, estar eliminado, y debe soportar escritura. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Opciones de guardado del documento, que definen el formato del documento resultante, así como opciones de guardado generales y específicas del formato. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Convierte el documento editado especificado, representado como instancia de '', al documento resultante del formato especificado y guarda su contenido en un archivo mediante la ruta de archivo especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versión del documento de entrada, que fue editado en un editor HTML WYSIWYG y se almacena como instancia de la clase '' , la cual debe convertirse al documento de salida de un formato específico. No debe ser null ni estar eliminado. |
|
|  | filePath | java.lang.String | Ruta al archivo en el que se guardará el documento de salida. Si existe un archivo con el mismo nombre, será sobrescrito completamente. La cadena de ruta no debe ser null, estar vacía o contener solo espacios en blanco. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Opciones de guardado del documento, que definen el formato del documento resultante, así como opciones de guardado generales y específicas del formato. No debe ser null. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Convierte el documento editado especificado (representado por un [EditableDocument](../../com.groupdocs.editor/editabledocument)) a un documento de salida cuyo formato se determina a partir de la extensión del nombre de archivo, y lo guarda en la ruta de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versión del documento de entrada que fue editado en un editor HTML WYSIWYG y se almacena como una instancia de [EditableDocument](../../com.groupdocs.editor/editabledocument). No debe ser  null  ni estar eliminado. |
|
|  | filePath | java.lang.String | Ruta al archivo donde se guardará el documento de salida. Si existe un archivo con el mismo nombre, será sobrescrito completamente. La cadena de ruta no debe ser  null , estar vacía o contener solo espacios en blanco. Debido a que las opciones de guardado predeterminadas y el formato de salida se determinan a partir de este nombre de archivo, debe tener una extensión válida. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Convierte el documento original después de la modificación (por ejemplo,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
al documento resultante del formato especificado y guarda su contenido en el flujo proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | El flujo al que se guardará el documento de salida. Este flujo debe ser escribible y estar posicionado al inicio del contenido del documento. No debe ser nulo. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Opciones de guardado del documento que definen el formato del documento resultante, así como opciones de guardado generales y específicas del formato. No debe ser nulo. |

<br />

*** ** * ** ***

Si el outputDocument o saveOptions es nulo, se lanzará una NullPointerException. Si falta el documento a guardar, se lanzará una NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - El flujo que contiene el contenido del documento guardado.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Guarde el contenido del documento actual en el flujo de salida especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | El flujo al que se guardará el contenido del documento. Esto no puede ser nulo. |

<br />

*** ** * ** ***

Este método copia el contenido de la representación interna del documento al flujo de salida proporcionado. La posición original del flujo se conserva después de la operación de guardado.

<br />

|

**Returns:**
java.io.OutputStream - El flujo con el contenido del documento guardado.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Devuelve los metadatos del documento que se cargó en esta instancia de 'Editor'


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contraseña | java.lang.String | El usuario puede especificar una contraseña para un documento, si este documento está encriptado con la contraseña. Puede ser NULL o una cadena vacía, lo que equivale a la ausencia de contraseña. Para aquellos formatos de documento que no tienen una función de protección con contraseña, este argumento será ignorado. Si el documento está encriptado y la contraseña no se especifica en este parámetro, pero se especificó anteriormente en las opciones de carga al crear esta instancia, se utilizará. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Desecha esta instancia de Editor, de modo que libere todo lo interno
recursos y deja de estar disponible para uso posterior


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Indica si esta instancia de Editor ya fue eliminada y no puede ser
utilizada más (true) o no, y está activa (false)


**Returns:**
boolean
