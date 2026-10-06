---
title: "FontResourceBase"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Basisklasse für jeden unterstützten Schriftarttyp als Ressource für das HTML-Dokument mit allen seinen Eigenschaften"
type: docs
weight: 11
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Basisklasse für jeden unterstützten Schriftarttyp als Ressource für das HTML-Dokument
mit allen seinen Eigenschaften

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Disposed](#Disposed) | Ereignis, das auftritt, wenn diese Schriftart freigegeben wird |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Gibt den Namen dieser Schriftartressource zurück. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Gibt den korrekten Dateinamen dieser Schriftartressource zurück, der aus dem Namen besteht |
und der Erweiterung.
|
|  | [getByteContent()](#getByteContent--) | Gibt den Inhalt dieser Schriftart als Bytestrom zurück |
|
|  | [getTextContent()](#getTextContent--) | Gibt den Inhalt dieser Schriftart als base64-kodierte Zeichenkette zurück. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert diese Schriftart in die angegebene Datei |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Überprüft diese Instanz mit der angegebenen HTML-Ressource auf Referenzgleichheit |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Überprüft diese Instanz mit der angegebenen Schriftart-Ressource auf Referenzgleichheit |
|
|  | [dispose()](#dispose--) | Gibt diese Schriftartressource frei, indem ihr Inhalt freigegeben wird und das meiste |
Methoden und Eigenschaften nicht funktionsfähig
|
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob diese Schriftart freigegeben ist oder nicht |
|
|  | [getType()](#getType--) | Bei der Implementierung sollte der Typ Informationen über den Typ einer bestimmten |
Schriftressource als Instanz eines bestimmten FontType-Typs, der
kapselt alle typspezifischen Informationen
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Ereignis, das auftritt, wenn diese Schriftart freigegeben wird


### getName() {#getName--}
```
public final String getName()
```


Gibt den Namen dieser Schriftressource zurück. Enthält normalerweise keinen Dateinamen
Erweiterung und kann theoretisch vom Dateinamen abweichen.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Gibt den korrekten Dateinamen dieser Schriftartressource zurück, der aus dem Namen besteht
und die Erweiterung. Theoretisch kann sie vom Namen abweichen.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Gibt den Inhalt dieser Schriftart als Bytestrom zurück


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Gibt den Inhalt dieser Schriftart als base64-kodierten String zurück. Dieser Wert ist
nach dem ersten Aufruf zwischengespeichert.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Speichert diese Schriftart in die angegebene Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Vollständiger Pfad zur Datei, die erstellt oder überschrieben wird. |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Überprüft diese Instanz mit der angegebenen HTML-Ressource auf Referenzgleichheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Andere Implementierung des IHtmlResource-Interfaces. |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Überprüft diese Instanz mit der angegebenen Schriftart-Ressource auf Referenzgleichheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Ein weiterer Erbe der abstrakten Klasse FontResourceBase |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### dispose() {#dispose--}
```
public final void dispose()
```


Gibt diese Schriftartressource frei, indem ihr Inhalt freigegeben wird und das meiste
Methoden und Eigenschaften nicht funktionsfähig


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bestimmt, ob diese Schriftart freigegeben ist oder nicht


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


Bei der Implementierung sollte der Typ Informationen über den Typ einer bestimmten
Schriftressource als Instanz eines bestimmten FontType-Typs, der
kapselt alle typspezifischen Informationen


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
