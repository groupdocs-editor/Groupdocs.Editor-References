---
title: "Redigera"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Öppnar ett tidigare inläst dokument för redigering med angivna format‑specifika alternativ genom att generera och returnera en instans av klassen EditableDocumentgroupdocs.editor/editabledocument som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser."
type: docs
weight: 60
url: /sv/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Öppnar ett tidigare inläst dokument för redigering med angivna format‑specifika alternativ genom att skapa och returnera en instans av '[`EditableDocument`](../../editabledocument)'‑klassen, som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| editOptions | IEditOptions | Format‑specifika dokumentalternativ, som möjliggör finjustering av konverteringsprocessen. Kan vara NULL — i så fall upptäcker GroupDocs.Editor formatet på det tidigare inlästa dokumentet och tillämpar standardalternativ för detta format. Ska inte konfliktera med tidigare tillämpade laddningsalternativ. |

### Returvärde

Instans av '[`EditableDocument`](../../editabledocument)'‑klassen, som kapslar in hela inmatningsdokumentet med alla dess resurser i ett mellanformat. Denna metod, om den slutförs framgångsrikt, returnerar aldrig NULL.

### Anmärkningar

När det ursprungliga inmatningsdokumentet laddas till 'Editor'-instansen via konstruktorn, gör denna metod det möjligt att öppna dokumentet för redigering genom att konvertera det till ett mellanformat, som kapslas in i en instans av 'EditableDocument'-klassen. '[`EditableDocument`](../../editabledocument)', som returneras från denna metod, innehåller alla nödvändiga metoder och egenskaper för att producera HTML‑markup och motsvarande resurser (såsom bilder, teckensnitt och stilmallar) i alla nödvändiga konfigurationer för att därefter kunna överföras till någon WYSIWYG‑HTML‑editor. Denna överlagring hämtar redigeringsalternativ som är specifika för familjeformat. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Se även

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Öppnar ett tidigare inläst dokument för redigering med standardalternativ genom att skapa och returnera en instans av '[`EditableDocument`](../../editabledocument)'‑klassen, som i sin tur innehåller metoder för att producera HTML‑markup och tillhörande resurser.

```csharp
public EditableDocument Edit()
```

### Returvärde

Instans av '[`EditableDocument`](../../editabledocument)'‑klassen, som kapslar in hela inmatningsdokumentet med alla dess resurser i ett mellanformat. Denna metod, om den slutförs framgångsrikt, returnerar aldrig NULL.

### Anmärkningar

När det ursprungliga inmatningsdokumentet laddas till 'Editor'-instansen via konstruktorn, gör denna metod det möjligt att öppna dokumentet för redigering genom att konvertera det till ett mellanformat, som kapslas in i en instans av '[`EditableDocument`](../../editabledocument)'‑klassen. '[`EditableDocument`](../../editabledocument)', som returneras från denna metod, innehåller alla nödvändiga metoder och egenskaper för att producera HTML‑markup och motsvarande resurser (såsom bilder, teckensnitt och stilmallar) i alla nödvändiga konfigurationer för att därefter kunna överföras till någon WYSIWYG‑HTML‑editor. Denna överlagring tillämpar redigeringsalternativ som är standard för det format som inmatningsdokumentet tillhör. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Se även

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
