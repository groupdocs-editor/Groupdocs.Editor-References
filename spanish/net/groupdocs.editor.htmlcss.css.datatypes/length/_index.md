---
title: Length
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa un valor de longitud de CSS en cualquier unidad compatible incluido el porcentaje y el tipo sin unidades. Los valores pueden ser enteros o flotantes negativos cero y positivos. Estructura inmutable.
type: docs
weight: 260
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Representa un valor de longitud de CSS en cualquier unidad compatible, incluido el porcentaje y el tipo sin unidades. Los valores pueden ser enteros o flotantes, negativos, cero y positivos. Estructura inmutable.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Devuelve un valor numérico flotante de la instancia de Longitud. Nunca arroja una excepción: convierte el valor entero en flotante si es necesario. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Devuelve un valor numérico entero de esta instancia de Longitud, si se almacena internamente como un número entero, o genera una excepción, si se almacenó originalmente como un número flotante. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Se obtiene si la longitud se da en unidades absolutas. Dicha longitud se puede convertir en píxeles. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indica si el valor numérico de esta instancia de Longitud se especificó y almacenó originalmente como un flotante (FP32) número |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indica si el valor numérico de esta instancia de longitud se especificó y almacenó originalmente como un número entero (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Determina si el valor numérico de esta longitud es un número negativo |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Determina si el valor numérico de esta longitud es un número positivo |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Se obtiene si la longitud se da en unidades relativas. Tal longitud no se puede convertir a píxeles. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | El valor tiene tipo sin unidad, pero no es un cero - número positivo o negativo |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Determina si esta instancia es un cero sin unidades o no. El cero sin unidades es el valor predeterminado de este tipo. Igual que la propiedad IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Determina si el valor numérico de esta longitud es un número cero |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Devuelve un tipo de unidad de esta instancia de Longitud. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Crea y devuelve una instancia de tipo Longitud por número doble especificado y unidad |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Crea y devuelve una instancia de tipo Longitud por número flotante especificado y unidad |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Crea y devuelve una instancia de tipo Longitud por número entero especificado y unidad |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analiza y devuelve la cadena especificada como un valor de Longitud, incluido su valor numérico y el nombre de la unidad, o lanza una excepción en caso de falla |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Devuelve una copia completa de esta instancia de Longitud |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Define si este valor es igual a la otra longitud especificada |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Determina si esta longitud es igual al objeto especificado |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calcula y devuelve un código hash de esta instancia de Longitud combinando códigos hash del valor y tipo de unidad |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Devuelve una representación de cadena de esta longitud en su forma nativa original (tal como está almacenada), sin convertir el valor de longitud a alguna otra unidad type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Convierte la longitud a la unidad dada, si es posible. Si el current o la unidad dada es relativa, se lanzará una excepción. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Convierte la longitud a un número de píxeles, si es posible. Si la unidad actual es relativa, se lanzará una excepción. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Devuelve una representación de cadena de esta longitud en el tipo de unidad especificado. El valor numérico se convertirá en el correspondiente al cambio de tipo de unidad. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Intenta analizar el nombre de unidad especificado y devuelve el valor correspondiente de una enumeración de unidad. Devuelve Unit.Unitless si no puede encontrar la unidad adecuada. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Intenta analizar una cadena especificada como un valor de Longitud, incluido su valor numérico y el nombre de la unidad |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Comprueba la igualdad de las dos longitudes dadas. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Comprueba la desigualdad de las dos longitudes dadas. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Multiplica la Longitud dada por el factor dado |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Número entero sin unidades cero: valor predeterminado, igual que el constructor sin parámetros predeterminado |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [Unit](length.unit) | Todas las unidades de longitud admitidas |

### Observaciones

Este tipo cubre los siguientes tipos de datos CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/porcentaje

### Ver también

* interface [ICssDataType](../icssdatatype)
* espacio de nombres [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
