---
title: OtfFont
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt nieuwe OtfFontklasse van inhoud weergegeven als base64gecodeerde tekenreeks en met gespecificeerde naam
type: docs
weight: 10
url: /nl/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

Maakt nieuwe OtfFont-klasse van inhoud, weergegeven als base64-gecodeerde tekenreeks, en met gespecificeerde naam

```csharp
public OtfFont(string name, string contentInBase64)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam van het OTF-lettertype. Mag niet null, leeg of spaties zijn. |
| contentInBase64 | String | Inhoud als base64-gecodeerde tekenreeks. Mag niet null, leeg of spaties zijn. Als het geen OTF-inhoud is, wordt er een uitzondering gegenereerd. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Zie ook

* class [OtfFont](../../otffont)
* naamruimte [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../otffont)
* montage [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

Creëert nieuwe OtfFont-klasse van inhoud, weergegeven als bytestroom, en met gespecificeerde naam

```csharp
public OtfFont(string name, Stream binaryContent)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam van het OTF-lettertype. Mag niet null, leeg of spaties zijn. |
| binaryContent | Stream | Inhoud als bytestroom. Het lezen begint vanaf de oorspronkelijke positie. Kan niet nul zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stream ook verwijderd. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Zie ook

* class [OtfFont](../../otffont)
* naamruimte [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../otffont)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
