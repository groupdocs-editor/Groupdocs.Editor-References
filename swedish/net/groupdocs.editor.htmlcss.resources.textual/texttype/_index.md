---
title: "TextType"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en stödbar textuell resurstyp"
type: docs
weight: 640
url: /sv/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

Representerar en stödbar textuell resurstyp

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | CSS-typ för den textuella resursen |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | Speciellt värde som markerar odefinierad, okänd eller ej stödd textuell resurs |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | XML-typ för den textuella resursen |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | Filändelse (utan inledande punkttecken) för en viss textuell resurs |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | Returnerar ett formellt namn för denna textuella resurstyp |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | MIME-kod för en viss textuell resurstyp |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | Returnerar TextType-värde som motsvarar filnamnstillägget som extraheras från det angivna filnamnet med tillägg eller ren filändelse |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | Bestämmer om detta objekt är lika med det angivna okastade objektet, som sannolikt är en annan "TextType"-instans |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | Bestämmer om detta objekt är lika med den angivna "TextType"-instansen |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | Returnerar en hashkod som är ett konstant tal för denna specifika värdetyp |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | Definierar huruvida två specifika "TextType"-instanser är lika |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | Definierar huruvida två specifika "TextType"-instanser är inte lika |

### Se även

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
