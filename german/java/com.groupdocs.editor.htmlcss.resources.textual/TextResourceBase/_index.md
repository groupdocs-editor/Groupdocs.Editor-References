---
title: "TextResourceBase"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Basisklasse für jede unterstützte Textressource mit Textinhalt und Codierung."
type: docs
weight: 11
url: /de/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Basisklasse für jede unterstützte Textressource mit Textinhalt und Codierung.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Erstellt neue Textressource aus angegebenem Textinhalt mit Kodierung |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Erstellt neue Textressource aus angegebenem Bytestrom und Kodierung |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Gibt den Namen dieser Textressource ohne Dateierweiterung zurück |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Gibt den korrekten Dateinamen dieser Textressource zurück, der aus dem Namen besteht |
und Erweiterung
|
|  | [getEncoding()](#getEncoding--) | Gibt die Kodierung dieser Textressource zurück. |
|
|  | [getByteContent()](#getByteContent--) | Gibt den Inhalt dieser Textressource als Bytestrom im Originalformat zurück. |
Kodierung
|
|  | [getTextContent()](#getTextContent--) | Gibt den Inhalt dieser Textressource als Standardzeichenkette zurück |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert diese Textressource in die angegebene Datei |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Überprüft diese Instanz auf Gleichheit mit dem angegebenen. |
|
|  | [dispose()](#dispose--) | Entfernt diese Textressource, gibt ihren Inhalt frei und macht die meisten |
Methoden und Eigenschaften nicht funktionsfähig.
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob diese Textressource freigegeben wurde oder nicht |
|
|  | [getType()](#getType--) | Der implementierende Typ sollte Informationen über den Typ des Textes zurückgeben |
Ressource
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Erstellt neue Textressource aus angegebenem Textinhalt mit Kodierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Erforderlicher Name der Ressource, der als eindeutiger Bezeichner dient. Üblicherweise ist es ein Dateiname. |
|
|  | textualContent | java.lang.String | Textlicher Inhalt der Ressource, darf nicht NULL oder leer sein |
|
|  | originalEncoding | java.nio.charset.Charset | Ursprüngliche Kodierung der Ressource, darf nicht NULL oder leer sein |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Erstellt neue Textressource aus angegebenem Bytestrom und Kodierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Erforderlicher Name der Ressource, der als eindeutiger Bezeichner dient. Üblicherweise ist es ein Dateiname. |
|
|  | binaryContent | java.io.InputStream | Binärer Inhalt einer Ressource als Bytestrom. Darf nicht NULL sein, nicht freigegeben sein und sollte lesbar sowie durchsuchbar sein. |
|
|  | originalEncoding | java.nio.charset.Charset | Ursprüngliche Kodierung der Ressource, darf nicht NULL oder leer sein |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Gibt den Namen dieser Textressource ohne Dateierweiterung zurück


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Gibt den korrekten Dateinamen dieser Textressource zurück, der aus dem Namen besteht
und Erweiterung


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Gibt die Kodierung dieser Textressource zurück. Gibt normalerweise UTF-8 zurück.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Gibt den Inhalt dieser Textressource als Bytestrom im Originalformat zurück.
Kodierung


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Gibt den Inhalt dieser Textressource als Standardzeichenkette zurück


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Speichert diese Textressource in die angegebene Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Vollständiger Pfad zur Datei, die erstellt oder überschrieben wird, falls sie bereits existiert |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Überprüft diese Instanz auf Gleichheit mit dem angegebenen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere HTML-Ressource unbekannten Typs, die vermutlich ebenfalls ein Erbe von TextResourceBase ist |
|

**Returns:**
boolean - Gibt true zurück, wenn gleich, sonst false

### dispose() {#dispose--}
```
public final void dispose()
```


Entfernt diese Textressource, gibt ihren Inhalt frei und macht die meisten
Methoden und Eigenschaften nicht funktionsfähig. Tolerant gegenüber mehrfachen Aufrufen.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestimmt, ob diese Textressource freigegeben wurde oder nicht


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


Der implementierende Typ sollte Informationen über den Typ des Textes zurückgeben
Ressource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
