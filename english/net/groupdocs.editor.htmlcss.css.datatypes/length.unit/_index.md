---
title: Length.Unit
second_title: GroupDocs.Editor for .NET API Reference
description: All supported length units
type: docs
weight: 240
url: /net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

All supported length units

```csharp
public enum Unit
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Unitless | `0` | Unitless - no defined length unit. Default value. |
| Px | `1` | Pixel. Relative to the viewing device. For screen display, typically one device pixel (dot) of the display. |
| Em | `2` | Em. This unit represents the calculated font-size of the element. |
| Ex | `3` | Ex (x-length). This unit represents the x-height of the element's font. On fonts with the 'x' letter, this is generally the height of lowercase letters in the font; 1ex ≈ 0.5em in many fonts. |
| Cm | `4` | Cm. One centimeter (10 millimeters). |
| Mm | `5` | Mm. One millimeter. |
| In | `6` | In. One inch (2.54 centimeters). |
| Pt | `7` | Pt. One point is 1/72th of an inch or 0.353 mm. |
| Pc | `8` | Pc. One pica (12 points). |
| Ch | `9` | Ch. This unit represents the width, or more precisely the advance measure, of the glyph '0' (zero, the Unicode character U+0030) in the element's font. |
| Rem | `10` | Rem. This unit represents the font-size of the root element (e.g. the font-size of the &lt;html&gt; element). When used on the font-size on this root element, it represents its initial value. |
| Vw | `11` | Vw - viewport width. 1/100th of the width of the viewport. |
| Vh | `12` | Vh - viewport height. 1/100th of the height of the viewport. |
| Vmin | `13` | Vmin. 1/100th of the minimum value between the height and the width of the viewport. |
| Vmax | `14` | Vmax. 1/100th of the maximum value between the height and the width of the viewport. |
| Percent | `15` | The value is relative to a fixed (external) value, that is context dependent. 1% = 1/100 of the external value. |

### Remarks

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### See Also

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
