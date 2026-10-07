---
title: "IImageResource"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt een afbeeldingsbron voor van elk type raster of vector"
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Stelt een afbeeldingsbron van elk type voor, raster of vector.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getType()](#getType--) | Bij implementatie moet type een type van een specifieke afbeelding retourneren als een |
instantie van specifieke ImageType, die alle type‑specifieke informatie omvat
|
|  | [getAspectRatio()](#getAspectRatio--) | Bij implementatie moet type een beeldverhouding van een specifieke afbeelding retourneren |
ongeacht het type.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Bij implementatie moet type de lineaire afmetingen van de afbeelding retourneren. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Bij implementatie moet type een type van een specifieke afbeelding retourneren als een
instantie van specifieke ImageType, die alle type‑specifieke informatie omvat


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Bij implementatie moet type een beeldverhouding van een specifieke afbeelding retourneren
ongeacht het type. Zowel vector- als rasterafbeeldingen hebben intrinsieke
beeldverhouding tussen de breedte en hoogte.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Bij implementatie moet type de lineaire afmetingen van de afbeelding retourneren. Voor
rasterafbeeldingen zijn dit intrinsieke afmetingen in pixels. Vectorafbeeldingen, in
tegenovergestelde, hebben geen vaste afmetingen, maar hun metadata kan bevatten
enkele basisafmetingen in verschillende meeteenheden.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
