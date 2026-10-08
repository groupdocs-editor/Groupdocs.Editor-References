---
title: "Dimensiones"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa las dimensiones lineales de ancho y alto de una imagen rectangular raster en una unidad arbitraria. Estructura inmutable."
type: docs
weight: 450
url: /es/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Representa las dimensiones lineales (ancho y alto) de una imagen rectangular raster en unidades arbitrarias. Estructura inmutable.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Crea una nueva instancia a partir del ancho y alto especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Devuelve una instancia Dimensions vacía |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Devuelve un área (Ancho x Alto) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Relación de aspecto de estas dimensiones como ancho/alto |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Devuelve la altura de la imagen. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Determina si esta instancia "Dimensions" está vacía y es predeterminada, es decir, no almacena el ancho y la altura correctos |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Determina si el 'Dimensions' especificado representa un cuadrado, es decir, si el ancho es igual a la altura |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Devuelve el ancho de la imagen |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Devuelve una copia completa de esta instancia |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Determina si esta instancia es igual a la instancia "Dimensions" especificada |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no convertido especificado, que presumiblemente es otra instancia "Dimensions" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Devuelve un código hash para esta instancia, que no puede cambiarse durante su vida útil |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Crea y devuelve una nueva instancia "Dimensions", que se redimensiona proporcionalmente a partir de la actual, basada en la altura especificada |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Crea y devuelve una nueva instancia "Dimensions", que se redimensiona proporcionalmente a partir de la actual, basada en el ancho especificado |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Devuelve una representación en cadena de este "Dimensions" |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | Comprueba si dos valores "Dimensions" son iguales, es decir, tienen el mismo ancho y altura, o ambos están vacíos |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | Comprueba si dos valores "Dimensions" no son iguales, es decir, su ancho y/o altura correspondientes son diferentes |

### Ver también

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
