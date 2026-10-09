---
title: "AudioType"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett stödjbart ljudtypformat"
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Representerar en stödbar ljudtyp (format)

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Formellt namn för detta ljudformat |
|
|  | [getFileExtension()](#getFileExtension--) | Filnamnstillägg (utan punkttecken) för detta ljudformat |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-kod för detta ljudformat |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Bestämmer om detta objekt är lika med den angivna "AudioType"-instansen |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med det angivna okastade objektet, som förmodligen är en annan "AudioType"-instans |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Kontrollerar om två "AudioType"-värden är lika |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Kontrollerar om två "AudioType"-värden inte är lika |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod, som är ett konstant tal för denna specifika värdetyp |
|
|  | [getUndefined()](#getUndefined--) | Speciellt värde som markerar odefinierat, okänt eller ej stödt ljudformat |
|
|  | [getMp3()](#getMp3--) | Representerar ett MPEG-1 Audio Layer III-ljudformat |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returnerar ett AudioType-värde, som är motsvarigheten till filnamnstillägget som extraheras från det angivna filnamnet |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Formellt namn för detta ljudformat


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Filnamnstillägg (utan punkttecken) för detta ljudformat


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-kod för detta ljudformat


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Bestämmer om detta objekt är lika med den angivna "AudioType"-instansen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Annan AudioType-instans att jämföra med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt är lika med det angivna okastade objektet, som förmodligen är en annan "AudioType"-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annan instans, förmodligen av AudioType-struct, som har boxats till System.Object |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Kontrollerar om två "AudioType"-värden är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Första AudioType att kontrollera |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Andra AudioType att kontrollera |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Kontrollerar om två "AudioType"-värden inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Första AudioType att kontrollera |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Andra AudioType att kontrollera |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod, som är ett konstant tal för denna specifika värdetyp


**Returns:**
int - 4-byte signerat heltal, 0 för Odefinierat värde

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Speciellt värde som markerar odefinierat, okänt eller ej stödt ljudformat


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Representerar ett MPEG-1 Audio Layer III-ljudformat


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Returnerar ett AudioType-värde, som är motsvarigheten till filnamnstillägget som extraheras från det angivna filnamnet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filnamn | java.lang.String | Godtyckligt filnamn, kan vara en relativ eller fullständig sökväg |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

