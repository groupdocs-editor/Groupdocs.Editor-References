---
title: "PresentationFormats"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Umfasst alle Presentation‑Formate. Enthält die folgenden Formate"
type: docs
weight: 120
url: /de/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Umfasst alle Präsentationsformate. Enthält die folgenden Formate:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

Erfahren Sie mehr über Presentation‑Formate [here](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ermittelt die Dateierweiterung des Dokumentformats. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ermittelt die Formatfamilie, zu der das Dokumentformat gehört. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ermittelt die eindeutige Kennung für die Formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ermittelt den MIME-Typ des Dokumentformats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ermittelt den Namen der Formatfamilie. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Gibt eine aufzählbare Sammlung aller [`PresentationFormats`](../presentationformats) zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Ruft eine Instanz des angegebenen Typs [`PresentationFormats`](../presentationformats) ab, die die angegebene Dateierweiterung besitzt. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestimmt, ob diese Instanz gleich der angegebenen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-Instanz ist. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich der angegebenen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-Instanz ist. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestimmt, ob diese Instanz gleich der angegebenen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-Instanz ist. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [`PresentationFormats`](../presentationformats)‑Objekt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation‑Vorlage (OTP). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97‑2003 Präsentationsvorlage (POT). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Makro‑aktivierte Vorlage (POTM). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Makro‑freie Vorlage (POTX). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97‑2003 Diashow (PPS). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Makro‑aktivierte Diashow (PPSM). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Makro‑freie Diashow (PPSX). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97‑2003 Präsentation (PPT). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 Präsentation (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Makro‑aktiviertes Dokument (PPTM). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML Makro‑freies Dokument (PPTX). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/presentation/pptx). |

### Siehe auch

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
