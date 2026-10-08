---
title: "Editor"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Initialiseert een nieuwe instantie van de Editorgroupdocs.editor/editor‑klasse en maakt een nieuw leeg document aan op basis van het opgegeven formaat."
type: docs
weight: 10
url: /nl/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Initialiseert een nieuwe instantie van de [`Editor`](../../editor)‑klasse en maakt een nieuw leeg document aan op basis van het opgegeven formaat.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formaat | DocumentFormatBase | Stelt het bestandsformaat van het document dat zal worden aangemaakt voor. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Voorbeelden

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Gebruik de editor‑instantie om documenten te bewerken en op te slaan
}
```

### Zie ook

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een stream).

```csharp
public Editor(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | Stream die documentinhoud bevat. Mag niet null zijn. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Voorbeelden

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Gebruik de editor‑instantie om documenten te bewerken en op te slaan
    }
}
```

### Zie ook

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een stream) met de laadopties.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | Stream die documentinhoud bevat. Mag niet null zijn. |
| loadOptions | ILoadOptions | Documentlaadopties. Mag null zijn. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer de documentstroom null is. |
| ArgumentException | Wordt gegooid wanneer de documentstroom ongeldig is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Voorbeelden

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Gebruik de editor‑instantie om documenten te bewerken en op te slaan
    }
}
```

### Zie ook

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een volledig bestandspad) met de laadopties.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Volledig pad naar het bestand. Mag niet null, leeg of alleen witruimtes bevatten. Moet geldig zijn en het bestand moet bestaan. |
| loadOptions | ILoadOptions | Documentlaadopties. Mag null zijn. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer het bestandspad ongeldig is. |
| FileNotFoundException | Wordt gegooid wanneer het bestand niet bestaat. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Voorbeelden

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Gebruik de editor‑instantie om documenten te bewerken en op te slaan
}
```

### Zie ook

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Initialiseert een nieuw Editor‑exemplaar met een opgegeven invoerdocument (als een volledig bestandspad) en Editor‑instellingen.

```csharp
public Editor(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Volledig pad naar het bestand. Mag niet NULL zijn. Moet geldig zijn en het bestand moet bestaan. |

### Zie ook

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
