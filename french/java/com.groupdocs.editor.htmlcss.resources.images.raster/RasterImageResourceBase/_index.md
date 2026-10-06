---
title: "RasterImageResourceBase"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Classe de base pour toute image raster prise en charge avec un nom, des dimensions, un ratio d'aspect, un type, une taille et un contenu fixes."
type: docs
weight: 15
url: /fr/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Classe de base pour toute image raster prise en charge avec un nom, des dimensions, un aspect
ratio, type, taille et contenu.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Renvoie le nom de cette image raster. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Renvoie le nom de fichier correct de cette image raster, qui consiste en le nom et |
l'extension.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Renvoie les dimensions linéaires de cette image raster (largeur et hauteur) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Renvoie le ratio d'aspect de cette image sous forme de relation largeur/hauteur |
|
|  | [getLength()](#getLength--) | Renvoie la longueur de ce fichier image raster en octets |
|
|  | [getByteContent()](#getByteContent--) | Renvoie le contenu de cette image raster sous forme de flux d'octets |
|
|  | [getTextContent()](#getTextContent--) | Renvoie le contenu de cette image raster sous forme de chaîne encodée en base64 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Enregistre cette image raster dans le fichier spécifié |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Vérifie cette instance avec celle spécifiée sur l'égalité de référence. |
|
|  | [dispose()](#dispose--) | Libère cette image raster, libérant son contenu et rendant la plupart des méthodes |
et propriétés non fonctionnelles
|
|  | [isDisposed()](#isDisposed--) | Détermine si cette image raster est libérée ou non |
|
|  | [getType()](#getType--) | Dans l'implémentation, le type doit renvoyer des informations sur le type du raster |
image
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Renvoie le nom de cette image raster. Habituellement ne contient pas le nom de fichier
extension et théoriquement peut différer du nom de fichier.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Renvoie le nom de fichier correct de cette image raster, qui consiste en le nom et
extension. Théoriquement peut différer du nom.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Renvoie les dimensions linéaires de cette image raster (largeur et hauteur)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Renvoie le ratio d'aspect de cette image sous forme de relation largeur/hauteur


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Renvoie la longueur de ce fichier image raster en octets


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Renvoie le contenu de cette image raster sous forme de flux d'octets


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Renvoie le contenu de cette image raster sous forme de chaîne encodée en base64


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Enregistre cette image raster dans le fichier spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Chemin complet du fichier, qui sera créé ou réécrit. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Vérifie cette instance avec celle spécifiée sur l'égalité de référence.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Autre implémentation de IHtmlResource |
|

**Returns:**
booléen - True si égaux, false si différents

### dispose() {#dispose--}
```
public final void dispose()
```


Libère cette image raster, libérant son contenu et rendant la plupart des méthodes
et propriétés non fonctionnelles


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Détermine si cette image raster est libérée ou non


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Dans l'implémentation, le type doit renvoyer des informations sur le type du raster
image


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
