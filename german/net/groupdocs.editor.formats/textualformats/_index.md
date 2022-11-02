---
title: TextualFormats
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Kapselt alle textuellen textbasierten Formate einschließlich Markup XML HTML und andere. Enthält die folgenden Formate Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /de/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Kapselt alle textuellen (textbasierten) Formate, einschließlich Markup (XML, HTML) und andere. Enthält die folgenden Formate: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Gibt eine Erweiterung (ohne führenden Punkt) dieses Textformats in Kleinbuchstaben zurück |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Gibt einen MIME-Code für dieses Format zurück |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Gibt einen formalen vollständigen Namen dieses Textformats zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Gibt eine Instanz von zurück[`TextualFormats`](../textualformats)Struktur, die der angegebenen Dateinamenerweiterung zugeordnet ist, oder löst eine Ausnahme aus, wenn die Erweiterung nicht richtig analysiert werden kann |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen IDocumentFormat ist instance |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Ermittelt, ob diese Instanz gleich dem anderen spezifizierten Objekt ist, das vermutlich ein TextualFormats -Objekt ist. |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Bestimmt, ob diese Instanz gleich den anderen angegebenen TextualFormats ist instance |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Gibt einen Hash-Code zurück, der für diese Instanz unveränderlich ist |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Gibt den Namen dieses bestimmten Formats zurück, genau wie „Name“ property |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Prüft zwei angegebene TextualFormats-Instanzen auf Gleichheit |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Prüft zwei angegebene TextualFormats-Instanzen auf Ungleichheit |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help ist ein Microsoft-eigenes Online-Hilfe-Binärformat, das aus einer Sammlung von HTML-Seiten, einem Index und anderen Navigationswerkzeugen besteht. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language document (HTML) ist die Erweiterung für Webseiten, die für die Anzeige in Browsern erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) ist ein offenes Standarddateiformat zum Teilen von Daten, das menschenlesbaren Text zum Speichern und Übertragen von Daten verwendet. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown ist eine leichte Auszeichnungssprache zum Erstellen von formatiertem Text mit einem Nur-Text-Editor. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | Die MIME-Kapselung von aggregierten HTML-Dokumenten ist ein Archivformat für Webseiten, das verwendet wird, um den HTML-Code und die zugehörigen Ressourcen in einer einzigen Computerdatei zu kombinieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) stellt ein Textdokument dar, das einfachen Text in Form von Zeilen enthält. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language-Dokument (XML), das HTML ähnelt, sich jedoch in der Verwendung von Tags zum Definieren von Objekten unterscheidet. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Gibt eine interne Klasse zurück, die aufzählbare Möglichkeiten über alle existierenden Textual-Formate bietet. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implementiert die generische IEnumerable-Schnittstelle, die eine „Foreach“-Möglichkeit für die TextualFormats type ermöglicht |

### Siehe auch

* interface [IDocumentFormat](../idocumentformat)
* namensraum [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
