---
title: XmlText
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt één tekstbron die een XML is.
type: docs
weight: 660
url: /nl/net/groupdocs.editor.htmlcss.resources.textual/xmltext/
---
## XmlText class

Vertegenwoordigt één tekstbron, die een XML is.

```csharp
public sealed class XmlText : TextResourceBase
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Retourneert inhoud van deze tekstbron als bytestroom met originele codering |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Retourneert codering van deze tekstuele bron. Retourneert meestal UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Retourneert de juiste bestandsnaam van deze tekstbron, die bestaat uit naam en extensie |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Bepaalt of deze tekstbron is verwijderd of niet |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Retourneert de naam van deze tekstbron zonder bestandsextensie |
| [ParsedDocument](../../groupdocs.editor.htmlcss.resources.textual/xmltext/parseddocument) { get; } | Retourneert een "XmlDocument" van deze XML-resource |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Retourneert de inhoud van deze tekstbron als een standaardtekenreeks |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/xmltext/type) { get; } | Geeft als resultaat TextType.Xml |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Verwijdert deze tekstbron, verwijdert de inhoud ervan en zorgt ervoor dat de meeste methoden en eigenschappen niet meer werken. Tolerant voor meerdere oproepen. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | Controleert deze instantie met gespecificeerd op gelijkheid. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Slaat deze tekstbron op in het gespecificeerde bestand |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Gebeurtenis die optreedt wanneer deze tekstbron wordt verwijderd |

### Zie ook

* class [TextResourceBase](../textresourcebase)
* naamruimte [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->