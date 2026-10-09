---
title: "Dimensions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les dimensions linéaires largeur et hauteur d'une image raster rectangulaire dans une unité arbitraire."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Représente les dimensions linéaires (largeur et hauteur) d'un raster rectangulaire
image dans une unité arbitraire. Structure immuable.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Crée une nouvelle instance à partir de la largeur et de la hauteur spécifiées |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Renvoie la largeur de l'image |
|
|  | [getHeight()](#getHeight--) | Renvoie la hauteur de l'image |
|
|  | [isSquare()](#isSquare--) | Détermine si le 'Dimensions' spécifié représente un carré, c'est‑à‑dire |
|
|  | [getArea()](#getArea--) | Renvoie une surface (Largeur x Hauteur) |
|
|  | [isEmpty()](#isEmpty--) | Détermine si cette instance \"Dimensions\" est vide et par défaut, c'est‑à‑dire |
|
|  | [getAspectRatio()](#getAspectRatio--) | Ratio d'aspect de ces dimensions en largeur/hauteur |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Crée et renvoie une nouvelle instance \"Dimensions\", qui est proportionnellement |
redimensionnée à partir de l'actuelle, basée sur la largeur spécifiée
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Crée et renvoie une nouvelle instance \"Dimensions\", qui est proportionnellement |
redimensionnée à partir de l'actuelle, basée sur la hauteur spécifiée
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Détermine si cette instance est égale au \"Dimensions\" spécifié |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est présumée être une autre instance \"Dimensions\"
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant son |
durée de vie
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Vérifie si deux valeurs \"Dimensions\" sont égales, c'est‑à‑dire |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Vérifie si deux valeurs "Dimensions" ne sont pas égales, c’est‑à‑dire. |
|
|  | [toString()](#toString--) | Renvoie une représentation sous forme de chaîne de caractères de cet objet "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Renvoie une copie complète de cette instance |
|
|  | [getEmpty()](#getEmpty--) | Renvoie une instance vide de Dimensions |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Crée une nouvelle instance à partir de la largeur et de la hauteur spécifiées


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | largeur | int | Largeur de l'image |
|
|  | hauteur | int | Hauteur de l'image |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Renvoie la largeur de l'image


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Renvoie la hauteur de l'image


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Détermine si le 'Dimensions' spécifié représente un carré, c’est‑à‑dire si
la largeur est égale à la hauteur


**Returns:**
booléen
### getArea() {#getArea--}
```
public final long getArea()
```


Renvoie une surface (Largeur x Hauteur)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Détermine si cette instance \"Dimensions\" est vide et par défaut, c'est‑à‑dire
il ne stocke pas correctement la largeur et la hauteur


**Returns:**
booléen
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Ratio d'aspect de ces dimensions en largeur/hauteur


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Crée et renvoie une nouvelle instance \"Dimensions\", qui est proportionnellement
redimensionnée à partir de l'actuelle, basée sur la largeur spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | targetWidth | int | Nouvelle largeur cible, qui sera présente dans la Dimension résultante |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Crée et renvoie une nouvelle instance \"Dimensions\", qui est proportionnellement
redimensionnée à partir de l'actuelle, basée sur la hauteur spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | targetHeight | int | Nouvelle hauteur cible, qui sera présente dans la Dimension résultante |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Détermine si cette instance est égale au \"Dimensions\" spécifié
instance


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Autre instance "Dimensions" à vérifier pour l'égalité |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est présumée être une autre instance \"Dimensions\"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre objet, qui est supposément du type "Dimensions", qui doit être vérifié pour l'égalité avec celui-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant son
durée de vie


**Returns:**
int - Code de hachage immuable (pour cette instance) sous forme d'entier signé de 4 octets

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Vérifie si deux valeurs "Dimensions" sont égales, c’est‑à‑dire qu'elles ont des
largeur et hauteur identiques, ou les deux sont vides


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Première instance à vérifier |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Deuxième instance à vérifier |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Vérifie si deux valeurs "Dimensions" ne sont pas égales, c’est‑à‑dire leurs
largeur et/ou hauteur correspondantes sont différentes


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Première instance à vérifier |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Deuxième instance à vérifier |
|

**Returns:**
booléen - Vrai si elles sont différentes, faux si elles sont égales

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de caractères de cet objet "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - Instance de chaîne, qui contient une largeur et une hauteur au format W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Renvoie une copie complète de cette instance


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Renvoie une instance vide de Dimensions


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
