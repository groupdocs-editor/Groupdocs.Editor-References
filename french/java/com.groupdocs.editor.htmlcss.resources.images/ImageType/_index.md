---
title: "ImageType"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente un format de type d'image pris en charge qui supporte les formats raster et vectoriel"
type: docs
weight: 11
url: /fr/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Représente un type d'image pris en charge (format), prend en charge les formats raster et vectoriel.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Type d'image indéfini - valeur spéciale, qui ne devrait normalement pas se produire |
|
|  | [getJpeg()](#getJpeg--) | Type d'image JPEG |
|
|  | [getPng()](#getPng--) | Type d'image PNG |
|
|  | [getBmp()](#getBmp--) | Type d'image BMP |
|
|  | [getGif()](#getGif--) | Type d'image GIF |
|
|  | [getIcon()](#getIcon--) | Type d'image ICON |
|
|  | [getSvg()](#getSvg--) | type d'image vectorielle SVG |
|
|  | [getWmf()](#getWmf--) | type d'image vectorielle WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | type d'image vectorielle EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | type d'image raster TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Renvoie un nom officiel de ce format d'image. |
|
|  | [isVector()](#isVector--) | Indique si ce format particulier est vectoriel (true) ou raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Extension de fichier (sans le caractère point initial) d'un type d'image particulier |
en minuscules.
|
|  | [toString()](#toString--) | Renvoie une propriété FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | Code MIME d'un type d'image particulier sous forme de chaîne. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Détermine si cette instance est égale à l\"ImageType\" spécifié |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est supposément une autre instance \"ImageType\"
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Définit si deux instances ImageType spécifiques sont égales |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Définit si deux instances ImageType spécifiques ne sont pas égales |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage, qui est un nombre immuable pour cet élément spécifique |
instance
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Renvoie la valeur ImageType, qui est équivalente à l'extension de nom de fichier, qui |
est extraite du nom de fichier spécifié
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Renvoie la valeur ImageType, qui est équivalente au code MIME spécifié |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Type d'image indéfini - valeur spéciale, qui ne devrait normalement pas se produire


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


Type d'image JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


Type d'image PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


Type d'image BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


Type d'image GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


Type d'image ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


type d'image vectorielle SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


type d'image vectorielle WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


type d'image vectorielle EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


type d'image raster TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Renvoie un nom officiel de ce format d'image. Ne renvoie jamais NULL. Si
l'instance n'est pas corrompue, ne lance jamais d'exception.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Indique si ce format particulier est vectoriel (true) ou raster
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extension de fichier (sans le caractère point initial) d'un type d'image particulier
en minuscules. Pour le type Undefined, renvoie la chaîne 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Renvoie une propriété FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Code MIME d'un type d'image particulier sous forme de chaîne. Pour le type Undefined
renvoie la chaîne 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Détermine si cette instance est égale à l\"ImageType\" spécifié
instance


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Autre instance ImageType à vérifier pour l'égalité avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est supposément une autre instance \"ImageType\"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance de System.Object, qui est probablement de type ImageType, pour vérifier l'égalité avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Définit si deux instances ImageType spécifiques sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Première instance de ImageType à vérifier |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Deuxième instance de ImageType à vérifier |
|

**Returns:**
booléen - True si égaux, false si différents

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Définit si deux instances ImageType spécifiques ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Première instance de ImageType à vérifier |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Deuxième instance de ImageType à vérifier |
|

**Returns:**
booléen - vrai si différentes, faux si égales

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage, qui est un nombre immuable pour cet élément spécifique
instance


**Returns:**
int - entier signé de 4 octets

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Renvoie la valeur ImageType, qui est équivalente à l'extension de nom de fichier, qui
est extraite du nom de fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom de fichier | java.lang.String | Nom de fichier arbitraire, peut être un chemin relatif ou complet |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Renvoie la valeur ImageType, qui est équivalente au code MIME spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Code MIME arbitraire |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

