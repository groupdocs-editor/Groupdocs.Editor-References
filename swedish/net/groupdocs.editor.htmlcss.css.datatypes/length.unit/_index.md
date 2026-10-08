---
title: "Length.Unit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Alla stödda längdenheter"
type: docs
weight: 240
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

Alla stödda längdenheter

```csharp
public enum Unit
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Unitless | `0` | Enhetslös - ingen definierad längdenhet. Standardvärde. |
| Px | `1` | Pixel. Relativt till visningsenheten. För skärmvisning är det vanligtvis en enhetspixel (punkt) på displayen. |
| Em | `2` | Em. Denna enhet representerar det beräknade teckenstorleken för elementet. |
| Ex | `3` | Ex (x-längd). Denna enhet representerar x-höjden på elementets teckensnitt. På teckensnitt med bokstaven 'x' är detta vanligtvis höjden på gemena bokstäver i teckensnittet; 1ex ≈ 0,5em i många teckensnitt. |
| Cm | `4` | Cm. En centimeter (10 millimeter). |
| Mm | `5` | Mm. En millimeter. |
| In | `6` | In. En tum (2,54 centimeter). |
| Pt | `7` | Pt. En punkt är 1/72 tum eller 0,353 mm. |
| Pc | `8` | Pc. En pica (12 punkter). |
| Ch | `9` | Ch. Denna enhet representerar bredden, eller mer exakt framstegsmåttet, för tecknet '0' (noll, Unicode-tecknet U+0030) i elementets teckensnitt. |
| Rem | `10` | Rem. Denna enhet representerar teckenstorleken för rot‑elementet (t.ex. teckenstorleken för &lt;html&gt;-elementet). När den används för teckenstorleken på detta rot‑element, representerar den dess ursprungliga värde. |
| Vw | `11` | Vw – viewport‑bredd. 1/100 av bredden på viewporten. |
| Vh | `12` | Vh – viewport‑höjd. 1/100 av höjden på viewporten. |
| Vmin | `13` | Vmin. 1/100 av det minsta värdet mellan höjden och bredden på viewporten. |
| Vmax | `14` | Vmax. 1/100 av det största värdet mellan höjden och bredden på viewporten. |
| Percent | `15` | Värdet är relativt ett fast (externt) värde, som är kontextberoende. 1 % = 1/100 av det externa värdet. |

### Anmärkningar

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### Se även

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
