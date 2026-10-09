---
title: "IImageResource"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt eine Bildressource beliebigen Typs dar, Raster oder Vektor"
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Stellt eine Bildressource beliebigen Typs, Raster oder Vektor, dar.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getType()](#getType--) | Der implementierende Typ sollte einen Typ eines spezifischen Bildes als einen zurückgeben |
Instanz des spezifischen ImageType, die alle typenspezifischen Informationen kapselt
|
|  | [getAspectRatio()](#getAspectRatio--) | Der implementierende Typ sollte ein Seitenverhältnis eines bestimmten Bildes zurückgeben |
unabhängig von seinem Typ.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Der implementierende Typ sollte lineare Abmessungen des Bildes zurückgeben. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Der implementierende Typ sollte einen Typ eines spezifischen Bildes als einen zurückgeben
Instanz des spezifischen ImageType, die alle typenspezifischen Informationen kapselt


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Der implementierende Typ sollte ein Seitenverhältnis eines bestimmten Bildes zurückgeben
unabhängig von seinem Typ. Sowohl Vektor- als auch Rasterbilder haben intrinsische
Seitenverhältnis zwischen seiner Breite und Höhe.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Der implementierende Typ sollte lineare Abmessungen des Bildes zurückgeben. Für
Rasterbilder sind dies intrinsische Abmessungen in Pixeln. Vektorbilder hingegen, in
Gegenstück haben keine festen Abmessungen, aber ihre Metadaten können enthalten
einige grundlegende Abmessungen in verschiedenen Maßeinheiten.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
