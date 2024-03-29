---
title: SvgImage
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt een nieuwe SvgImageinstantie van inhoud weergegeven als gebruikelijke tekenreeks en met opgegeven naam
type: docs
weight: 10
url: /nl/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Maakt een nieuwe SvgImage-instantie van inhoud, weergegeven als gebruikelijke tekenreeks, en met opgegeven naam

```csharp
public SvgImage(string name, string content)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam van de SVG-afbeelding. Mag niet null, leeg of spaties zijn. |
| content | String | Inhoud als een gebruikelijke tekenreeks, die een geldige XML-compatibele inhoud van een SVG-afbeelding bevat. Mag niet null, leeg of spaties zijn. Als het geen SVG-inhoud is, wordt er een uitzondering gegenereerd. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Sommige parameters zijn ongeldig |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* argument bevat ongeldige SVG-inhoud |

### Zie ook

* class [SvgImage](../../svgimage)
* naamruimte [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../svgimage)
* montage [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Maakt nieuwe SvgImage-instantie van inhoud, weergegeven als bytestroom, en met opgegeven naam

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam van de SVG-afbeelding. Mag niet null, leeg of spaties zijn. |
| binaryContent | Stream | Inhoud als bytestroom. Het lezen begint vanaf de oorspronkelijke positie. Kan niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stream ook verwijderd. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Zie ook

* class [SvgImage](../../svgimage)
* naamruimte [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../svgimage)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
