---
title: "AudioType"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein unterstützbares Audioformat dar"
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Stellt einen unterstützbaren Audiodatentyp (Format) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Formaler Name dieses Audioformats |
|
|  | [getFileExtension()](#getFileExtension--) | Dateierweiterung (ohne Punktzeichen) für dieses Audioformat |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-Code für dieses Audioformat |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Bestimmt, ob diese Instanz gleich der angegebenen "AudioType"-Instanz ist |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz gleich dem angegebenen nicht gecasteten Objekt ist, das vermutlich eine weitere "AudioType"-Instanz ist |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Überprüft, ob zwei "AudioType"-Werte gleich sind |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Überprüft, ob zwei "AudioType"-Werte nicht gleich sind |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode zurück, der eine konstante Zahl für diesen spezifischen Werttyp ist |
|
|  | [getUndefined()](#getUndefined--) | Spezialwert, der ein undefiniertes, unbekanntes oder nicht unterstütztes Audioformat kennzeichnet |
|
|  | [getMp3()](#getMp3--) | Stellt ein MPEG-1 Audio Layer III Audioformat dar |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Gibt einen AudioType-Wert zurück, der der Dateierweiterung entspricht, die aus dem angegebenen Dateinamen extrahiert wird |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Formaler Name dieses Audioformats


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Dateierweiterung (ohne Punktzeichen) für dieses Audioformat


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-Code für dieses Audioformat


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Bestimmt, ob diese Instanz gleich der angegebenen "AudioType"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Andere AudioType-Instanz zum Vergleich mit dieser |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz gleich dem angegebenen nicht gecasteten Objekt ist, das vermutlich eine weitere "AudioType"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere Instanz, vermutlich vom AudioType-Struct, die zu System.Object geboxt wurde |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Überprüft, ob zwei "AudioType"-Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Erster AudioType zum Prüfen |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Zweiter AudioType zum Prüfen |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Überprüft, ob zwei "AudioType"-Werte nicht gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Erster AudioType zum Prüfen |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Zweiter AudioType zum Prüfen |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode zurück, der eine konstante Zahl für diesen spezifischen Werttyp ist


**Returns:**
int – 4‑Byte vorzeichenbehaftete Ganzzahl, 0 für undefinierten Wert

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Spezialwert, der ein undefiniertes, unbekanntes oder nicht unterstütztes Audioformat kennzeichnet


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Stellt ein MPEG-1 Audio Layer III Audioformat dar


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Gibt einen AudioType-Wert zurück, der der Dateierweiterung entspricht, die aus dem angegebenen Dateinamen extrahiert wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateiname | java.lang.String | Beliebiger Dateiname, kann ein relativer oder voller Pfad sein |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

