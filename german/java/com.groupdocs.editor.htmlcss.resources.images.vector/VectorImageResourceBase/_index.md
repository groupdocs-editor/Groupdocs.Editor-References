---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Basisklasse für jedes unterstützte Vektorbild."
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
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
|  | [getName()](#getName--) | Gibt den Namen dieses Vektor‑Bildes zurück. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Gibt den korrekten Dateinamen dieses Vektor‑Bildes zurück, der aus Namen und |
der Erweiterung besteht.
|
|  | [getAspectRatio()](#getAspectRatio--) | Gibt das Seitenverhältnis dieses Vektor‑Bildes zurück. |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Gibt die linearen Abmessungen dieses Vektor‑Bildes zurück (Breite und Höhe). |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Überprüft diese Instanz auf Referenzgleichheit mit dem angegebenen Objekt. |
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob dieses Rasterbild freigegeben wurde oder nicht |
|
|  | [getType()](#getType--) | Der implementierende Typ sollte Informationen über den Typ des Vektors zurückgeben. |
Bild
|
|  | [getByteContent()](#getByteContent--) | Der implementierende Typ sollte den Inhalt dieses Vektor‑Bildes als Byte zurückgeben. |
stream
|
|  | [getTextContent()](#getTextContent--) | Der implementierende Typ sollte den Inhalt dieses Vektor‑Bildes als Text zurückgeben. |
form: base64‑kodiert von XML bezüglich des Bildtyps
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Der implementierende Typ sollte dieses Bild auf die Festplatte unter dem angegebenen Pfad speichern. |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Der implementierende Typ sollte das aktuelle Vektor‑Bild als Raster‑PNG speichern. |
In den angegebenen Byte‑Stream formatieren.
|
|  | [dispose()](#dispose--) | Der implementierende Typ sollte diese Instanz freigeben. |
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


Gibt den Namen dieses Vektor‑Bildes zurück. Enthält normalerweise keinen Dateinamen.
Erweiterung und kann theoretisch vom Dateinamen abweichen.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Gibt den korrekten Dateinamen dieses Vektor‑Bildes zurück, der aus Namen und
Erweiterung. Theoretisch kann sie vom Namen abweichen.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Gibt das Seitenverhältnis dieses Vektor‑Bildes zurück.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Gibt die linearen Abmessungen dieses Vektor‑Bildes zurück (Breite und Höhe).


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Überprüft diese Instanz auf Referenzgleichheit mit dem angegebenen Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere Instanz eines Vektor‑Bildes |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestimmt, ob dieses Rasterbild freigegeben wurde oder nicht


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Der implementierende Typ sollte Informationen über den Typ des Vektors zurückgeben.
Bild


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Der implementierende Typ sollte den Inhalt dieses Vektor‑Bildes als Byte zurückgeben.
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Der implementierende Typ sollte den Inhalt dieses Vektor‑Bildes als Text zurückgeben.
form: base64‑kodiert von XML bezüglich des Bildtyps


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Der implementierende Typ sollte dieses Bild auf die Festplatte unter dem angegebenen Pfad speichern.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Der implementierende Typ sollte das aktuelle Vektor‑Bild als Raster‑PNG speichern.
In den angegebenen Byte‑Stream formatieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Byte‑Stream, in dem die PNG‑Version dieses Raster‑Bildes gespeichert wird. Darf nicht NULL sein und sollte Schreibvorgänge unterstützen. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Der implementierende Typ sollte diese Instanz freigeben.


