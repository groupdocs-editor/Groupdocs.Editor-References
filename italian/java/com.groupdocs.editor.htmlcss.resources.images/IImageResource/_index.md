---
title: "IImageResource"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta una risorsa immagine di qualsiasi tipo, raster o vettoriale"
type: docs
weight: 13
url: /it/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Rappresenta una risorsa immagine di qualsiasi tipo, raster o vettoriale.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getType()](#getType--) | Nell'implementazione, il tipo dovrebbe restituire un tipo di immagine specifica come un |
istanza di ImageType specifico, che incapsula tutte le informazioni specifiche del tipo
|
|  | [getAspectRatio()](#getAspectRatio--) | Nell'implementazione, il tipo dovrebbe restituire il rapporto d'aspetto di una particolare immagine |
indipendentemente dal suo tipo.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Nell'implementazione, il tipo dovrebbe restituire le dimensioni lineari dell'immagine. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Nell'implementazione, il tipo dovrebbe restituire un tipo di immagine specifica come un
istanza di ImageType specifico, che incapsula tutte le informazioni specifiche del tipo


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Nell'implementazione, il tipo dovrebbe restituire il rapporto d'aspetto di una particolare immagine
indipendentemente dal suo tipo. Sia le immagini vettoriali che raster hanno intrinsecamente
rapporto d'aspetto tra la sua larghezza e altezza.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Nell'implementazione, il tipo dovrebbe restituire le dimensioni lineari dell'immagine. Per
le immagini raster sono dimensioni intrinseche in pixel. Le immagini vettoriali, in
al contrario, non hanno dimensioni fisse, ma i loro metadati possono contenere
alcune dimensioni di base in diverse unità di misura.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
