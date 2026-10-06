---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt die Basisklasse für Dokumentformate dar, die gemeinsame Funktionalität für Formatinstanzen bereitstellt."
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Stellt die Basisklasse für Dokumentformate dar und bietet gemeinsame Funktionalität für Formatinstanzen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMime()](#getMime--) | Ermittelt den MIME-Typ des Dokumentformats. |
|
|  | [getExtension()](#getExtension--) | Ermittelt die Dateierweiterung des Dokumentformats. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Ermittelt die Formatfamilie, zu der das Dokumentformat gehört. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Ruft eine Instanz des angegebenen Typs ab. |
T
die den angegebenen MIME-Typ hat.
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode für das aktuelle Objekt zurück. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Bestimmt, ob diese Instanz gleich der angegebenen [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) Instanz ist. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz gleich der angegebenen [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz ist. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Konvertiert implizit eine [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz in einen String. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Ermittelt den MIME-Typ des Dokumentformats.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ermittelt die Dateierweiterung des Dokumentformats.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Ermittelt die Formatfamilie, zu der das Dokumentformat gehört.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Ruft eine Instanz des angegebenen Typs ab.
T
die den angegebenen MIME-Typ hat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Der MIME-Typ des Dokumentformats. |


T
: Der Typ des Dokumentformats.
|

**Returns:**
T - Eine Instanz des angegebenen Typs T mit dem angegebenen MIME-Typ.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für das aktuelle Objekt zurück.


**Returns:**
int - Ein Hashcode für das aktuelle Objekt, der die Hashcodes des Basisobjekts, des MIME-Typs, der Dateierweiterung und der Formatfamilie kombiniert.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Bestimmt, ob diese Instanz gleich der angegebenen [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) Instanz ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Die [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) Instanz zum Vergleich mit der aktuellen Instanz. |
|

**Returns:**
boolean -  true  wenn die angegebene [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) gleich der aktuellen Instanz ist; andernfalls  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz gleich der angegebenen [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Die [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz zum Vergleich mit der aktuellen Instanz. |
|

**Returns:**
boolean -  true  wenn die angegebene [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) gleich der aktuellen Instanz ist; andernfalls  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Konvertiert implizit eine [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz in einen String.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Die [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz zum Konvertieren. |
|

**Returns:**
java.lang.String - Die Dateierweiterung der [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) Instanz.

