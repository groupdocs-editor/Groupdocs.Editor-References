---
title: PresentationFormats
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Kapselt alle Präsentationsformate. Enthält die folgenden Formate Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Erfahren Sie mehr über Präsentationsformatehierhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /de/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Kapselt alle Präsentationsformate. Enthält die folgenden Formate: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Erfahren Sie mehr über Präsentationsformate[hier](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Gibt eine Erweiterung (ohne führenden Punkt) dieses Präsentationsformats in Kleinbuchstaben zurück |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Gibt einen MIME-Code für dieses Format zurück |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Gibt einen formalen vollständigen Namen dieses Präsentationsformats zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Gibt eine Instanz von zurück[`PresentationFormats`](../presentationformats)Struktur, die der angegebenen Dateinamenerweiterung zugeordnet ist, oder löst eine Ausnahme aus, wenn die Erweiterung nicht richtig analysiert werden kann |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen IDocumentFormat ist instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Ermittelt, ob diese Instanz gleich dem anderen angegebenen Objekt ist, das vermutlich ein Boxed PresentationFormats ist |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Bestimmt, ob diese Instanz gleich den anderen angegebenen PresentationFormats ist instance |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Gibt einen Hash-Code zurück, der für diese Instanz unveränderlich ist |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Prüft zwei angegebene PresentationFormats-Instanzen auf Gleichheit |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Prüft zwei angegebene PresentationFormats-Instanzen auf Ungleichheit |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP)-Datei stellt das Präsentationsdateiformat dar, das von OpenOffice.org im OASISOpen-Standard verwendet wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OTP-Datei (OpenDocument Presentation Template) stellt Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003-Präsentationsvorlagendatei (POT) stellt Microsoft PowerPoint-Vorlagendateien dar, die von PowerPoint 97-2003-Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) sind Dateien mit Unterstützung für Makros. POTM-Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zum Erstellen weiterer Präsentationsdateien verwendet werden können. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX)-Datei stellt Microsoft PowerPoint-Vorlagenpräsentationen dar, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS)-Dateien werden mit Microsoft PowerPoint für Diashow-Zwecke erstellt. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM)-Dateien werden mit Microsoft PowerPoint 2007 oder höher erstellt. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX)-Dateien werden mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint-Präsentation (.ppt) stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien zur Anzeige als Diashow besteht. Es gibt das von Microsoft PowerPoint 97-2003 verwendete binäre Dateiformat an. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95-Präsentation (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | PPTM-Dateien (Microsoft Office Open XML PresentationML Macro-Enabled Document), die mit Microsoft PowerPoint 2007 oder höheren Versionen erstellt wurden. Sie ähneln PPTX-Dateien mit dem Unterschied, dass die Seiten keine Makros ausführen können, obwohl sie Makros enthalten können. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML-Präsentation (.pptx) ist eine Präsentationsdatei, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurde. Anders als die vorherige Version des Präsentationsdateiformats PPT, die binär war, basiert das PPTX-Format auf dem offenen XML-Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Gibt eine interne Klasse zurück, die aufzählbare Möglichkeiten über alle existierenden Präsentationsformate bietet |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implementiert die generische IEnumerable-Schnittstelle, die eine 'Foreach'-Möglichkeit für die Präsentationsformate type ermöglicht |

### Siehe auch

* interface [IDocumentFormat](../idocumentformat)
* namensraum [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
