---
title: "VectorImageResourceBase"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Classe de base pour toute image vectorielle prise en charge"
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Classe de base pour toute image vectorielle prise en charge

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Renvoie le nom de cette image vectorielle. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Renvoie le nom de fichier correct de cette image vectorielle, qui se compose du nom et |
l'extension.
|
|  | [getAspectRatio()](#getAspectRatio--) | Renvoie le rapport d'aspect de cette image vectorielle |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Vérifie cette instance avec celle spécifiée sur l'égalité de référence. |
|
|  | [isDisposed()](#isDisposed--) | Détermine si cette image raster est libérée ou non |
|
|  | [getType()](#getType--) | Dans le type implémentant, il faut renvoyer des informations sur le type du vecteur |
image
|
|  | [getByteContent()](#getByteContent--) | Dans le type implémentant, il faut renvoyer le contenu de cette image vectorielle sous forme d'octet |
flux
|
|  | [getTextContent()](#getTextContent--) | Dans le type implémentant, il faut renvoyer le contenu de cette image vectorielle sous forme de texte |
forme : XML encodé en base64 concernant le type d'image
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Dans le type implémentant, il faut enregistrer cette image sur le disque à l'emplacement spécifié |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Dans le type implémentant, il faut enregistrer l'image vectorielle actuelle au format PNG raster |
formater dans le flux d'octets spécifié
|
|  | [dispose()](#dispose--) | Dans le type implémentant, il faut libérer cette instance |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Renvoie le nom de cette image vectorielle. Contient généralement pas le nom de fichier
extension et théoriquement peut différer du nom de fichier.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Renvoie le nom de fichier correct de cette image vectorielle, qui se compose du nom et
extension. Théoriquement peut différer du nom.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Renvoie le rapport d'aspect de cette image vectorielle


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Vérifie cette instance avec celle spécifiée sur l'égalité de référence.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Autre instance d'image vectorielle |
|

**Returns:**
booléen - True si égaux, false si différents

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


Dans le type implémentant, il faut renvoyer des informations sur le type du vecteur
image


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Dans le type implémentant, il faut renvoyer le contenu de cette image vectorielle sous forme d'octet
flux


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Dans le type implémentant, il faut renvoyer le contenu de cette image vectorielle sous forme de texte
forme : XML encodé en base64 concernant le type d'image


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Dans le type implémentant, il faut enregistrer cette image sur le disque à l'emplacement spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Dans le type implémentant, il faut enregistrer l'image vectorielle actuelle au format PNG raster
formater dans le flux d'octets spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flux d'octets, dans lequel la version PNG de cette image raster sera stockée. Ne doit pas être NULL et doit prendre en charge l'écriture. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Dans le type implémentant, il faut libérer cette instance


