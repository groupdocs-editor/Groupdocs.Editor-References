---
title: Editor
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Clase principal que encapsula los métodos de conversión. La clase Editor proporciona métodos para cargar editar y guardar documentos de todos los formatos admitidos. Es desechable así que use una directiva de uso o elimine sus recursos manualmente a través de la llamada al método Dispose . La carga de documentos se realiza a través de constructores. Edición de documentos a través del método Editar y guardar de nuevo en el documento resultante después de la edición a través del método Guardar.
type: docs
weight: 20
url: /es/net/groupdocs.editor/editor/
---
## Editor class

Clase principal, que encapsula los métodos de conversión. La clase Editor proporciona métodos para cargar, editar y guardar documentos de todos los formatos admitidos. Es desechable, así que use una directiva de 'uso' o elimine sus recursos manualmente a través de la llamada al método 'Dispose ()'. La carga de documentos se realiza a través de constructores. Edición de documentos: a través del método 'Editar' y guardar de nuevo en el documento resultante después de la edición, a través del método 'Guardar'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Inicializa la nueva instancia del Editor con el documento de entrada especificado (como flujo) |
| [Editor](editor#constructor_2)(string) | Inicializa la nueva instancia del Editor con el documento de entrada especificado (como una ruta de archivo completa) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Inicializa la nueva instancia del Editor con el documento de entrada especificado (como flujo) con sus opciones de carga |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Inicializa la nueva instancia del Editor con el documento de entrada especificado (como una ruta de archivo completa) con sus opciones de carga |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indica si esta instancia del Editor ya se eliminó y ya no se puede usar (verdadero) o si aún no se eliminó y, por lo tanto, está activa (falso) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Elimina esta instancia de Editor, de modo que libera todos los recursos internos y deja de estar disponible para su uso posterior |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Abre un documento previamente cargado para editar usando las opciones predeterminadas al generar y devolver una instancia de '[`EditableDocument`](../editabledocument) clase, que, a su vez, contiene métodos para producir marcado HTML y recursos asociados. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Abre un documento previamente cargado para editarlo usando opciones específicas de formato específicas al generar y devolver una instancia de '[`EditableDocument`](../editabledocument) clase, que, a su vez, contiene métodos para producir marcado HTML y recursos asociados. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Devuelve metadatos sobre el documento, que se cargó en esta instancia de 'Editor' |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Convierte el documento editado especificado, representado como instancia de '[`EditableDocument`](../editabledocument) , al documento resultante de formato especificado y guarda su contenido en stream especificado |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Convierte el documento editado especificado, representado como instancia de '[`EditableDocument`](../editabledocument) , al documento resultante del formato especificado y guarda su contenido en un archivo mediante la ruta de archivo especificada |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Evento, que ocurre cuando esta instancia del Editor se desecha con todos sus recursos internos |

### Observaciones

La clase Editor debe considerarse como un punto de entrada y el objeto raíz de GroupDocs.Editor. Todas las operaciones se realizan utilizando esta clase. El uso típico de la clase Editor para realizar una canalización completa de edición de documentos es el siguiente:

1. Cargue un documento en la instancia del Editor a través de su constructor.
2. Opcionalmente, detecte un tipo de documento usando un[`GetDocumentInfo`](./getdocumentinfo) método.
3. Abra un documento para editar llamando a un[`Edit`](./edit)método y obtener una instancia de[`EditableDocument`](../editabledocument) clase de ella.
4. Edición del contenido de un documento en el lado del cliente utilizando cualquier editor HTML WYSIWYG.
5. Crear una nueva instancia de[`EditableDocument`](../editabledocument) del contenido del documento editado.
6. Guardar un documento editado en algún formato de salida llamando a un[`Save`](./save) método.
7. Desechar una instancia de la clase Editor a través del operador 'usar' o manualmente.

### Ver también

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* espacio de nombres [GroupDocs.Editor](../../groupdocs.editor)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
