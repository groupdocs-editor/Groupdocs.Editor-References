---
title: "AudioType"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Desteklenebilir bir ses türü biçimini temsil eder"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Desteklenen bir ses türünü (formatı) temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Bu ses biçiminin resmi adı |
|
|  | [getFileExtension()](#getFileExtension--) | Bu ses biçimi için dosya adı uzantısı (nokta karakteri olmadan) |
|
|  | [getMimeCode()](#getMimeCode--) | Bu ses biçimi için MIME kodu |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Bu örneğin belirtilen "AudioType" örneğiyle eşit olup olmadığını belirler |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "AudioType" örneğidir |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | İki "AudioType" değerinin eşit olup olmadığını denetler |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | İki "AudioType" değerinin eşit olmama durumunu denetler |
|
|  | [hashCode()](#hashCode--) | Bu belirli değer türü için sabit bir sayı olan bir hash kodu döndürür |
|
|  | [getUndefined()](#getUndefined--) | Tanımsız, bilinmeyen veya desteklenmeyen ses biçimini işaret eden özel bir değer |
|
|  | [getMp3()](#getMp3--) | MPEG-1 Audio Layer III ses biçimini temsil eder |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Belirtilen dosya adından çıkarılan dosya adı uzantısına eşdeğer bir AudioType değeri döndürür |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Bu ses biçiminin resmi adı


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bu ses biçimi için dosya adı uzantısı (nokta karakteri olmadan)


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Bu ses biçimi için MIME kodu


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
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Bu ile kontrol edilecek diğer AudioType örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "AudioType" örneğidir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | System.Object'e kutulanmış, muhtemelen AudioType yapısının diğer örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


İki "AudioType" değerinin eşit olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ilk AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ikinci AudioType |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


İki "AudioType" değerinin eşit olmama durumunu denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ilk AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Kontrol edilecek ikinci AudioType |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu belirli değer türü için sabit bir sayı olan bir hash kodu döndürür


**Returns:**
int - 4 bayt işaretli tam sayı, Tanımsız değer için 0

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Tanımsız, bilinmeyen veya desteklenmeyen ses biçimini işaret eden özel bir değer


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


MPEG-1 Audio Layer III ses biçimini temsil eder


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Belirtilen dosya adından çıkarılan dosya adı uzantısına eşdeğer bir AudioType değeri döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya adı | java.lang.String | İsteğe bağlı dosya adı, göreli ya da tam yol olabilir |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

