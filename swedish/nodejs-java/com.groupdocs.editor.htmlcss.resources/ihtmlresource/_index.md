---
title: "IHtmlResource"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en instans av den okända HTML-resursen raster- eller vektorbild, stilmall, teckensnitt, textresurs, CSS, XML etc."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Representerar en instans av den okända HTML-resursen (raster- eller vektorbild,
stilmall, teckensnitt, textresurs (CSS, XML) etc.)

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Namn på HTML-resursen |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Korrekt filnamn för den angivna resursen med lämplig fil |
filändelse
|
|  | [getType()](#getType--) | Typ av HTML-resurs |
|
|  | [getByteContent()](#getByteContent--) | Innehåll i HTML-resursen i form av en byte-ström |
|
|  | [getTextContent()](#getTextContent--) | Innehåll i HTML-resursen i form av en base64-kodad textsträng |
för binära resurser eller enkel text för textbaserade resurser
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar den aktuella resursen till den angivna filen |
|
### getName() {#getName--}
```
public abstract String getName()
```


Namn på HTML-resursen


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Korrekt filnamn för den angivna resursen med lämplig fil
filändelse


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Typ av HTML-resurs


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Innehåll i HTML-resursen i form av en byte-ström


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Innehåll i HTML-resursen i form av en base64-kodad textsträng
för binära resurser eller enkel text för textbaserade resurser


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Sparar den aktuella resursen till den angivna filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen som kommer att skapas eller skrivas om med innehållet från den aktuella resursen |
|

