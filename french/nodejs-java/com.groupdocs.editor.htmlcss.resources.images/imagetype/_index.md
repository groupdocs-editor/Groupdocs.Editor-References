---
title: "ImageType"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente un format de type d'image pris en charge qui supporte à la fois les formats raster et vecteur"
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
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
|  | [getJpeg()](#getJpeg--) | type d'image JPEG |
|
|  | [getPng()](#getPng--) | type d'image PNG |
|
|  | [getBmp()](#getBmp--) | type d'image BMP |
|
|  | [getGif()](#getGif--) | type d'image GIF |
|
|  | [getIcon()](#getIcon--) | type d'image ICON |
|
|  | [getSvg()](#getSvg--) | Type d'image vectorielle SVG |
|
|  | [getWmf()](#getWmf--) | Type d'image vectorielle WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | Type d'image vectorielle EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | Type d'image raster TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Renvoie un nom formel de ce format d'image. |
|
|  | [isVector()](#isVector--) | Indique si ce format particulier est vectoriel (true) ou raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Extension de fichier (sans le point initial) d'un type d'image particulier |
en minuscules.
|
|  | [toString()](#toString--) | Renvoie la propriété FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | Code MIME d'un type d'image particulier sous forme de chaîne. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Détermine si cette instance est égale à l'"ImageType" spécifié |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'objet non converti spécifié, |
qui est probablement une autre instance "ImageType"
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


type d'image JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


type d'image PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


type d'image BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


type d'image GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


type d'image ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


Type d'image vectorielle SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


Type d'image vectorielle WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


Type d'image vectorielle EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


Type d'image raster TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Renvoie un nom formel de ce format d'image. Ne renvoie jamais NULL. Si
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
booléen
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extension de fichier (sans le point initial) d'un type d'image particulier
en minuscules. Pour le type Undefined, renvoie la chaîne 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Renvoie la propriété FormalName


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


Détermine si cette instance est égale à l'"ImageType" spécifié
instance


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Autre instance ImageType à vérifier l'égalité avec celle-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'objet non converti spécifié,
qui est probablement une autre instance "ImageType"


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Autre instance de System.Object, qui est présumée de type ImageType, pour vérifier l'égalité avec celle-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Définit si deux instances ImageType spécifiques sont égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Première instance ImageType à vérifier |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Deuxième instance ImageType à vérifier |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Définit si deux instances ImageType spécifiques ne sont pas égales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Première instance ImageType à vérifier |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Deuxième instance ImageType à vérifier |
|

**Returns:**
booléen - Vrai si elles sont différentes, faux si elles sont égales

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage, qui est un nombre immuable pour cet élément spécifique
instance


**Returns:**
int - Entier signé de 4 octets

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

