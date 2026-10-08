---
title: "Length.Unit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Todas las unidades de longitud compatibles"
type: docs
weight: 240
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

Todas las unidades de longitud compatibles

```csharp
public enum Unit
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Unitless | `0` | Sin unidad - no hay una unidad de longitud definida. Valor predeterminado. |
| Px | `1` | Píxel. Relativo al dispositivo de visualización. Para la visualización en pantalla, típicamente un píxel del dispositivo (punto) de la pantalla. |
| Em | `2` | Em. Esta unidad representa el tamaño de fuente calculado del elemento. |
| Ex | `3` | Ex (x-length). Esta unidad representa la altura x de la fuente del elemento. En fuentes con la letra 'x', generalmente es la altura de las letras minúsculas; 1ex ≈ 0.5em en muchas fuentes. |
| Cm | `4` | Cm. Un centímetro (10 milímetros). |
| Mm | `5` | Mm. Un milímetro. |
| In | `6` | In. Una pulgada (2,54 centímetros). |
| Pt | `7` | Pt. Un punto es 1/72 de una pulgada o 0,353 mm. |
| Pc | `8` | Pc. Una pica (12 puntos). |
| Ch | `9` | Ch. Esta unidad representa el ancho, o más precisamente la medida de avance, del glifo '0' (cero, el carácter Unicode U+0030) en la fuente del elemento. |
| Rem | `10` | Rem. Esta unidad representa el tamaño de fuente del elemento raíz (p. ej., el tamaño de fuente del elemento &lt;html&gt;). Cuando se usa en el tamaño de fuente de este elemento raíz, representa su valor inicial. |
| Vw | `11` | Vw - ancho del viewport. 1/100 del ancho del viewport. |
| Vh | `12` | Vh - altura del viewport. 1/100 de la altura del viewport. |
| Vmin | `13` | Vmin. 1/100 del valor mínimo entre la altura y el ancho del viewport. |
| Vmax | `14` | Vmax. 1/100 del valor máximo entre la altura y el ancho del viewport. |
| Percent | `15` | El valor es relativo a un valor fijo (externo), que depende del contexto. 1 % = 1/100 del valor externo. |

### Observaciones

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### Ver también

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
