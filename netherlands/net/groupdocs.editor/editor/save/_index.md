---
title: "Save"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Converteert het opgegeven bewerkte document, weergegeven als instance van EditableDocumentgroupdocs.editor/editabledocument, naar het resulterende document in het opgegeven formaat en slaat de inhoud op in de opgegeven stream."
type: docs
weight: 80
url: /nl/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Converteert het opgegeven bewerkte document, weergegeven als instance van '[`EditableDocument`](../../editabledocument)', naar het resulterende document in het opgegeven formaat en slaat de inhoud op in de opgegeven stream.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputDocument | EditableDocument | Versie van het invoerdocument, dat bewerkt is in een WYSIWYG HTML-editor en opgeslagen is als instance van de klasse '[`EditableDocument`](../../editabledocument)', die moet worden geconverteerd naar een uitvoerdocument van een specifiek formaat. Mag niet null of verwijderd zijn. |
| outputDocument | Stream | Uitvoerstroom waarin de inhoud van het resulterende document wordt vastgelegd. Mag niet null of verwijderd zijn en moet schrijven ondersteunen. |
| saveOptions | ISaveOptions | Documentopslagopties die het formaat van het resulterende document definiëren, evenals algemene en formaat-specifieke opslagopties. Mag niet null zijn. |

### Opmerkingen

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Zie ook

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Converteert het opgegeven bewerkte document, weergegeven als instance van '[`EditableDocument`](../../editabledocument)', naar het resulterende document in het opgegeven formaat en slaat de inhoud op in een bestand via het opgegeven bestandspad.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputDocument | EditableDocument | Versie van het invoerdocument, dat bewerkt is in een WYSIWYG HTML-editor en opgeslagen is als instance van de klasse '[`EditableDocument`](../../editabledocument)', die moet worden geconverteerd naar een uitvoerdocument van een specifiek formaat. Mag niet null of verwijderd zijn. |
| filePath | String | Pad naar het bestand waarin het uitvoerdocument wordt opgeslagen. Als er al een bestand met dezelfde naam bestaat, wordt dit volledig overschreven. De tekenreeks met het pad mag niet null, leeg of alleen uit witruimtes bestaan. |
| saveOptions | ISaveOptions | Documentopslagopties die het formaat van het resulterende document definiëren, evenals algemene en formaat-specifieke opslagopties. Mag niet null zijn. |

### Opmerkingen

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Zie ook

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Converteert het opgegeven bewerkte document, weergegeven als een instantie van '[`EditableDocument`](../../editabledocument)', naar het resulterende document van het formaat, bepaald aan de hand van de bestandsextensie, en slaat de inhoud op in een bestand op het opgegeven bestandspad.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputDocument | EditableDocument | Versie van het invoerdocument, dat bewerkt is in een WYSIWYG HTML-editor en opgeslagen is als instance van de klasse '[`EditableDocument`](../../editabledocument)', die moet worden geconverteerd naar een uitvoerdocument van een specifiek formaat. Mag niet null of verwijderd zijn. |
| filePath | String | Pad naar het bestand waarin het uitvoerdocument wordt opgeslagen. Als er al een bestand met dezelfde naam bestaat, wordt het volledig overschreven. De tekenreeks met het pad mag niet null, leeg of alleen witruimtes bevatten. Omdat de standaardopslagopties en het uitvoerformaat worden bepaald op basis van deze bestandsnaam, moet het een geldige extensie hebben. |

### Zie ook

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Converteert het originele document na bewerking (bijvoorbeeld [`FormFieldManager`](../formfieldmanager)) naar het resulterende document van het opgegeven formaat en slaat de inhoud op in de opgegeven stream.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputDocument | Stream | De stream waarin het uitvoerdocument wordt opgeslagen. Deze stream moet schrijfbaar zijn en zich aan het begin van de documentinhoud bevinden. Mag niet null zijn. |
| saveOptions | WordProcessingSaveOptions | Documentopslagopties die het formaat van het resulterende document definiëren, evenals algemene en formaat‑specifieke opslagopties. Mag niet null zijn. |

### Retourwaarde

De stream die de opgeslagen documentinhoud bevat.

### Opmerkingen

Als *outputDocument* of *saveOptions* null is, wordt een ArgumentNullException gegooid. Als het op te slaan document ontbreekt, wordt een ArgumentNullException gegooid.

Gegooid wanneer *outputDocument* of *saveOptions* null is, of wanneer het op te slaan document ontbreekt.**Meer informatie:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Zie ook

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Sla de huidige documentinhoud op naar de opgegeven uitvoer‑stream.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputDocument | Stream | De stream waarin de documentinhoud wordt opgeslagen. Deze mag niet null zijn. |

### Retourwaarde

De stream met de opgeslagen documentinhoud.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gegooid wanneer *outputDocument* null is of wanneer de documentinhoud ontbreekt. |

### Opmerkingen

Deze methode kopieert de inhoud van de interne documentrepresentatie naar de opgegeven uitvoerstream. De oorspronkelijke positie van de stream wordt behouden na de opslagbewerking.

### Zie ook

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
