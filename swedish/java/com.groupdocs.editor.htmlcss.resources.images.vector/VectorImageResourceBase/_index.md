---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Basisklass för alla stödda vektorbilder."
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Basisklass för alla stödda vektorbilder.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Returnerar namn på denna vektorbild. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Returnerar korrekt filnamn för denna vektorbild, som består av namn och |
filändelse.
|
|  | [getAspectRatio()](#getAspectRatio--) | Returnerar bildförhållandet för denna vektorbild |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Returnerar linjära dimensioner för denna vektorbild (bredd och höjd) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Kontrollerar detta objekt mot den angivna för referenslikhet. |
|
|  | [isDisposed()](#isDisposed--) | Bestämmer om denna rasterbild har frigjorts eller inte |
|
|  | [getType()](#getType--) | I implementerande typ bör returnera information om typen av vektorn |
bild
|
|  | [getByteContent()](#getByteContent--) | I implementerande typ bör returnera innehållet i denna vektorbild som byte |
stream
|
|  | [getTextContent()](#getTextContent--) | I implementerande typ bör returnera innehållet i denna vektorbild i text |
form: base64-kodad XML avseende bildtyp
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | I implementerande typ bör spara denna bild till disken via angiven sökväg |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | I implementerande typ bör spara den aktuella vektorbilden till raster-PNG |
formatera till angiven byte‑stream
|
|  | [dispose()](#dispose--) | I implementerande typ bör disponera denna instans |
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


Returnerar namn på denna vektorbild. Innehåller vanligtvis inte filnamn
filändelse och kan teoretiskt skilja sig från filnamnet.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returnerar korrekt filnamn för denna vektorbild, som består av namn och
filändelse. Kan teoretiskt skilja sig från namnet.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Returnerar bildförhållandet för denna vektorbild


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Returnerar linjära dimensioner för denna vektorbild (bredd och höjd)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Kontrollerar detta objekt mot den angivna för referenslikhet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Annan instans av vektorbild |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

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


I implementerande typ bör returnera information om typen av vektorn
bild


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


I implementerande typ bör returnera innehållet i denna vektorbild som byte
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


I implementerande typ bör returnera innehållet i denna vektorbild i text
form: base64-kodad XML avseende bildtyp


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


I implementerande typ bör spara denna bild till disken via angiven sökväg


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


I implementerande typ bör spara den aktuella vektorbilden till raster-PNG
formatera till angiven byte‑stream


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Bytestream, där PNG-versionen av denna rasterbild kommer att lagras. Får inte vara NULL och bör stödja skrivning. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


I implementerande typ bör disponera denna instans


