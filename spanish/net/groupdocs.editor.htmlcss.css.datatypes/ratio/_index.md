---
title: "Proporción"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un tipo de datos CSS de proporción que se utiliza para describir relaciones de aspecto en consultas de medios y para imágenes rasterizadas al denotar la proporción entre dos valores sin unidad llamados numerador y denominador. Estructura inmutable."
type: docs
weight: 250
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Representa un tipo de datos CSS "ratio", que se utiliza para describir relaciones de aspecto en consultas de medios y para imágenes rasterizadas al indicar la proporción entre dos valores sin unidad llamados "numerador" y "denominador". Estructura inmutable.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Devuelve el denominador de esta proporción |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | Determina si esta proporción tiene el valor predeterminado o es un "1/1" (Simple) |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Devuelve el numerador de esta proporción |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Crea y devuelve una instancia de Ratio a partir del numerador y denominador especificados |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Calcula y devuelve esta proporción como un único número de punto flotante |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Devuelve una copia completa de esta proporción |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no convertido especificado, que presumiblemente es otra instancia de "Ratio" |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Determina si esta instancia es igual a la instancia de "Ratio" especificada |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Devuelve un código hash para esta instancia, que no puede cambiarse durante su vida útil |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Genera y devuelve una proporción inversa (recíproca) para esta proporción |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Serializa esta proporción a una cadena y la devuelve |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Devuelve una representación en cadena de esta proporción; lo mismo que "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Compara dos proporciones y devuelve un booleano que indica si ambas coinciden. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Compara dos proporciones y devuelve un booleano que indica si las dos no coinciden. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Proporción predeterminada única 1/1 |

### Observaciones

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Ver también

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
