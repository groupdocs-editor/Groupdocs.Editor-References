---
title: TextualFormats
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat alle tekstuele op tekst gebaseerde formaten inclusief opmaak XML HTML en andere. Bevat de volgende formaten Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /nl/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Bevat alle tekstuele (op tekst gebaseerde) formaten, inclusief opmaak (XML, HTML) en andere. Bevat de volgende formaten: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Retourneert een extensie (zonder beginpunt) van deze tekstindeling in kleine letters |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Retourneert een MIME-code voor deze indeling |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Retourneert een formele volledige naam van deze tekstuele indeling |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Retourneert instantie van[`TextualFormats`](../textualformats) structuur, gekoppeld aan de opgegeven bestandsnaamextensie, of genereert een uitzondering als de extensie niet correct kan worden geparseerd |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de andere opgegeven IDocumentFormat-instantie |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Bepaalt of deze instantie gelijk is aan het andere gespecificeerde object, dat vermoedelijk een omkaderd TextualFormats is |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Bepaalt of deze instantie gelijk is aan de andere opgegeven TextualFormats-instantie |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Retourneert een hash-code, die onveranderlijk is voor deze instantie |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Retourneert de naam van dit specifieke formaat, hetzelfde als 'Name' property |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Controleert twee gegeven TextualFormats-instanties op gelijkheid |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Controleert twee gegeven TextualFormats-instanties op inequality |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help is een door Microsoft gepatenteerde binaire indeling voor online help, bestaande uit een verzameling HTML-pagina's, een index en andere navigatiehulpmiddelen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language-document (HTML) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) is een open standaard bestandsindeling voor het delen van gegevens die door mensen leesbare tekst gebruikt om gegevens op te slaan en te verzenden. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown is een lichtgewicht opmaaktaal voor het maken van opgemaakte tekst met behulp van een editor voor platte tekst. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME-inkapseling van geaggregeerde HTML-documenten is een archiefindeling voor webpagina's die wordt gebruikt om de HTML-code en de bijbehorende bronnen in één computerbestand te combineren. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) staat voor een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language-document (XML) dat lijkt op HTML, maar verschilt in het gebruik van tags voor het definiëren van objecten. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Geeft een interne klasse terug, die ontelbare mogelijkheden biedt voor alle bestaande tekstformaten. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implementeert IEnumerable generieke interface, die een 'foreach'-mogelijkheid mogelijk maakt voor de TextualFormats type |

### Zie ook

* interface [IDocumentFormat](../idocumentformat)
* naamruimte [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
