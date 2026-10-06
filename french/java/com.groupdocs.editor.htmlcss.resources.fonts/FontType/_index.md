---
title: "FontType"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente un type de police pris en charge."
type: docs
weight: 12
url: /fr/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Représente un type de police pris en charge.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontType()](#FontType--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Valeur spéciale, qui indique une police indéfinie, inconnue ou non prise en charge |
ressource
|
|  | [getWoff()](#getWoff--) | Représente un type de police WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Représente un type de police WOFF2 (Web Open Font Format version 2) |
|
|  | [getTtf()](#getTtf--) | Représente un type de police TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Représente un type de police OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Représente une police TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Représente un type de police EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Renvoie le nom compatible CSS de ce type de police, qui est utilisé dans le |
|
|  | [getFormalName()](#getFormalName--) | Renvoie un nom officiel de ce type de police |
|
|  | [getFileExtension()](#getFileExtension--) | Extension de nom de fichier (sans le caractère point) pour ce type de police |
|
|  | [getFontFormat()](#getFontFormat--) | Format de police pour le format @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | Code MIME d'un type de police particulier |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Renvoie la valeur FontType, qui est équivalente au CSS-compatible spécifié |
nom du type de police
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Renvoie la valeur FontType, qui est équivalente à l'extension de nom de fichier, qui |
est extraite du nom de fichier spécifié
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Renvoie la valeur FontType, qui est équivalente au code MIME spécifié |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Renvoie le premier type de police de l'ensemble spécifié, qui n'est pas "Undefined" |
valeur, ou le type de police "Undefined" sinon (lorsque tous les éléments sont
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Détermine si cette instance est égale à la "FontType" spécifiée |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est probablement une autre instance "FontType"
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Vérifie si deux valeurs "FontType" sont égales |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Vérifie si deux valeurs "FontType" ne sont pas égales |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage, qui est un nombre constant pour cette valeur spécifique |
type
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Valeur spéciale, qui indique une police indéfinie, inconnue ou non prise en charge
ressource


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Représente un type de police WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Représente un type de police WOFF2 (Web Open Font Format version 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Représente un type de police TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Représente un type de police OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Représente une police TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Représente un type de police EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Renvoie le nom compatible CSS de ce type de police, qui est utilisé dans le


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Renvoie un nom officiel de ce type de police


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extension de nom de fichier (sans le caractère point) pour ce type de police


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Format de police pour le format @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Code MIME d'un type de police particulier


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Renvoie la valeur FontType, qui est équivalente au CSS-compatible spécifié
nom du type de police


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Nom compatible CSS du type de police |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Renvoie la valeur FontType, qui est équivalente à l'extension de nom de fichier, qui
est extraite du nom de fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom de fichier | java.lang.String | Nom de fichier avec extension, peut être un nom complet |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Renvoie la valeur FontType, qui est équivalente au code MIME spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Code MIME |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Renvoie le premier type de police de l'ensemble spécifié, qui n'est pas "Undefined"
valeur, ou le type de police "Undefined" sinon (lorsque tous les éléments sont
"Undefined")


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Une ou plusieurs valeurs FontType, NULL ou collection vide ne sont pas autorisés |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Détermine si cette instance est égale à la "FontType" spécifiée
instance


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Autre instance FontType à vérifier avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est probablement une autre instance "FontType"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance probablement de la structure FontType, qui a été encapsulée dans System.Object |
|

**Returns:**
booléen - True si égaux, false si différents

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Vérifie si deux valeurs "FontType" sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Premier FontType à vérifier |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Deuxième FontType à vérifier |
|

**Returns:**
booléen - True si égaux, false si différents

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Vérifie si deux valeurs "FontType" ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Premier FontType à vérifier |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Deuxième FontType à vérifier |
|

**Returns:**
booléen - True si égaux, false si différents

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage, qui est un nombre constant pour cette valeur spécifique
type


**Returns:**
int - entier signé de 4 octets, 0 pour la valeur Undefined

