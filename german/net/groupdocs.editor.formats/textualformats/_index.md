---
title: "TextualFormats"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Umfasst alle textbasierten Formate einschließlich Markup XML HTML und andere. Enthält die folgenden Formate Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /de/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Umfasst alle textbasierten Formate, einschließlich Markup (XML, HTML) und andere. Enthält die folgenden Formate: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ermittelt die Dateierweiterung des Dokumentformats. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ermittelt die Formatfamilie, zu der das Dokumentformat gehört. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ermittelt die eindeutige Kennung für die Formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ermittelt den MIME-Typ des Dokumentformats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ermittelt den Namen der Formatfamilie. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Gibt eine aufzählbare Sammlung aller [`TextualFormats`](../textualformats) zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Ruft eine Instanz des angegebenen Typs [`TextualFormats`](../textualformats) ab, die die angegebene Dateierweiterung besitzt. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestimmt, ob diese Instanz gleich der angegebenen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-Instanz ist. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich der angegebenen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-Instanz ist. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestimmt, ob diese Instanz gleich der angegebenen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-Instanz ist. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [`TextualFormats`](../textualformats)-Objekt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help ist ein proprietäres Online-Hilfs-Binärformat von Microsoft, das aus einer Sammlung von HTML-Seiten, einem Index und weiteren Navigationswerkzeugen besteht. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language-Dokument (HTML) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) ist ein offenes Standard-Dateiformat zum Austausch von Daten, das menschenlesbaren Text verwendet, um Daten zu speichern und zu übertragen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown ist eine leichtgewichtige Auszeichnungssprache zum Erstellen von formatiertem Text mit einem einfachen Texteditor. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME-Kapselung aggregierter HTML-Dokumente ist ein Webseitensicherungsformat, das verwendet wird, um in einer einzigen Datei den HTML-Code und zugehörige Ressourcen zu kombinieren. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) ist ein Textdokument, das reinen Text in Form von Zeilen enthält. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language-Dokument (XML) ist ähnlich wie HTML, unterscheidet sich jedoch durch die Verwendung von Tags zur Definition von Objekten. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/web/xml). |

### Siehe auch

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
