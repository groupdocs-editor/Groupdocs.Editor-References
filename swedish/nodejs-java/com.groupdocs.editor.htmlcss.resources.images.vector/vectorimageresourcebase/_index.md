---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Basisklass för alla stödda vektorbilder"
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Basisklass för alla stödda vektorbilder

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
|  | [getName()](#getName--) | Returnerar namnet på denna vektorbild. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Returnerar korrekt filnamn för denna vektorbild, som består av namn och |
filändelse.
|
|  | [getAspectRatio()](#getAspectRatio--) | Returnerar bildförhållandet för denna vektorbild |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Returnerar linjära dimensioner för denna vektorbild (bredd och höjd) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Kontrollerar detta objekt med den angivna för referenslikhet. |
|
|  | [isDisposed()](#isDisposed--) | Bestämmer om den här rasterbilden har frigjorts eller inte |
|
|  | [getType()](#getType--) | I implementeringen bör typen returnera information om vektortypen |
bild
|
|  | [getByteContent()](#getByteContent--) | I implementeringen bör typen returnera innehållet i denna vektorbild som byte |
ström
|
|  | [getTextContent()](#getTextContent--) | I implementeringen bör typen returnera innehållet i denna vektorbild i text |
formulär: base64-kodad XML avseende bildtyp
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | I implementeringen bör typen spara denna bild till disken på angiven sökväg |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | I implementeringen bör typen spara den aktuella vektorbilden till raster-PNG |
formatera till angiven byte‑ström
|
|  | [dispose()](#dispose--) | I implementeringen bör typen frigöra denna instans |
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


Returnerar namnet på denna vektorbild. Innehåller vanligtvis inte filnamnet
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


Kontrollerar detta objekt med den angivna för referenslikhet.


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


Bestämmer om den här rasterbilden har frigjorts eller inte


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


I implementeringen bör typen returnera information om vektortypen
bild


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


I implementeringen bör typen returnera innehållet i denna vektorbild som byte
ström


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


I implementeringen bör typen returnera innehållet i denna vektorbild i text
formulär: base64-kodad XML avseende bildtyp


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


I implementeringen bör typen spara denna bild till disken på angiven sökväg


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


I implementeringen bör typen spara den aktuella vektorbilden till raster-PNG
formatera till angiven byte‑ström


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Byte‑ström, i vilken PNG‑versionen av denna rasterbild kommer att lagras. Den får inte vara NULL och bör stödja skrivning. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


I implementeringen bör typen frigöra denna instans


