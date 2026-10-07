---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt de basis‑klasse voor documentformaten voor die gemeenschappelijke functionaliteit biedt voor format‑instanties."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Stelt de basisklasse voor documentformaten voor, die gemeenschappelijke functionaliteit voor formatinstanties biedt.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMime()](#getMime--) | Haalt het MIME‑type van het documentformaat op. |
|
|  | [getExtension()](#getExtension--) | Haalt de bestandsextensie van het documentformaat op. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Haalt de formatfamilie op waartoe het documentformaat behoort. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Haalt een instantie op van het opgegeven type |
T
die de opgegeven MIME-type heeft.
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor het huidige object. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Bepaalt of deze instantie gelijk is aan de opgegeven [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instantie. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan de opgegeven [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Converteert een [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie impliciet naar een string. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Haalt het MIME‑type van het documentformaat op.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Haalt de bestandsextensie van het documentformaat op.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Haalt de formatfamilie op waartoe het documentformaat behoort.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Haalt een instantie op van het opgegeven type
T
die de opgegeven MIME-type heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Het MIME-type van het documentformaat. |


T
: Het type documentformaat.
|

**Returns:**
T - Een instantie van het opgegeven type  T  met het opgegeven MIME-type.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor het huidige object.


**Returns:**
int - Een hashcode voor het huidige object, die de hashcodes van het basisobject, MIME-type, bestandsextensie en formatfamilie combineert.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instantie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | De [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instantie om te vergelijken met de huidige instantie. |
|

**Returns:**
boolean -  true  als de opgegeven [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) gelijk is aan de huidige instantie; anders,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan de opgegeven [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | De [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie om te vergelijken met de huidige instantie. |
|

**Returns:**
boolean -  true  als de opgegeven [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) gelijk is aan de huidige instantie; anders,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Converteert een [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie impliciet naar een string.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | De [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie om te converteren. |
|

**Returns:**
java.lang.String - De bestandsextensie van de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instantie.

