---
title: "Editor"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Clase principal que encapsula los métodos de conversión. La clase Editor proporciona métodos para cargar, editar y guardar documentos de todos los formatos compatibles. Es desechable, por lo que use una directiva using o libere sus recursos manualmente mediante la llamada al método Dispose. La carga de documentos se realiza a través de los constructores. La edición de documentos mediante el método Edit y el guardado del documento resultante después de la edición mediante el método Save."
type: docs
weight: 20
url: /es/net/groupdocs.editor/editor/
---
## Editor class

Clase principal, que encapsula los métodos de conversión. La clase Editor proporciona métodos para cargar, editar y guardar documentos de todos los formatos admitidos. Es desechable, por lo que use una directiva 'using' o libere sus recursos manualmente mediante la llamada al método 'Dispose()'. La carga de documentos se realiza a través de constructores. La edición de documentos — mediante el método 'Edit' — y el guardado del documento resultante después de la edición — mediante el método 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Inicializa una nueva instancia de la clase [`Editor`](../editor) y crea un nuevo documento vacío basado en el formato especificado. |
| [Editor](editor#constructor_1)(Stream) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un flujo). |
| [Editor](editor#constructor_3)(string) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) y la configuración de Editor. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un flujo) y sus opciones de carga. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) y sus opciones de carga. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Proporciona acceso a la funcionalidad para gestionar campos de formulario dentro del documento. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indica si esta instancia de Editor ya fue eliminada y no puede usarse más (true) o si aún no ha sido eliminada y, por lo tanto, está activa (false). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Elimina esta instancia de Editor, liberando todos los recursos internos y haciéndola indisponible para su uso posterior. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Abre un documento previamente cargado para edición usando opciones predeterminadas, generando y devolviendo una instancia de la clase '[`EditableDocument`](../editabledocument)', que, a su vez, contiene métodos para producir marcado HTML y recursos asociados. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Abre un documento previamente cargado para edición usando opciones específicas del formato, generando y devolviendo una instancia de la clase '[`EditableDocument`](../editabledocument)', que, a su vez, contiene métodos para producir marcado HTML y recursos asociados. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Devuelve los metadatos del documento que se cargó en esta instancia de 'Editor'. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Guarda el contenido del documento actual en el flujo de salida especificado. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Convierte el documento editado especificado, representado como una instancia de '[`EditableDocument`](../editabledocument)', al documento resultante de formato determinado por la extensión del nombre de archivo, y guarda su contenido en un archivo en la ruta especificada. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Convierte el documento original después de la modificación (por ejemplo, [`FormFieldManager`](./formfieldmanager)) al documento resultante del formato especificado y guarda su contenido en el flujo proporcionado. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Convierte el documento editado especificado, representado como una instancia de '[`EditableDocument`](../editabledocument)', al documento resultante del formato especificado y guarda su contenido en el flujo especificado. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Convierte el documento editado especificado, representado como una instancia de '[`EditableDocument`](../editabledocument)', al documento resultante del formato especificado y guarda su contenido en un archivo en la ruta especificada. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Evento que ocurre cuando esta instancia de Editor es eliminada junto con todos sus recursos internos. |

### Observaciones

La clase Editor debe considerarse como el punto de entrada y el objeto raíz de GroupDocs.Editor. Todas las operaciones se realizan usando esta clase. El uso típico de la clase Editor para ejecutar una canalización completa de edición de documentos es el siguiente:

1. Carga un documento en la instancia de Editor a través de su constructor.
2. Opcionalmente, detecta el tipo de documento usando el método [`GetDocumentInfo`](./getdocumentinfo).
3. Abre un documento para edición llamando al método [`Edit`](./edit) y obteniendo una instancia de la clase [`EditableDocument`](../editabledocument) a partir de él.
4. Edita el contenido del documento en el cliente usando cualquier editor HTML WYSIWYG.
5. Crea una nueva instancia de [`EditableDocument`](../editabledocument) a partir del contenido del documento editado.
6. Guarda un documento editado en algún formato de salida llamando al método [`Save`](./save).
7. Eliminando una instancia de la clase Editor mediante el operador 'using' o manualmente.

### Ver también

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
