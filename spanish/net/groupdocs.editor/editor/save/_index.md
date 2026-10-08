---
title: "Save"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte el documento editado especificado representado como instancia de EditableDocumentgroupdocs.editor/editabledocument al documento resultante del formato especificado y guarda su contenido en el flujo especificado."
type: docs
weight: 80
url: /es/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Convierte el documento editado especificado, representado como instancia de '[`EditableDocument`](../../editabledocument)', al documento resultante del formato especificado y guarda su contenido en el flujo especificado.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| inputDocument | EditableDocument | Versión del documento de entrada, que fue editado en el editor HTML WYSIWYG y se almacena como instancia de la clase '[`EditableDocument`](../../editabledocument)', que debe convertirse al documento de salida de un formato específico. No debe ser nulo ni estar dispuesto. |
| outputDocument | Stream | Flujo de salida, en el que se registrará el contenido del documento resultante. No debe ser nulo, estar dispuesto, y debe soportar escritura. |
| saveOptions | ISaveOptions | Opciones de guardado del documento, que definen el formato del documento resultante, y también opciones de guardado generales y específicas del formato. No debe ser nulo. |

### Observaciones

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Ver también

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Convierte el documento editado especificado, representado como instancia de '[`EditableDocument`](../../editabledocument)', al documento resultante del formato especificado y guarda su contenido en un archivo mediante la ruta de archivo especificada.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| inputDocument | EditableDocument | Versión del documento de entrada, que fue editado en el editor HTML WYSIWYG y se almacena como instancia de la clase '[`EditableDocument`](../../editabledocument)', que debe convertirse al documento de salida de un formato específico. No debe ser nulo ni estar dispuesto. |
| filePath | String | Ruta al archivo en el que se guardará el documento de salida. Si existe un archivo con el mismo nombre, será sobrescrito completamente. La cadena con la ruta no debe ser nula, vacía ni contener solo espacios en blanco. |
| saveOptions | ISaveOptions | Opciones de guardado del documento, que definen el formato del documento resultante, y también opciones de guardado generales y específicas del formato. No debe ser nulo. |

### Observaciones

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Ver también

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Convierte el documento editado especificado, representado como instancia de '[`EditableDocument`](../../editabledocument)', al documento resultante con formato determinado por la extensión del nombre de archivo, y guarda su contenido en un archivo en la ruta especificada.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| inputDocument | EditableDocument | Versión del documento de entrada, que fue editado en el editor HTML WYSIWYG y se almacena como instancia de la clase '[`EditableDocument`](../../editabledocument)', que debe convertirse al documento de salida de un formato específico. No debe ser nulo ni estar dispuesto. |
| filePath | String | Ruta al archivo en el que se guardará el documento de salida. Si existe un archivo con el mismo nombre, será sobrescrito por completo. La cadena con la ruta no debe ser nula, vacía ni contener solo espacios en blanco. Debido a que las opciones de guardado predeterminadas y el formato de salida se determinan a partir de este nombre de archivo, debe tener una extensión válida. |

### Ver también

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Convierte el documento original después de la modificación (por ejemplo, [`FormFieldManager`](../formfieldmanager)), al documento resultante del formato especificado y guarda su contenido en el flujo proporcionado.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| outputDocument | Stream | El flujo al que se guardará el documento de salida. Este flujo debe ser escribible y estar posicionado al inicio del contenido del documento. No debe ser nulo. |
| saveOptions | WordProcessingSaveOptions | Opciones de guardado del documento que definen el formato del documento resultante, así como opciones de guardado generales y específicas del formato. No debe ser nulo. |

### Valor devuelto

El flujo que contiene el contenido del documento guardado.

### Observaciones

Si *outputDocument* o *saveOptions* son nulos, se lanzará una ArgumentNullException. Si falta el documento a guardar, se lanzará una ArgumentNullException.

Se lanza cuando *outputDocument* o *saveOptions* son nulos, o cuando falta el documento a guardar.**Aprende más:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Ver también

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Guarda el contenido del documento actual en el flujo de salida especificado.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| outputDocument | Stream | El flujo al que se guardará el contenido del documento. No puede ser nulo. |

### Valor devuelto

El flujo con el contenido del documento guardado.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *outputDocument* es nulo o si falta el contenido del documento. |

### Observaciones

Este método copia el contenido de la representación interna del documento al flujo de salida proporcionado. La posición original del flujo se conserva después de la operación de guardado.

### Ver también

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
