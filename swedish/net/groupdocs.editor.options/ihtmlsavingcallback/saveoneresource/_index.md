---
title: "SaveOneResource"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Instansmetod som utlöses under anropet av Savegroupdocs.editor/editabledocument/save‑metoden och som måste implementeras av slutanvändaren för att hämta och spara den tillhandahållna HTML‑resursen och sedan returnera en länk till denna resurs tillbaka till anroparen."
type: docs
weight: 10
url: /sv/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

Instansmetod som utlöses under anropet av [`Save`](../../../groupdocs.editor/editabledocument/save)-metoden och som måste implementeras av slutanvändaren för att hämta och spara den tillhandahållna HTML‑resursen och sedan returnera en länk till denna resurs tillbaka till anroparen.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| resurs | IHtmlResource | HTML‑resurs av vilken typ som helst (bilder och teckensnitt, eventuellt stilmallar om de inte är inbäddade i HTML‑markupen), som skickas av GroupDocs.Editor till den användardefinierade implementeringen av detta gränssnitt, erhålls av användaren, och användaren kan utföra alla nödvändiga procedurer såsom att spara, skicka, konvertera den osv. GroupDocs.Editor kommer aldrig att skicka en `null` HTML‑resurs till denna metod. |

### Returvärde

En länk (referens) till resursen, erhållen i *resource*-parametern, som användaren måste tillhandahålla till GroupDocs.Editor, så att GroupDocs.Editor placerar denna länk i HTML‑markupen.

### Anmärkningar

GroupDocs.Editor förväntar sig att den användardefinierade implementeringen av denna metod inte kastar undantag under körning. Om undantag ändå uppstår kommer GroupDocs.Editor att skriva ett värde för egenskapen [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) till HTML‑markupen.

### Se även

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
