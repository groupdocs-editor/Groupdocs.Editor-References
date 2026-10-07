---
title: "IImageResource"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un recurso de imagen de cualquier tipo, ráster o vectorial"
type: docs
weight: 13
url: /es/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Representa un recurso de imagen de cualquier tipo, raster o vectorial.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Métodos

| Método | Descripción |
| --- | --- |
|  | [getType()](#getType--) | Al implementar, el tipo debe devolver un tipo de imagen específica como un |
instancia de ImageType específico, que encapsula toda la información específica del tipo
|
|  | [getAspectRatio()](#getAspectRatio--) | Al implementar, el tipo debe devolver una relación de aspecto de una imagen particular |
independientemente de su tipo.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Al implementar, el tipo debe devolver las dimensiones lineales de la imagen. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Al implementar, el tipo debe devolver un tipo de imagen específica como un
instancia de ImageType específico, que encapsula toda la información específica del tipo


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Al implementar, el tipo debe devolver una relación de aspecto de una imagen particular
independientemente de su tipo. Tanto las imágenes vectoriales como las ráster tienen intrínsecamente
una relación de aspecto entre su ancho y alto.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Al implementar, el tipo debe devolver las dimensiones lineales de la imagen. Para
las imágenes ráster son dimensiones intrínsecas en píxeles. Las imágenes vectoriales, en
contrario, no tienen dimensiones fijas, pero sus metadatos pueden contener
algunas dimensiones básicas en diferentes unidades de medida.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
