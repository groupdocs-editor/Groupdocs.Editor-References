---
title: Edit
second_title: GroupDocs.Editor för .NET API-referens
description: Öppnar ett tidigare laddat dokument för redigering med angivna formatspecifika alternativ genom att generera och returnera en instans av EditableDocumentgroupdocs.editor/editabledocument klass som i sin tur innehåller metoder för att producera HTMLuppmärkning och tillhörande resurser.
type: docs
weight: 50
url: /sv/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Öppnar ett tidigare laddat dokument för redigering med angivna formatspecifika alternativ genom att generera och returnera en instans av '[`EditableDocument`](../../editabledocument) klass, som i sin tur innehåller metoder för att producera HTML-uppmärkning och tillhörande resurser.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| editOptions | IEditOptions | Formatspecifika dokumentalternativ, som gör det möjligt att finjustera konverteringsprocessen. Kan vara NULL — i så fall upptäcker GroupDocs.Editor ett format för tidigare inlästa dokument och tillämpar alternativ, standard för detta format. Bör inte komma i konflikt med tidigare tillämpade laddningsalternativ. |

### Returvärde

Exempel på '[`EditableDocument`](../../editabledocument) klass, som kapslar in övergripande indatadokument med alla dess resurser i mellanformat. Den här metoden, om den är klar, returnerar aldrig NULL.

### Anmärkningar

När inmatat originaldokument läses in i "Editor"-instansen genom konstruktorn, tillåter denna metod att öppna dokument för redigering genom att konvertera det till mellanformat, som är inkapslat i instans av klassen "EditableDocument". '[`EditableDocument`](../../editabledocument) som returneras från den här metoden, innehåller alla nödvändiga metoder och egenskaper för att producera HTML-uppmärkning och motsvarande resurser (som bilder, typsnitt och stilmallar) i alla nödvändiga konfigurationer för att senare överföra dem till valfri WYSIWYG HTML-redigerare. Denna överbelastning erhåller redigeringsalternativ, som är specifika för familjeformat. **Läs mer**

* Mer om att redigera dokument med GroupDocs.Editor: [Hur man redigerar dokument med GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Se även

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namnutrymme [GroupDocs.Editor](../../editor)
* hopsättning [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Öppnar ett tidigare laddat dokument för redigering med standardalternativ genom att generera och returnera en instans av '[`EditableDocument`](../../editabledocument) klass, som i sin tur innehåller metoder för att producera HTML-uppmärkning och tillhörande resurser.

```csharp
public EditableDocument Edit()
```

### Returvärde

Exempel på '[`EditableDocument`](../../editabledocument) klass, som kapslar in övergripande indatadokument med alla dess resurser i mellanformat. Den här metoden, om den är klar, returnerar aldrig NULL.

### Anmärkningar

När inmatat originaldokument läses in i 'Editor'-instansen via konstruktorn, tillåter denna metod att öppna dokument för redigering genom att konvertera det till mellanformat, som är inkapslat i instans av '[`EditableDocument`](../../editabledocument) klass. '[`EditableDocument`](../../editabledocument) som returneras från den här metoden, innehåller alla nödvändiga metoder och egenskaper för att producera HTML-uppmärkning och motsvarande resurser (som bilder, typsnitt och stilmallar) i alla nödvändiga konfigurationer för att senare överföra dem till valfri WYSIWYG HTML-redigerare. Denna överbelastning tillämpar redigeringsalternativ, som är standard för formatet som inmatningsdokumentet tillhör. **Läs mer**

* Mer om att redigera dokument med GroupDocs.Editor: [Hur man redigerar dokument med GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Se även

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namnutrymme [GroupDocs.Editor](../../editor)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
