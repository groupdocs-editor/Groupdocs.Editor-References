---
title: "Longueur"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une valeur de longueur CSS dans n’importe quelle unité prise en charge, y compris le pourcentage et le type sans unité."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Représente une valeur de longueur CSS dans n’importe quelle unité prise en charge, y compris le pourcentage
et le type sans unité. Les valeurs peuvent être entières ou flottantes, négatives, nulles et
positives. Structure immuable.

*** ** * ** ***


Ce type couvre les types de données CSS suivants :

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Length()](#Length--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Entier zéro sans unité - valeur par défaut, identique au paramètre par défaut sans arguments |
constructeur
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Crée et renvoie une instance du type Longueur à partir du nombre flottant spécifié |
et unité
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Crée et renvoie une instance du type Longueur à partir du nombre double spécifié |
et unité
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Crée et renvoie une instance du type Length à partir d'un entier spécifié |
nombre et unité
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Détermine si cette instance est un zéro sans unité ou non. |
|
|  | [isDefault()](#isDefault--) | Indique si cette instance Length a une valeur par défaut \\u2014 sans unité |
zéro.
|
|  | [getUnitType()](#getUnitType--) | Renvoie un type d'unité de cette instance Length. |
|
|  | [isInteger()](#isInteger--) | Indique si la valeur numérique de cette instance Length était |
initialement spécifiée et stockée en tant que nombre entier (INT32)
|
|  | [isFloat()](#isFloat--) | Indique si la valeur numérique de cette instance Length était |
initialement spécifiée et stockée en tant que nombre flottant (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | Renvoie une valeur numérique flottante de l'instance Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Renvoie une valeur numérique entière de cette instance Length, si elle est |
stockée en interne comme un entier, ou lève une exception, si elle était
initialement stockée comme un nombre flottant.
|
|  | [isAbsolute()](#isAbsolute--) | Obtient si la longueur est donnée en unités absolues. |
|
|  | [isRelative()](#isRelative--) | Obtient si la longueur est donnée en unités relatives. |
|
|  | [isZero()](#isZero--) | Détermine si la valeur numérique de cette longueur est un nombre zéro |
|
|  | [isNegative()](#isNegative--) | Détermine si la valeur numérique de cette longueur est un nombre négatif |
|
|  | [isPositive()](#isPositive--) | Détermine si la valeur numérique de cette longueur est un nombre positif |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | La valeur est de type sans unité, mais n'est pas un zéro - positif ou négatif |
number
|
|  | [toPixel()](#toPixel--) | Convertit la longueur en un nombre de pixels, si possible. |
|
|  | [to(int unit)](#to-int-) | Convertit la longueur dans l'unité donnée, si possible. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Renvoie une représentation sous forme de chaîne de cette longueur dans le type d'unité spécifié. |
|
|  | [serializeDefault()](#serializeDefault--) | Renvoie une représentation sous forme de chaîne de cette longueur dans son format natif original |
forme (telle qu'elle est stockée), sans convertir la valeur de longueur en une autre
type d'unité
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Définit si cette valeur est égale à l'autre longueur spécifiée |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette longueur est égale à l'objet spécifié |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Multiplie la Length donnée par le facteur fourni |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Vérifie l'égalité des deux longueurs données. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Vérifie l'inégalité des deux longueurs données. |
|
|  | [hashCode()](#hashCode--) | Calcule et renvoie un code de hachage de cette instance Length en combinant |
les codes de hachage de la valeur et du type d'unité
|
|  | [deepClone()](#deepClone--) | Renvoie une copie complète de cette instance Length |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Essaie d'analyser le nom d'unité spécifié et renvoie la valeur correspondante d'un |
Énumération Unit.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Essaie d'analyser une chaîne spécifiée comme une valeur Length, y compris son |
valeur numérique et nom d'unité
|
|  | [parse(String input)](#parse-java.lang.String-) | Analyse et renvoie la chaîne spécifiée comme une valeur Length, y compris son |
valeur numérique et nom d'unité, ou lève une exception en cas d'échec
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Entier zéro sans unité - valeur par défaut, identique au paramètre par défaut sans arguments
constructeur


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Crée et renvoie une instance du type Longueur à partir du nombre flottant spécifié
et unité


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | \>Tout nombre flottant (FP32) |
|
|  | unité | int | Tout type d'unité valide |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Crée et renvoie une instance du type Longueur à partir du nombre double spécifié
et unité


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | Tout nombre double (FP64), qui sera converti en flottant (FP32) |
|
|  | unité | int | Tout type d'unité valide |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Crée et renvoie une instance du type Length à partir d'un entier spécifié
nombre et unité


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Tout nombre entier |
|
|  | unité | int | Tout type d'unité valide |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Détermine si cette instance est un zéro sans unité ou non. Zéro sans unité
est la valeur par défaut de ce type. Identique à la propriété IsDefault.


**Returns:**
booléen
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indique si cette instance Length a une valeur par défaut \\u2014 sans unité
zéro. Identique à la propriété IsUnitlessZero.


**Returns:**
booléen
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Renvoie un type d'unité de cette instance Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Indique si la valeur numérique de cette instance Length était
initialement spécifiée et stockée en tant que nombre entier (INT32)


**Returns:**
booléen
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Indique si la valeur numérique de cette instance Length était
initialement spécifiée et stockée en tant que nombre flottant (FP32)


**Returns:**
booléen
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Renvoie une valeur numérique flottante de l'instance Length. Ne lève jamais une
exception - convertit la valeur Integer en Float si nécessaire.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Renvoie une valeur numérique entière de cette instance Length, si elle est
stockée en interne comme un entier, ou lève une exception, si elle était
initialement stockée comme un nombre flottant.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Obtient si la longueur est donnée en unités absolues. Une telle longueur peut être
convertie en pixels.


**Returns:**
booléen
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Obtient si la longueur est donnée en unités relatives. Une telle longueur ne peut pas être
convertie en pixels.


**Returns:**
booléen
### isZero() {#isZero--}
```
public final boolean isZero()
```


Détermine si la valeur numérique de cette longueur est un nombre zéro


**Returns:**
booléen
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Détermine si la valeur numérique de cette longueur est un nombre négatif


**Returns:**
booléen
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Détermine si la valeur numérique de cette longueur est un nombre positif


**Returns:**
booléen
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


La valeur est de type sans unité, mais n'est pas un zéro - positif ou négatif
number


**Returns:**
booléen
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Convertit la longueur en un nombre de pixels, si possible. Si l'actuel
l'unité est relative, alors une exception sera levée.


**Returns:**
float - Le nombre de pixels représenté par la longueur actuelle.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Convertit la longueur dans l'unité donnée, si possible. Si l'actuelle ou
l'unité donnée est relative, alors une exception sera levée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | unité | int | L'unité vers laquelle convertir. |
|

**Returns:**
float - La valeur dans l'unité donnée de la longueur actuelle.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Renvoie une représentation sous forme de chaîne de cette longueur dans le type d'unité spécifié.
La valeur numérique sera convertie en fonction du changement de type d'unité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | unité | int | Unité spécifiée, vers laquelle cette instance doit être convertie avant de la sérialiser en chaîne. Doit être valide. Ne peut pas être sans unité. |
|

**Returns:**
java.lang.String - Représentation de chaîne

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Renvoie une représentation sous forme de chaîne de cette longueur dans son format natif original
forme (telle qu'elle est stockée), sans convertir la valeur de longueur en une autre
type d'unité


**Returns:**
java.lang.String - Instance de chaîne

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Définit si cette valeur est égale à l'autre longueur spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Autre instance du type Length |
|

**Returns:**
boolean - Vrai si égal, sinon faux

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette longueur est égale à l'objet spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance du type Length, qui est encapsulée dans System.Object ou tout autre type abstrait ou interface |
|

**Returns:**
boolean - Vrai si égal, sinon faux

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Multiplie la Length donnée par le facteur fourni


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - multiplicande |
|
|  | facteur | int | Entier arbitraire - facteur |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Vérifie l'égalité des deux longueurs données.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'opérande de longueur gauche. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'opérande de longueur droite. |
|

**Returns:**
boolean - Vrai si les deux longueurs sont égales, sinon faux.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Vérifie l'inégalité des deux longueurs données.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'opérande de longueur gauche. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'opérande de longueur droite. |
|

**Returns:**
boolean - Vrai si les deux longueurs ne sont pas égales, sinon faux.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcule et renvoie un code de hachage de cette instance Length en combinant
les codes de hachage de la valeur et du type d'unité


**Returns:**
int - Nombre entier

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Renvoie une copie complète de cette instance Length


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Essaie d'analyser le nom d'unité spécifié et renvoie la valeur correspondante d'un
Énumération Unit. Retourne LengthUnit.Unitless si aucune LengthUnit appropriée n'est trouvée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | unitName | java.lang.String | Chaîne, qui représente le nom d'une unité |
|

**Returns:**
int - Valeur de l'énumération Unit dans tous les cas, LengthUnit.Unitless lorsqu'aucune unité appropriée n'est trouvée

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Essaie d'analyser une chaîne spécifiée comme une valeur Length, y compris son
valeur numérique et nom d'unité


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | input | java.lang.String | Chaîne d'entrée, qui doit être analysée |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Paramètre de sortie, qui contient le résultat de l'analyse. Si l'analyse échoue, il contient une valeur Length par défaut \\u2014 un zéro sans unité. |
|

**Returns:**
boolean - Vrai si l'analyse réussit, false si elle échoue

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Analyse et renvoie la chaîne spécifiée comme une valeur Length, y compris son
valeur numérique et nom d'unité, ou lève une exception en cas d'échec


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | input | java.lang.String | Chaîne d'entrée, qui doit être analysée |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

