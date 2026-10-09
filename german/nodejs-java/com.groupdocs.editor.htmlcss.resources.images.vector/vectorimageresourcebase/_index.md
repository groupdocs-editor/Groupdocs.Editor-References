---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Basisklasse für jedes unterstützte Vektorbild."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Basisklasse für jedes unterstützte Vektorbild.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Gibt den Namen dieses Vektorbildes zurück. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Gibt den korrekten Dateinamen dieses Vektorbildes zurück, der aus Name und |
der Erweiterung besteht.
|
|  | [getAspectRatio()](#getAspectRatio--) | Gibt das Seitenverhältnis dieses Vektorbildes zurück |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Gibt die linearen Abmessungen dieses Vektorbildes zurück (Breite und Höhe) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Überprüft diese Instanz mit der angegebenen auf Referenzgleichheit. |
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob dieses Rasterbild freigegeben ist oder nicht |
|
|  | [getType()](#getType--) | Der implementierende Typ sollte Informationen über den Typ des Vektors zurückgeben |
Bild
|
|  | [getByteContent()](#getByteContent--) | Der implementierende Typ sollte den Inhalt dieses Vektorbildes als Byte zurückgeben |
Stream
|
|  | [getTextContent()](#getTextContent--) | Der implementierende Typ sollte den Inhalt dieses Vektorbildes als Text zurückgeben |
Formular: base64-codiert von XML bezüglich des Bildtyps
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Der implementierende Typ sollte dieses Bild unter dem angegebenen Pfad auf die Festplatte speichern |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Der implementierende Typ sollte das aktuelle Vektorbild als Raster-PNG speichern |
Format in den angegebenen Byte-Stream
|
|  | [dispose()](#dispose--) | Der implementierende Typ sollte diese Instanz freigeben |
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


Gibt den Namen dieses Vektorbildes zurück. Enthält normalerweise keinen Dateinamen
Erweiterung und kann theoretisch vom Dateinamen abweichen.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Gibt den korrekten Dateinamen dieses Vektorbildes zurück, der aus Name und
Erweiterung. Kann theoretisch vom Namen abweichen.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Gibt das Seitenverhältnis dieses Vektorbildes zurück


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Gibt die linearen Abmessungen dieses Vektorbildes zurück (Breite und Höhe)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Überprüft diese Instanz mit der angegebenen auf Referenzgleichheit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere Instanz eines Vektorbildes |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestimmt, ob dieses Rasterbild freigegeben ist oder nicht


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Der implementierende Typ sollte Informationen über den Typ des Vektors zurückgeben
Bild


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Der implementierende Typ sollte den Inhalt dieses Vektorbildes als Byte zurückgeben
Stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Der implementierende Typ sollte den Inhalt dieses Vektorbildes als Text zurückgeben
Formular: base64-codiert von XML bezüglich des Bildtyps


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Der implementierende Typ sollte dieses Bild unter dem angegebenen Pfad auf die Festplatte speichern


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vollerPfadZurDatei | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Der implementierende Typ sollte das aktuelle Vektorbild als Raster-PNG speichern
Format in den angegebenen Byte-Stream


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Byte‑Stream, in den die PNG‑Version dieses Raster‑Bildes gespeichert wird. Sollte nicht NULL sein und Schreiben unterstützen. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Der implementierende Typ sollte diese Instanz freigeben


