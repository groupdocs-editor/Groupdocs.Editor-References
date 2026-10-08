---
title: "TextualFormats"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Omvat alle tekstuele, op tekst gebaseerde formaten, inclusief markup XML HTML en andere. Bevat de volgende formaten Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /nl/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Omvat alle tekstuele (op tekst gebaseerde) formaten, inclusief markup (XML, HTML) en andere. Bevat de volgende formaten: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Haalt de bestandsextensie van het documentformaat op. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Haalt de formatfamilie op waartoe het documentformaat behoort. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Haalt de unieke identifier op voor de formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Haalt het MIME-type van het documentformaat op. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Haalt de naam van de formatfamilie op. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Haalt een doorzoekbare collectie op van alle [`TextualFormats`](../textualformats). |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Haal een instantie op van het opgegeven type [`TextualFormats`](../textualformats) dat de opgegeven bestandsextensie heeft. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bepaalt of deze instantie gelijk is aan de opgegeven [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de opgegeven [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instantie. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bepaalt of deze instantie gelijk is aan de opgegeven [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instantie. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Retourneert een hashcode voor het huidige object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [`TextualFormats`](../textualformats) object. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help is een door Microsoft gepatenteerd online help binair formaat, bestaande uit een verzameling HTML-pagina's, een index en andere navigatietools. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language-document (HTML) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) is een open standaard bestandsformaat voor het delen van gegevens dat menselijk leesbare tekst gebruikt om gegevens op te slaan en te verzenden. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown is een lichtgewicht opmaaktaal voor het maken van opgemaakte tekst met een platte-tekst editor. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME-encapsulatie van samengestelde HTML-documenten is een webpagina-archiefformaat dat wordt gebruikt om, in één computerbestand, de HTML-code en bijbehorende bronnen te combineren. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language-document (XML) dat vergelijkbaar is met HTML maar verschilt door tags te gebruiken voor het definiëren van objecten. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/web/xml). |

### Zie ook

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
