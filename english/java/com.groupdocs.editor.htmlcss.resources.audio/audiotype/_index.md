---
title: AudioType
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one supportable audio type format
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Represents one supportable audio type (format)
## Constructors

| Constructor | Description |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormalName()](#getFormalName--) | Formal name of this audio format |
| [getFileExtension()](#getFileExtension--) | Filename extension (without dot character) for this audio format |
| [getMimeCode()](#getMimeCode--) | MIME code for this audio format |
| [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Determines whether this instance is equal with specified "AudioType" instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal with specified uncasted object, which presumably is another "AudioType" instance |
| [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Checks whether two "AudioType" values are equal |
| [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Checks whether two "AudioType" values are not equal |
| [hashCode()](#hashCode--) | Returns a hash-code, which is a constant number for this specific value type |
| [getUndefined()](#getUndefined--) | Special value, which marks undefined, unknown or unsupported audio format |
| [getMp3()](#getMp3--) | Represents a MPEG-1 Audio Layer III audio format |
| [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returns AudioType value, which is equivalent of filename extension, which is extracted from specified filename |
| [CloneTo(AudioType that)](#CloneTo-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Formal name of this audio format

**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Filename extension (without dot character) for this audio format

**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME code for this audio format

**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Determines whether this instance is equal with specified "AudioType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Other AudioType instance to check with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal with specified uncasted object, which presumably is another "AudioType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other instance presumably of AudioType struct, that was boxed to System.Object |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Checks whether two "AudioType" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | First AudioType to check |
| second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Second AudioType to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Checks whether two "AudioType" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | First AudioType to check |
| second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Second AudioType to check |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, which is a constant number for this specific value type

**Returns:**
int - 4-byte signed integer, 0 for Undefined value
### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Special value, which marks undefined, unknown or unsupported audio format

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Represents a MPEG-1 Audio Layer III audio format

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Returns AudioType value, which is equivalent of filename extension, which is extracted from specified filename

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Arbitrary filename, can be a relative or full path |

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.
### CloneTo(AudioType that) {#CloneTo-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public void CloneTo(AudioType that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) |  |

### Clone() {#Clone--}
```
public AudioType Clone()
```




**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
