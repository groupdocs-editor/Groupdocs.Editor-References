---
title: "Longitud"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un valor de longitud CSS en cualquier unidad compatible, incluyendo porcentaje y tipo sin unidad. Los valores pueden ser enteros o flotantes, cero negativo y positivo. Estructura inmutable."
type: docs
weight: 230
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Representa un valor de longitud CSS en cualquier unidad compatible, incluyendo porcentaje y tipo sin unidad. Los valores pueden ser enteros o flotantes, negativos, cero y positivos. Estructura inmutable.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Devuelve un valor numérico flotante de la instancia Length. Nunca lanza una excepción - convierte el valor entero a flotante si es necesario. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Devuelve un valor numérico entero de esta instancia Length, si está almacenado internamente como entero, o lanza una excepción, si originalmente se almacenó como número flotante. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Obtiene si la longitud se da en unidades absolutas. Esa longitud puede convertirse a píxeles. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indica si esta instancia Length tiene un valor predeterminado — cero sin unidad. Igual que la propiedad IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indica si el valor numérico de esta instancia Length se especificó y almacenó originalmente como un número flotante (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indica si el valor numérico de esta instancia Length se especificó y almacenó originalmente como un número entero (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Determina si el valor numérico de esta longitud es un número negativo. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Determina si el valor numérico de esta longitud es un número positivo. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Obtiene si la longitud se da en unidades relativas. Esa longitud no puede convertirse a píxeles. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | El valor tiene tipo sin unidad, pero no es cero - es un número positivo o negativo. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Determina si esta instancia es un cero sin unidad o no. El cero sin unidad es el valor predeterminado de este tipo. Igual que la propiedad IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Determina si el valor numérico de esta longitud es un número cero. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Devuelve el tipo de unidad de esta instancia Length. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Crea y devuelve una instancia del tipo Length a partir del número double especificado y la unidad. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Crea y devuelve una instancia del tipo Length a partir del número float especificado y la unidad. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Crea y devuelve una instancia del tipo Length a partir del número entero especificado y la unidad. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analiza y devuelve la cadena especificada como un valor Length, incluyendo su valor numérico y nombre de unidad, o lanza una excepción en caso de error. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Devuelve una copia completa de esta instancia Length. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Define si este valor es igual a la otra longitud especificada. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Determina si esta longitud es igual al objeto especificado. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calcula y devuelve un código hash de esta instancia Length combinando los códigos hash del valor y del tipo de unidad. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Devuelve una representación en cadena de esta longitud en su forma nativa original (tal como está almacenada), sin convertir el valor de longitud a otro tipo de unidad. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Convierte la longitud a la unidad dada, si es posible. Si la unidad actual o la dada es relativa, se lanzará una excepción. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Convierte la longitud a un número de píxeles, si es posible. Si la unidad actual es relativa, se lanzará una excepción. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Devuelve una representación en cadena de esta longitud en el tipo de unidad especificado. El valor numérico se convertirá de acuerdo con el cambio de tipo de unidad. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Intenta analizar el nombre de unidad especificado y devolver el valor correspondiente de un enum Unit. Devuelve Unit.Unitless si no se puede encontrar una unidad adecuada. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Intenta analizar una cadena especificada como un valor Length, incluyendo su valor numérico y el nombre de la unidad |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Comprueba la igualdad de las dos longitudes dadas. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Comprueba la desigualdad de las dos longitudes dadas. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Multiplica la Length dada por el factor proporcionado |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Entero cero sin unidad - valor predeterminado, igual que el constructor predeterminado sin parámetros |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [Unit](length.unit) | Todas las unidades de longitud compatibles |

### Observaciones

Este tipo cubre los siguientes tipos de datos CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Ver también

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
