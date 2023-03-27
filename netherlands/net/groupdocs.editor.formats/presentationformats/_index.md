---
title: PresentationFormats
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat alle presentatieformaten. Bevat de volgende formaten Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Meer informatie over presentatieindelingenhierhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /nl/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Bevat alle presentatieformaten. Bevat de volgende formaten: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Meer informatie over presentatie-indelingen[hier](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Retourneert een extensie (zonder beginpunt) van deze presentatie-indeling in kleine letters |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Retourneert een MIME-code voor deze indeling |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Retourneert een formele volledige naam van deze presentatie-indeling |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Retourneert instantie van[`PresentationFormats`](../presentationformats) structuur, gekoppeld aan de opgegeven bestandsnaamextensie, of genereert een uitzondering als de extensie niet correct kan worden geparseerd |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de andere opgegeven IDocumentFormat-instantie |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Bepaalt of deze instantie gelijk is aan het andere gespecificeerde object, dat is vermoedelijk een boxed PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Bepaalt of deze instantie gelijk is aan de andere gespecificeerde PresentationFormats-instantie |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Retourneert een hash-code, die onveranderlijk is voor deze instantie |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Controleert twee gegeven PresentationFormats-instanties op gelijkheid |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Controleert twee gegeven PresentationFormats-instanties op inequality |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP)-bestand vertegenwoordigt presentatiebestandsindeling gebruikt door OpenOffice.org in de OASISOpen-standaard. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument-presentatiesjabloonbestand (OTP) vertegenwoordigt presentatiesjabloonbestanden gemaakt door toepassingen in OASIS OpenDocument-standaardindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT)-bestand vertegenwoordigt Microsoft PowerPoint-sjabloonbestanden gemaakt door PowerPoint 97-2003-versies. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) zijn bestanden met ondersteuning voor macro's. POTM-bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om meer presentatiebestanden te maken. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX)-bestand vertegenwoordigt Microsoft PowerPoint-sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow-bestanden (PPS) worden gemaakt met behulp van Microsoft PowerPoint voor diavoorstellingen. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM)-bestanden worden gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX)-bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint-presentatie (.ppt) vertegenwoordigt een PowerPoint-bestand dat bestaat uit een verzameling dia's voor weergave als SlideShow. Het specificeert de binaire bestandsindeling die wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95-presentatie (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM)-bestanden die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Ze lijken op PPTX-bestanden, met het verschil dat de laterale geen macro's kan uitvoeren, hoewel ze wel macro's kunnen bevatten. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML-presentatie (.pptx) is een presentatiebestand dat is gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het Microsoft PowerPoint open XML-presentatiebestandsformaat. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Geeft een interne klasse terug, die talloze mogelijkheden biedt voor alle bestaande presentatieformaten |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implementeert IEnumerable generieke interface, die een 'foreach'-mogelijkheid mogelijk maakt voor de PresentationFormats type |

### Zie ook

* interface [IDocumentFormat](../idocumentformat)
* naamruimte [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
