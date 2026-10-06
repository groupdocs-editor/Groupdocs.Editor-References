---
title: "QuoteType"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les caractères de citation - guillemet simple et guillemet double"
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Représente les caractères de citation - guillemet simple (') et guillemet double (\")

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Guillemet simple (caractère U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | Guillemet double (caractère U+0022 QUOTATION MARK) |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCode()](#getCode--) | Point de code du caractère actuel (U+0027 ou U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Caractère à encadrer de guillemets |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | Caractère encodé en HTML |
|
|  | [toString()](#toString--) | Renvoie une chaîne \"SingleQuote\" ou \"DoubleQuote\" selon la valeur actuelle |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Indique si cette instance du type de guillemet est égale à celle spécifiée |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Indique si cette instance du type de guillemet est égale à celle spécifiée non castée |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour ce caractère |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Vérifie si deux valeurs \"QuoteType\" sont égales |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Vérifie si deux valeurs \"QuoteType\" ne sont pas égales |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Convertit l'instance [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) spécifiée en char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Convertit le char spécifique en le [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) correspondant, lève une exception si le cast est invalide |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Guillemet simple (caractère U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Guillemet double (caractère U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


Point de code du caractère actuel (U+0027 ou U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Caractère à encadrer de guillemets


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


Caractère encodé en HTML


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne \"SingleQuote\" ou \"DoubleQuote\" selon la valeur actuelle


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Indique si cette instance du type de guillemet est égale à celle spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Autre instance de QuoteType à vérifier |
|

**Returns:**
booléen - vrai si égaux, faux si différents

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indique si cette instance du type de guillemet est égale à celle spécifiée non castée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Objet non converti, attendu d'être du type [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
booléen - vrai si égaux, faux si différents

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour ce caractère


**Returns:**
int - Code de hachage en tant qu'entier signé

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Vérifie si deux valeurs \"QuoteType\" sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Première valeur à vérifier |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - vrai si sont égaux, faux sinon

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Vérifie si deux valeurs \"QuoteType\" ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Première valeur à vérifier |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Deuxième valeur à vérifier |
|

**Returns:**
booléen - faux si sont égaux, vrai sinon

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Convertit l'instance [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) spécifiée en char


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Instance du type Quote à convertir |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Convertit le char spécifique en le [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) correspondant, lève une exception si le cast est invalide


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | caractère | char | Un caractère guillemet simple (U+0027 APOSTROPHE) ou guillemet double (U+0022 QUOTATION MARK). Une exception sera levée si un autre caractère est spécifié. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
