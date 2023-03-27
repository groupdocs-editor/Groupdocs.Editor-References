---
title: FixedLayoutFormats
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Kapselt alle Formate mit festem Layout auch bekannt als feste Seite einschließlich PDF und XPS dies schließt keine Rasterbilder ein
type: docs
weight: 80
url: /de/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Kapselt alle Formate mit festem Layout (auch bekannt als "feste Seite"), einschließlich PDF und XPS (dies schließt keine Rasterbilder ein)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Gibt eine Erweiterung (ohne führenden Punkt) dieses Formats mit festem Layout in Kleinbuchstaben zurück |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Gibt einen MIME-Code für dieses Format zurück |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Gibt einen formalen vollständigen Namen dieses Formats mit festem Layout zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Gibt eine Instanz von zurück[`FixedLayoutFormats`](../fixedlayoutformats) Struktur, die der angegebenen Dateinamenerweiterung zugeordnet ist, oder löst eine Ausnahme aus, wenn die Erweiterung nicht richtig analysiert werden kann |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Bestimmt, ob diese Instanz gleich den anderen angegebenen FixedLayoutFormats ist instance |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen IDocumentFormat ist instance |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen Objekt ist, das vermutlich ein geschachteltes FixedLayoutFormats ist |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Gibt einen Hash-Code zurück, der für diese Instanz unveränderlich ist |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Gibt den Namen dieses bestimmten Formats zurück, genau wie „Name“ property |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Prüft zwei gegebene FixedLayoutFormats-Instanzen auf Gleichheit |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Gibt einen Bytewert aus dem zugrunde liegenden Feld des angegebenen FixedLayoutFormats zurück. instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Prüft zwei gegebene FixedLayoutFormats-Instanzen auf Ungleichheit |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er Jahren erstellt wurde. Der Zweck dieses Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | XPS-Datei stellt Seitenlayoutdateien dar, die auf von Microsoft erstellten XML-Papierspezifikationen basieren. Es wurde als Ersatz für das EMF-Dateiformat entwickelt und ähnelt dem PDF-Dateiformat, verwendet jedoch XML für Layout, Aussehen und Druckinformationen eines Dokuments. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Gibt eine interne Klasse zurück, die aufzählbare Möglichkeiten über alle existierenden Formate mit festem Layout bietet |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Implementiert die generische IEnumerable-Schnittstelle, die eine „Foreach“-Möglichkeit für das FixedLayoutFormats type ermöglicht |

### Bemerkungen

Verschiedene Anwendungen zum Anzeigen oder Veröffentlichen von Dokumenten ermöglichen es Benutzern, Dokumente in bestimmten Formaten zu öffnen (Adobe Acrobat, XPS Viewer) und manchmal zu bearbeiten (Adobe InDesign). Diese Anwendungen erzeugen typischerweise Dokumente im sogenannten "Festseiten"-Format. Ein solches Dokumentenformat beschreibt genau, wo der Inhalt eines Dokuments auf jeder Seite platziert wird. Intern enthält das PDF- oder XPS-Format eine Beschreibung jeder Seite sowie Zeichenanweisungen, die das Layout des Inhalts auf der Seite angeben. Dies ähnelt den Bildformaten und beschreibt, wo der Inhalt entweder in Raster- oder Vektorform angezeigt wird.

### Siehe auch

* interface [IDocumentFormat](../idocumentformat)
* namensraum [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
