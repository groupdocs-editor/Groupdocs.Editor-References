---
title: "Dimensions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les dimensions linéaires largeur et hauteur d'une image raster rectangulaire en unité arbitraire."
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Représente les dimensions linéaires (largeur et hauteur) d'un raster rectangulaire
image en unité arbitraire. Structure immuable.

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
|  | [isSquare()](#isSquare--) | Détermine si le 'Dimensions' spécifié représente un carré, c.-à-d. |
|
|  | [getArea()](#getArea--) | Renvoie une aire (Width x Height) |
|
|  | [isEmpty()](#isEmpty--) | Détermine si cette instance "Dimensions" est vide et par défaut, c.-à-d. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Ratio d'aspect de ces dimensions en largeur/hauteur |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Crée et renvoie une nouvelle instance "Dimensions", qui est proportionnellement |
redimensionnée à partir de l'actuelle, basée sur la largeur spécifiée
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Crée et renvoie une nouvelle instance "Dimensions", qui est proportionnellement |
redimensionnée à partir de l'actuelle, basée sur la hauteur spécifiée
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Détermine si cette instance est égale à la "Dimensions" spécifiée |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est probablement une autre instance "Dimensions"
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant son |
durée de vie
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Vérifie si deux valeurs "Dimensions" sont égales, c.-à-d. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Vérifie si deux valeurs "Dimensions" ne sont pas égales, c.-à-d. |
|
|  | [toString()](#toString--) | Renvoie une représentation sous forme de chaîne de caractères de cette "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Renvoie une copie complète de cette instance |
|
|  | [getEmpty()](#getEmpty--) | Renvoie une instance Dimensions vide |
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


Détermine si le 'Dimensions' spécifié représente un carré, c.-à-d. si
la largeur est égale à la hauteur


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Renvoie une aire (Width x Height)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Détermine si cette instance "Dimensions" est vide et par défaut, c.-à-d.
il ne stocke pas la largeur et la hauteur correctes


**Returns:**
boolean
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


Crée et renvoie une nouvelle instance "Dimensions", qui est proportionnellement
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


Crée et renvoie une nouvelle instance "Dimensions", qui est proportionnellement
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


Détermine si cette instance est égale à la "Dimensions" spécifiée
instance


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Autre instance "Dimensions" à vérifier pour l'égalité |
|

**Returns:**
booléen - vrai si égaux, faux sinon

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est probablement une autre instance "Dimensions"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre objet, qui est supposément de type "Dimensions", qui doit être vérifié pour l'égalité avec celui-ci |
|

**Returns:**
booléen - vrai si égaux, faux sinon

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant son
durée de vie


**Returns:**
int - code de hachage immuable (pour cette instance) sous forme d'entier signé de 4 octets

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Vérifie si deux valeurs "Dimensions" sont égales, c’est‑à‑dire qu’elles ont les mêmes
largeur et hauteur, ou les deux sont vides


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Première instance à vérifier |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Deuxième instance à vérifier |
|

**Returns:**
booléen - vrai si égaux, faux sinon

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Vérifie si deux valeurs "Dimensions" ne sont pas égales, c’est‑à‑dire que leurs
largeur et/ou hauteur correspondantes sont différentes


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Première instance à vérifier |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Deuxième instance à vérifier |
|

**Returns:**
booléen - vrai si différentes, faux si égales

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de caractères de cette "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - instance String, qui contient une largeur et une hauteur au format W:(width)×H:(height)

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


Renvoie une instance Dimensions vide


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
