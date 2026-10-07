---
title: "AudioType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één ondersteund audioformaat voor"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Stelt één ondersteund audiotype (formaat) voor

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Formele naam van dit audioformaat |
|
|  | [getFileExtension()](#getFileExtension--) | Bestandsextensie (zonder punt) voor dit audioformaat |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-code voor dit audioformaat |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Bepaalt of deze instantie gelijk is aan de opgegeven "AudioType" instantie |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, dat vermoedelijk een andere \"AudioType\"-instantie is |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Controleert of twee \"AudioType\"-waarden gelijk zijn |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Controleert of twee \"AudioType\"-waarden niet gelijk zijn |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode, die een constant getal is voor dit specifieke waardetype |
|
|  | [getUndefined()](#getUndefined--) | Speciale waarde, die een ongedefinieerd, onbekend of niet-ondersteund audioformaat aangeeft |
|
|  | [getMp3()](#getMp3--) | Stelt een MPEG-1 Audio Layer III audioformaat voor |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Retourneert een AudioType-waarde, die gelijk is aan de bestandsnaamextensie die uit de opgegeven bestandsnaam wordt gehaald |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Formele naam van dit audioformaat


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bestandsextensie (zonder punt) voor dit audioformaat


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-code voor dit audioformaat


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven "AudioType" instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Andere AudioType-instantie om met deze te vergelijken |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, dat vermoedelijk een andere \"AudioType\"-instantie is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere instantie, vermoedelijk van de AudioType-struct, die is verpakt naar System.Object |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Controleert of twee \"AudioType\"-waarden gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Eerste AudioType om te controleren |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Tweede AudioType om te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Controleert of twee \"AudioType\"-waarden niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Eerste AudioType om te controleren |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Tweede AudioType om te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode, die een constant getal is voor dit specifieke waardetype


**Returns:**
int - 4-byte ondertekend geheel getal, 0 voor ongedefinieerde waarde

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Speciale waarde, die een ongedefinieerd, onbekend of niet-ondersteund audioformaat aangeeft


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Stelt een MPEG-1 Audio Layer III audioformaat voor


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Retourneert een AudioType-waarde, die gelijk is aan de bestandsnaamextensie die uit de opgegeven bestandsnaam wordt gehaald


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bestandsnaam | java.lang.String | Willekeurige bestandsnaam, kan een relatief of volledig pad zijn |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

