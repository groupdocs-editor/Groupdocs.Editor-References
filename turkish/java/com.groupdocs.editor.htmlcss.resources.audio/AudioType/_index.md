---
title: "AudioType"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Desteklenebilir bir ses tipi formatını temsil eder"
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Desteklenebilir bir ses türünü (format) temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Bu ses formatının resmi adı |
|
|  | [getFileExtension()](#getFileExtension--) | Bu ses formatı için dosya adı uzantısı (nokta karakteri olmadan) |
|
|  | [getMimeCode()](#getMimeCode--) | Bu ses formatının MIME kodu |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Bu örneğin belirtilen "AudioType" örneğiyle eşit olup olmadığını belirler |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "AudioType" örneğidir. |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | İki "AudioType" değerinin eşit olup olmadığını denetler. |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | İki "AudioType" değerinin eşit olmadığını denetler. |
|
|  | [hashCode()](#hashCode--) | Bu belirli değer türü için sabit bir sayı olan bir hash kodu döndürür. |
|
|  | [getUndefined()](#getUndefined--) | Tanımsız, bilinmeyen veya desteklenmeyen ses formatını işaret eden özel bir değer. |
|
|  | [getMp3()](#getMp3--) | Bir MPEG-1 Audio Layer III ses formatını temsil eder. |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Belirtilen dosya adından çıkarılan dosya uzantısına eşdeğer bir AudioType değeri döndürür. |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Bu ses formatının resmi adı


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bu ses formatı için dosya adı uzantısı (nokta karakteri olmadan)


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Bu ses formatının MIME kodu


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Bu örneğin belirtilen "AudioType" örneğiyle eşit olup olmadığını belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Bu ile karşılaştırılacak diğer AudioType örneği. |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "AudioType" örneğidir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Muhtemelen AudioType yapısının bir diğer örneği, System.Object'e kutulanmış. |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


İki "AudioType" değerinin eşit olup olmadığını denetler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ilk AudioType. |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ikinci AudioType. |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


İki "AudioType" değerinin eşit olmadığını denetler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ilk AudioType. |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ikinci AudioType. |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu belirli değer türü için sabit bir sayı olan bir hash kodu döndürür.


**Returns:**
int - 4 bayt işaretli tam sayı, Tanımsız değer için 0.

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Tanımsız, bilinmeyen veya desteklenmeyen ses formatını işaret eden özel bir değer.


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Bir MPEG-1 Audio Layer III ses formatını temsil eder.


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Belirtilen dosya adından çıkarılan dosya uzantısına eşdeğer bir AudioType değeri döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya adı | java.lang.String | İsteğe bağlı dosya adı, göreli ya da tam yol olabilir. |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

