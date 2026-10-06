---
title: "IHtmlResource"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Instanz der unbekannten HTML‑Ressource Raster‑ oder Vektor‑Bild, Stylesheet, Schriftart, Text‑Ressource, CSS, XML usw. dar"
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Stellt eine Instanz der unbekannten HTML‑Ressource (Raster‑ oder Vektor‑Bild,
Stylesheet, Schriftart, Textressource (CSS, XML) usw.)

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Name der HTML-Ressource |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Korrekter Dateiname der angegebenen Ressource mit passender Datei |
Erweiterung
|
|  | [getType()](#getType--) | Typ der HTML-Ressource |
|
|  | [getByteContent()](#getByteContent--) | Inhalt der HTML-Ressource in Form eines Byte-Streams |
|
|  | [getTextContent()](#getTextContent--) | Inhalt der HTML-Ressource in Form einer base64-codierten Textzeichenkette |
für binäre Ressourcen oder ein einfacher Text für textuelle Ressourcen
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert die aktuelle Ressource in die angegebene Datei |
|
### getName() {#getName--}
```
public abstract String getName()
```


Name der HTML-Ressource


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Korrekter Dateiname der angegebenen Ressource mit passender Datei
Erweiterung


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Typ der HTML-Ressource


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Inhalt der HTML-Ressource in Form eines Byte-Streams


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Inhalt der HTML-Ressource in Form einer base64-codierten Textzeichenkette
für binäre Ressourcen oder ein einfacher Text für textuelle Ressourcen


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Speichert die aktuelle Ressource in die angegebene Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Vollständiger Pfad zur Datei, die mit dem Inhalt der aktuellen Ressource erstellt oder überschrieben wird |
|

