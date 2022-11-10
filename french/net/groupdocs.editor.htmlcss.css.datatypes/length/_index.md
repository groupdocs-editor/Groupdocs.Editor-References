---
title: Length
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Représente une valeur de longueur CSS dans nimporte quelle unité prise en charge y compris le pourcentage et le type sans unité. Les valeurs peuvent être entières ou flottantes négatives nulles et positives. Structure immuable.
type: docs
weight: 190
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Représente une valeur de longueur CSS dans n'importe quelle unité prise en charge, y compris le pourcentage et le type sans unité. Les valeurs peuvent être entières ou flottantes, négatives, nulles et positives. Structure immuable.

```csharp
public struct Length : ICloneable, IEquatable<  >, IEquatable<Length>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Renvoie une valeur numérique flottante de l'instance Length. Ne lève jamais d'exception - convertit la valeur Integer en Float si nécessaire. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Renvoie une valeur numérique entière de cette instance de longueur, si elle est stockée en interne sous forme d'entier, ou lève une exception, si elle était initialement stockée sous forme de nombre flottant. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Obtient si la longueur est donnée en unités absolues. Une telle longueur peut être convertie en pixels. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indique si cette instance de longueur a une valeur par défaut — zéro sans unité. Identique à la propriété IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indique si la valeur numérique de cette instance de longueur a été initialement spécifiée et stockée en tant que nombre flottant (FP32) number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indique si la valeur numérique de cette instance de longueur a été initialement spécifiée et stockée sous la forme d'un nombre entier (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Détermine si la valeur numérique de cette longueur est un nombre négatif |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Détermine si la valeur numérique de cette longueur est un nombre positif |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Obtient si la longueur est donnée en unités relatives. Une telle longueur ne peut pas être convertie en pixels. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | La valeur a un type sans unité, mais n'est pas un zéro - nombre positif ou négatif |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Détermine si cette instance est un zéro sans unité ou non. Le zéro sans unité est la valeur par défaut de ce type. Identique à la propriété IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Détermine si la valeur numérique de cette longueur est un nombre nul |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Renvoie un type d'unité de cette instance de longueur. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Crée et renvoie une instance de type Longueur par le nombre double spécifié et l'unité |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Crée et renvoie une instance de type Longueur par le nombre flottant spécifié et l'unité |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Crée et renvoie une instance de type Longueur par le nombre entier spécifié et l'unité |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analyse et renvoie la chaîne spécifiée en tant que valeur de longueur, y compris sa valeur numérique et le nom de l'unité, ou lève une exception en cas d'échec |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Renvoie une copie complète de cette instance Length |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Définit si cette valeur est égale à l'autre longueur spécifiée |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Détermine si cette longueur est égale à l'objet spécifié |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Calcule et renvoie un code de hachage de cette instance de longueur en combinant les codes de hachage de la valeur et du type d'unité |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Renvoie une représentation sous forme de chaîne de cette longueur dans sa forme native d'origine (telle qu'elle est stockée), sans convertir la valeur de longueur en un autre type d'unité |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Convertit la longueur dans l'unité donnée, si possible. Si l'unité actuelle ou donnée est relative, une exception sera levée. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Convertit la longueur en nombre de pixels, si possible. Si l'unité actuelle est relative, une exception sera levée. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Renvoie une représentation sous forme de chaîne de cette longueur dans le type d'unité spécifié. La valeur numérique sera convertie en correspondant au changement de type d'unité. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Essaie d'analyser le nom d'unité spécifié et de renvoyer la valeur correspondante d'une énumération d'unité. Renvoie Unit.Unitless si ne peut pas trouver l'unité appropriée. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Tente d'analyser une chaîne spécifiée en tant que valeur de longueur, y compris sa valeur numérique et son nom d'unité |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Vérifie l'égalité des deux longueurs données. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Vérifie l'inégalité des deux longueurs données. |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Entier sans unité zéro - valeur par défaut, identique au constructeur sans paramètre par défaut |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Autres membres

| Nom | La description |
| --- | --- |
| enum [Unit](length.unit) | Toutes les unités de longueur prises en charge |

### Remarques

Ce type couvre les types de données CSS suivants : https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/pourcentage

### Voir également

* espace de noms [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
