---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "문서 형식에 대한 공통 기능을 제공하는 기본 클래스이며, 형식 인스턴스에 사용됩니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

문서 형식의 기본 클래스를 나타내며, 형식 인스턴스에 공통 기능을 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMime()](#getMime--) | 문서 형식의 MIME 유형을 가져옵니다. |
|
|  | [getExtension()](#getExtension--) | 문서 형식의 파일 확장자를 가져옵니다. |
|
|  | [getFormatFamily()](#getFormatFamily--) | 문서 형식이 속한 형식 패밀리를 가져옵니다. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | 지정된 유형의 인스턴스를 검색합니다. |
T
지정된 MIME 유형을 가진.
|
|  | [hashCode()](#hashCode--) | 현재 객체에 대한 해시 코드를 반환합니다. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | 이 인스턴스가 지정된 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스와 같은지 여부를 결정합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스와 같은지 여부를 결정합니다. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | 지정된 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스를 문자열로 암시적으로 변환합니다. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


문서 형식의 MIME 유형을 가져옵니다.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


문서 형식의 파일 확장자를 가져옵니다.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


문서 형식이 속한 형식 패밀리를 가져옵니다.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


지정된 유형의 인스턴스를 검색합니다.
T
지정된 MIME 유형을 가진.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | 문서 형식의 MIME 유형. |


T
: 문서 형식의 유형.
|

**Returns:**
T - 지정된 유형 T와 지정된 MIME 유형을 가진 인스턴스.

### hashCode() {#hashCode--}
```
public int hashCode()
```


현재 객체에 대한 해시 코드를 반환합니다.


**Returns:**
int - 현재 객체에 대한 해시 코드이며, 기본 객체, MIME 유형, 파일 확장자 및 형식 패밀리의 해시 코드를 결합합니다.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


이 인스턴스가 지정된 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | 현재 인스턴스와 비교할 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스. |
|

**Returns:**
boolean - 지정된 [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)이 현재 인스턴스와 같으면  true , 그렇지 않으면  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 현재 인스턴스와 비교할 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스. |
|

**Returns:**
boolean - 지정된 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)이 현재 인스턴스와 같으면  true , 그렇지 않으면  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


지정된 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스를 문자열로 암시적으로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | 변환할 [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스. |
|

**Returns:**
java.lang.String - [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스의 파일 확장자.

