---
title: "VectorImageResourceBase"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Classe de base pour toute image vectorielle prise en charge"
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
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
extension.
|
|  | [getAspectRatio()](#getAspectRatio--) | Renvoie le rapport d'aspect de cette image vectorielle |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Vérifie cette instance avec celle spécifiée sur l'égalité de référence. |
|
|  | [isDisposed()](#isDisposed--) | Détermine si cette image raster est libérée ou non |
|
|  | [getType()](#getType--) | Dans l'implémentation, le type doit renvoyer des informations sur le type de l'image vectorielle |
image
|
|  | [getByteContent()](#getByteContent--) | Dans l'implémentation, le type doit renvoyer le contenu de cette image vectorielle en tant qu'octet |
flux
|
|  | [getTextContent()](#getTextContent--) | Dans l'implémentation, le type doit renvoyer le contenu de cette image vectorielle sous forme de texte |
form: XML encodé en base64 concernant le type d'image
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Dans l'implémentation, le type doit enregistrer cette image sur le disque à l'emplacement spécifié |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Dans l'implémentation, le type doit enregistrer l'image vectorielle actuelle au format raster PNG |
format dans le flux d'octets spécifié
|
|  | [dispose()](#dispose--) | Dans l'implémentation, le type doit libérer cette instance |
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


Renvoie le nom de cette image vectorielle. Habituellement ne contient pas le nom de fichier
extension et peut théoriquement différer du nom de fichier.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Renvoie le nom de fichier correct de cette image vectorielle, qui se compose du nom et
extension. Peut théoriquement différer du nom.


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
booléen - Vrai si égaux, faux si différents

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Détermine si cette image raster est libérée ou non


**Returns:**
booléen -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Dans l'implémentation, le type doit renvoyer des informations sur le type de l'image vectorielle
image


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Dans l'implémentation, le type doit renvoyer le contenu de cette image vectorielle en tant qu'octet
flux


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Dans l'implémentation, le type doit renvoyer le contenu de cette image vectorielle sous forme de texte
form: XML encodé en base64 concernant le type d'image


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Dans l'implémentation, le type doit enregistrer cette image sur le disque à l'emplacement spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Dans l'implémentation, le type doit enregistrer l'image vectorielle actuelle au format raster PNG
format dans le flux d'octets spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Flux d'octets, dans lequel la version PNG de cette image raster sera stockée. Ne doit pas être NULL et doit prendre en charge l'écriture. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Dans l'implémentation, le type doit libérer cette instance


