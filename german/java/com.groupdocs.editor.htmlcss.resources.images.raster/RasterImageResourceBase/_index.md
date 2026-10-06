---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Basisklasse für jedes unterstützte Rasterbild mit festem Namen, Abmessungen, Seitenverhältnis, Typ, Größe und Inhalt."
type: docs
weight: 15
url: /de/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Basisklasse für jedes unterstützte Rasterbild mit festem Namen, Abmessungen, Seitenverhältnis
Typ, Größe und Inhalt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Gibt den Namen dieses Rasterbildes zurück. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Gibt den korrekten Dateinamen dieses Rasterbildes zurück, der aus dem Namen und |
der Erweiterung besteht.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Gibt die linearen Abmessungen dieses Rasterbildes (Breite und Höhe) zurück |
|
|  | [getAspectRatio()](#getAspectRatio--) | Gibt das Seitenverhältnis dieses Bildes als Breite‑zu‑Höhe‑Verhältnis zurück |
|
|  | [getLength()](#getLength--) | Gibt die Länge dieser Rasterbilddatei in Bytes zurück |
|
|  | [getByteContent()](#getByteContent--) | Gibt den Inhalt dieses Rasterbildes als Byte-Stream zurück |
|
|  | [getTextContent()](#getTextContent--) | Gibt den Inhalt dieses Rasterbildes als base64-codierte Zeichenkette zurück |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert dieses Rasterbild in die angegebene Datei |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Überprüft diese Instanz auf Referenzgleichheit mit dem angegebenen Objekt. |
|
|  | [dispose()](#dispose--) | Entfernt dieses Rasterbild, gibt dessen Inhalt frei und macht die meisten Methoden unbrauchbar |
und Eigenschaften funktionieren nicht
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob dieses Rasterbild freigegeben wurde oder nicht |
|
|  | [getType()](#getType--) | Der implementierende Typ sollte Informationen über den Typ des Rasters zurückgeben |
Bild
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


Gibt den Namen dieses Rasterbildes zurück. Enthält normalerweise keinen Dateinamen
Erweiterung und kann theoretisch vom Dateinamen abweichen.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Gibt den korrekten Dateinamen dieses Rasterbildes zurück, der aus dem Namen und
Erweiterung. Theoretisch kann sie vom Namen abweichen.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Gibt die linearen Abmessungen dieses Rasterbildes (Breite und Höhe) zurück


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Gibt das Seitenverhältnis dieses Bildes als Breite‑zu‑Höhe‑Verhältnis zurück


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Gibt die Länge dieser Rasterbilddatei in Bytes zurück


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Gibt den Inhalt dieses Rasterbildes als Byte-Stream zurück


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Gibt den Inhalt dieses Rasterbildes als base64-codierte Zeichenkette zurück


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Speichert dieses Rasterbild in die angegebene Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Vollständiger Pfad zur Datei, die erstellt oder überschrieben wird. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Überprüft diese Instanz auf Referenzgleichheit mit dem angegebenen Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere IHtmlResource-Erweiterung |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### dispose() {#dispose--}
```
public final void dispose()
```


Entfernt dieses Rasterbild, gibt dessen Inhalt frei und macht die meisten Methoden unbrauchbar
und Eigenschaften funktionieren nicht


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


Der implementierende Typ sollte Informationen über den Typ des Rasters zurückgeben
Bild


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
