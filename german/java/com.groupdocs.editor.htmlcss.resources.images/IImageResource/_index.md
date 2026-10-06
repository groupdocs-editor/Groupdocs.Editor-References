---
title: "IImageResource"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Bildressource jeglichen Typs dar, Raster oder Vektor"
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
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
|  | [getType()](#getType--) | Bei der Implementierung sollte der Typ einen Typ eines bestimmten Bildes zurückgeben als ein |
Instanz des spezifischen ImageType, der alle typenspezifischen Informationen kapselt
|
|  | [getAspectRatio()](#getAspectRatio--) | Bei der Implementierung sollte der Typ ein Seitenverhältnis eines bestimmten Bildes zurückgeben |
unabhängig von seinem Typ.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Bei der Implementierung sollte der Typ lineare Abmessungen des Bildes zurückgeben. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Bei der Implementierung sollte der Typ einen Typ eines bestimmten Bildes zurückgeben als ein
Instanz des spezifischen ImageType, der alle typenspezifischen Informationen kapselt


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Bei der Implementierung sollte der Typ ein Seitenverhältnis eines bestimmten Bildes zurückgeben
unabhängig von seinem Typ. Sowohl Vektor- als auch Rasterbilder haben intrinsische
Seitenverhältnisse zwischen ihrer Breite und Höhe.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Bei der Implementierung sollte der Typ lineare Abmessungen des Bildes zurückgeben. Für
Rasterbilder sind dies intrinsische Abmessungen in Pixeln. Vektorbilder, in
Gegenstück, haben keine festen Abmessungen, aber ihre Metadaten können enthalten
einige grundlegende Abmessungen in verschiedenen Maßeinheiten.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
