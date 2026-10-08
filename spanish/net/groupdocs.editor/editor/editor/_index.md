---
title: "Editor"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Inicializa una nueva instancia de la clase Editorgroupdocs.editor/editor y crea un nuevo documento vacío basado en el formato especificado."
type: docs
weight: 10
url: /es/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Inicializa una nueva instancia de la clase [`Editor`](../../editor) y crea un nuevo documento vacío basado en el formato especificado.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| formato | DocumentFormatBase | Representa el formato de archivo del documento que se creará. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ejemplos

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Utiliza la instancia del editor para editar y guardar documentos
}
```

### Ver también

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un flujo).

```csharp
public Editor(Stream document)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| documento | Stream | Flujo que contiene el contenido del documento. No debe ser nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ejemplos

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Utiliza la instancia del editor para editar y guardar documentos
    }
}
```

### Ver también

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Inicializa una nueva instancia de Editor con el documento de entrada especificado (como un flujo) y sus opciones de carga.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| documento | Stream | Flujo que contiene el contenido del documento. No debe ser nulo. |
| loadOptions | ILoadOptions | Opciones de carga del documento. Puede ser nulo. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando el flujo del documento es nulo. |
| ArgumentException | Se lanza cuando el flujo del documento no es válido. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ejemplos

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Utiliza la instancia del editor para editar y guardar documentos
    }
}
```

### Ver también

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) y sus opciones de carga.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| filePath | String | Ruta completa al archivo. No debe ser nula, vacía o contener solo espacios en blanco. Debe ser válida y el archivo debe existir. |
| loadOptions | ILoadOptions | Opciones de carga del documento. Puede ser nulo. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando la ruta del archivo no es válida. |
| FileNotFoundException | Se lanza cuando el archivo no existe. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ejemplos

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Utiliza la instancia del editor para editar y guardar documentos
}
```

### Ver también

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Inicializa una nueva instancia de Editor con el documento de entrada especificado (como una ruta de archivo completa) y la configuración de Editor.

```csharp
public Editor(string filePath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| filePath | String | Ruta completa al archivo. No debe ser NULL. Debe ser válida y el archivo debe existir. |

### Ver también

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
