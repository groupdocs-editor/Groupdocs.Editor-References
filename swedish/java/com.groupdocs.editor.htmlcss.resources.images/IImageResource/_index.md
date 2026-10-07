---
title: "IImageResource"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar bildresurs av vilken typ som helst, raster eller vektor"
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Representerar en bildresurs av vilken typ som helst, raster eller vektor.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getType()](#getType--) | I implementeringen bör typen returnera en typ av specifik bild som en |
instans av specifik ImageType, som kapslar in all typ-specifik information
|
|  | [getAspectRatio()](#getAspectRatio--) | I implementeringen bör typen returnera ett bildförhållande för en viss bild |
oavsett dess typ.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | I implementeringen bör typen returnera bildens linjära dimensioner. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


I implementeringen bör typen returnera en typ av specifik bild som en
instans av specifik ImageType, som kapslar in all typ-specifik information


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


I implementeringen bör typen returnera ett bildförhållande för en viss bild
oavsett dess typ. Både vektor- och rasterbilder har inneboende
bildförhållande mellan dess bredd och höjd.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


I implementeringen bör typen returnera bildens linjära dimensioner. För
rasterbilder är de inneboende dimensionerna i pixlar. Vektorbilder, i
motsvarande fall har de inga fasta dimensioner, men deras metadata kan innehålla
några grundläggande dimensioner i olika mätenheter.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
