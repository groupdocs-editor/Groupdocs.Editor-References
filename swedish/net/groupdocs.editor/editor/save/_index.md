---
title: "Save"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Konverterar det angivna redigerade dokumentet som representeras som en instans av EditableDocumentgroupdocs.editor/editabledocument till det resulterande dokumentet i angivet format och sparar dess innehåll till den angivna strömmen."
type: docs
weight: 80
url: /sv/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Konverterar angivet redigerat dokument, representerat som en instans av '[`EditableDocument`](../../editabledocument)', till det resulterande dokumentet i angivet format och sparar dess innehåll till angiven ström

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| inputDocument | EditableDocument | Version av inmatningsdokumentet som redigerades i en WYSIWYG HTML-editor och lagras som en instans av klassen '[`EditableDocument`](../../editabledocument)', som ska konverteras till utdata-dokument i ett specifikt format. Får inte vara null eller disponerad. |
| outputDocument | Stream | Utdatastream, i vilken innehållet i det resulterande dokumentet kommer att registreras. Får inte vara null, disponerad, och måste stödja skrivning. |
| saveOptions | ISaveOptions | Dokumentets sparalternativ, som definierar formatet för det resulterande dokumentet, samt allmänna och format‑specifika sparalternativ. Får inte vara null. |

### Anmärkningar

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Se även

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Konverterar angivet redigerat dokument, representerat som en instans av '[`EditableDocument`](../../editabledocument)', till det resulterande dokumentet i angivet format och sparar dess innehåll till en fil via den angivna filsökvägen

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| inputDocument | EditableDocument | Version av inmatningsdokumentet som redigerades i en WYSIWYG HTML-editor och lagras som en instans av klassen '[`EditableDocument`](../../editabledocument)', som ska konverteras till utdata-dokument i ett specifikt format. Får inte vara null eller disponerad. |
| filePath | String | Sökväg till filen där utdata‑dokumentet kommer att sparas. Om en fil med samma namn finns, kommer den att skrivas över helt. Strängen med sökvägen får inte vara null, tom eller bestå enbart av blanksteg. |
| saveOptions | ISaveOptions | Dokumentets sparalternativ, som definierar formatet för det resulterande dokumentet, samt allmänna och format‑specifika sparalternativ. Får inte vara null. |

### Anmärkningar

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Se även

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Konverterar angivet redigerat dokument, representerat som en instans av '[`EditableDocument`](../../editabledocument)', till det resulterande dokumentet i ett format som bestäms av filnamnstillägget, och sparar dess innehåll till en fil via den angivna filsökvägen

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| inputDocument | EditableDocument | Version av inmatningsdokumentet som redigerades i en WYSIWYG HTML-editor och lagras som en instans av klassen '[`EditableDocument`](../../editabledocument)', som ska konverteras till utdata-dokument i ett specifikt format. Får inte vara null eller disponerad. |
| filePath | String | Sökväg till filen där utdata‑dokumentet kommer att sparas. Om en fil med samma namn finns, kommer den att skrivas över helt. Strängen med sökvägen får inte vara null, tom eller bestå enbart av blanksteg. Eftersom standard‑sparalternativ och utdataformat bestäms av detta filnamn, måste det ha en giltig filändelse. |

### Se även

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Konverterar det ursprungliga dokumentet efter modifiering (till exempel [`FormFieldManager`](../formfieldmanager)), till det resulterande dokumentet i det angivna formatet och sparar dess innehåll till den tillhandahållna strömmen.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| outputDocument | Stream | Strömmen som utdata‑dokumentet ska sparas till. Denna ström bör vara skrivbar och placerad i början av dokumentets innehåll. Får inte vara null. |
| saveOptions | WordProcessingSaveOptions | Sparalternativ för dokumentet som definierar formatet för det resulterande dokumentet, samt allmänna och format‑specifika sparalternativ. Får inte vara null. |

### Returvärde

Strömmen som innehåller det sparade dokumentinnehållet.

### Anmärkningar

Om *outputDocument* eller *saveOptions* är null kastas ett ArgumentNullException. Om dokumentet som ska sparas saknas kastas ett ArgumentNullException.

Kastas när *outputDocument* eller *saveOptions* är null, eller när dokumentet som ska sparas saknas.**Learn more:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Se även

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Spara det aktuella dokumentets innehåll till den angivna utströmmen.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| outputDocument | Stream | Strömmen som dokumentinnehållet ska sparas till. Detta får inte vara null. |

### Returvärde

Strömmen med det sparade dokumentinnehållet.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *outputDocument* är null eller om dokumentinnehållet saknas. |

### Anmärkningar

Denna metod kopierar innehållet från den interna dokumentrepresentationen till den angivna utströmmen. Utströmmens ursprungliga position bevaras efter sparoperationen.

### Se även

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
