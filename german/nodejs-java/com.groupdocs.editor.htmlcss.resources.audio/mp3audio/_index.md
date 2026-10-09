---
title: "Mp3Audio"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt eine Audioressource beliebigen Formats dar."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Stellt eine Audioressource beliebigen Formats dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Erstellt eine neue Mp3Audio‑Klasse aus MP3‑Inhalt, dargestellt als Byte‑Stream, und mit angegebenem Namen |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Prüft, ob der angegebene Stream ein gültiger MP3‑Inhalt ist |
|
|  | [getName()](#getName--) | Gibt den Namen dieses MP3‑Inhalts zurück. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Gibt den korrekten Dateinamen dieses MP3‑Inhalts zurück, der aus Name und Erweiterung besteht. |
|
|  | [getType()](#getType--) | Gibt ein AudioFormat.Mp3 zurück (erfüllt zudem IHtmlResource.getFormat() durch kovariante Rückgabe) |
|
|  | [getByteContent()](#getByteContent--) | Gibt den Inhalt dieser Schriftart als Bytestrom zurück |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Gibt den Inhalt dieser MP3-Audioressource als Bytestrom mit ursprünglicher Position zurück |
|
|  | [getTextContent()](#getTextContent--) | Gibt den Inhalt dieser MP3-Ressource als base64-kodierten String zurück. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert diese MP3-Ressource in die angegebene Datei |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Überprüft diese Instanz mit der angegebenen HTML-Ressource auf Referenzgleichheit |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Überprüft diese Instanz mit der angegebenen Schriftart-Ressource auf Referenzgleichheit |
|
|  | [dispose()](#dispose--) | Entsorgt diese MP3-Ressource, wobei ihr Inhalt freigegeben wird und die meisten Methoden und Eigenschaften nicht mehr funktionieren |
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob dieser MP3-Inhalt freigegeben wurde oder nicht |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Erstellt eine neue Mp3Audio‑Klasse aus MP3‑Inhalt, dargestellt als Byte‑Stream, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des MP3-Inhalts. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | com.aspose.ms.System.IO.Stream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|
|  | offenlassen | boolesch | Bestimmt, ob der angegebene Strom freigegeben wird, wenn die Mp3Audio-Instanz freigegeben wird |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Prüft, ob der angegebene Stream ein gültiger MP3‑Inhalt ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | com.aspose.ms.System.IO.Stream | Bytestrom, der vermutlich einen MP3-Inhalt enthält |
|

**Returns:**
boolesch – Wahr, wenn der angegebene Strom gültigen MP3-Inhalt enthält, sonst falsch

### getName() {#getName--}
```
public String getName()
```


Gibt den Namen dieses MP3-Inhalts zurück. Enthält normalerweise keine Dateierweiterung und kann theoretisch vom Dateinamen abweichen.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Gibt den korrekten Dateinamen dieses MP3-Inhalts zurück, der aus Name und Erweiterung besteht. Theoretisch kann er vom Namen abweichen.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Gibt ein AudioFormat.Mp3 zurück (erfüllt zudem IHtmlResource.getFormat() durch kovariante Rückgabe)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Gibt den Inhalt dieser Schriftart als Bytestrom zurück


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Gibt den Inhalt dieser MP3-Audioressource als Bytestrom mit ursprünglicher Position zurück


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Gibt den Inhalt dieser MP3-Ressource als base64-kodierten String zurück. Dieser Wert wird nach dem ersten Aufruf zwischengespeichert.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Speichert diese MP3-Ressource in die angegebene Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | vollerPfadZurDatei | java.lang.String | Vollständiger Pfad zur Datei, die erstellt oder überschrieben wird |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Überprüft diese Instanz mit der angegebenen HTML-Ressource auf Referenzgleichheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Anderer Erbe des IHtmlResource-Interfaces |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Überprüft diese Instanz mit der angegebenen Schriftart-Ressource auf Referenzgleichheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Andere Instanz der Mp3Audio-Klasse |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### dispose() {#dispose--}
```
public void dispose()
```


Entsorgt diese MP3-Ressource, wobei ihr Inhalt freigegeben wird und die meisten Methoden und Eigenschaften nicht mehr funktionieren


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Bestimmt, ob dieser MP3-Inhalt freigegeben wurde oder nicht


**Returns:**
boolesch
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

