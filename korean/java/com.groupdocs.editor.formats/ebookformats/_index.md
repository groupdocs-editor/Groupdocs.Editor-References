---
title: "EBookFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "모든 eBook 형식을 캡슐화합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

모든 eBook 형식을 캡슐화합니다. 다음 파일 유형을 포함합니다:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Mobi 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/ebook/mobi/)를, ePub 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/ebook/epub/)를 클릭하세요.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI는 MobiPocket Reader용으로 개발된 형식에 부여된 이름입니다. |
|
|  | [Epub](#Epub) | Electronic Publication (IDPF ePub) 형식은 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 e-book 파일 형식입니다. |
|
|  | [Azw3](#Azw3) | AZW3는 Kindle Format 8 (KF8)이라고도 하며, Amazon Kindle 기기를 위해 개발된 AZW eBook 디지털 파일 형식의 수정 버전입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 지정된 유형 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 객체로 변환합니다. |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI는 MobiPocket Reader용으로 개발된 형식에 부여된 이름이며, PRC, AZW라고도 합니다.
현재 Amazon에서 약간 다른 DRM 방식을 사용하여 AZW라고 부릅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (IDPF ePub) 형식은 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 e-book 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3는 Kindle Format 8 (KF8)이라고도 하며, Amazon Kindle 기기를 위해 개발된 AZW eBook 디지털 파일 형식의 수정 버전입니다.
이 형식은 이전 AZW 파일을 개선한 것입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


모든 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 인스턴스를 포함하는 IEnumerable{EBookFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 지정된 유형 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats)의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

