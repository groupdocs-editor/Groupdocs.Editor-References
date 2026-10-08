---
title: "GetBodyContent"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar kroppens inre innehåll i HTML‑dokumentet mellan öppnings‑ och stängningstaggarna för BODY utan dessa taggar som en sträng."
type: docs
weight: 120
url: /sv/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

Returnerar en kropp av HTML-dokumentet (innehållet mellan öppnings- och stängningstaggarna BODY utan dessa taggar) som en sträng.

```csharp
public string GetBodyContent()
```

### Returvärde

Sträng som innehåller kroppen i HTML‑dokumentet (utan öppnings‑ och stängningstaggar för BODY)

### Anmärkningar

De flesta WYSIWYG‑redigerare arbetar vanligtvis med det inre innehållet i dokumentets BODY och kan inte korrekt bearbeta dess metainformation från HEAD‑blocket. Denna metod är avsedd för sådana fall. Denna överlagring tillåter inte justering av URI:er för externa resursförfrågningar.

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

Returnerar en kropp av HTML-dokumentet (innehållet mellan öppnings- och stängningstaggarna BODY utan dessa taggar) som en sträng, där länkar till externa resurser innehåller angiven mall med platshållare.

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| externalImagesTemplate | String | Genom den här parametern kan du ange en strängmall med en platshållare, som kommer att tillämpas på länkarna till alla externa bilder i IMG‑element som kommer att finnas i den resulterande HTML‑strängen. Om NULL eller tom, kommer mallen inte att läggas till, och rena filnamn kommer att finnas i den resulterande HTML‑markupen. Om mallen är ogiltig kommer den att behandlas som ett prefix, så att filnamnen konkateneras till dess slut. |

### Returvärde

Sträng som innehåller kroppen i HTML‑dokumentet (utan öppnings‑ och stängningstaggar för BODY) med länkar, anpassade till de externa bilderna

### Anmärkningar

De flesta WYSIWYG‑redigerare arbetar vanligtvis med innehållet i BODY i dokumentet och kan inte korrekt bearbeta dess metadata från HEAD‑blocket. Denna metod är avsedd för sådana fall. Denna överlagring möjliggör att justera URI:er för externa resursförfrågningar.

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
