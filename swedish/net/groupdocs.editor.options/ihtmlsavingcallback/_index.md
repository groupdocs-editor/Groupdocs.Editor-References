---
title: "IHtmlSavingCallback"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Gränssnitt som används vid sparande till HTML-formatet och som måste implementeras av slutanvändaren för att spara den tillhandahållna resursen och returnera en länk till den"
type: docs
weight: 920
url: /sv/net/groupdocs.editor.options/ihtmlsavingcallback/
---
## IHtmlSavingCallback interface

Gränssnitt som används vid sparande till HTML-formatet och som måste implementeras av slutanvändaren för att spara den tillhandahållna resursen och returnera en länk till den

```csharp
public interface IHtmlSavingCallback
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SaveOneResource](../../groupdocs.editor.options/ihtmlsavingcallback/saveoneresource)(IHtmlResource) | Instansmetod som utlöses under anropet av [`Save`](../../groupdocs.editor/editabledocument/save) och som måste implementeras av slutanvändaren för att hämta och spara den tillhandahållna HTML-resursen och sedan returnera en länk till denna resurs tillbaka till anroparen. |

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
