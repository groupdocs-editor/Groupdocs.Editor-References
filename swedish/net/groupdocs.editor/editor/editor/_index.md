---
title: "Editor"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Initierar en ny instans av Editorgroupdocs.editor/editor-klassen och skapar ett nytt tomt dokument baserat på det angivna formatet."
type: docs
weight: 10
url: /sv/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Initierar en ny instans av [`Editor`](../../editor)-klassen och skapar ett nytt tomt dokument baserat på det angivna formatet.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| format | DocumentFormatBase | Representerar filformatet för dokumentet som ska skapas. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exempel

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Använd editor‑instansen för att redigera och spara dokument
}
```

### Se även

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Initierar en ny Editor-instans med angivet inmatningsdokument (som en ström).

```csharp
public Editor(Stream document)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Ström som innehåller dokumentinnehåll. Får inte vara null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exempel

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Använd editor‑instansen för att redigera och spara dokument
    }
}
```

### Se även

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Initierar en ny Editor-instans med angivet inmatningsdokument (som en ström) med dess laddningsalternativ.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Ström som innehåller dokumentinnehåll. Får inte vara null. |
| loadOptions | ILoadOptions | Dokumentets laddningsalternativ. Får vara null. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när dokumentströmmen är null. |
| ArgumentException | Kastas när dokumentströmmen är ogiltig. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exempel

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Använd editor‑instansen för att redigera och spara dokument
    }
}
```

### Se även

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) med dess laddningsalternativ.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| filePath | String | Fullständig sökväg till filen. Får inte vara null, tom eller bara bestå av blanksteg. Måste vara giltig och filen måste finnas. |
| loadOptions | ILoadOptions | Dokumentets laddningsalternativ. Får vara null. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när filsökvägen är ogiltig. |
| FileNotFoundException | Kastas när filen inte finns. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exempel

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Använd editor‑instansen för att redigera och spara dokument
}
```

### Se även

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Initierar en ny Editor-instans med angivet inmatningsdokument (som en fullständig filsökväg) och Editor-inställningar.

```csharp
public Editor(string filePath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| filePath | String | Fullständig sökväg till filen. Får inte vara NULL. Måste vara giltig och filen måste finnas. |

### Se även

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
