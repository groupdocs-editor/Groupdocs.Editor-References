---
title: "FontWeight"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "La propriété font-weight définit le poids ou l'épaisseur de la police."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

La propriété font-weight définit le poids (ou l'épaisseur) de la police. Les poids disponibles dépendent de la famille de polices actuellement définie.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Lighter](#Lighter) | Un poids de police relatif plus léger que l'élément parent |
|
|  | [Bolder](#Bolder) | Un poids de police relatif plus lourd que l'élément parent |
|
|  | [Normal](#Normal) | Poids de police normal. |
|
|  | [Bold](#Bold) | Poids de police gras. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indique si cette taille de police a une valeur initiale (Medium) |
|
|  | [getNumber()](#getNumber--) | Renvoie un nombre - valeur entière comprise entre 1 et 1000, inclusive, qui décrit le gras de la police, ou lève une exception si le gras actuel n'est pas absolu, mais relatif. |
|
|  | [isAbsolute()](#isAbsolute--) | Indique si cette instance de font-weight stocke une valeur absolue du poids (gras) de la police, sous forme de nombre entier. |
|
|  | [isRelative()](#isRelative--) | Indique si cette instance de font-weight stocke une valeur relative du poids (gras) de la police - comparée au gras de l'élément parent. |
|
|  | [getValue()](#getValue--) | Renvoie la valeur de ce font-weight sous forme de chaîne. |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Détermine si les instances de FontWeight spécifiées sont égales. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance de FontWeight est égale à l'instance non convertie spécifiée. |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Vérifie si deux valeurs "FontWeight" sont égales. |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Vérifie si deux valeurs "FontWeight" ne sont pas égales. |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Crée un font-weight à partir du nombre spécifié. |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Tente d'analyser une chaîne spécifiée et renvoie une instance valide de FontWeight en cas de succès. |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Un poids de police relatif plus léger que l'élément parent


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Un poids de police relatif plus lourd que l'élément parent


### Normal {#Normal}
```
public static final FontWeight Normal
```


Poids de police normal. Identique à 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Poids de police gras. Identique à 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indique si cette taille de police a une valeur initiale (Medium)


**Returns:**
booléen
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Renvoie un nombre - valeur entière comprise entre 1 et 1000, inclusive, qui décrit le gras de la police, ou lève une exception si le gras actuel n'est pas absolu, mais relatif.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Indique si cette instance de font-weight stocke une valeur absolue du poids (gras) de la police, sous forme de nombre entier.


**Returns:**
booléen
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Indique si cette instance de font-weight stocke une valeur relative du poids (gras) de la police - comparée au gras de l'élément parent.


**Returns:**
booléen
### getValue() {#getValue--}
```
public final String getValue()
```


Renvoie la valeur de ce font-weight sous forme de chaîne.


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Détermine si les instances de FontWeight spécifiées sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Autre instance de FontWeight pour vérifier l'égalité. |
|

**Returns:**
booléen - vrai si égaux, faux si différents.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance de FontWeight est égale à l'instance non convertie spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance de FontWeight non convertie, peut être nulle. |
|

**Returns:**
booléen - vrai si sont égaux, faux si différents, nul ou d'un autre type

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.


**Returns:**
int - Code de hachage en tant qu'entier signé

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Vérifie si deux valeurs "FontWeight" sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Première valeur à vérifier |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - vrai si sont égaux, faux sinon

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Vérifie si deux valeurs "FontWeight" ne sont pas égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Première valeur à vérifier |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - faux si sont égaux, vrai sinon

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Crée un font-weight à partir du nombre spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | number | int | Entier non signé, doit être compris dans l'intervalle [1..1000]. |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Tente d'analyser une chaîne spécifiée et renvoie une instance valide de FontWeight en cas de succès.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | input | java.lang.String | Chaîne d'entrée à analyser. |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Valeur FontWeight valide en cas de succès ou #Normal.Normal en cas d'échec. |
|

**Returns:**
booléen - Succès (true) ou échec (false) de l'analyse.

