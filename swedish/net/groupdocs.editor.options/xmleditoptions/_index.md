---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av XML (eXtensible Markup Language)-dokument och konvertering av dem till HTML"
type: docs
weight: 1270
url: /sv/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Tillåter att ange anpassade alternativ för redigering av XML (eXtensible Markup Language)-dokument och konvertering av dem till HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Tillåter att ange citatteckenstyp (enkla eller dubbla citattecken) för attributvärden. Dubbla citattecken är standard. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Teckenkodning för textdokumentet som kommer att tillämpas vid öppning. Som standard är den null — intern dokumentkodning kommer att användas. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Tillåter att aktivera eller inaktivera mekanismen för att reparera korrupt XML-struktur. Som standard är den inaktiverad (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | Tillåter att justera XML-formateringen som kommer att tillämpas på XML-strukturen när den visas i HTML. Standardformatering används och kan justeras. Får inte vara null. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | Tillåter att justera XML-markeringen som kommer att tillämpas på XML-strukturen när den visas i HTML. Standardmarkering används och kan justeras. Får inte vara null. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Tillåter att aktivera igenkänningsalgoritmen för e-postadresser i attributvärden |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Tillåter att aktivera URI-igenkänningsalgoritmen |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Tillåter att aktivera trunkering av avslutande blanksteg i inner-tag-texten. Som standard är den inaktiverad (false) – avslutande blanksteg kommer att bevaras. |

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
