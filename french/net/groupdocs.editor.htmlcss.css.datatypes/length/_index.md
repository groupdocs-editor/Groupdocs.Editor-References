---
title: "Longueur"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une valeur de longueur CSS dans n'importe quelle unité prise en charge, y compris le pourcentage et le type sans unité. Les valeurs peuvent être entières ou flottantes, zéro négatif ou positif. Structure immuable."
type: docs
weight: 230
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Représente une valeur de longueur CSS dans n'importe quelle unité prise en charge, y compris le pourcentage et le type sans unité. Les valeurs peuvent être entières ou flottantes, négatives, zéro ou positives. Structure immuable.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Renvoie une valeur numérique flottante de l'instance Length. Ne lance jamais d'exception – convertit la valeur Integer en Float si nécessaire. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Renvoie une valeur numérique entière de cette instance Length, si elle est stockée en interne comme un entier, ou lance une exception si elle était initialement stockée comme un nombre flottant. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Obtient si la longueur est donnée en unités absolues. Une telle longueur peut être convertie en pixels. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indique si cette instance Length possède une valeur par défaut — zéro sans unité. Identique à la propriété IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indique si la valeur numérique de cette instance Length a été initialement spécifiée et stockée comme un nombre flottant (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indique si la valeur numérique de cette instance Length a été initialement spécifiée et stockée comme un nombre entier (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Détermine si la valeur numérique de cette longueur est un nombre négatif. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Détermine si la valeur numérique de cette longueur est un nombre positif. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Obtient si la longueur est donnée en unités relatives. Une telle longueur ne peut pas être convertie en pixels. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | La valeur est de type sans unité, mais n'est pas zéro – nombre positif ou négatif. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Détermine si cette instance est un zéro sans unité ou non. Le zéro sans unité est la valeur par défaut de ce type. Identique à la propriété IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Détermine si la valeur numérique de cette longueur est zéro. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Renvoie le type d'unité de cette instance Length. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Crée et renvoie une instance du type Length à partir du nombre double spécifié et de l'unité. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Crée et renvoie une instance du type Length à partir du nombre flottant spécifié et de l'unité. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Crée et renvoie une instance du type Length à partir du nombre entier spécifié et de l'unité. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analyse et renvoie la chaîne spécifiée en tant que valeur Length, incluant sa valeur numérique et le nom de l'unité, ou lance une exception en cas d'échec. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Renvoie une copie complète de cette instance Length. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Définit si cette valeur est égale à l'autre longueur spécifiée. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Détermine si cette longueur est égale à l'objet spécifié. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calcule et renvoie un code de hachage de cette instance Length en combinant les codes de hachage de la valeur et du type d'unité. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Renvoie une représentation sous forme de chaîne de cette longueur dans son format natif original (tel qu'il est stocké), sans convertir la valeur de longueur en un autre type d'unité. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Convertit la longueur à l'unité donnée, si possible. Si l'unité actuelle ou donnée est relative, une exception sera levée. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Convertit la longueur en nombre de pixels, si possible. Si l'unité actuelle est relative, une exception sera levée. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Renvoie une représentation sous forme de chaîne de cette longueur dans le type d'unité spécifié. La valeur numérique sera convertie en fonction du changement de type d'unité. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Tente d'analyser le nom d'unité spécifié et renvoie la valeur correspondante d'une énumération Unit. Renvoie Unit.Unitless si aucune unité appropriée n'est trouvée. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Tente d'analyser une chaîne spécifiée comme une valeur Length, incluant sa valeur numérique et le nom de l'unité. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Vérifie l'égalité des deux longueurs fournies. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Vérifie l'inégalité des deux longueurs fournies. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Multiplie la Length donnée par le facteur fourni. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Entier zéro sans unité - valeur par défaut, identique au constructeur sans paramètres par défaut. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Autres membres

| Nom | Description |
| --- | --- |
| enum [Unit](length.unit) | Toutes les unités de longueur prises en charge |

### Remarques

Ce type couvre les types de données CSS suivants : https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Voir aussi

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
