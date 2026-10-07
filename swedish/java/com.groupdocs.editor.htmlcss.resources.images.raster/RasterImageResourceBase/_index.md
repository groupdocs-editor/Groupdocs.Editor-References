---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Basisklass för alla stödda rasterbilder med fast namn, dimensioner, bildförhållande, typ, storlek och innehåll."
type: docs
weight: 15
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Basisklass för alla stödda rasterbilder med fast namn, dimensioner, bildförhållande
förhållande, typ, storlek och innehåll.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Returnerar namnet på denna rasterbild. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Returnerar korrekt filnamn för denna rasterbild, som består av namn och |
filändelse.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Returnerar linjära dimensioner för denna rasterbild (bredd och höjd) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Returnerar ett bildförhållande för denna bild som bredd‑till‑höjd‑relation |
|
|  | [getLength()](#getLength--) | Returnerar längden på denna rasterbildsfil i byte |
|
|  | [getByteContent()](#getByteContent--) | Returnerar innehållet i denna rasterbild som byte‑ström |
|
|  | [getTextContent()](#getTextContent--) | Returnerar innehållet i denna rasterbild som base64‑kodad sträng |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar denna rasterbild till den angivna filen |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Kontrollerar detta objekt mot den angivna för referenslikhet. |
|
|  | [dispose()](#dispose--) | Avslutar denna rasterbild, frigör dess innehåll och gör de flesta metoder otillgängliga. |
och egenskaper fungerar inte
|
|  | [isDisposed()](#isDisposed--) | Bestämmer om denna rasterbild har frigjorts eller inte |
|
|  | [getType()](#getType--) | Den implementerande typen bör returnera information om rastertypens typ |
bild
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Returnerar namn på denna rasterbild. Innehåller vanligtvis inte filnamn.
filändelse och kan teoretiskt skilja sig från filnamnet.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returnerar korrekt filnamn för denna rasterbild, som består av namn och
filändelse. Kan teoretiskt skilja sig från namnet.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Returnerar linjära dimensioner för denna rasterbild (bredd och höjd)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Returnerar ett bildförhållande för denna bild som bredd‑till‑höjd‑relation


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Returnerar längden på denna rasterbildsfil i byte


**Returns:**
int - 
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returnerar innehållet i denna rasterbild som byte‑ström


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returnerar innehållet i denna rasterbild som base64‑kodad sträng


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Sparar denna rasterbild till den angivna filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen, som kommer att skapas eller skrivas om. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Kontrollerar detta objekt mot den angivna för referenslikhet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Annan IHtmlResource-arvtagare |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### dispose() {#dispose--}
```
public final void dispose()
```


Avslutar denna rasterbild, frigör dess innehåll och gör de flesta metoder otillgängliga.
och egenskaper fungerar inte


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestämmer om denna rasterbild har frigjorts eller inte


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Den implementerande typen bör returnera information om rastertypens typ
bild


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
