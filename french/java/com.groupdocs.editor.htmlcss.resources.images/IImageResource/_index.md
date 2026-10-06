---
title: "IImageResource"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une ressource d'image de tout type, raster ou vecteur"
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Représente une ressource d'image de tout type, raster ou vectorielle.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getType()](#getType--) | Dans l'implémentation, le type doit renvoyer un type d'image spécifique en tant que |
instance d'ImageType spécifique, qui encapsule toutes les informations propres au type
|
|  | [getAspectRatio()](#getAspectRatio--) | Dans l'implémentation, le type doit renvoyer le rapport d'aspect d'une image particulière |
indépendamment de son type.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Dans l'implémentation, le type doit renvoyer les dimensions linéaires de l'image. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Dans l'implémentation, le type doit renvoyer un type d'image spécifique en tant que
instance d'ImageType spécifique, qui encapsule toutes les informations propres au type


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Dans l'implémentation, le type doit renvoyer le rapport d'aspect d'une image particulière
indépendamment de son type. Les images vectorielles et raster ont intrinsèquement
un rapport d'aspect entre sa largeur et sa hauteur.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Dans l'implémentation, le type doit renvoyer les dimensions linéaires de l'image. Pour
les images raster, ce sont des dimensions intrinsèques en pixels. Les images vectorielles, en
contrepartie, n'ont pas de dimensions fixes, mais leurs métadonnées peuvent contenir
certaines dimensions de base dans différentes unités de mesure.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
