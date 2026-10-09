---
title: "IImageResource"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en bildresurs av vilken typ som helst, raster eller vektor"
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
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
|  | [getType()](#getType--) | I implementeringstyp ska den returnera en typ av specifik bild som en |
instans av specifik ImageType, som kapslar in all typ-specifik information
|
|  | [getAspectRatio()](#getAspectRatio--) | I implementeringstyp ska den returnera ett bildförhållande för en specifik bild |
oavsett dess typ.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | I implementeringstyp ska den returnera linjära dimensioner för bilden. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


I implementeringstyp ska den returnera en typ av specifik bild som en
instans av specifik ImageType, som kapslar in all typ-specifik information


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


I implementeringstyp ska den returnera ett bildförhållande för en specifik bild
oavsett dess typ. Både vektor- och rasterbilder har inneboende
bildförhållande mellan dess bredd och höjd.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


I implementeringstyp ska den returnera linjära dimensioner för bilden. För
rasterbilder är de inneboende dimensioner i pixlar. Vektorbilder, i
motsats, har inga fasta dimensioner, men deras metadata kan innehålla
vissa grundläggande dimensioner i olika måttenheter.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
