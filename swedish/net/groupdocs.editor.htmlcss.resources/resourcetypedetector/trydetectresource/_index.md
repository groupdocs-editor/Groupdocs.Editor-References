---
title: "TryDetectResource"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Försöker analysera en inmatningsström och skapar en av de stödjade HTML‑resurserna från den med hänsyn till en specificerad antagen typ om den inte är null"
type: docs
weight: 20
url: /sv/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

Försöker analysera en inmatningsström och skapar en av de stödjade HTML-resurserna från den, med hänsyn till en angiven antagen typ om den inte är null

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| inputResourceStream | Stream | Inmatningsström, som förmodas innehålla en HTML‑resurs. Om den är ogiltig kastas ett undantag. |
| namn | String | Resursnamn, som kommer att användas för den skapade och returnerade resursen vid framgång. Får inte vara NULL, tomt eller bara blanksteg |
| assumptiveFormat | IResourceType | Antagen format för den inmatade HTML‑resursen, vilket är användbart för att uppnå bästa prestanda. Om den är helt okänd, använd NULL‑värdet. Kan vara felaktig, vilket bara försämrar prestandan. |

### Returvärde

Instans som implementerar 'IHtmlResource'-gränssnittet och representerar en av de stödjade HTML-resurserna vid framgång, eller NULL vid fel

### Se även

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
