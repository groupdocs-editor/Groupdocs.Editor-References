---
title: "ArgbColor"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente une valeur de couleur au format ARGB avec des convertisseurs et des sérialiseurs"
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Représente une valeur de couleur au format ARGB avec des convertisseurs et des sérialiseurs

<br />

*** ** * ** ***

Ce type est conçu pour être utile aux opérations CSS (mais pas uniquement). Voir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Crée une valeur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) à partir des canaux Rouge, Vert, Bleu et Alpha spécifiés |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Crée une valeur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) à partir des canaux Rouge, Vert, Bleu spécifiés, tandis que le canal Alpha est totalement opaque |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Crée une couleur totalement opaque (A=255) à partir d'une valeur unique, qui sera appliquée à tous les canaux |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Crée une valeur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) à partir du [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) spécifié |
|
|  | [getValue()](#getValue--) | Obtient la valeur Int32 de la couleur. |
|
|  | [getA()](#getA--) | Obtient la partie alpha de la couleur. |
|
|  | [getAlpha()](#getAlpha--) | Obtient la partie alpha de la couleur en pourcentage (0..1). |
|
|  | [getR()](#getR--) | Obtient la partie rouge de la couleur. |
|
|  | [getG()](#getG--) | Obtient la partie verte de la couleur. |
|
|  | [getB()](#getB--) | Obtient la partie bleue de la couleur. |
|
|  | [isEmpty()](#isEmpty--) | Couleur non initialisée - les 4 canaux sont réglés à 0. |
|
|  | [isDefault()](#isDefault--) | Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est par défaut (Transparent) - les 4 canaux sont réglés à 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est totalement transparente - son canal Alpha a la valeur minimale (0), de sorte que les autres canaux R, G et B n'ont aucun effet visible. |
|
|  | [isTranslucent()](#isTranslucent--) | Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est translucide (pas totalement transparente, mais pas non plus totalement opaque) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est totalement opaque, sans transparence (son canal Alpha a la valeur maximale) |
|
|  | [toSystemColor()](#toSystemColor--) | Convertit une valeur de cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) en instance [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) et la renvoie |
|
|  | [toRGBA()](#toRGBA--) | Sérialise cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) en notation de fonction CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | Sérialise cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) en notation de fonction CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | Sérialise cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dans la notation de fonction CSS la plus appropriée en fonction de la translucidité |
|
|  | [toString()](#toString--) | Identique à #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Compare deux couleurs et renvoie un booléen indiquant si les deux correspondent. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Compare deux couleurs et renvoie un booléen indiquant si les deux ne correspondent pas. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vérifie l'égalité de deux couleurs [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Vérifie l'égalité de deux couleurs [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Teste si un autre objet est égal à cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor). |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage qui définit la couleur actuelle. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Crée une valeur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) à partir des canaux Rouge, Vert, Bleu et Alpha spécifiés


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | rouge | int | Valeur du canal rouge |
|
|  | vert | int | Valeur du canal vert |
|
|  | bleu | int | Valeur du canal bleu |
|
|  | alpha | int | Valeur du canal alpha |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Crée une valeur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) à partir des canaux Rouge, Vert, Bleu spécifiés, tandis que le canal Alpha est totalement opaque


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | rouge | int | Valeur du canal rouge |
|
|  | vert | int | Valeur du canal vert |
|
|  | bleu | int | Valeur du canal bleu |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Crée une couleur totalement opaque (A=255) à partir d'une valeur unique, qui sera appliquée à tous les canaux


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte | Une valeur d'octet, identique pour les canaux rouge, vert et bleu |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Crée une valeur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) à partir du [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| couleur | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Obtient la valeur Int32 de la couleur.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Obtient la partie alpha de la couleur.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Obtient la partie alpha de la couleur en pourcentage (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Obtient la partie rouge de la couleur.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Obtient la partie verte de la couleur.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Obtient la partie bleue de la couleur.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Couleur non initialisée - les 4 canaux sont réglés à 0. Identique à Default et Transparent.


**Returns:**
booléen
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est par défaut (Transparent) - les 4 canaux sont réglés à 0


**Returns:**
booléen
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est totalement transparente - son canal Alpha a la valeur minimale (0), de sorte que les autres canaux R, G et B n'ont aucun effet visible.


**Returns:**
booléen
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est translucide (pas totalement transparente, mais pas non plus totalement opaque)


**Returns:**
booléen
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Indique si cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) est totalement opaque, sans transparence (son canal Alpha a la valeur maximale)


**Returns:**
booléen
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Convertit une valeur de cette instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) en instance [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) et la renvoie


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Sérialise cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) en notation de fonction CSS 'rgba'


**Returns:**
java.lang.String - Une chaîne au format 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Sérialise cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) en notation de fonction CSS 'rgb'


**Returns:**
java.lang.String - Une chaîne avec le format 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Sérialise cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dans la notation de fonction CSS la plus appropriée en fonction de la translucidité


**Returns:**
java.lang.String - Une chaîne avec le format 'rgba(r, g, b, a)' ou 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Identique à #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Même valeur de retour que dans #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Compare deux couleurs et renvoie un booléen indiquant si les deux correspondent.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | La première couleur à utiliser. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | La deuxième couleur à utiliser. |
|

**Returns:**
boolean - Vrai si les deux couleurs sont égales, sinon faux.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Compare deux couleurs et renvoie un booléen indiquant si les deux ne correspondent pas.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | La première couleur à utiliser. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | La deuxième couleur à utiliser. |
|

**Returns:**
boolean - Vrai si les deux couleurs ne sont pas égales, sinon faux.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Vérifie l'égalité de deux couleurs [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | L'autre couleur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|

**Returns:**
boolean - Vrai si les deux couleurs sont égales, sinon faux.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Vérifie l'égalité de deux couleurs [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | L'autre couleur [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor), castée en ICssDataType |
|

**Returns:**
boolean - Vrai si les deux couleurs sont égales, sinon faux.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Teste si un autre objet est égal à cette instance de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | autre | java.lang.Object | L'objet avec lequel tester. |
|

**Returns:**
boolean - Vrai si les deux objets sont égaux, sinon faux.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage qui définit la couleur actuelle.


**Returns:**
int - La valeur entière du code de hachage.

