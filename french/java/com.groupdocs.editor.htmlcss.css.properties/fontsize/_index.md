---
title: "FontSize"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une taille de police comme une unité spéciale ou une valeur de longueur qui spécifie la taille de la police, historiquement la largeur du M majuscule."
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Représente une taille de police comme une unité spéciale ou une valeur de longueur, qui spécifie la taille de la police (historique la largeur du caractère majuscule "M").

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Medium](#Medium) | Taille moyenne. |
|
|  | [XxSmall](#XxSmall) | La très petite taille absolue |
|
|  | [XSmall](#XSmall) | La petite taille absolue moyenne |
|
|  | [Small](#Small) | La petite taille absolue normale |
|
|  | [Large](#Large) | La grande taille absolue normale |
|
|  | [XLarge](#XLarge) | La grande taille absolue moyenne |
|
|  | [XxLarge](#XxLarge) | La très grande taille absolue |
|
|  | [Larger](#Larger) | Taille relative plus grande - la police sera plus grande par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue ci‑dessus. |
|
|  | [Smaller](#Smaller) | Taille relative plus petite - la police sera plus petite par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue ci‑dessus. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indique si cette taille de police a une valeur initiale (Moyenne) |
|
|  | [getValue()](#getValue--) | Renvoie une valeur de cette taille de police sous forme de chaîne |
|
|  | [isLengthDefined()](#isLengthDefined--) | Indique si cette taille de police (font-size) est définie avec une valeur [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | Une valeur de longueur, si cette font-size a été définie avec elle, ou une exception levée sinon |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Indique si cette font-size est définie avec une taille absolue sous forme de mot‑clé, basée sur la taille de police par défaut de l'utilisateur (qui est medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Indique si cette font-size est définie avec une taille relative sous forme de mot‑clé. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Détermine si cette instance de font-size est égale à celle spécifiée |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance de font-size est égale à celle spécifiée non convertie |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Vérifie si deux valeurs "FontSize" sont égales |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Vérifie si deux valeurs "FontSize" ne sont pas égales |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Crée une font-size à partir de la longueur spécifiée |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Essaie de reconnaître un mot‑clé spécifié comme valeur de mot‑clé appropriée de la 'font-size' et le renvoie en cas de succès ou NULL en cas d'échec. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Taille medium. Valeur initiale.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


La très petite taille absolue


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


La petite taille absolue moyenne


### Small {#Small}
```
public static final FontSize Small
```


La petite taille absolue normale


### Large {#Large}
```
public static final FontSize Large
```


La grande taille absolue normale


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


La grande taille absolue moyenne


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


La très grande taille absolue


### Larger {#Larger}
```
public static final FontSize Larger
```


Taille relative plus grande - la police sera plus grande par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue ci‑dessus.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Taille relative plus petite - la police sera plus petite par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue ci‑dessus.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indique si cette taille de police a une valeur initiale (Moyenne)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Renvoie une valeur de cette taille de police sous forme de chaîne


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Indique si cette taille de police (font-size) est définie avec une valeur [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Une valeur de longueur, si cette font-size a été définie avec elle, ou une exception levée sinon


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Indique si cette font-size est définie avec une taille absolue sous forme de mot‑clé, basée sur la taille de police par défaut de l'utilisateur (qui est medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Indique si cette font-size est définie avec une taille relative sous forme de mot‑clé. La police sera plus grande ou plus petite par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Détermine si cette instance de font-size est égale à celle spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Autre instance de font-size |
|

**Returns:**
booléen - vrai si sont égaux, faux sinon

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance de font-size est égale à celle spécifiée non convertie


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance de font-size non convertie, peut être nulle |
|

**Returns:**
booléen - vrai si sont égaux, faux si différents, null ou d'un autre type

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.


**Returns:**
int - Code de hachage en tant qu'entier signé

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Vérifie si deux valeurs "FontSize" sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Première valeur à vérifier |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - vrai si sont égaux, faux sinon

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Vérifie si deux valeurs "FontSize" ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Première valeur à vérifier |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - faux si sont égaux, vrai sinon

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Crée une font-size à partir de la longueur spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Une valeur de longueur, ne peut être sans unité ou négative |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Essaie de reconnaître un mot‑clé spécifié comme valeur de mot‑clé appropriée de la 'font-size' et le renvoie en cas de succès ou NULL en cas d'échec.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mot‑clé | java.lang.String | Un mot‑clé à analyser |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Résultat, le parsing a réussi, ou #Medium.Medium sinon |
|

**Returns:**
booléen - vrai si l'analyse a réussi, faux sinon

