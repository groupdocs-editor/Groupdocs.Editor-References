---
title: "FontStyle"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Définit comment la police doit être stylisée avec une forme normale, italique ou oblique provenant de sa famille de polices."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Définit comment la police doit être stylisée avec : une version normale, italique ou oblique provenant de sa famille de polices.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Normal](#Normal) | Sélectionne une police classée comme normale au sein d’une famille de polices. |
|
|  | [Italic](#Italic) | Sélectionne une police classée comme italique. |
|
|  | [Oblique](#Oblique) | Sélectionne une police classée comme oblique. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indique si ce style de police possède une valeur initiale (Normal). |
|
|  | [getValue()](#getValue--) | Renvoie une valeur de ce style de police sous forme de chaîne. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Détermine si cette instance de style de police est égale à celle spécifiée. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance de style de police est égale à celle spécifiée non convertie. |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Vérifie si deux valeurs "FontStyle" sont égales. |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Vérifie si deux valeurs "FontStyle" ne sont pas égales. |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Tente de reconnaître un mot-clé spécifié comme une valeur de mot-clé appropriée du 'font-style' et le renvoie en cas de succès ou NULL en cas d’échec. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Sélectionne une police classée comme normale au sein d’une famille de polices. Valeur initiale.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Sélectionne une police classée comme italique. Si aucune version italique de la police n’est disponible, une version classée comme oblique est utilisée à la place. Si aucune n’est disponible, le style est simulé artificiellement.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Sélectionne une police classée comme oblique. Si aucune version oblique de la police n’est disponible, une version classée comme italique est utilisée à la place. Si aucune n’est disponible, le style est simulé artificiellement.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indique si ce style de police possède une valeur initiale (Normal).


**Returns:**
booléen
### getValue() {#getValue--}
```
public final String getValue()
```


Renvoie une valeur de ce style de police sous forme de chaîne.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Détermine si cette instance de style de police est égale à celle spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Autre instance de style de police |
|

**Returns:**
booléen - vrai si sont égaux, faux sinon

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance de style de police est égale à celle spécifiée non convertie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance de style de police non convertie, peut être nulle |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Vérifie si deux valeurs "FontStyle" sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Première valeur à vérifier |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - vrai si sont égaux, faux sinon

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Vérifie si deux valeurs "FontStyle" ne sont pas égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Première valeur à vérifier |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - faux si sont égaux, vrai sinon

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Tente de reconnaître un mot-clé spécifié comme une valeur de mot-clé appropriée du 'font-style' et le renvoie en cas de succès ou NULL en cas d’échec.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mot‑clé | java.lang.String | Un mot‑clé à analyser |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Résultat, si l'analyse a réussi, ou #Normal.Normal sinon |
|

**Returns:**
booléen - vrai si l'analyse a réussi, faux sinon

