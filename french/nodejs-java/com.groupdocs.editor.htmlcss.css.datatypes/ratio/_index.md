---
title: "Ratio"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente un type de données CSS « ratio » qui est utilisé pour décrire les rapports d’aspect dans les requêtes média et pour les images raster en indiquant la proportion entre deux valeurs sans unité appelées numérateur et dénominateur."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Représente un type de données CSS "ratio", qui est utilisé pour décrire l’aspect
ratios dans les requêtes média et pour les images raster en indiquant la proportion
entre deux valeurs sans unité appelées "numerator" et "denominator". Immuable
struct.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Single](#Single) | Ratio par défaut simple 1/1 |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Renvoie le numérateur de ce ratio |
|
|  | [getDenominator()](#getDenominator--) | Renvoie le dénominateur de ce ratio |
|
|  | [calculate()](#calculate--) | Calcule et renvoie ce ratio sous forme d’un nombre à virgule flottante unique |
|
|  | [getInverseRatio()](#getInverseRatio--) | Génère et renvoie un ratio inverse (réciproque) pour ce ratio |
|
|  | [serializeDefault()](#serializeDefault--) | Sérialise ce ratio en chaîne et le renvoie |
|
|  | [toString()](#toString--) | Renvoie une représentation sous forme de chaîne de ce ratio ; identique à |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Détermine si ce ratio a la valeur par défaut ou est un "1/1" (Simple) |
|
|  | [deepClone()](#deepClone--) | Renvoie une copie complète de ce ratio |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Détermine si cette instance est égale à l'instance \"Ratio\" spécifiée |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est probablement une autre instance \"Ratio\"
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Compare deux ratios et renvoie un booléen indiquant si les deux correspondent. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Compare deux ratios et renvoie un booléen indiquant si les deux ne |
correspondent.
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant son |
durée de vie
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Crée et renvoie une instance Ratio à partir du numérateur spécifié et du |
dénominateur
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Ratio par défaut simple 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Renvoie le numérateur de ce ratio


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Renvoie le dénominateur de ce ratio


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Calcule et renvoie ce ratio sous forme d’un nombre à virgule flottante unique


**Returns:**
double - Nombre à virgule flottante à double précision

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Génère et renvoie un ratio inverse (réciproque) pour ce ratio


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Sérialise ce ratio en chaîne et le renvoie


**Returns:**
java.lang.String - Chaîne au format \"numérateur/dénominateur\"

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de ce ratio ; identique à
"SerializeDefault()"


**Returns:**
java.lang.String - Chaîne au format \"numérateur/dénominateur\"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Détermine si ce ratio a la valeur par défaut ou est un "1/1" (Simple)


**Returns:**
booléen
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Renvoie une copie complète de ce ratio


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Détermine si cette instance est égale à l'instance \"Ratio\" spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Autre instance Ratio à vérifier pour l'égalité avec celle-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est probablement une autre instance \"Ratio\"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | autre | java.lang.Object | Autre instance System.Object, qui est probablement de type Ratio, à vérifier pour l'égalité avec celle-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Compare deux ratios et renvoie un booléen indiquant si les deux correspondent.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Le premier ratio à utiliser. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Le deuxième ratio à utiliser. |
|

**Returns:**
boolean - Vrai si les deux ratios sont égaux, sinon faux.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Compare deux ratios et renvoie un booléen indiquant si les deux ne
correspondent.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Le premier ratio à utiliser. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Le deuxième ratio à utiliser. |
|

**Returns:**
boolean - Vrai si les deux ratios ne sont pas égaux, sinon faux.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant son
durée de vie


**Returns:**
int - Entier signé de 4 octets, qui est immuable pour cette instance

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Crée et renvoie une instance Ratio à partir du numérateur spécifié et du
dénominateur


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | numérateur | int | Numérateur du ratio. Doit être un nombre entier strictement positif. |
|
|  | dénominateur | int | Dénominateur du ratio. Doit être un nombre entier strictement positif. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

