---
title: "TextDecorationLineType"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les types de ligne de décoration du texte underline underscore overline et line-through strikethrough."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Représente les types de ligne de décoration du texte : souligné (underscore), surligné et barré (strikethrough).

<br />

*** ** * ** ***

Structure immuable. Similaire à https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [None](#None) | Ne produit aucune décoration de texte. |
|
|  | [Underline](#Underline) | Chaque ligne de texte est soulignée. |
|
|  | [Overline](#Overline) | Chaque ligne de texte possède une ligne au-dessus. |
|
|  | [LineThrough](#LineThrough) | Chaque ligne de texte possède une ligne au milieu. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indique si cette instance a une valeur initiale \\u2014 Aucun |
|
|  | [isUnderline()](#isUnderline--) | Indique si le soulignement (underscore) est activé |
|
|  | [isOverline()](#isOverline--) | Indique si la ligne supérieure est activée |
|
|  | [isLineThrough()](#isLineThrough--) | Indique si le trait traversant (strikethrough) est activé |
|
|  | [getValue()](#getValue--) | Renvoie une valeur de tous les indicateurs de cette instance sous forme de texte |
|
|  | [toString()](#toString--) | Renvoie une valeur de tous les indicateurs de cette instance sous forme de texte |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Indique si cette instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) est égale à celle spécifiée |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Indique si cette instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) est égale à celle spécifiée non convertie |
|
|  | [hashCode()](#hashCode--) | Renvoie le code de hachage de cette instance |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Vérifie si deux valeurs \"TextDecorationLineType\" sont égales |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Vérifie si deux valeurs \"TextDecorationLineType\" ne sont pas égales |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Crée et renvoie une instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) avec des indicateurs, définis par les paramètres spécifiés |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Tente d’analyser une chaîne spécifiée et renvoie une instance valide [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Combine (fusionne) deux types de ligne spécifiés et produit un nouveau type de ligne résultant, où les indicateurs sont fusionnés (union) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Soustrait le deuxième type de ligne spécifié du premier type de ligne spécifié et produit un nouveau type de ligne résultant, où ne sont présents que les indicateurs du premier opérande qui ne se trouvent pas dans le deuxième opérande (différence) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Renvoie l’intersection entre le premier et le deuxième type de ligne, où seuls les indicateurs activés simultanément dans les deux opérandes le sont. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Convertit un octet (8 bits) spécifique en le [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) correspondant, lève une exception si la conversion est invalide |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Ne produit aucune décoration de texte. Valeur initiale.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Chaque ligne de texte est soulignée.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Chaque ligne de texte possède une ligne au-dessus.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Chaque ligne de texte possède une ligne au milieu.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indique si cette instance a une valeur initiale \\u2014 Aucun


**Returns:**
booléen
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Indique si le soulignement (underscore) est activé


**Returns:**
booléen
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Indique si la ligne supérieure est activée


**Returns:**
booléen
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Indique si le trait traversant (strikethrough) est activé


**Returns:**
booléen
### getValue() {#getValue--}
```
public final String getValue()
```


Renvoie une valeur de tous les indicateurs de cette instance sous forme de texte


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Renvoie une valeur de tous les indicateurs de cette instance sous forme de texte


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Indique si cette instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) est égale à celle spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Autre instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
booléen -  true  si égaux,  false  sinon

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Indique si cette instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) est égale à celle spécifiée non convertie


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | java.lang.Object | Autre instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), convertie en objet |
|

**Returns:**
booléen -  true  si égaux,  false  sinon

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage de cette instance


**Returns:**
int - Code de hachage entier signé

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Vérifie si deux valeurs \"TextDecorationLineType\" sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Premier opérande à vérifier |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Deuxième opérande à vérifier |
|

**Returns:**
booléen -  true  si égaux,  false  sinon

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Vérifie si deux valeurs \"TextDecorationLineType\" ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Premier opérande à vérifier |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Deuxième opérande à vérifier |
|

**Returns:**
boolean -  vrai  si sont différents,  faux  sinon

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Crée et renvoie une instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) avec des indicateurs, définis par les paramètres spécifiés


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | isUnderline | booléen | Détermine si le drapeau de soulignement est activé ou non |
|
|  | isOverline | booléen | Détermine si le drapeau de surlignement est activé ou non |
|
|  | isLineThrough | booléen | Détermine si le drapeau de barré est activé ou non |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Tente d’analyser une chaîne spécifiée et renvoie une instance valide [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | input | java.lang.String | Chaîne d'entrée |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Résultat. Si l'analyse est invalide, c'est une valeur #None.None |
|

**Returns:**
boolean -  vrai  si l'analyse a réussi,  faux  en cas d'échec

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Combine (fusionne) deux types de ligne spécifiés et produit un nouveau type de ligne résultant, où les indicateurs sont fusionnés (union)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Premier opérande de type de ligne |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Deuxième opérande de type de ligne |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Soustrait le deuxième type de ligne spécifié du premier type de ligne spécifié et produit un nouveau type de ligne résultant, où ne sont présents que les indicateurs du premier opérande qui ne se trouvent pas dans le deuxième opérande (différence)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Premier opérande de type de ligne |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Deuxième opérande de type de ligne |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Renvoie une intersection entre le premier et le deuxième type de ligne, où seuls les drapeaux activés simultanément dans les deux opérandes le sont. Possède la priorité la plus élevée parmi tous les opérateurs (supérieure à l'union et à la différence)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Premier opérande de type de ligne |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Deuxième opérande de type de ligne |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Convertit un octet (8 bits) spécifique en le [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) correspondant, lève une exception si la conversion est invalide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | octet | byte | Un octet de 8 bits (champ de bits), où les 5 bits de tête sont à zéro, tandis que les 3 derniers indiquent des drapeaux |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
